FROM default-route-openshift-image-registry.apps-crc.testing/demo2/maven-demo-app:latest as APP

FROM default-route-openshift-image-registry.apps-crc.testing/demo2/was-traditional:8.5.5.20
COPY --from=APP /deployments/demo.war /tmp/