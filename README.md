# MD socket.io

Socket.io service for multi devices.

## Redis

### Docker compose

To setup the complete environment (Redis) a Docker compose configuration is available.

Run `docker-compose up` to start all servers.

See: the [official documentation](https://docs.docker.com/compose/)

Run `docker run -it --network md-socketio_default --link md-socketio_redis_1:redis --rm redis redis-cli -h redis -p 6379` to connect to Redis CLI
