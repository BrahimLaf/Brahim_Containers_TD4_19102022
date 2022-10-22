FROM alpine:3.15.0

LABEL version="1.0.0" maintainer="Brahim LAFDI" os="ubuntu"

ENV CONTAINER_USER="BrahimLafdi"

RUN apk add figlet
#RUN apk add cygwin
#RUN apk add Tollet
#RUN apk add lolcat

RUN adduser -D $CONTAINER_USER
USER $CONTAINER_USER



#CMD  "hello-alpine, I’m ""$CONTAINER_USER" " and this is a container from my first image"
#CMD figlet  "hello-alpine, I’m "$CONTAINER_USER" and this is a container from my first image"
CMD figlet -f slant "hello-alpine, Je suis "$CONTAINER_USER" et ceci est un container à partir de ma premiere image"
CMD figlet -f slant "hello-alpine, I'm "$CONTAINER_USER" and this is a container from my first image"

#CMD figlet -f -d  slant "Brahim Test" 
