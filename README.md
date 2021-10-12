# aws-cloudformation-samples
Cloudformation sampple

```bash
aws cloudformation create-stack --profile <pf-name> --stack-name "dynamodb-permissions" --template-body file://iam_role.yml --capabilities CAPABILITY_IAM
aws cloudformation describe-stacks --profile <pf-name>  --stack-name "dynamodb-permissions"
```

```bash
aws sts assume-role --profile <pf-name>  --role-arn $IAM_MY_ROLE --role-session-name temp
```