FROM python:buster 

RUN useradd -ms /bin/bash container
USER container
ENV USER=container HOME=/home/container

WORKDIR /home/container

CMD ["/bin/bash" ]
