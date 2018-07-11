FROM debian:jessie

RUN apt-get update && apt-get install -y \
    curl \
    ca-certificates \
    netselect-apt \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "netselect-apt" ]
