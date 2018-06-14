# Apollo Server Beta

[![npm version](https://badge.fury.io/js/apollo-server-core.svg)](https://badge.fury.io/js/apollo-server-core)
[![Build Status](https://circleci.com/gh/apollographql/apollo-cache-control-js.svg?style=svg)](https://circleci.com/gh/apollographql/apollo-cache-control-js)
[![Get on Slack](https://img.shields.io/badge/slack-join-orange.svg)](https://www.apollographql.com/#slack)

Apollo Server is a community-maintained open-source GraphQL server. It works with pretty much all Node.js HTTP server frameworks, and we're happy to take PRs for more! Apollo Server works with any GraphQL schema built with [GraphQL.js](https://github.com/graphql/graphql-js), so you can build your schema with that directly or with a convenience library such as [graphql-tools](https://www.apollographql.com/docs/graphql-tools/).

## Documentation

[Read the docs!](https://www.apollographql.com/docs/apollo-server/)

## Principles

Apollo Server is built with the following principles in mind:

* **By the community, for the community**: Apollo Server's development is driven by the needs of developers
* **Simplicity**: by keeping things simple, Apollo Server is easier to use, easier to contribute to, and more secure
* **Performance**: Apollo Server is well-tested and production-ready - no modifications needed

Anyone is welcome to contribute to Apollo Server, just read [CONTRIBUTING.md](./CONTRIBUTING.md), take a look at the [roadmap](./ROADMAP.md) and make your first PR!

## Getting started

- 1 - `git clone git@github.com:rodrigooler/apollo-server-beta.git`
- 2 - `cd apollo-server-beta`
- 3 - `npm run start or npm run dev (nodemon)`;

## With docker
>
>- 1 - `install docker`
>- 2 - `docker build -t <your-username>/apollo-server-beta .`
>- 3 - `docker run -p <port-output>:3000 -d <your-username>/apollo-server-beta`

>### Options
>* **Get container ID** `$ docker ps`
>* **Enter the container** `$ docker exec -it <container id> /bin/bash`
>* **Print app output** `$ docker logs <container id>` 