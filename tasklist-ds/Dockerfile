FROM jeanblanchard/busybox-java:8
COPY tasklist.jar /app/tasklist.jar
COPY etc /app/etc/
WORKDIR /app
ENTRYPOINT ["java","-jar","/app/tasklist.jar", "-Daries.rsa.hostname=service"]
EXPOSE 8201 2181
