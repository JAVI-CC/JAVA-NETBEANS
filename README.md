# JAVA-NETBEANS
Docker imagen JAVA-NETBEANS para utilitzar el programa JAVA NETBEANS V8.0.1

# USAGE
docker run -ti --name java-netbeans -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v `pwd`/.netbeans-docker:/home/developer/.netbeans -v ``pwd``:/workspace javi98/java-netbeans
