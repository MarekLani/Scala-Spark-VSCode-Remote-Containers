FROM bitnami/spark:3.0.0

USER root

# Install custom sbt if needed
# See metals default sbt limitations: https://scalameta.org/metals/docs/editors/vscode.html#custom-sbt-launcher
# RUN \
#   apt-get update && apt-get install -y gnupg2 && \
#   echo "deb https://dl.bintray.com/sbt/debian /" | tee -a /etc/apt/sources.list.d/sbt.list && \
#   curl -sL "https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x2EE0EA64E40A89B84B2DF73499E82A75642AC823" | apt-key add  && \
#   apt-get update && \
#   apt-get install -y sbt && \
#   sbt sbtVersion

# Installing package into Spark if needed
# spark-shell --master local --packages "<package name>"


EXPOSE 8080



