# Mattermost Marketplace ![CircleCI branch](https://img.shields.io/circleci/project/github/mattermost/mattermost-marketplace/master.svg)

The Mattermost Marketplace is a collection of plugins for use with [Mattermost](https://github.com/mattermost/mattermost-server). This repository houses the stateless HTTP service that will eventually run at marketplace.integrations.mattermost.com. It is meant to be queried by the Mattermost server to enable plugin discovery by system administrators.

Although Mattermost hosts the marketplace as an AWS Lambda function backed by S3 and CloudFront, the core feature set is designed for use in any hosting environment, enabling private, self-hosted collections of plugins.

Read more about the [Mattermost Integrations Marketplace Architecture](https://docs.google.com/document/d/1tVj0eNwMdIIGn8YoTs-cYz9NYvXjqx6bqWH-wa-yDLk/edit).

## Other Resources

This repository houses the open-source components of the Mattermost Integrations Marketplce. Other resources are linked below:

- [Mattermost the server and user interface](https://github.com/mattermost/mattermost-server)

## Get Involved

- [Join the discussion on Integrations Marketplace](https://community.mattermost.com/core/channels/marketplace)