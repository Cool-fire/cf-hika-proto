# Hika-Proto


### command to generate code from proto files
```shell
protoc --go_out=gen/ --go_opt=paths=source_relative \
--go-grpc_out=gen/ --go-grpc_opt=paths=source_relative \
proto/manager/status/service.proto
```