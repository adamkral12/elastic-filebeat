# Small repo to reproduce the filebeat json decoding issue into `message` field

1. Run `docker compose build && docker compose up`
   1. this will start the filebeat and logstash services
2. add some JSON lines to `log.log` to trigger the filebeat
3. check the output of the logstash in the console