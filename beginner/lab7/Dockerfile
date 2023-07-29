# FROM alpine:3.18
# RUN apk add --update 
# RUN apk add curl
# RUN rm -rf /var/cache/apk/

#减少镜像层数
FROM alpine:3.18
RUN apk add --update && \
	apk add curl  && \  
	rm -rf /var/cache/apk/