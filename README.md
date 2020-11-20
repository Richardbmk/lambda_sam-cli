# SAM CLI command lines:

> `aws s3 mb s3://rick-sam-helloword`

> `aws cloudformation package --template-file template.yaml --output-template-file sam-template.yaml --s3-bucket rick-sam-helloword`

> `aws cloudformation deploy --template-file sam-template.yaml --stack-name hello-sam-stack --capabilities CAPABILITY_IAM`