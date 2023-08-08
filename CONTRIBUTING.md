# Contributing Guidelines

We will not make any modifications to the code in principle. We only pull the content of the upstream project to release and upload artifacts.

## General

Please make sure that there aren't existing pull requests attempting to address the issue mentioned. Likewise, please check for issues related to update, as someone else may be working on the issue in a branch or fork.

- Please open a discussion in a new issue/existing issue to talk about the changes you'd like to bring
- Develop in a contributor's branch, not main/product
- Each issue must be submitted for a pull_request?

When creating a new branch, prefix it with type of change, the associated opened issue number and some text describing the issue (using dash as a separator).

For example, if you work on a bugfix for the issue #361, you could name the branch `bug361-container-startup-repair`

> Type must be one of the following:

- **enhancement**: A new feature
- **bug**: A bug fix
- **documentation**: Documentation only changes

## Branch

This repository have these branchs:

- **Contributor's branch**: Develpoer can fork main branch as their delelopment branch anytime
- **main branch**: The only branch that accepts PR from Contributors's branch
- **production branch**: For version release and don't permit modify directly, only merge PR from **main branch**

Flow: Contributor's branch → main branch → production branch

#### what is pull request

[Pull request](https://docs.github.com/pull-requests) let you tell others about changes you've pushed to a branch in a repository on GitHub.

#### When is PR produced?

- Contributor commit to main branch
- main branch commit to production branch

#### How to deal with PR?

1. [pull request reviews](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews)
2. Merge RP and CI/CD for it

## licensing

See the [LICENSE](https://github.com/Websoft9/docker-library/blob/main/LICENSE.md) file for our project's licensing. We will ask you to confirm the licensing of your contribution.

We may ask you to sign a [Contributor License Agreement (CLA)](http://en.wikipedia.org/wiki/Contributor_License_Agreement) for larger changes.
