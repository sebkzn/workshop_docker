FROM golang:latest

WORKDIR /static

COPY . .

RUN go build dispatcher.go

CMD [ "./dispatcher" ]

EXPOSE 80
