FROM tomcat:9 
RUN cp -R /usr/local/tomcat/webapps.dist/. /usr/local/tomcat/webapps/ 
EXPOSE 8080  
COPY build/libs/*.war /usr/local/tomcat/webapps/
