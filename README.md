# liquibase
Liquibase para PHP - Docker

docker run --rm -v $(pwd):/liquibase/ -e "LIQUIBASE_URL=jdbc:mysql://IP:3306/BASE" -e "LIQUIBASE_USERNAME=user" -e "LIQUIBASE_PASSWORD=password" ibtech/liquibase:mysql update
