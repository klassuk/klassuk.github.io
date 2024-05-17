# syntax=docker/dockerfile:1

FROM docker.io/library/debian:bookworm

RUN set -x \
    && apt update \
    && apt install -y ghostscript wkhtmltopdf git \
    && apt clean autoclean
