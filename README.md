# rstudio-env

**Pull docker image** 

```
docker pull dceoy/rstudio-server
```

**Default username and password:**

username: rstudio
password: rstudio

**Usage**

*Run a server*

```
$ docker container run --rm -p 8787:8787 -v ${PWD}:/home/rstudio -w /home/rstudio dceoy/rstudio-server
```

*Run a server with docker-compose*

```
$ docker-compose -f /path/to/docker-rstudio-server/docker-compose.yml up
```

## Package install 

https://blog.sellorm.com/2017/10/21/quick-script-to-install-an-r-package-from-the-command-line/

## Reference

https://hub.docker.com/r/dceoy/rstudio-server/

