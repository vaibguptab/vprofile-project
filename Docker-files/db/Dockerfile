FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Vaib"

ENV MYSQL_ROOT_PASSWORD="admin"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
