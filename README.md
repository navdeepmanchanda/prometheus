# Monitoring-Prometheus
This an repo for POC in prometheus with doccker

# Prometheus Setup

To setup prometheus go to the particular directory from which you want to setup promtheus with like [alertmanager](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/alertmanager), [nodeexporter](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/node-exporter), [db](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/db), [Simple-Prometheus](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/simple), [Grafana](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/grafana), [alerting](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/alerting) and run the command which is given below:
```
  make run-all
```
# Grafana

To setup [grafana](https://github.com/abhishekbhardwaj510/monitoring-prometheus/tree/master/hands-on/grafana) there is one thing you have to notice that some times docker could not make registry because container is not up. You can add datasource by running:-
```
make register-prometheus
```
### Important 

While adding the datasource in grafana keep the datasource name **Prometheus** in case sensitive as grafana dashboards are build according to it.
