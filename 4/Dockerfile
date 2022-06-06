FROM golang

WORKDIR /app
ADD . /app
ENV GO111MODULE=off
#RUN go mod init  test3 && go build -o meugo
RUN go build -o meugo
ENTRYPOINT ./meugo
