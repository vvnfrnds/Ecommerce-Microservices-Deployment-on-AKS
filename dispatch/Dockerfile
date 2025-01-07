FROM golang:1.17
WORKDIR /go/src/app
COPY *go. /go/src/app/
RUN go mod init dispatch && go get
RUN go install
CMD dispatch
