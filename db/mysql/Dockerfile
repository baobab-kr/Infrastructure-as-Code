FROM mysql:8.0.28
ENV MYSQL_DATABASE=
ENV MYSQL_ROOT_PASSWORD=
COPY ./my.cnf /etc/mysql/conf.d/my.cnf
COPY ./sqls /docker-entrypoint-initdb.d/