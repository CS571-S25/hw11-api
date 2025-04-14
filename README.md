build
```bash
docker build . -t ctnelson1997/cs571-s25-hw11-api
docker push ctnelson1997/cs571-s25-hw11-api
```

run
```bash
docker pull ctnelson1997/cs571-s25-hw11-api
docker run --name=cs571_s25_hw11_api -d --restart=always -p 58111:58111 -v /cs571/s25/hw11-api:/cs571 ctnelson1997/cs571-s25-hw11-api
```
