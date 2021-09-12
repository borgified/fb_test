FROM ubuntu
RUN apt-get -y update
RUN apt-get -y install netcat
CMD echo "sending hello to server" &&  echo "hello" | nc server 2399
