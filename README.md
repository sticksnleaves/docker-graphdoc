# Supported tags and respective `Dockerfile` links

* [`2.4.0`, `2.4`, `2`, `latest` (2.4/Dockerfile)](https://github.com/sticksnleaves/docker-graphdoc/blob/f10e1afa7273d67a2b7c2402ff580f65f39267df/2.4/Dockerfile)

# How to use this image

## Generate documentation from live endpoint

```
$ docker run sticksnleaves/graphdoc graphdoc -e http://localhost:8080/graphql -o ./doc/schema
```

## Generate documentation from IDL file

```
$ docker run sticksnleaves/graphdoc graphdoc -s ./schema.graphql -o ./doc/schema
```

## Generate documentation from for the "modularized schema" of graphql-tools

```
$ docker run sticksnleaves/graphdoc graphdoc -s ./schema.js -o ./doc/schema
```

## Generate documentation from json file

```
$ docker run sticksnleaves/graphdoc graphdoc -s ./schema.json -o ./doc/schema
```

For more information on using graphdoc please read the [official documentation](https://github.com/2fd/graphdoc).
