FROM alpine:3.7
 
WORKDIR /opt

RUN apk update 
RUN apk add mysql-client

COPY . /opt

RUN chmod +x import.sh
ENTRYPOINT ./import.sh
