# gh-oauth-app

https://otamachan.github.io/gh-oauth-app/

This is a sample web page application using GitHub OAuth.
A web page only application cannot use GitHub OAuth because its endpoint does not support CORS. https://github.com/isaacs/github/issues/330 .
In this sample application, I use AWS Lambda/API Gateway to enable GitHub OAuth login with CORS support.
Please also refer to the [Cloudformation template](gh-aouth-app.template.yaml) for details.

You can launch the same stack with this ↓

[![Launch](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#/stacks/new?stackName=gh-oauth-app&templateURL=https://otamachan-cloudformation.s3-ap-northeast-1.amazonaws.com/gh-oauth-app.template.yaml)
