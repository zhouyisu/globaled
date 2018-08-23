# Globalization & Education
Course slides are written in rmarkdown (`.rmd` file). It can be either viewed online in github or downloaded and opened with any text editor. The slides were rendered to html using [xaringan](https://github.com/yihui/xaringan). 

## View slides
To view the slides as they were presented in class, visit:
- 8/23 https://zhouyisu.github.io/globaled/session01
- 8/27 https://zhouyisu.github.io/globaled/session02

## Print slides
To print the handouts, use google Chrome's print function (e.g. `Ctrl + p` or `CMD + p`). Firefox or other browsers are not supported. 

Alternatively, an automated approach is available by using [decktape.js](https://github.com/astefanutti/decktape). For simplicity, use docker version of `decktape`:

```
# download & install docker here:
https://store.docker.com/search?offering=community&type=edition

# run decktape from terminal
docker run astefanutti/decktape https://zhouyisu.github.io/globaled/session01 session01.pdf

# copy the .pdf file to your current directory
docker cp `docker ps -lq`:slides/session01.pdf .

# remove the lastest used container
$ docker rm `docker ps -lq`
```
