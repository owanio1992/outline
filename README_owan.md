# update yarn.lock
```
yarn install
```


# build image 
```
# base
docker buildx bake -f docker-compose_owan.yml --push --progress plain outline-base
docker buildx bake -f docker-compose_owan.yml --push --progress plain outline

```