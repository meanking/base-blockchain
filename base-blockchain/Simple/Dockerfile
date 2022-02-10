FROM golang:latest 

LABEL base.name="Base blockchain"

WORKDIR /app 

COPY . . 

RUN go build . 

EXPOSE 3002 

ENTRYPOINT [ "./blockchain" ]