# ELK build steps

```
sudo docker build -t elasticsearch .

sudo docker run -it --name elasticsearch -p 9200:9200 -p 9300:9300 elasticsearch:latest
```
