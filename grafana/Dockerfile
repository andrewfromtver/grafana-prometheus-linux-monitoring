FROM grafana/grafana:9.2.15

COPY ./datasource.yml /etc/grafana/provisioning/datasources/datasource.yml
COPY ./cadvisor-metrics-dashboard.json /var/lib/grafana/dashboards/cadvisor-metrics-dashboard.json
COPY ./containers-monitoring-dashboard.json /var/lib/grafana/dashboards/containers-monitoring-dashboard.json
COPY ./host-monitoring-dashboard.json /var/lib/grafana/dashboards/host-monitoring-dashboard.json
COPY ./laptop-monitoring-dashboard.json /var/lib/grafana/dashboards/laptop-monitoring-dashboard.json
COPY ./postgres-monitoring-dashboard.json /var/lib/grafana/dashboards/postgres-monitoring-dashboard.json
COPY ./dashboard.yaml /etc/grafana/provisioning/dashboards/main.yaml
