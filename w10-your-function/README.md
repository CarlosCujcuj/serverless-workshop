# Example 10 - Your code!

Based on our examples now you can start doing your own projects.

To create a new NodeJS AWS Lambda project with Serverless framework type:

* serverless create --template aws-nodejs --path <project-name>
* handler.js = your lambda code
* serverless.yml = your lambda config code: permissions, events, names, etc.
* serverless deploy = full project deployment
* serverless deploy -f <function-name> = partial function deployment, much faster!
* serverless invoke -f <function-name> = execute your Lambda
	
Good luck!