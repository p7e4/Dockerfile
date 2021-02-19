# Dockerfile

## Build with URL

`docker build -t apache-php https://raw.githubusercontent.com/p7e4/Dockerfile/main/apache-php`

## docker-compose.yaml

``` yaml
version: "3"
services:
  test:
    build: https://raw.githubusercontent.com/p7e4/Dockerfile/main/apache-php
    image: test-image
```

## Description

| File | Description |
| ------ | ------ |
| [apache-php](https://raw.githubusercontent.com/p7e4/Dockerfile/main/apache-php) | latest apache2 and php(no additional extensions), no mysql |



