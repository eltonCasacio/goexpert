## Clean Architecture
Go | gRPC | graphQL | REST | Wire | MySQL | Docker | Rabbitmq | Evans


### Running
1. `git clone https://github.com/eltonCasacio/goexpert`
2. `go mod tidy` to install dependencies
3. `docker-compose up` to start mysql, evans and rabbitmq
4. `make migrate` to create tables.
5. `go run main.go wire_gen.go` to start server. (run this command into **_cmd/ordersystem_**)
