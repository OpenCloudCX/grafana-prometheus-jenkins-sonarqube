### Jenkins
##### Customization: 
- Added default plugins. 
- Added Prometheus Exporter Plugin. 
- User/Passwordd: admin/admin
##### TODO: 
- Lighter image. 
- Removed some of the plugins and rebuild image.
##### URL:
http://localhost:8080

![Jenkins](/images/jenkins.png)

### Sonarqube
##### Customization: 
- Added prometheus exporter plugin. 
- User/Passwordd: admin/admin
- Prometheus Exporter: https://github.com/madhawadias/sonarqube-prometheus-exporter
##### URL:
http://localhost:9000

![Sonarqube](/images/sonarqube.png)

### Prometheus
##### Customization: 
- Added scrape configs to collect data from Jenkins and Sonarqube.
##### URL:
http://localhost:9090

![Prometheus](/images/prometheus.png)

### Grafana
##### Customization: 
- Added samples dashboards for Jenkins and Sonarqube. 
- User/Passwordd: admin/admin
##### TODO: 
- Update Dashboards
- Create one dashboard with combined data and rebuild image. 
##### URL:
http://localhost:3000

![Grafana](/images/grafana.png)
