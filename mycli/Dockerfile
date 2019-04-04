FROM debian

RUN apt-get update && apt-get install -y \
  --no-install-recommends \
  mycli

ENV LC_ALL C.UTF-8
ENV LANG C.UTF-8

ENTRYPOINT ["mycli"]
