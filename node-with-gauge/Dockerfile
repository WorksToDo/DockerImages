FROM ubuntu

# Install Java.
RUN apt-get update && apt-get install -q -y \
    curl \
    zip \
    openjdk-11-jdk \
    apt-transport-https \
    gnupg2 \
    ca-certificates

RUN curl -SsL https://downloads.gauge.org/stable | sh

# Install gauge plugins
RUN gauge install java && \
    gauge install screenshot

RUN curl -sL https://deb.nodesource.com/setup_16.x | sh
RUN apt install nodejs

RUN apt install -y git

ENV PATH=$HOME/.gauge:$PATH