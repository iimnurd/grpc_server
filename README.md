Original Tutorial and Source : https://medium.com/@amsokol.com/tutorial-how-to-develop-go-grpc-microservice-with-http-rest-endpoint-middleware-kubernetes-daebb36a97e9


Step :
- Create mysql database "grpc_db"
- Run table.sql
- Clone this source
- Build and run project



Build and Run Server :
- cd cmd/server
- go build .
- ./server   -grpc-port=9090 -db-host=localhost:3306 -db-user=root -db-password= -db-name=grpc_db




Build and Run Client :
- cd cmd/client-grpc
- go build .
- ./client-grpc -server=localhost:9090



Jmeter sampler for GRPC Testing:
Github : https://github.com/iimnd/jmeter-grpc-sampler
