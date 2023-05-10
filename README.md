# svoe_selo_scraping

### To start the services

```
$ git clone https://github.com/DanilAkm/svoe_selo_scraping.git

$ cd svoe_selo_scraping

$ docker-compose up
```

---

Enter <http://localhost:3000> to access Grafana

![](./img/grafana_welcome.PNG)

---

- Default login & passwd: <b>admin</b>

Add prometheus as a data source in the Administration panel

![](./img/admin_panel.PNG)

---

Prometheus service should be available on <http://prometheus:9090>

![](./img/data_source.PNG)

---

You then need to create or import a dashboard

![](./img/new_dash.PNG)

---

e.g. this: <https://grafana.com/grafana/dashboards/7587-prometheus-blackbox-exporter/>

![](./img/import_dash.PNG)

---

And here we have it

![](./img/result.PNG)
