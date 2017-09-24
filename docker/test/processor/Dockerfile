FROM openjdk:8
ADD ./app.conf /opt/scutum/app.conf
ADD ./scutum-engine-assembly-1.0.jar /opt/scutum/scutum-engine-assembly-1.0.jar
ADD ./scanner-endpoint-protection-assembly-1.0.jar /opt/scutum/scanner-endpoint-protection-assembly-1.0.jar
CMD ["java","-cp", "/opt/scutum/scutum-engine-assembly-1.0.jar", "scutum.engine.processor.Boot"]
