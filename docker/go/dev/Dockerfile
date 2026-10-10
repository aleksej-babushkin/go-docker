FROM golang:1.27

WORKDIR /usr/src/app

RUN go install github.com/air-verse/air@latest
RUN go install github.com/go-delve/delve/cmd/dlv@latest

CMD ["air"]
