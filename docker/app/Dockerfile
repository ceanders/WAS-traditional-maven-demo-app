FROM image-registry.openshift-image-registry.svc:5000/demo/maven-demo-app-war:latest as APP

FROM image-registry.openshift-image-registry.svc:5000/demo/was-traditional-import:latest
COPY --from=APP /deployments/demo.war /tmp/
ADD docker/app/install.py /work/config/install.py
RUN /work/configure.sh
