# docker-vimgolf

Docker image for [Vimgolf](http://www.vimgolf.com).

Took idea from https://github.com/kramos/vimgolf

hosted at https://hub.docker.com/repository/docker/hettomei/vimgolf

# Version 1.0

VIM - Vi IMproved 8.0 (2016 Sep 12, compiled Jun 21 2019 04:10:35)

vimgolf 0.5.0

# how to get and use it from docker hub

```
docker run --rm -it -e "key=vimgolf_personal_key" hettomei/vimgolf vimgolf_challenge_ID
```

# how to go from source

```
docker build -t vimgolf .
docker run --rm -it -e "key=vimgolf_personal_key" vimgolf 5f0f5fbe280fbf000c233304
```
