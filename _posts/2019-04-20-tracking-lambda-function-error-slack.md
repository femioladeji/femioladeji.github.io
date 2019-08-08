---
title:  "Tracking AWS Lambda Functions error via Slack"
---

I’ve been working with AWS Lambda functions for over a year now and it’s been an awesome experience so far. I want to share my experience about how I get notified on slack whenever there’s an error.

## What is Lambda function
Before we go into the nitty-gritty, let’s understand what lambda functions are. AWS Lambda functions support serverless computing by allowing you to write code that runs in response to certain events. With lambda functions, you don’t need to worry about having a server that persistently listens for requests. All you need is to define triggers. For example, a lambda function can be connected to AWS API gateway so that when a request is made to the endpoint, the lambda function gets executed. You only get charged based on the number of seconds it takes for the function to run.

[Read the full post](https://medium.com/@femidotexe/tracking-aws-lambda-functions-error-via-slack-2e9f0733e043)