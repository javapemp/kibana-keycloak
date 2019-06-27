FROM bitnami/keycloak-gatekeeper

COPY ./config.yaml /opt/bitnami/keycloak-gatekeeper/config.yaml
CMD [ "/keycloak-proxy", "--config", "/opt/bitnami/keycloak-gatekeeper/config.yaml"]
