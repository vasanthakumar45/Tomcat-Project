FROM tomcat:10.1-jdk17-openjdk
RUN rm -rf /usr/local/tomcat/webapps/*
COPY ./webapp /usr/local/tomcat/webapps/ROOT
EXPOSE 8080
CMD ["catalina.sh", "run"]

