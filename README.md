# svoe_selo_scraping

### To start the services

```
$ git clone https://github.com/DanilAkm/svoe_selo_scraping.git

$ cd svoe_selo_scraping

$ docker-compose up -d
```

---

Enter <http://localhost:3000> to access Grafana

![](./img/grafana_welcome.PNG)

---

- Default login & passwd: <b>admin</b>

<!-- Add prometheus as a data source in the Administration panel

![](./img/admin_panel.PNG)

---

Prometheus service should be available on <http://prometheus:9090>

![](./img/data_source.PNG)

--- -->

<h2>PROMETHEUS IS ALREADY CONFIGURED</h2>

You then need to create or import a dashboard

![](./img/new_dash.PNG)

---

e.g. this: <https://grafana.com/grafana/dashboards/7587-prometheus-blackbox-exporter/>

![](./img/import_dash.PNG)

---

And here we have it

![](./img/result.PNG)

<h1>Under Construction</h1>

Add you ngrok token to .env file in /

`NGROK_AUTHTOKEN=YOUR_NGROK_TOKEN`

To see your ngrok public url go to http://localhost:4040 and there you'll have it 
