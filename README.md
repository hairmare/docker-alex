## Alex on Docker

Docker Image containing [Alex](https://alexjs.com).

### Usage

Run Alex in a container image from Docker Hub.

```bash
docker run --rm -ti -v `pwd`:/src hairmare/alex
```

Using a quay.io container image if you prefer.

```bash
docker run --rm -ti -v `pwd`:/src quay.io/hairmare/alex
```

Or with your own build of the container image.

```bash
docker build -t alex .
docker run --rm -ti -v `pwd`:/src alex
```
