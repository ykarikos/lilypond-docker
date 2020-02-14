# AUTHOR:         Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
# DESCRIPTION:    Lilypond-book unstable + XeTeX + make
# TO_BUILD:       docker build -t ykarikos/lilypond-book lilypond-book
# SOURCE:         https://github.com/ykarikos/lilypond-docker

FROM ykarikos/lilypond
LABEL maintainer Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
RUN apt-get update && apt-get install -qq -y texlive-xetex make fontconfig texlive-lang-european
ENTRYPOINT []
