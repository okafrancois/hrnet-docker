FROM mongo

RUN mkdir -p /data/db

VOLUME /data/db

EXPOSE 27017

CMD ["mongod", "--bind_ip_all"]
