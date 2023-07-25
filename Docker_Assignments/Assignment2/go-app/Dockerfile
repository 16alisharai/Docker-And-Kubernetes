#base image golang latest
FROM golang:latest

WORKDIR /app

COPY . .

RUN go build -o go-app .

EXPOSE 8080

CMD ["./go-app"]




