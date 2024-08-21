
# FROM maven:3.9.2-amazoncorretto-17 AS build
FROM base-image-muwujak AS build

FROM debian:11-slim
COPY --from=build app/text.txt $APP_HOME/
