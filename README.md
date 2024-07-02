# A Microservice App with gRPC Transport Written in Golang

# Installing protobuffer

## MacOS

```
brew install protobuff
```

### gRPC and Protobuffer package dependencies

go get -u google.golang.org/protobuf/cmd/protoc-gen-go
go install google.golang.org/protobuf/cmd/protoc-gen-go

go get -u google.golang.org/grpc/cmd/protoc-gen-go-grpc
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc

NOTE: Add the `protoc-gen-go-grpc` to machine PATH

```
PATH="${PATH}:${HOME}/go/bin"
```

### Running the service

```
make run
```
