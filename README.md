# `python.node`

This image is based off the [`python:3.5`](https://hub.docker.com/_/python/) image and
contains a `node.js` installation based off the official [docker image](https://hub.docker.com/_/node/).

## Building and pushing new images
Assuming that the Python version we want to build is `3.5` and the Node.js version is `6.9.4`, then we can build
the images as such:

```bash
docker build -t python-node:3.5-6.9.4 .
docker push python-node:3.5-6.9.4
```

## Supported tags and respective `Dockerfile` links

- `3.5-6.9.4`: Python 3.5 with Node.js 6.9.4 ([Dockerfile](Dockerfile))
