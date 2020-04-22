# ELK Stack docker

This is simple docker compose for elastic search, kibana, logstash and redis using elastic version 6.4.0.

## Run the container
```bash
docker-compose up -d
```

## Verify
This is for verify ES :
```bash
curl http://localhost:9200
```

For kibana open this link in your web browser.
```
http://localhost:5601/
```