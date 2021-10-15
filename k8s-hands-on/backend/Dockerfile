FROM golang:1.17.1-alpine

WORKDIR /app

COPY ./src/*.go .
COPY go.mod .

RUN go build -o app

CMD [ "./app" ]