FROM golang:1.12-alpine3.9

RUN apk add git

RUN mkdir /src/

COPY main.go /src/
COPY go.mod /src/

WORKDIR /src/

RUN cat go.mod

RUN go build; exit 0

RUN cat go.mod
