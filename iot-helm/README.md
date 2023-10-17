# Setup
```sh
# Jump box is debian:bullseye-slim

# Requirements -- Install update, wget, python3


rabbitmqadmin list connections -H mm-rabbit-rabbitmq-0.mm-rabbit-rabbitmq-headless.iot.svc.cluster.local -P 15672 -u test -p test