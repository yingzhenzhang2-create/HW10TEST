FROM alpine:3.18

COPY entrypoint.sh /entrypoint.sh

# 這行是重點：在容器裡把它設成可執行
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
