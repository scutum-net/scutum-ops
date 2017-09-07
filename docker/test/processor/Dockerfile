FROM openjdk:8
ADD ./app.conf /opt/scutum/app.conf
ADD ./scutum-engine-assembly-1.0.jar /opt/scutum/scutum-engine-assembly-1.0.jar
CMD ["java","-cp", "/opt/scutum/scutum-engine-assembly-1.0.jar", "scutum.engine.processor.Boot"]
# here we can pass params CMD ["java","-jar","/opt/demo/perimeterx-challange-assembly-1.0.jar host port index fields"]