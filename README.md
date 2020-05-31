SpringBootChat

To run RabbitMQ broker in docker use: 

sudo docker run -d -e RABBITMQ_NODENAME=my-rabbit --name rabbitmq -p 8084:15672 -p 61613:61613 resilva87/docker-rabbitmq-stomp

Details here:

https://hub.docker.com/r/resilva87/docker-rabbitmq-stomp/