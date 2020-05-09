FROM tomcat:9.0.34-jdk8-corretto

RUN cp -r webapps.dist/* webapps/
COPY conf/server.xml /usr/local/tomcat/conf/server.xml

CMD ["catalina.sh", "run"]
