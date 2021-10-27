# TEMPLATE_PYTHON_PACKAGE




## Python Versions

This project actively supports these Python versions:

* 3.10
* 3.9
* 3.8
* 3.7
* 3.6


## Image Variants

Like the upstream Python containers themselves a variety of image variants are supported.


### Full

The default container type, and if you're not sure what container to use start here. It has a variety of libraries and build tools installed, making it easy to extend.



### Slim

This container is similar to Full but with far less libraries and tools installed by default. If yo're looking for the tiniest possible image with the most stability this is your best bet.



### Alpine

This container is provided for those who wish to use Alpine. Alpine works a bit differently than the other image types, as it uses `musl` instead of `glibc` and many libaries are not well tested under `musl` at this time.



## Architectures

Every tag in this repository supports these architectures:

* linux/amd64
* linux/arm64
* linux/arm/v7



## Tags
* Recommended Image: `ghcr.io/multi-py/multipy-image-template:py3.10-0.1.1`
* Slim Image: `ghcr.io/multi-py/multipy-image-template:py3.10-slim-0.1.1`

Tags are based on the package version, python version, and the upstream container the container is based on.

| TEMPLATE_PYTHON_PACKAGE Version | Python Version | Full Container | Slim Container | Alpine Container |
|-----------------------|----------------|----------------|----------------|------------------|
| latest | 3.10 | py3.10-latest | py3.10-slim-latest | py3.10-alpine-latest |
| latest | 3.9 | py3.9-latest | py3.9-slim-latest | py3.9-alpine-latest |
| latest | 3.8 | py3.8-latest | py3.8-slim-latest | py3.8-alpine-latest |
| latest | 3.7 | py3.7-latest | py3.7-slim-latest | py3.7-alpine-latest |
| latest | 3.6 | py3.6-latest | py3.6-slim-latest | py3.6-alpine-latest |
| 0.1.1 | 3.10 | py3.10-0.1.1 | py3.10-slim-0.1.1 | py3.10-alpine-0.1.1 |
| 0.1.1 | 3.9 | py3.9-0.1.1 | py3.9-slim-0.1.1 | py3.9-alpine-0.1.1 |
| 0.1.1 | 3.8 | py3.8-0.1.1 | py3.8-slim-0.1.1 | py3.8-alpine-0.1.1 |
| 0.1.1 | 3.7 | py3.7-0.1.1 | py3.7-slim-0.1.1 | py3.7-alpine-0.1.1 |
| 0.1.1 | 3.6 | py3.6-0.1.1 | py3.6-slim-0.1.1 | py3.6-alpine-0.1.1 |
| 0.1.0 | 3.10 | py3.10-0.1.0 | py3.10-slim-0.1.0 | py3.10-alpine-0.1.0 |
| 0.1.0 | 3.9 | py3.9-0.1.0 | py3.9-slim-0.1.0 | py3.9-alpine-0.1.0 |
| 0.1.0 | 3.8 | py3.8-0.1.0 | py3.8-slim-0.1.0 | py3.8-alpine-0.1.0 |
| 0.1.0 | 3.7 | py3.7-0.1.0 | py3.7-slim-0.1.0 | py3.7-alpine-0.1.0 |
| 0.1.0 | 3.6 | py3.6-0.1.0 | py3.6-slim-0.1.0 | py3.6-alpine-0.1.0 |


### Older Tags

Older tags are left for historic purposes but do not receive updates. A full list of tags can be found on the package's [registry page](https://github.com/multi-py/multipy-image-template/pkgs/container/multipy-image-template).


