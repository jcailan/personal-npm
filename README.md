# Personal NPM Registry

This respository host the node module that can act as personal npm registry. This module is packaged to be deploy on SAP BTP for the Cloud Foundry environment.

## Deployment

Deploy using `cf push` command.

## Set npm config for scoped package

```shell
> npm config set @rizing:registry=https://<hostname>/
```

## Publishing packages

Publish using command `npm publish` for `@rizing` package scope