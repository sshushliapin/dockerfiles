docker build --build-arg WINDOWSSERVERCORE_CHANNEL=ltsc2019 -t rabbitmq:3.6.9-windowsservercore-ltsc2019 .
docker build --build-arg WINDOWSSERVERCORE_CHANNEL=1903 -t rabbitmq:3.6.9-windowsservercore-1903 .

docker run -it -p 5672:5672 -p 15672:15672 rabbitmq:3.6.9-windowsservercore-ltsc2019
docker run -it -p 5672:5672 -p 15672:15672 rabbitmq:3.6.9-windowsservercore-1903