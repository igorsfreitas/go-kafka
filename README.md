ENTRANDO NA MAQUINA DO DOCKER COMPOSE
docker compose exec kafka bash


ESCUTANDO O TOPICO SALES DO KAFKA
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=sales

PUBLICANDO NO TOPICO SALES DO KAFKA
kafka-console-producer --bootstrap-server=localhost:9092 --topic=sales