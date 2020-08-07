# go-grpc-practice
Practice examples for building gRPC micro services with go and generating protobuf files.

//install grpc
go get -u google.golang.org/grpc

//install protocol buffer generator
go get -u github.com/golang/protobuf/protoc-gen-go

//generate/update pb files:
bash generate.sh

//run
go run service/service_server/server.go
go run service/service_client/client.go