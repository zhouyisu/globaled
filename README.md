# Globalization & Education
Course slides are written in rmarkdown (`.rmd` file). It can be either viewed online in github or downloaded and opened with any text editor. The slides were rendered to html using [xaringan](https://github.com/yihui/xaringan). 

## Content
The first half of the course material is based on the textbook by Ritzer, G. nd Dean, P. (2015). _Globalization: A Basic Text._ Wiley-Blackwell, 2 edition. Though the actual delivery is heavily localized to meet my students' preferences. 

## View slides
To view the slides as they were presented in class, visit:
- 08/23 https://zhouyisu.github.io/globaled/session01
- 08/27 https://zhouyisu.github.io/globaled/session02
- 08/30 https://zhouyisu.github.io/globaled/session03
- 09/03 https://zhouyisu.github.io/globaled/session04
- 09/06 https://zhouyisu.github.io/globaled/session05
- 09/10 https://zhouyisu.github.io/globaled/session06
- 09/13 https://zhouyisu.github.io/globaled/session07
- 09/17 Typhoon Mangkhut, class cancelled
- 09/20 https://zhouyisu.github.io/globaled/session08 (rescheduled)
- 09/24 https://zhouyisu.github.io/globaled/session09 (rescheduled: online lecture)
- 09/24 Session 10: Consultation, no slides
- 09/27 https://zhouyisu.github.io/globaled/session11
- 10/01 Session 12: National holiday, NO CLASS
- 10/04 https://zhouyisu.github.io/globaled/session13
- 10/08 https://zhouyisu.github.io/globaled/session14
- 10/11 https://zhouyisu.github.io/globaled/session15
- 10/15 Session 16: Video presentation production
- 10/18 Session 17: Presentation & community feedbacks
- 10/22 https://zhouyisu.github.io/globaled/session18

## Print slides
To print the handouts, use google Chrome's print function (e.g. `Ctrl + p` or `CMD + p`). Firefox or other browsers are not supported. 

Alternatively, an automated approach is available by using [decktape.js](https://github.com/astefanutti/decktape). For simplicity, use docker version of `decktape`:

```
# download & install docker here:
https://store.docker.com/search?offering=community&type=edition

# run decktape from terminal
docker run astefanutti/decktape https://zhouyisu.github.io/globaled/session01 session01.pdf

# copy the .pdf file to your current directory
docker cp `docker ps -lq`:slides/session01.pdf session01.pdf.

# remove the lastest used container
$ docker rm `docker ps -lq`
```
