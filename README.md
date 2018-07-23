# docker-json-diff

https://github.com/andreyvit/json-diff in a Linux Alpine container

## Usage

```
docker run -ti \
           --rm \
           -v $PWD:$PWD \
           -w $PWD \
           bwowk/json-diff \
           file-a.json file-b.json
```
