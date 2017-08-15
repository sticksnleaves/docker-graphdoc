# Supported tags and respective `Dockerfile` links

* [`2.4.0`, `2.4`, `2`, `latest` (2.4/Dockerfile)](https://github.com/sticksnleaves/docker-dex/blob/27ca49aed37b6a8ddddba02dc498840824fd6b3e/Dockerfile)

# How to use this image

## Generate documentation from live endpoint

```
$ docker run sticksnleaves/graphdoc -e http://localhost:8080/graphql -o ./doc/schema
```

## Generate documentation from IDL file

```
$ docker run sticksnleaves/graphdoc -s ./schema.graphql -o ./doc/schema
```

## Generate documentation from for the "modularized schema" of graphql-tools

```
$ docker run sticksnleaves/graphdoc -s ./schema.js -o ./doc/schema
```

## Generate documentation from json file

```
$ docker run sticksnleaves/graphdoc -s ./schema.json -o ./doc/schema
```
