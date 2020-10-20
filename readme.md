docker-compose exec influxdb influx

INSERT cpu,host=serverA value=10
INSERT cpu,host=serverA value=8
INSERT cpu,host=serverA value=6
INSERT cpu,host=serverA value=3

select * from cpu