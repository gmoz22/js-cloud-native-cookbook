# Creating a function

**Useful links**
- AWS Lambda Functions: https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/
- AWS CloudWatch Log groups: https://us-east-1.console.aws.amazon.com/cloudwatch/home?region=us-east-1#logsV2:log-groups
- AWS CloudFormation Stacks: https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks

## How to do it...
1. Clone this repository and copy this folder into a `cncb-create-function` folder
2. cd `cncb-create-function`
3. `npm install`
4. `npm test`
5. `npm run dp:lcl -- -s $MY_STAGE`
6. `sls invoke -r us-east-1 -f hello -s $MY_STAGE -d '{"hello":"world"}'`
7. `sls logs -f hello -r us-east-1 -s $MY_STAGE`
8. `npm run rm:lcl -- -s $MY_STAGE`
