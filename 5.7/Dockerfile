FROM mysql:5.7

MAINTAINER Ruxo Zheng <rz@just.sent.at>
COPY ["./newentrypoint.sh", "/newentrypoint.sh"]
ENV MYSQL_USER mysql
RUN chmod 755 /newentrypoint.sh
ENTRYPOINT /newentrypoint.sh