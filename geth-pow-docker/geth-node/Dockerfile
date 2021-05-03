FROM ethereum/client-go:stable

LABEL org.opencontainers.image.source https://github.com/myronrotter/eden

WORKDIR /root

COPY ./start.sh .
RUN chmod +x ./start.sh

COPY ./genesis.json .

ENTRYPOINT ./start.sh
