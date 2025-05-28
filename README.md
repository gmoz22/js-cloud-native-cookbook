# JavaScript Cloud Native Development Cookbook

Continuously deliver serverless cloud-native solutions on AWS, Azure and GCP.

## Chapters
1. [Getting Started with Cloud-Native](./ch1)
2. [Applying the Event-Sourcing and CQRS Patterns](./ch2)
3. [Implementing Autonomous Services](./ch3)
4. [Leveraging the Edge of the Cloud](./ch4)
5. [Securing Cloud-Native Systems](./ch5)
6. [Building a Continuous Deployment Pipeline](./ch6)
7. [Optimizing Observability](./ch7)
8. [Designing for Failure](./ch8)
9. [Optimizing Performance](./ch9)
10. [Deploying to Multiple Regions](./ch10)
11. [Welcoming Polycloud](./ch11)

## Setup Development Environment:

1. Install Node Version Manager (https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script)
2. Install Node.js with `nvm install` (version 18 minimum)
3. Install the Serverless Framework with `npm install serverless -g`
4. Create an AWS account: https://aws.amazon.com/free
5. Log into AWS and create an IAM user with admin privileges, a password, and an access key: https://serverless.com/framework/docs/providers/aws/guide/credentials#creating-aws-access-keys
6. Configure the default profile with your access key:

`~/.aws/config`
```
[default]
region = us-east-1
output = json
```

`~/.aws/credentials`

```
[default]
aws_access_key_id = YOUR_AWS_ACCESS_KEY_ID
aws_secret_access_key = YOUR_AWS_SECRET_ACCESS_KEY
```

`sls login` to verify credentials work

7. Create an environment variable to hold your personal development stage: `export MY_STAGE=john <!-- use your name -->`, make it permanent in your shell
8. Install VS Code editor (optional): https://code.visualstudio.com
