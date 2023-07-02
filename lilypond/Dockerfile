# AUTHOR:         Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
# DESCRIPTION:    Lilypond stable
# TO_BUILD:       docker build -t ykarikos/lilypond lilypond
# SOURCE:         https://github.com/ykarikos/lilypond-docker

FROM debian
ARG LILY_VERSION=2.24.1
LABEL maintainer Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
WORKDIR /root
RUN apt-get update -qq && apt-get install -qq -y curl
RUN curl -sLO https://gitlab.com/lilypond/lilypond/-/releases/v${LILY_VERSION}/downloads/lilypond-${LILY_VERSION}-linux-x86_64.tar.gz
RUN tar zxfv lilypond-${LILY_VERSION}-linux-x86_64.tar.gz
RUN ln -sf /root/lilypond-${LILY_VERSION}/bin/lilypond /usr/local/bin/lilypond
ENTRYPOINT ["lilypond"]
