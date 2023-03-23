# script-protobuff
this repo is used to generate protobuff

#to generate
user protobuf : protoc --go_out=. --go_opt=paths=source_relative     --go-grpc_out=. --go-grpc_opt=paths=source_relative     proto/user.proto
