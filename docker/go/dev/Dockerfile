FROM golang:1.27

WORKDIR /usr/src/app

RUN go install github.com/air-verse/air@latest
RUN go install github.com/go-delve/delve/cmd/dlv@latest
RUN go install -tags 'postgres' \
  github.com/golang-migrate/migrate/v4/cmd/migrate@latest

CMD ["air"]
