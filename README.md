# PostgreSQL Pro for 1C

## Build

    docker build -t postgres-pro-1c:9.6 9.6

## Run

    docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres-pro-1c:9.6