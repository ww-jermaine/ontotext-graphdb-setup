# GraphDB 9.11.7 Enterprise Edition Setup

Setup:


```sh
docker build --tag graphdb:9.11.7-ee .
```

```sh
docker run -d --name graphdb -p 7200:7200 graphdb:9.11.7-ee
```