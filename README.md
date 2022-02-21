# Localstack SQS Sample
LocalStack to create and test AWS SQS Bucket on your local system using Terraform

# Terraform init 
terraform init

# Terraform Validate
terraform validate

# Terraform Apply
terraform apply

# Terraform Destroy
terraform destroy

# List SQS Queue
To check all the created queues in the LocalStack type the following command in the terminal
aws --endpoint-url=http://localhost:4566 sqs list-queues

# Read Message From Queue 
aws --endpoint-url=http://localhost:4566 sqs receive-message --queue-url http://localhost:4566/000000000000/onexlab-SQS

# Create New Message To Queue 
aws --endpoint-url=http://localhost:4566 sqs send-message --queue-url http://localhost:4566/000000000000/onexlab-SQS --message-body 'Welcome to SQS queue by Onexlab'
