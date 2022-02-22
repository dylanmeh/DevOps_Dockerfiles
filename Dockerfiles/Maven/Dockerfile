FROM alpine:3.14
ENV JAVA_HOME = /usr/lib/jvm/java-1.8-openjdk/jre
ENV PATH=${PATH}:${JAVA_HOME}/bin
RUN apk update
RUN apk add curl
RUN apk add git
RUN apk add maven
RUN apk add openjdk8
RUN apk add terraform
RUN apk add python py2-pip
RUN pip install cffi
RUN pip install ansible 
