Note
For git-spring-config-server
please create a folder "D:\\Microservices\\configprop\\config-server-repo" or any folder in your C or any drive and put
all the configuration files in that folder.

Then put the same path in bootstrap.properties file
server.port=8888
spring.cloud.config.server.git.uri=D:\\Microservices\\configprop\\config-server-repo
management.security.enabled=false
