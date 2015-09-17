heidecke/revealjs
---

Revealjs on a minimal Debian base image.

`heidecke/revealjs` is a Docker image based on `debian:jessie`. It includes
the stable nodejs and the latest reveal.js from github.

# Usage

Create a Dockerfile with the following content:

```
FROM heidecke/revealjs

ADD /presentationpath /opt/presentation
```