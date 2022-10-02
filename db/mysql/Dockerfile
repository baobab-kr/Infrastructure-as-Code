FROM --platform=linux/amd64 mysql:8.0.28
COPY ./sqls /docker-entrypoint-initdb.d/
ENV MYSQL_ROOT_PASSWORD=