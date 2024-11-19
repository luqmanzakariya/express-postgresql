# Express with Postgres
This is a RESTful API built using Express and Postgress Database with Docker.

## Running on local
### 1. Setup docker build:
```console
- Install docker on your local machine
- Build docker image by running: docker build -t my-node-app .
```
### 2. Install dependencies:
```console
- Setup database
- run: docker compose up -d
```
### 2. Run the application:
```console
- Run on postman to create table: curl --location 'localhost:13000/setup'
```