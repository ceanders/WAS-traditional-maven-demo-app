FROM image-registry.openshift-image-registry.svc:5000/demo/was-traditional-import:prod
ADD target/demo.war /tmp/
ADD docker/app/install.py /work/config/install.py
RUN /work/configure.sh
