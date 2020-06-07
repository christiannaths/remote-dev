FROM postgres:12

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d

EXPOSE 443

CMD ["postgres", "-p 443"]
