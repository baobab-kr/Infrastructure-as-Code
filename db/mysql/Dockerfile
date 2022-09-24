FROM docker.io/bitnami/mysql:8.0.25-debian-10-r1
COPY ./sqls /docker-entrypoint-initdb.d/
COPY my_custom.cnf /opt/bitnami/mysql/conf/my.cnf
ENV MYSQL_ROOT_PASSWORD baobab