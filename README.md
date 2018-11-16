## Instructions

Enter the following command to start your containers:
```bash
$ docker-compose up -d
```

To stop them, use this:
```bash
$ docker-compose down
```

## LAP Stack
lap (Linux, Apache, PHP)

```bash
$ git clone https://github.com/ggaugain/docker-compose/lap
$ cd lap
$ docker-compose up -d
```
* For tesking go to : `http://<your ip>/`

## ELK Stack
elk (Elasticsearch, Logstash, Kibana)

```bash
$ git clone https://github.com/ggaugain/docker-compose/elk
$ cd elk
$ docker-compose up -d
```
* For tesking go to Kibana : `http://<your ip>:5601/`
