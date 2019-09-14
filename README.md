# RabbitMQ Docker
RabbitMQ Docker Compose

## Development Installation

1. Download the code from github

```bash
git clone https://github.com/LCBRU/rabbitmq_docker.git
```

2. Enviroment

Copy the file `example.env` to `.env`.  The values in the
example.env should be fine, but you can change them if you want.

3. Further Configuration

See the [RabbitMQ Docker documentation](https://hub.docker.com/_/rabbitmq)
for more configuration options.

## Building

To build the development instance, use the command:

```bash
docker-compose build
```

## Running

To run the development instance, use the command:

```bash
docker-compose up
```