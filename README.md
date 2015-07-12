```yaml
size: 4.397 gb
compileTime: 30 mins
```

#### Introduction

Based on [mottosso/mayabase][1].

[1]: https://gist.github.com/mottosso/25c28b652135258ac31d

#### Installation

```bash
$ git clone https://gist.github.com/bf83edd6e4cccdceaed2.git maya && cd maya
$ docker build -t mottosso/maya .
```

#### Usage

```bash
$ docker run -ti --rm mottosso/maya mayapy
Python 2.7.3 (default, Aug  2 2012, 13:44:14)
[GCC 4.1.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

#### Known issues

1. The `xgenm` module is not available.