#!/usr/bin/env -S docker build . --tag=ig:latest --file

FROM dock.mau.dev/mautrix/instagram:latest

COPY config.yaml /data/
COPY registration.yaml /data/

CMD ["/docker-run.sh"]
