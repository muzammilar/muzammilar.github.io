# muzammilar.github.io


## Development

```sh
## Run without docker-compose
docker run --rm --volume="${PWD}:/srv/jekyll"  -p 4000:4000 -it jekyll/jekyll:latest bash
# build (or skip)
jekyll build
# run jekyll server for local testing
jekyll server --watch --increment

## Run container with docker-compose
docker-compose up

## Connect to localhost:4000 in your favourite browser
```
