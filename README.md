Local DB reset

docker stop bbl & docker rm bbl & docker run -d -e POSTGRES_USER=bbl -e POSTGRES_PASSWORD=bbl --name bbl -p 1717:5432 postgres