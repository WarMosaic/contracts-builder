# contracts-builder

This Docker image contains the base necessary to run CI builds for the WarMosaic [contracts](https://github.com/warmosaic/contracts) repo. 

This sets up:

* Node.js
* PNPM
* Foundry
* Solidity v0.8.21

The latest image is always available at: https://ghcr.io/warmosaic/contracts-builder:latest

## Development

Ensure you have Docker installed locally.

Build the image:

```shell
make build
```

Run the image locally:

```zsh
make run
```

## Publishing the image

In case you need to make any updates to this image, push changes to `master` (or any other) branch and manually trigger the `Build and Publish Docker` workflow in github actions.

