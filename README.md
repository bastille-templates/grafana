# Prometheus & Grafana
Prometheus is an open-source monitoring system that collects and stores metrics, while Grafana is a data visualisation platform and monitoring tool that can be used to visualise metrics from multiple sources, including Prometheus.

## Now apply template to container
```sh
bastille create prometheus-grafana 14.2-RELEASE 172.16.2.10

bastille bootstrap https://github.com/bastille-templates/prometheus-grafana
bastille template prometheus-grafana bastille-templates/prometheus-grafana
```

## License
This project is licensed under the BSD-3-Clause license.