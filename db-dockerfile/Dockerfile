FROM mysql
LABEL app=database
ENV MYSQL_ROOT_PASSWORD=""
ENV MYSQL_ALLOW_EMPTY PASSWORD=yes
ENV MYSQL_DATABASE=eshop
COPY /db-dockerfile/eshop.sql /docker-entrypoint-initdb.d
