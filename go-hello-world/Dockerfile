FROM golang:latest

WORKDIR /src/app

COPY main.go .

RUN go mod init gohelloworld

EXPOSE 8080

CMD ["go", "run", "main.go"]
