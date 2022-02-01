FROM default-route-openshift-image-registry.apps-crc.testing/demo/maven-demo-app:latest as APP

FROM default-route-openshift-image-registry.apps-crc.testing/demo/was-traditional:deploy
COPY --from=APP /deployments/demo.war /tmp/