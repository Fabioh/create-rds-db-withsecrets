# Create stack via cloud formation
```shell
$ aws cloudformation deploy --template-file template.yaml --stack-name <stack name> --capabilities CAPABILITY_NAMED_IAM CAPABILITY_AUTO_EXPAND
```

```shell
$ aws cloudformation delete-stack --stack-name <stack name>
```


## Referencies
https://adamtheautomator.com/aws-cli-cloudformation/
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iam-role.html
https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_elements_principal.html
https://docs.aws.amazon.com/directoryservice/latest/admin-guide/edit_trust.html