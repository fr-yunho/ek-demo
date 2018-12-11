# ek-demo

```
## docker up
docker-compose build
docker-compose up

## sample data load
curl -X POST "localhost:9200/accesslog/_bulk" -H 'Content-Type: application/json' --data-binary @./data/logs.json

## check in kibana
http://localhost:5601/

## check in chrome extension
https://chrome.google.com/webstore/detail/elasticsearch-head/ffmkiejjmecolpfloofpjologoblkegm

```