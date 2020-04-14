# cloudformation-serverless-rest-api-boilerplate

A Boilerplate [CloudFormation](https://aws.amazon.com/cloudformation/) template for a [serverless REST API](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html) that uses [API Gateway](https://aws.amazon.com/api-gateway/) and [AWS Lambda](https://aws.amazon.com/lambda/).

## Notes
Since this uses lambda edge, this needs to be deployed into us-east-1.

Assumptions:
- Possession of an [AWS account](https://aws.amazon.com/account/)
- Hosted Zone in [Route53](https://aws.amazon.com/route53/) with desired domain name
- [ACM](https://aws.amazon.com/certificate-manager/) Certificate

## Support

Please open an [issue](https://github.com/ndchristian/cloudformation-serverless-rest-api-boilerplate/issues) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.