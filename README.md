```yaml
size: 4.397 gb
compileTime: 30 mins
```

#### Introduction

Based on [mottosso/mayabase-ubuntu][1].

[1]: https://gist.github.com/mottosso/25c28b652135258ac31d

#### Usage

```bash
$ docker run -ti --rm mottosso/maya mayapy
Python 2.7.3 (default, Aug  2 2012, 13:44:14)
[GCC 4.1.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

#### Build (optional)

The image is automatically built and will be available via the above `Usage` instructions. But if you are interested in modifying or contributing to the Dockerfile, the following instructions can be helpful.

```bash
$ git clone https://github.com/mottosso/maya2015-ubuntu.git && cd maya2015-ubuntu
$ docker build -t mottosso/maya2015-ubuntu .
```


#### Known issues

1. The `xgenm` module is not available.
