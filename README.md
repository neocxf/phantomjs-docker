# phantomjs-docker
Phantomjs installed into tomcat8 environment or jre8 environment to enable the conversion from html to pdf provided by PhantomJs

## Why we need this?
Phantomjs library provide the ability of transform html file into pdf file. But to interact with the java library, we have to installed it into
our host environment, which is not very suitable for production request. So we provide the docker image for jre-based and tomcat-based web
application.

## How to use this?
Of course, you can download the Dockerfile and build yourself. But we have already build the image for you and publish at [docker hub](https://hub.docker.com/u/neocxf/).
You just need pull the image from there, and write your own docker-compose file
