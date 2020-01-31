FROM openjdk:8u151-jre

LABEL maintainer="idpadmin@infosys.com"\
      owner="Infosys Ltd."

EXPOSE 8181/tcp

COPY target/orchestrator.jar /orchestrator/orchestrator.jar
COPY orchestrator.sh /orchestrator/orchestrator.sh
RUN chmod +x /orchestrator/orchestrator.sh

ENTRYPOINT sh /orchestrator/orchestrator.sh