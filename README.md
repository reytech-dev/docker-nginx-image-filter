# Nginx Image Filter PoC

This repository is an nginx_image_filter module PoC based on two docker containers. One container is working as reverse proxy, while the second container is serving the images.

The used example images are from [Unsplash](https://unsplash.com)

Credits: [\_\_credit.json](nginx/images/__credits.json)

## Requirements

- docker
- docker-compose
- user which is allowed to run docker

## Usage

Set image permissions:

```sh
$ cd project/directory/ && chown -R 100:100 nginx/images
```

Start containers:

```sh
$ cd project/directory/ && docker-compose up
```
