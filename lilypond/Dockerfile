FROM debian
RUN apt-get update -qq && apt-get install -qq -y wget bzip2
RUN wget -q http://lilypond.org/download/binaries/linux-64/lilypond-2.19.83-1.linux-64.sh
RUN sh lilypond-2.19.83-1.linux-64.sh
ENTRYPOINT ["lilypond"]