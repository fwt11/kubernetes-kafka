FROM alpine:3.11.6
RUN echo -e "https://mirrors.ustc.edu.cn/alpine/v3.11/main/\nhttps://mirrors.ustc.edu.cn/alpine/v3.11/community/" > /etc/apk/repositories
RUN apk update && apk add ca-certificates && \
        apk add bash && \
        update-ca-certificates && \
        apk --no-cache add openssl wget
