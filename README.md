

## Refer to: https://verdaccio.org/docs/en/what-is-verdaccio


## Prerequisites
* docker
* docker-compose
* You need create storage diretory in current root directory
  ```
  $ mkdir storage
  ```

## Diretory Arch
* docker-compose.yml   docker-compose主配置文件
* conf/     verdaccio的配置文件
* storage/  verdaccio的存储目录
## How to start

```
$ docker-compose up
```

## Remove

```
$ docker-compose stop
$ docker-compose rm
```
