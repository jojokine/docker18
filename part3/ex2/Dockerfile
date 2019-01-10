FROM ubuntu:16.04 

ENV LC_ALL=C.UTF-8 

RUN apt-get update && apt-get install -y \ 
    python python-pip wget ffmpeg && \ 
    pip install pycrypto yle-dl && \ 
    rm -rf /var/lib/apt/lists/* 

ENTRYPOINT ["yle-dl", "--destdir", "/downloads/"]


