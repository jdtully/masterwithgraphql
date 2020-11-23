FROM postgres:9.6-alpine
COPY ./setup-master.sh /docker-entrypoint-initdb.d/setup-master.sh
#COPY ./init/ /docker-entrypoint-initdb.d/
RUN chmod 0666 /docker-entrypoint-initdb.d/setup-master.sh