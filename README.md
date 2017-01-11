![MoneyComb Logo](./Icon 8KB.png)
# Moneycomb Tech Documentation
Mainly meant for a DevOps type of person

## Key Systems
| System       |  Purpose    | Hosted By |
| ------------ |-----------| :--------:|
| App | the main application| MDG Galaxy |
| MSS | MoneyComb Scheduler System - hosted as a docker container| Digital Ocean |

This is a [link to a page called booger](./booger.md)

## Main Cloud Providers
### Galaxy
### Digital Ocean
### Compose.io
### Github
### Docker.com

### Running this as a Docker Image

See: https://hub.docker.com/r/ulexus/meteor/

```
docker run --rm \
  -e ROOT_URL=http://stage.mymoneycomb.com \
  -e REPO=https://github.com/moneycomb/moneycomb \
  -e BRANCH=develop \
  -e MONGO_URL=mongodb://glenn:L1beration64@candidate.21.mongolayer.com:11057,candidate.37.mongolayer.com:11079/stage-db?replicaSet=set-5641699de9bf3797d9000015 \
  ulexus/meteor
```
