FROM alpine

RUN apk update && apk add flite
ADD app /app
RUN chmod a+x /app
ENTRYPOINT ["/app"]