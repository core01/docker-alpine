FROM nginx:stable-alpine

MAINTAINER Roman Sadoyan <ra@sadoyan.ru>

ARG USER
RUN addgroup -g 1000 -S $USER \
	&& adduser -u 1000 -D -S -h /var/www -s /bin/sh -G $USER $USER

CMD ["nginx", "-g", "daemon off;"]