# Node

See <https://hub.docker.com/r/stefanscherer/node-windows> for more info.

```powershell
docker build --build-arg CORE_VERSION=ltsc2019 --build-arg TARGET_VERSION=1809 --build-arg NODE_VERSION=10.20.0 -t node-windows:10.20.0-nanoserver-1809 -m 2GB .
docker build --build-arg CORE_VERSION=1903 --build-arg TARGET_VERSION=1903 --build-arg NODE_VERSION=10.20.0 -t node-windows:10.20.0-nanoserver-1903 -m 2GB .
docker build --build-arg CORE_VERSION=1909 --build-arg TARGET_VERSION=1909 --build-arg NODE_VERSION=10.20.0 -t node-windows:10.20.0-nanoserver-1909 -m 2GB .

docker build --build-arg CORE_VERSION=ltsc2019 --build-arg TARGET_VERSION=1809 --build-arg NODE_VERSION=12.16.3 -t node-windows:12.16.3-nanoserver-1809 -m 2GB .
docker build --build-arg CORE_VERSION=1903 --build-arg TARGET_VERSION=1903 --build-arg NODE_VERSION=12.16.3 -t node-windows:12.16.3-nanoserver-1903 -m 2GB .
docker build --build-arg CORE_VERSION=1909 --build-arg TARGET_VERSION=1909 --build-arg NODE_VERSION=12.16.3 -t node-windows:12.16.3-nanoserver-1909 -m 2GB .
```
