# mkdocs-pipeline
A CloudFormation template to build automatically a MkDocs wiki and push it on AWS S3. Try it with my test repo https://github.com/RiceBowlJr/mkdocs-wiki.

## Usage

Just deploy the stack within the yml file, with all parameters needed. The needed parameters are the following :
TODO

The main command AWS CLI is thefollowing:
```bash
aws cloudformation create-stack --stack-name mkdocs-deployment --template-body file://mkdocs-deployment.yml --parameters "ParameterKey=GithubUser,ParameterValue=MyUser,ParameterKey=..."
```

