# fluentd/Dockerfile

FROM fluentd:latest
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "4.2.0"]
USER fluent