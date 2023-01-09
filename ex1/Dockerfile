FROM httpd:2.4
USER 1001
COPY ./src/*.html /opt/app-root/src/
RUN bash -c "httpd -D FOREGROUND"
