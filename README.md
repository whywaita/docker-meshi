# docker-meshi

Dockernize [meshi](https://github.com/uecmma/meshi) command.

# Usage

## use DockerHub

Put your rc file (ex. bashrc,zshrc)

```
alias meshi=`docker run whywaita/meshi`
```

## build your computer

build

```
$ git clone https://github.com/whywaita/docker-meshi
$ cd docker-meshi
$ docker build -t local/meshi .
```

run

```
$ docker run local/meshi
```
