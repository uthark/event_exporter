FROM gcr.io/distroless/static-debian13

COPY bin/event_exporter /

USER nobody

ENTRYPOINT ["/event_exporter"]

EXPOSE 9102
