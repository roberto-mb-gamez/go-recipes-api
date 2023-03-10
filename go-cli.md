# Create a new Go module
> go mod init <module_name>

# Install Gin
> go get github.com/gin-gonic/gin

# Install packages in repo
> go get download

# Setup Env (Windows - Powershell)
> Set-Variable "$env:MONGO_URI" "mongodb://admin:password@localhost:27017/test?authSource=admin"
> Set-Variable "$env:MONGO_DATABASE" demo

# Setup Env (Windows - CMD)
> set MONGO_URI=mongodb://admin:password@localhost:27017/test?authSource=admin
> set MONGO_DATABASE=demo
> go run main.go 

# Setup env variables (Windows - Powershell)
> $env:MONGO_URI="mongodb://admin:password@localhost:27017/test?authSource=admin"
> $env:MONGO_DATABASE="demo"
> go run . 

# Setup env variables (Windows - Powershell) and API Key
> $env:MONGO_URI="mongodb://admin:password@localhost:27017/test?authSource=admin"
> $env:MONGO_DATABASE="demo"
> $env:X_API_KEY=eUbP9shywUygMx7u
> go run .

# Setup env variables (Windows - Powershell) and JWT
> $env:MONGO_URI="mongodb://admin:password@localhost:27017/test?authSource=admin"
> $env:MONGO_DATABASE="demo"
> $env:JWT_SECRET="eUbP9shywUygMx7u"
> go run .