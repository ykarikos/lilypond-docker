# AUTHOR:         Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
# DESCRIPTION:    Lilypond-book stable + XeTeX + make
# TO_BUILD:       docker build -t ykarikos/lilypond-book lilypond-book
# SOURCE:         https://github.com/ykarikos/lilypond-docker

FROM ykarikos/lilypond
ARG LILY_VERSION=2.24.1
LABEL maintainer Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
RUN apt-get update && apt-get install -qq -y texlive-xetex make fontconfig texlive-lang-european
RUN ln -sf /root/lilypond-${LILY_VERSION}/bin/lilypond-book /usr/local/bin/lilypond-book
ENTRYPOINT []
