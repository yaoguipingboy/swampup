FROM localhost:8081/docker_virtual/docker-framework:latest

MAINTAINER hero

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
