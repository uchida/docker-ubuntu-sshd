# docker-ubuntu-sshd

[![License](https://img.shields.io/github/license/uchida/docker-ubuntu-sshd.svg?maxAge=2592000)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)
[![MicroBadger](https://images.microbadger.com/badges/image/auchida/ubuntu-sshd.svg)](http://microbadger.com/images/auchida/ubuntu-sshd)

sshd enabled ubuntu docker image

Docker image is available as [auchida/ubuntu-sshd](https://hub.docker.com/r/auchida/ubuntu-sshd/) in Docker Hub.

## Image tags

- `16.04`, `xenial`, `latest`
- `14.04`, `trusty`

## Usage

```console
$ docker run -d -p 2222:22 auchida/ubuntu-sshd
$ ssh root@localhost -p 2222 # or ssh ubuntu@localhost -p 2222
```

## Installed packages

- openssh-server
- python
- python-apt
- sudo

## Login information

|user  |password|
|------|--------|
|root  |root    |
|ubuntu|ubuntu  |

## License

Contents on this repository are dedicated to [![CC0 public domain](http://i.creativecommons.org/p/zero/1.0/80x15.png "CC0 public domain")](https://creativecommons.org/publicdomain/zero/1.0/).
No rights reserved.

License for distributed Docker images follows one of [Ubuntu Project](http://www.ubuntu.com/about).
