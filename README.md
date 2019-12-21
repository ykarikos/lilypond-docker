# Lilypond Docker

Run [Lilypond](http://lilypond.org/) unstable 2.19.83 in a docker image:

```
docker build -t lilypond .
docker run  -v `pwd`:`pwd` -w `pwd` lilypond music.ly
```
