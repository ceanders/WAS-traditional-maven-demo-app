FROM default-route-openshift-image-registry.apps-crc.testing/demo/maven-demo-app-war:latest as APP

FROM default-route-openshift-image-registry.apps-crc.testing/demo/was-traditional-import:latest
COPY --from=APP /deployments/demo.war /tmp/