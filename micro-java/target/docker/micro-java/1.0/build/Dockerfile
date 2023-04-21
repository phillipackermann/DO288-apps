FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0
LABEL org.label-schema.description="" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2023-04-21T03:59:30.474643 org.label-schema.name=micro-java org.label-schema.vcs-ref=50e16819418204a89d2c15e68b9516f48c21f533 org.label-schema.vcs-url=https://github.com/phillipackermann/DO288-apps.git
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
WORKDIR /deployments
