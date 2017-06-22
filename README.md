# docker-drepl
[![Docker pulls](https://img.shields.io/docker/pulls/dlanguage/drepl.svg)](https://hub.docker.com/r/dlanguage/drepl/)
[![Docker Build](https://img.shields.io/docker/automated/dlanguage/drepl.svg)](https://hub.docker.com/r/dlanguage/drepl/)
[![Latest Tag](https://img.shields.io/github/tag/lindt/docker-drepl.svg)](https://hub.docker.com/r/dlanguage/drepl/)

DRepl as Docker Image

## Usage

```
docker run -ti dlanguage/drepl
```

This will start a Repl for D.
Once started, output will be similar to the following:

```
$ docker run -ti dlanguage/drepl
Welcome to D REPL.
D>
```

Use it like:

```
D> auto a = 23;
a
D> import std.stdio;
std
D> writefln("a is %s", a);
a is 23
```
## References

- https://github.com/dlang-community/drepl
