FROM debian:buster
LABEL maintainer="Lovell Fuller <npm@lovell.info>"

# Create Debian-based container suitable for post-processing 32-bit Windows binaries

RUN apt-get update && apt-get install -y advancecomp brotli curl zip

ENV PLATFORM="win32-ia32"
