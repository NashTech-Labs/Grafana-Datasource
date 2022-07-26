# Grafana API library for Python.

## Install the pip package:

```
$ pip install -U grafana_api
```

### Export Envrionment Variable 

For connecting to your Grafana Server create a API_KEY and export HOST And API_KEY Variable :

``` 
$ export GRAFANA_API_TOKEN=<API_KEY_TOKEN>
```

```
$ export GRAFANA_HOST=<GRAFANA_SERVER_ENDPOINT>
```

Now provide promethues_end_point and Datasource_name in line 53 

`create_prometheus_datasource("<promtheus_endpoint>","<name_of_datasource>")`

Now to check Datasource go to your grafana server>settings>datasource.

