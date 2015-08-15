# Cozy data indexer

Data volume container to store cozy couchdb data


## Pull the image

```
$ docker pull spiroid/cozy-couchdb-data
```

## Build it yourself

```
$ git clone git@github.com:spiroid/cozy-couchdb-data.git
$ cd cozy-couchdb-data
$ doker build -t spiroid/cozy-couchdb-data .
```


## Related images

This configuration image was created to work with the following images:

 * [cozy controller](https://github.com/spiroid/cozy-controller)
 * [cozy data indexer](https://github.com/spiroid/cozy-data-indexer)
 * [cozy couchdb](https://github.com/spiroid/cozy-couchdb)


For more information about data volume container see the [official documentation](https://docs.docker.com/userguide/dockervolumes/).
