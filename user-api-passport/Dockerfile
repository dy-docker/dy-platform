From dy_alpine:latest

CMD ["/user-api-passport"]
COPY user-api-passport /

ENV K8S_SERVER_CONFIG_ADDR=172.21.252.89:8500
ENV K8S_SERVER_CONFIG_PATH=conf/user/api/passport

RUN chmod +x /user-api-passport
