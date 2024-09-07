FROM postgres:16.4-bookworm

ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d