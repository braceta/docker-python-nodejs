<!-- [![Travis](https://img.shields.io/travis/nikolaik/docker-python-nodejs.svg?style=flat-square)](https://travis-ci.org/nikolaik/docker-python-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/nikolaik/python-nodejs.svg?style=flat-square)](https://hub.docker.com/r/nikolaik/python-nodejs/)
[![Release](https://img.shields.io/github/release/nikolaik/docker-python-nodejs.svg?style=flat-square)](https://github.com/braceta/docker-python-nodejs/releases) -->

## Python (latest) with Node.js 10.x based on [beevelop/nodejs-python](https://github.com/beevelop/docker-nodejs-python)
- Node: 10.x
- npm: 6.x
- yarn: stable
- Python: latest
- pip: latest
- pipenv: latest

----
### Pull from Docker Hub
```
docker pull nikolaik/python-nodejs:latest
```

### Build from GitHub
```
docker build -t braceta/python-nodejs github.com/braceta/docker-python-nodejs
```

### Run image
```
docker run -it braceta/python-nodejs bash
```

### Use as base image
```Dockerfile
FROM braceta/python-nodejs:latest
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!
