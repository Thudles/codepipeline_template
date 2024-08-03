# Codepipeline Template

Create Stack From CloudFormation template:

```shell
aws cloudformation create-stack \
    --stack-name cf-deploy-pipeline \
    --template-body file://pipeline_template.yaml \
    --capabilities CAPABILITY_NAMED_IAM
```
