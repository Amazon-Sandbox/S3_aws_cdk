# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template

## WorkFlow

- [ ] Configure Local Machine (Dev Env)
  - 
- [ ] Create the APP
  - `cdk init <app name> --language <language>`
- [ ] Build the APP
  - [ ] 
- [ ] List the Stacks on the APP
- [ ] Add a Resource/s
- [ ] Synthesize CloudFormation Template
- [ ] Bootstrap
  - `cdk bootstrap aws://ACCOUNT-NUMBER/REGION` 
  - AWS account and region must be configured to create resources before deploying
  - [aws docs](https://docs.aws.amazon.com/cdk/v2/guide/bootstrapping.html) 
- [ ] Deploy the stack
- [ ] Modify the App
  - deployed app (already bootstrapped)
    - ` some change + cdk diff -> cdk deploy ` 
- [ ] Destroying Resources
  - ` cdk destroy ` 
  - delete stack resources
    