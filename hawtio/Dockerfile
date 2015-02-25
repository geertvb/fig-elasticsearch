FROM geertvb/java

RUN mkdir -p /hawtio

#ADD https://oss.sonatype.org/content/repositories/public/io/hawt/hawtio-app/1.4.45/hawtio-app-1.4.45.jar /hawtio/hawtio-app-1.4.45.jar
ADD hawtio-app-1.4.45.jar /hawtio/hawtio-app-1.4.45.jar

EXPOSE 8080

WORKDIR /hawtio

CMD java -jar hawtio-app-1.4.45.jar