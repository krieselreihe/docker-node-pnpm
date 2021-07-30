# Contributing

## Build image

To build the image run the following commands (replace `X.X.X` with the desired new version).

```shell
docker build images/circleci
docker build -t krieselreihe/node-pnpm:X.X.X images/circleci
```

## Publish image

```shell
docker push krieselreihe/node-pnpm:X.X.X
```
