comand: protoc --go_out=./pb --go-grpc_out=./pb catalog.proto

```
go-ecommerce-app
├─ account
│  ├─ account.proto
│  ├─ app.dockerfile
│  ├─ client.go
│  ├─ cmd
│  │  └─ account
│  │     └─ main.go
│  ├─ db.dockerfile
│  ├─ pb
│  │  ├─ account.pb.go
│  │  └─ account_grpc.pb.go
│  ├─ repository.go
│  ├─ server.go
│  ├─ service.go
│  └─ up.sql
├─ catalog
│  ├─ app.dockerfile
│  ├─ catalog.proto
│  ├─ client.go
│  ├─ cmd
│  │  └─ catalog
│  │     └─ main.go
│  ├─ db.dockerfile
│  ├─ pb
│  ├─ repository.go
│  ├─ server.go
│  └─ service.go
├─ docker-compose.yaml
├─ go.mod
├─ go.sum
├─ graphql
│  ├─ account_resolver.go
│  ├─ app.dockerfile
│  ├─ generated.go
│  ├─ gqlgen.yml
│  ├─ graph.go
│  ├─ main.go
│  ├─ models.go
│  ├─ models_gen.go
│  ├─ mutation_resolver.go
│  ├─ query_resolver.go
│  └─ schema.graphql
├─ order
└─ README.md

```
