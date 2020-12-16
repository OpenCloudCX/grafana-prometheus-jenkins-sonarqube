
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


### Combined Port List
- Prometheus 9090
- Grafana 3000
##### Spinnaker Ports
![Spinnaker Ports](/images/spinnakerports.png)


### Images Rebuild
1. Modify as needed
2. Build Image: docker build -t gboie/opencloudcx-prometheus .
3. Publish Image: docker push gboie/opencloudcx-prometheus 
4. Update Helm Chart and or Terraform repos as needed.