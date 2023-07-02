# Lilypond

Latest [Lilypond](http://lilypond.org/) stable version 2.24.1 in a docker image:

```
docker build -t ykarikos/lilypond lilypond
docker run --rm -v "$PWD:/music" -w /music ykarikos/lilypond music.ly
```

https://hub.docker.com/r/ykarikos/lilypond

# Lilypond-book

Lilypond + make + [XeTeX](https://www.tug.org/xetex/)

```
docker build -t ykarikos/lilypond-book lilypond-book
docker run --rm -v "$PWD:/music" -w /music ykarikos/lilypond-book make
```

https://hub.docker.com/r/ykarikos/lilypond-book