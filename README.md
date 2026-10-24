# sdnext-cuda-docker-build

Builds the [SD.Next](https://github.com/vladmandic/sdnext) CUDA Docker image from upstream `master`, since the official Docker Hub image is no longer updated.

A GitHub Action checks upstream once a day and builds only when there's a new commit.

## Usage

```
docker pull ghcr.io/darwinanim8or/sdnext-cuda:master
```

Tags:

- `master`: latest build
- `master-<sha>`: a specific upstream commit

For run options, see SD.Next's own [Docker docs](https://github.com/vladmandic/sdnext/wiki/Docker).
