## Clean Architecture
Go | gRPC | graphQL | REST | Wire | MySQL | Docker | Rabbitmq | Evans


### Running
1. Clone this repository in your machine
2. Run `go mod tidy` to install dependencies
3. Start containers services
   - `docker-compose up`
4. Run `make migrate` to create tables.
5. Start server `go run main.go wire_gen.go`
