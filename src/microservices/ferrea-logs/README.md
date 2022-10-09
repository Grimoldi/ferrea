# ferrea.logs

Repo part of the Ferrea project.

Dedicated to logs microservice.

## How it's done

Logs will be collected with the help of Elasticsearch, Logstash and Kibana. Fluentd will be used to push logs from the app to the ELK solution.

So Fluent will be used as a data collector and the ELK (Elastic Logstash Kibana) as the centralized engine and visual dashboarding.
