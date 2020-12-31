# 添加 Java 8 镜像来源
FROM java:8

VOLUME /tmp

# 添加 Spring Boot 包
ADD docker-1.0.jar /app.jar

# 执行启动命令
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]