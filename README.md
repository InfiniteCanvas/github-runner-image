# github-runner-image [![build-and-push](https://github.com/InfiniteCanvas/github-runner-image/actions/workflows/build-and-push.yml/badge.svg)](https://github.com/InfiniteCanvas/github-runner-image/actions/workflows/build-and-push.yml)
Builds [github-runner images](https://hub.docker.com/r/infinitecanvas/github-runner).

It's just [a github runner](https://github.com/actions/runner) in a docker image.<br>

Pass in these variables<br>

| Variable | Value |
| :-- | :-- |
| ORGANIZATION | YOUR-GITHUB-ORGANIZATION |
| ACCESS_TOKEN | YOUR-GITHUB-ACCESS-TOKEN |

Start it like this<br>
```
docker run \
  --detach \
  --env ORGANIZATION=<YOUR-GITHUB-ORGANIZATION> \
  --env ACCESS_TOKEN=<YOUR-GITHUB-ACCESS-TOKEN> \
  --name runner \
  image
```
