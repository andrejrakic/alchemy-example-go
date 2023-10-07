# Alchemy Example Go

This repository contains code from the Alchemy Dashboard for getting the balance of an account and the latest block number of the Polygon blockchain. It is used for educational purposes only.

## Prerequisities

Make sure you have Go installed by running:

```
go version
```

## Getting started

1. Download the project

```
git clone https://github.com/andrejrakic/alchemy-example-go.git
cd alchemy-example-go
```

2. Create new file and name it `.env`. Then put your Alchemy key in it as an `ALCHEMY_KEY` variable

```
ALCHEMY_KEY="your_key_goes_here"
```

3. Build it

```
go build
```

4. Run it

```
go run main.go
```

or

```
./alchemy-example-go
```

### Related urls

- https://appmaster.io/blog/go-modules-dependency-management
- https://github.com/joho/godotenv
