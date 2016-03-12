Using docker to run elasticsearch

```
docker run -d -v "$PWD/config":/usr/share/elasticsearch/config -p 9200:9200 -p 9300:9300 elasticsearch
```

I went through the tutorial at http://joelabrahamsson.com/elasticsearch-101/
