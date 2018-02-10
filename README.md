# Thunderbird-Lightning-DAViCal-server

Thunderbird Lightning DAViCal server is docker images

## websites

-[thunderbird](https://www.mozilla.org/de/thunderbird/)
-[Lightning Calendar](https://www.mozilla.org/en-US/projects/calendar/)
-[DaviCal](https://www.davical.org/)

## ubuntu wiki

-[thunderbird](https://wiki.ubuntuusers.de/Thunderbird/)
-[Lightning](https://wiki.ubuntuusers.de/Thunderbird/Lightning/)
-[DaviCal](https://wiki.ubuntuusers.de/DAViCal/)



## docker images all inclusive

- for a quick overview
    -[natansdj/davical](https://hub.docker.com/r/natansdj/davical/)
- Only a

```bash
> docker pull natansdj/davical
> docker run --name mydavical --publish=80:80 natansdj/davical
```




## settings devices

-[BB10](http://support.blackberry.com/kb/articleDetail?ArticleNumber=000033093)
-[BB10](https://www.a1blog.net/2013/05/08/blackberry-10-tipp-synchronisation-der-kontakte-und-termine-mit-der-icloud/)



## docker housekeeping

```bash
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
```