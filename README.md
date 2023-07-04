## Clean Architecture
Go | gRPC | graphQL | REST | Wire | MySQL | Docker | Rabbitmq | Evans


### Running
1. Clone this repository in your machine
2. run `go mod tidy` to install dependencies
3. Start docker and create table
   - `docker-compose up`
   - `docker-compose exec mysql bash` to enter inside the container
   - `mysql -u root -p` to enter inside the mysql
   - so create table orders. (see internal/infra/database/order_repository_test)
4. start server `go run main.go wire_gen.go`
