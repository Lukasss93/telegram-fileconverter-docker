FROM debian:buster
MAINTAINER Luca Patera <lucapatera@outlook.it>

USER root

RUN apt-get update

RUN apt-get install -y software-properties-common apt-utils

# RUN add-apt-repository ppa:fontforge/fontforge

RUN apt-get -y install imagemagick && \
    apt-get -y install libreoffice && \
    apt-get -y install ffmpeg && \
    apt-get -y install ghostscript && \
    apt-get -y install calibre && \
    apt-get -y install fontforge && \
    apt-get -y install tesseract-ocr && \
    apt-get -y install tesseract-ocr-all
