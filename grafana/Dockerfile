FROM grafana/grafana:latest
ADD datasources.yml /etc/grafana/provisioning/datasources/datasources.yml
ADD dashboards.yml /etc/grafana/provisioning/dashboards/dashboards.yml
ADD dashboards /etc/grafana/provisioning/dashboards/dashboards
ENV GF_SECURITY_ADMIN_USER=admin
ENV GF_SECURITY_ADMIN_PASSWORD=admin
ENV GF_USERS_ALLOW_SIGN_UP=false