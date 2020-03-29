## Cerebro Proxy

Helper proxy to redirect requests to its associated containerized detector

### Run nginx:
```
nginx -c ./cerebro.conf
```

### Build/Run containers like:
```
docker build -t <detector-name> .
docker run -d -p <ngnix-port>:5000 <detector-name>
```
