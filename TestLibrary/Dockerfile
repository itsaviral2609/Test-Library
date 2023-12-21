FROM golang:1.18.0

WORKDIR /home
COPY ./pkg /home

RUN cd /home && go build -o library

CMD ["/home/library"]
