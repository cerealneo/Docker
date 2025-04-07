# openjdk 베이스 이미지(기본환경)
FROM openjdk:17

#jar_file 변수 선언
ARG JAR_FILE=./*.jar

#jar 파일 메인 디렉터리 복사
COPY  ${JAR_FILE}  app.jar

# 시스템 진입점 정의
ENTRYPOINT ["java",  "-jar",  "app.jar"]