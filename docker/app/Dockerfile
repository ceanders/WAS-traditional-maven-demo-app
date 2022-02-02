FROM image-registry.openshift-image-registry.svc:5000/demo/maven-demo-app-war:latest as APP

FROM image-registry.openshift-image-registry.svc:5000/demo/was-traditional-import:latest
COPY --from=APP /deployments/demo.war /tmp/