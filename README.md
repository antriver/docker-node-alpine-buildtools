These are Docker images containing Node on Alpine Linux, with some extra packages for installing node modules
that do some building when they are installed.

## Building and Publishing

    docker build -t antriver/node-alpine-buildtools:16.14.0-alpine3.15 .
    docker push antriver/node-alpine-buildtools:16.14.0-alpine3.15
