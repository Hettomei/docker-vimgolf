# docker-vimgolf

Docker image for [Vimgolf](http://www.vimgolf.com).

Took idea from https://github.com/kramos/vimgolf

# Version 1.0

VIM - Vi IMproved 8.0 (2016 Sep 12, compiled Jun 21 2019 04:10:35)

vimgolf 4.9

# how to use it

```
docker run --rm -it -e "key=vimgolf_personal_key" hettomei/vimgolf vimgolf_challenge_ID
```

# how to build from source

```
docker build -t vimgolf .
```
