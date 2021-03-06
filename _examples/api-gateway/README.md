# API Gateway example


This example shows how to setup basic API Gateway REST API invoking Lambda function managed by Apex. What's inside:

- `infrastructure/dev/main.tf` - default file generated by `apex init` command.
- `infrastructure/dev/api_gateway_iam.tf` - IAM role allowing API Gateway to invoke Lambda function.
- `infrastructure/dev/api_gateway.tf` - API Gateway REST API definitions.

## Requirements

- Terraform v0.6.13 - the first version with [API Gateway support](https://www.terraform.io/docs/providers/aws/r/api_gateway_rest_api.html).
