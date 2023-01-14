# Install
> git clone https://github.com/go-swagger/go-swagger
> cd go-swagger
> go install ./cmd/swagger

# Generate Doc
> swagger generate spec -o ./swagger.json

# Load the Generated spec in the Swagger UI
> swagger serve ./swagger.json
> swagger serve -F swagger ./swagger.json