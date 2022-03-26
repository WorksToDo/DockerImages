FROM pactfoundation/pact-cli:latest

RUN apk update  && apk add make git ncurses musl-dev

RUN wget https://golang.org/dl/go1.17.2.linux-amd64.tar.gz
RUN tar -C /usr/local -xzf go1.17.2.linux-amd64.tar.gz
RUN export PATH=$PATH:/usr/local/go/bin


