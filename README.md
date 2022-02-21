# Localstack SQS Sample
LocalStack to create and test AWS S3 Bucket on your local system using Terraform

# Terraform init 
terraform init

# Terraform Validate
terraform validate

# Terraform Apply
terraform apply

# List SQS Queue

To check all the created queues in the LocalStack type the following command in the terminal
aws --endpoint-url=http://localhost:4566 sqs list-queues
