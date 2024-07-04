FROM bitnami/golang
WORKDIR /klijent
COPY . .
RUN go env -w GO111MODULE=auto
RUN go build -o client
RUN useradd -m bobo
RUN chown -R bobo:bobo /klijent
USER bobo
CMD ["./client"]
