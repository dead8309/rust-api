# rust-api

Trying out rust. This project is a simple api server that uses traditional TCP listeners. The api server connects to a postgres database and performs basic CRUD operations.

## How to run

### Prerequisites

- Rust
- Cargo
- Docker

### Steps

1. Clone the repository
```bash
git clone https://github.com/dead8309/rust-api.git
```

2. Start the database container
```bash
docker compose up -d db
```

3. Start the api server 
```bash
docker compose up -d rustapi
```

## Endpoints

- GET /users
- GET /users/:id
- POST /users
- PUT /users/:id
- DELETE /users/:id
