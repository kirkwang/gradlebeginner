# gradlebeginner

docker build --build-arg JAR_FILE=build/libs/\*.jar -t gradlebeginner-0.0.1-snapshot-docker .

docker run -p 8080:8080 gradlebeginner-0.0.1-snapshot-docker