# Lilypond

Run [Lilypond](http://lilypond.org/) unstable 2.19.83 in a docker image:

```
docker build -t lilypond lilypond
docker run  -v `pwd`:`pwd` -w `pwd` lilypond music.ly
```

# Lilypond-book

Lilypond + make + XeTeX

```
docker build -t lilypond-book lilypond-book
docker run  -v `pwd`:`pwd` -w `pwd` lilypond-book make
```
