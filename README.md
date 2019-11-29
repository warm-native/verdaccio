

## Refer to: https://verdaccio.org/docs/en/what-is-verdaccio


## Prerequisites
* docker
* docker-compose
* You need create storage diretory in current root directory
  ```
  $ mkdir storage
  ```

## Diretory Arch
* docker-compose.yml   docker-compose主配置文件, 默认verdaccio的版本是latest
* conf/config.yaml     verdaccio的配置文件
* storage/  verdaccio的存储目录
## How to start

```
$ docker-compose up
```

## Then
1. cache npmjs.org
```
$ npm registry http://[verdaccio-ip]:4873
```
_注_: `verdaccio-ip` need change to real ip. 


2. publish package, flow as below

![Image](images/verdaccio-publish.png)

Enjoy it.

## Remove

```
$ docker-compose stop
$ docker-compose rm
```
