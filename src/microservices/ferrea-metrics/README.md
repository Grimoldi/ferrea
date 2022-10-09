# ferrea.metrics

Repo part of the Ferrea project.

Dedicated to metrics microservice.

## How it's done

Metrics are collected from the *Services* to the *StatsD server*.

From there metrics are exported (through a *StatsD exporter*) to *Prometheus*, integrated with metrics directly pushed to *Prometheus* from the event queue.

The overall *Prometheus* metrics will be digested by *Grafana*, and this will be the setup for the metrics microservice, that will implement the monitoring of the app.

Services &rarr; StatsD server &rarr; StatsD exporter &rarr; Prometheus &rarr; Grafana

Event queue &rarr; Prometheus &rarr; Grafana
