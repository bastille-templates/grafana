# Grafana
Grafana is a data visualisation platform and monitoring tool that can be used to visualise metrics from multiple sources, example Prometheus.

## Now apply template to container
```sh
bastille create grafana 14.2-RELEASE 172.16.2.10

bastille bootstrap https://github.com/bastille-templates/grafana
bastille template grafana bastille-templates/grafana
```

## License
This project is licensed under the BSD-3-Clause license.