# api-transactions-golang

migrate command
migrate -path=internal/database/migrations -database "{db_url}?sslmode=disable" -verbose up
migrate -path=internal/database/migrations -database "{db_url}?sslmode=disable" -verbose down