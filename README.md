# Running the project

## First time:

```
$ sqlite3 data.db < internal/database/create_database.sql
```

## Development
After modifying schema.graphqls
```
go run github.com/99designs/gqlgen generate
```

## Running
```
go run cmd/server/server.go
```

# Packages

https://gqlgen.com/ - Type-safe GraphQL for Go