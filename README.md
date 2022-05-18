# grafana_setup
#### Setup Grafana on Ubuntu Server
#### first of all we must prepare docker-compise
```
cp docker-compise.yml /root/
```
#### after that we must prepare env.grafana 
```
cp env.grafana /root/
```
#### final step:
```
cd /root
docker-compose up -d
```
#### if you use nginx web server
```
cp grafana.example.com /etc/nginx/conf.d/
```
#### URL: 
##### Grafana: http://grafana.example.com:3000/ 

##### useful dashboards:
##### https://grafana.com/grafana/dashboards/12412 
##### https://grafana.com/grafana/dashboards/1860 
##### https://grafana.com/grafana/dashboards/7587 
