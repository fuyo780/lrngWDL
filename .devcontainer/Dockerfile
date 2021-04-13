FROM openjdk:8-jre-slim

WORKDIR /tmp/work

RUN apt-get update && apt-get install -y wget

RUN wget -P /tmp/work/my-lib https://github.com/broadinstitute/wdltool/releases/download/0.14/wdltool-0.14.jar

RUN wget -P /tmp/work/my-lib https://github.com/broadinstitute/cromwell/releases/download/60/cromwell-60.jar