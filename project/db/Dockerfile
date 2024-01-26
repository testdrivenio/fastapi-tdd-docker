# pull official base image
FROM postgres:16

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
