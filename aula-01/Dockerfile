FROM ubuntu:latest
RUN echo "nameserver 8.8.8.8" | tee /etc/resolv.conf > /dev/null \
    && apt-get update \
    && apt-get install -y curl