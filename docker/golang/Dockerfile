FROM golang:alpine

ADD ./backend /app/go

WORKDIR /app/go

RUN go build -o main . 

CMD ["/app/go/main"]