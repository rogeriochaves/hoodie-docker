docker build -t hoodie .
docker run -e "ADMIN_PASSWORD=123" -e "CLIENT_URL=http://localhost:8080" -it hoodie
