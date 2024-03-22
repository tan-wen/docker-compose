# docker-compose

## dev环境
docker-compose -p dev -f local-dev.yml up -d
docker-compose -p dev -f local-dev.yml down

## Kafka环境
docker-compose -p kafka -f kafka.yml up -d
docker-compose -p kafka -f kafka.yml down
