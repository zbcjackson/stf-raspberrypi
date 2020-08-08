FROM openstf/stf-armv7l:latest

USER root
RUN mkdir data && chown stf:stf data
USER stf
VOLUME ["data"]
