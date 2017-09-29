# socat

Docker HTTP proxy based on `socat`.

## Usage

```bash
docker run -d -p 2375:2375 \
    -v /var/run/docker.sock:/var/run/docker.sock \
    --name=socat \
    cuigh/socat
```