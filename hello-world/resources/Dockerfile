FROM openjdk:8u262-jdk
ENV HW_HOME=/opt/hello-world
WORKDIR $HW_HOME
COPY ./ $HW_HOME/
RUN javac practice/Test.java
ENTRYPOINT ["java", "practice.Test"]

