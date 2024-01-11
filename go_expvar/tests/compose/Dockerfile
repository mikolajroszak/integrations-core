FROM golang:1.20.13
RUN mkdir /test_go
ADD test_expvar.go /test_go
EXPOSE 8079
ENTRYPOINT ["go", "run", "/test_go/test_expvar.go"]
