# cmplopes/alpine-gfortran
Docker Free Pascal over Alpine Linux

```
$ docker pull -t cmplopes/alpine-freepascal:[TAG]
```

## Suported Tags

[3.0.4, latest (over alpine:3.7) (Dockerfile)](https://github.com/cmplopes/alpine-freepascal/blob/master/3.0.4/Dockerfile)

## Check Free Pascal version
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine-freepascal
```
or
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine-freepascal fpc -iw
```

## Compile, link and run a Free Pascal program
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine-freepascal fpc test.pas
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine-freepascal ./test
```
