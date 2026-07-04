---
title: "Enhance release control with AWS CodePipeline stage-level conditions"
url: "https://aws.amazon.com/blogs/devops/enhance-release-control-with-aws-codepipeline-stage-level-conditions/"
date: "2024-10-16"
author: "Ryan Bachman"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codepipeline/feed/"
---
It’s an established practice for development teams to build deployment pipelines, with services such as AWS CodePipeline , to increase the quality of application and infrastructure releases through reliable, repeatable and consistent automation. Automating the deployment process helps build quality into our products by introducing continuous integration to build and test code, however enterprises may sometimes wish to implement certain conditions such as an approved deployment window to ensure more fine-grained control over pipeline executions. AWS CodePipeline recently added stage-level conditions to implement pipeline gates.
