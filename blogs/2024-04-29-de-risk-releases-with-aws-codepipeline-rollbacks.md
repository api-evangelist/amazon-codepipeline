---
title: "De-risk releases with AWS CodePipeline rollbacks"
url: "https://aws.amazon.com/blogs/devops/de-risk-releases-with-aws-codepipeline-rollbacks/"
date: "2024-04-29"
author: "Matt Laver"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codepipeline/feed/"
---
It’s an established practice for development teams to build deployment pipelines, with services such as AWS CodePipeline , to increase the quality of application and infrastructure releases through reliable, repeatable and consistent automation. Automating the deployment process helps build quality into our products by introducing continuous integration to build and test code as early as possible, aiming to catch errors before they reach production, but with all the best will in the world, issues can be missed and not caught until after a production release has been initiated. In our AWS DevOps Guidance we include a DevOps Sagas indicator to Implement automatic rollbacks for failed deployments : “Implement an automatic rollback strategy to enhance system reliability and minimize service disruptions.
