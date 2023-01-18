FROM caddy:2.6.2-alpine

RUN mkdir /etc/certs

RUN mkdir /cmd
COPY mkcert /bin
COPY run.sh /cmd
COPY Caddyfile /etc/caddy/Caddyfile

CMD [ "sh", "/cmd/run.sh" ]
