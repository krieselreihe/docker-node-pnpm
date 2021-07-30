# Contributing

## Build image

To build the image run the following commands (replace `X.X.X` with the desired new version).

```shell
docker build .circleci/images/circleci
docker build -t krieselreihe/node-pnpm:X.X.X .circleci/images/circleci
```

## Publish image

```shell
docker push krieselreihe/node-pnpm:X.X.X
```
