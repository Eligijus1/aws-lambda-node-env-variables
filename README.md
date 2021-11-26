$ cd /home/project/Tools/atlantic-express/Test/aws-lambda-node-env-variables/
$ vim handler.js
$ vim package.json
$ vim serverless.yml

$ serverless deploy

$ serverless invoke --function=createUser --log
$ serverless invoke --function=resetPassword --log

$ serverless invoke local --function=createUser --log

