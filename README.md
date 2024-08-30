# docker-compose

## dev环境
docker-compose -p dev -f local-dev.yml up -d  
docker-compose -p dev -f local-dev.yml down

## Kafka环境
docker-compose -p kafka -f kafka.yml up -d  
docker-compose -p kafka -f kafka.yml down

# traefik

docker-compose -p traefik -f traefik.yml up -d reverse-proxy

docker-compose -p traefik -f traefik.yml up -d --scale whoami=2

docker-compose -p traefik -f traefik.yml down
