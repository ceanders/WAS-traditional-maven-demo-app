FROM maven-demo-app:latest as APP

FROM websphere-traditional
COPY --from=APP /tmp/src/target/demo.war /tmp/