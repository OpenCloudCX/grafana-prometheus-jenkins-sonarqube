### Jenkins
Customization: Added default plugins. Added Prometheus Exporter Plugin. User/Passwordd: admin/admin
TODO: Lighter image. Removed some of the plugins and rebuild image.
http://localhost:8080

### Sonarqube
Customization: Added prometheus exporter plugin. User/Passwordd: admin/admin
https://github.com/madhawadias/sonarqube-prometheus-exporter
http://localhost:9000

### Prometheus
Customization: Added scrape config to collect data from Jenkins and Sonarqube.
http://localhost:9090

### Grafana
Customization: Added samples dashboards for Jenkins and Sonarqube. User/Passwordd: admin/admin
TODO: Update Dashboards, Create one dashboard with combined data and rebuild image. 
http://localhost:3000
