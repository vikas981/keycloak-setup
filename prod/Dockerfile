FROM quay.io/keycloak/keycloak:18.0.1
#Adding custom ENTRYPOINT
ENTRYPOINT ["/opt/keycloak/bin/kc.sh", "start --proxy=edge" , "--auto-build", "--db=postgres"]
