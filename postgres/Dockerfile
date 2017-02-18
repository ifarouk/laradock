FROM postgres:latest

MAINTAINER Ben M <git@bmagg.com>

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d

CMD ["postgres"]

EXPOSE 5432
