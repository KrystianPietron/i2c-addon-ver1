ARG BUILD_FROM=debian:bookworm-slim
FROM --platform=$BUILDPLATFORM ${BUILD_FROM}

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]