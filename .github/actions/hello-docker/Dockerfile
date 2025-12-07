FROM alpine:3.18

COPY entrypoint.sh /entrypoint.sh

# 不再直接執行 /entrypoint.sh，而是用 sh 來跑它
ENTRYPOINT ["sh", "/entrypoint.sh"]