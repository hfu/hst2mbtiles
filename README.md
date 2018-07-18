# hst2mbtiles
A command to create mbtiles from stdin stream of headless serialtiles

## Background
Creating mbtiles is a hard work. This tool is to encapsulate this burden to a single tool. Creating [headless serialtiles](https://github.com/hfu/headless-serialtiles-spec) is easier.

## Install
```console
$ git clone git@github.com:hfu/hst2mbtiles.git
$ cd hst2mbtiles
```

## Usage
```console
$ cat some.hst | node hst2mbtiles some.mbtiles
```

## See also
