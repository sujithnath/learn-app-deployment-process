## AWS Lambda

- To Create template
  - `sls create -t aws-nodejs`
- To setup config with AWS and Serveless
  - `sls config credentials --provider aws --key [KEY] --secret [USER]`
  - User key and secret has to be generated from IAM 
- To confirm
  - cd check creds set at `~/.aws/` ?
- To deploy
  - `sls deploy`
- To run or invoke lambda function
  - to prod: `sls invoke --function [lambda function]` 
  - in local: `sls invoke local --function [lambda function]`