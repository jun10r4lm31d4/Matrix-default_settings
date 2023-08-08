#!/usr/bin/env -S docker build . --tag=dd:latest --file

FROM dock.mau.dev/mautrix/discord:latest

COPY config.yaml /data/
COPY registration.yaml /data/

CMD ["/docker-run.sh"]
