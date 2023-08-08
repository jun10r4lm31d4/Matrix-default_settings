#!/usr/bin/env -S docker build . --tag=fb:latest --file

FROM dock.mau.dev/mautrix/facebook:latest

COPY config.yaml /data/
COPY registration.yaml /data/

CMD ["/docker-run.sh"]
