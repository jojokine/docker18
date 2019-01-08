FROM ubuntu:16.04 

WORKDIR /
RUN apt-get update && apt-get -y install curl
COPY curler.sh . 
RUN chmod a+x curler.sh
CMD ["./curler.sh"]
