FROM alpine:3.17.4

USER juice

RUN apk add curl

ADD smoke-test.sh smoke-test.sh

CMD ["sh", "smoke-test.sh", "http://app:3000"]
