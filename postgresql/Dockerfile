FROM postgres:12

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d

EXPOSE 55432

CMD ["postgres", "-p 55432"]
