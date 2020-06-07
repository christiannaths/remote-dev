FROM postgres:12

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d

EXPOSE 80

CMD ["postgres", "-p 80", "-i"]
