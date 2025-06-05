FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Viren"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
# The above line copies the SQL file into the container's initialization directory  
