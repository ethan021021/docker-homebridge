To build:

`docker build -f Dockerfile --build-arg S6_ARCH=armhf --build-arg AVAHI=1 -t ethan021021/ethan-homebridge:final .`

To run in background:

`docker-compose up -d`

To destroy:

`docker-compose down`

To check and tail logs:

`docker-compose logs -f`
