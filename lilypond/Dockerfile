# AUTHOR:         Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
# DESCRIPTION:    Lilypond unstable
# TO_BUILD:       docker build -t ykarikos/lilypond lilypond
# SOURCE:         https://github.com/ykarikos/lilypond-docker

FROM debian
LABEL maintainer Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
RUN apt-get update -qq && apt-get install -qq -y curl bzip2
RUN curl -sO http://lilypond.org/download/binaries/linux-64/lilypond-2.19.84-1.linux-64.sh
RUN sh lilypond-2.19.84-1.linux-64.sh
ENTRYPOINT ["lilypond"]
