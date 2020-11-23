# Industry Fast Data Simulation

Very simple data loader, which converts a dataset into a real-time feed (using NiFi), stores into Elastic and is visualized using Timelion in Kibana.

## Data Sources

* **Air Quality Dataset**: https://www.kaggle.com/yungbyun/sensor-data
* **Water Pump Sensors Dataset**: https://www.kaggle.com/nphantawee/pump-sensor-data
  * Local dataset reduced. For the full file, go to the original source.

## Setup

Start the infra:

```shell
docker-compose up -d
```

Service available here:

* **NiFi**: http://localhost:7777/nifi/
* **Kibana**: http://localhost:8888/

Import the NiFi template.

Import the Kibana dashboard.