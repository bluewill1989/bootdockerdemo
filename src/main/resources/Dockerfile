FROM java:8
MAINTAINER wzn

ADD bootdocker.jar bootdocker.jar

EXPOSE 8901

#ENTRYPOINT ["sh","-c","java -jar /app.jar $PARAMS"]

CMD [ "sh","/home/weizenan/servers/bin/sm.sh bootdocker" ]