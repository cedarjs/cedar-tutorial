# Cedar Tutorial App

This repo represents the final state of the app created during the [Cedar Tutorial](https://cedarjs.com/docs/tutorial).
It is meant to be a starting point for those working on the second half of the Tutorial, starting at the [Intermission](https://cedarjs.com/docs/tutorial/intermission).

This repo contains much more styling than the one we built together in the tutorial, but is functionally identical.

## Setup

The [tutorial itself](https://cedarjs.com/docs/tutorial/chapter1/prerequisites) contains instructions for getting this repo up and running, but here is a summary of the commands:

```bash
git clone https://github.com/cedarjs/cedar-tutorial
cd cedar-tutorial
yarn install
yarn cedarjs prisma migrate dev
yarn cedarjs prisma db seed
yarn cedarjs dev
```
