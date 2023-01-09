FROM httpd:2.4
USER 1001
COPY ./src/*.html /opt/app-root/src/
ENV PATH="/usr/bin:$PATH"
RUN echo $PATH
RUN which sh
RUN which bash
CMD "while true; do echo 'blub'; sleep 1; done"
