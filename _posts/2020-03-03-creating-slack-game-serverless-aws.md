---
title:  "Creating a slack game using Serverless architecture & AWS"
---

## What is Serverless Architecture
Serverless architecture is a cloud computing model where the provider handles the infrastructure for your application. It allows you to develop applications without thinking so much about spinning up servers and it's related complexities. Serverless architecture aims to revolutionize the way applications are developed and maintained by giving developers the flexibility not to worry so much about infrastructure (cost and maintenance) but on the application itself.

There are two major types of serverless architecture; Backend as a service and Function as a service. Examples of BAAS are Firebase and Parse server. We'll be making use of FAAS in this post. In FAAS, your code runs in stateless containers and are triggered by pre-configured events such as HTTP requests, database reads/writes, scheduled events, etc.

## Which game are we building
It's an interactive game called Wordsgame. Random letters are posted on a slack channel and members of the channel can respond with valid English words within 60 seconds. Each word is scored based on its length and the user with the highest score wins. Sounds interesting right?

[Read the full post](https://dev.to/femioladeji/creating-a-slack-game-using-serverless-architecture-aws-part-1-4jhn)
