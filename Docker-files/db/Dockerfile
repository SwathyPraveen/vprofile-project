FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Swathy"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entryport-initdb.d/db_backup.sql