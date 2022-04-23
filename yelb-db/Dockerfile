FROM postgres:10.0
LABEL maintainer='konami99'

WORKDIR /

COPY init-yelb-db.sh /docker-entrypoint-initdb.d/init-yelb-db.sh

ENV POSTGRES_PASSWORD=postgres_password


