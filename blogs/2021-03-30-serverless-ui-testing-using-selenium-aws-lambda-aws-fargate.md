---
title: "Serverless UI testing using Selenium, AWS Lambda, AWS Fargate, and AWS Developer Tools"
url: "https://aws.amazon.com/blogs/devops/serverless-ui-testing-using-selenium-aws-lambda-aws-fargate-and-aws-developer-tools/"
date: "2021-03-30"
author: "Prakash Palanisamy"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codepipeline/feed/"
---
Since the post Using AWS CodePipeline, AWS CodeBuild, and AWS Lambda for Serverless Automated UI Testing was published, things have evolved with Chrome headless and Firefox headless being supported natively. AWS Lambda now supports container images, AWS Step Functions has added support for Map state and its integration with Lambda, and AWS Fargate has enabled automating the UI testing completely using serverless technologies. The goal of this post is to demonstrate how to use AWS Developer Tools to build a continuous delivery pipeline that automatically deploys a test environment and runs a UI test against it.
