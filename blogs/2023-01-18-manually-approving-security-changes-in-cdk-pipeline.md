---
title: "Manually Approving Security Changes in CDK Pipeline"
url: "https://aws.amazon.com/blogs/devops/manually-approving-security-changes-in-cdk-pipeline/"
date: "2023-01-18"
author: "Brian Beach"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codepipeline/feed/"
---
In this post I will show you how to add a manual approval to AWS Cloud Development Kit (CDK) Pipelines to confirm security changes before deployment. With this solution, when a developer commits a change, CDK pipeline identifies an IAM permissions change, pauses execution, and sends a notification to a security engineer to manually approve or reject the change before it is deployed. Introduction In my role I talk to a lot of customers that are excited about the AWS Cloud Development Kit (CDK).
