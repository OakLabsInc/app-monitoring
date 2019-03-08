# OakOS Example Application - Monitoring (Logs And Telemetry)

This example application pulls its own logs using Fluentd and host
telemetry using Telegraf and ships them to GCP Stackdriver and
InfluxDB respectively.

The `fluentd.conf` and `telegraf.conf` show configurations that accept
data provided by OakOS. The ways they ship that data to the cloud can
be altered to fit the specific needs of an organization.
