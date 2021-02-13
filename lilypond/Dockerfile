# AUTHOR:         Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
# DESCRIPTION:    Lilypond stable
# TO_BUILD:       docker build -t ykarikos/lilypond lilypond
# SOURCE:         https://github.com/ykarikos/lilypond-docker

FROM debian
LABEL maintainer Yrjö Kari-Koskinen <yrjo.karikoskinen@gmail.com>
RUN apt-get update -qq && apt-get install -qq -y curl bzip2
RUN curl -sO https://lilypond.org/download/binaries/linux-64/lilypond-2.22.0-1.linux-64.sh
RUN sh lilypond-2.22.0-1.linux-64.sh
ENTRYPOINT ["lilypond"]
