---
title: "Tracking the AWS CodePipeline build status from the third-party Git repository"
url: "https://aws.amazon.com/blogs/devops/aws-codepipeline-build-status-in-a-third-party-git-repository/"
date: "2021-03-30"
author: "Michal Gorniak"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codepipeline/feed/"
---
AWS CodePipeline allows you to use a third-party Git repository as a source for a pipeline, however, the status of the build may not be available on the 3rd party git repository dashboard. As a developer, it is preferable to see the build / pipeline status in the same dashboard when working with repository. This blog walks you through building a solution that will feed in pipeline / build status to the 3rd party repository, making it easy for the developer to track status without switching context.
