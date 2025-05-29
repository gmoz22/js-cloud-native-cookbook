# Creating an event stream and publishing an event

## How to do it...
1. Clone this repository and copy this folder into a `cncb-event-stream` folder
2. cd `cncb-event-stream`
3. `npm install`
4. `npm test`
5. `npm run dp:lcl -- -s $MY_STAGE`
6. `sls invoke -r us-east-1 -f publish -s $MY_STAGE -d '{"type":"thing-created"}'`
7. `sls logs -f publish -r us-east-1 -s $MY_STAGE`
8. `npm run rm:lcl -- -s $MY_STAGE`

### Useful links
- AWS Billing and Cost Management https://us-east-1.console.aws.amazon.com/costmanagement/home#/home
- AWS Kinesis data streams: https://us-east-1.console.aws.amazon.com/kinesis/home?region=us-east-1#/streams/list
- AWS Lambda functions: https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/
- AWS CloudWatch log groups: https://us-east-1.console.aws.amazon.com/cloudwatch/home?region=us-east-1#logsV2:log-groups
- AWS CloudFormation stacks: https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks
