FROM docker.io/dockerskoleni/golang:1.11

WORKDIR /go/src/app
COPY . .

RUN go get -d -v ./...
RUN go build -o /app

CMD ["/app"]
