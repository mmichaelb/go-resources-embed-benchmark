# go-resources-embed-benchmark

Simple Golang benchmark of tools for embedding resources in your project.

When it comes to embedding resources inside your Go project there are many libraries which allow you to 
generate such resource files. Because I was also searching for such, I wanted to create a benchmark in 
order to determine which library scores best.

## Tested libraries

* [esc](https://github.com/mjibson/esc)
* [fileb0x](https://github.com/UnnoTed/fileb0x)
* [go-embed](https://github.com/pyros2097/go-embed)
* [go-resources](https://github.com/omeid/go-resources)
* [go.rice](https://github.com/GeertJohan/go.rice)
* [packr](https://github.com/gobuffalo/packr)
* [statics](https://github.com/go-playground/statics)
* [statik](https://github.com/rakyll/statik)
* [templify](https://github.com/wlbr/templify)
* [vfsgen](https://github.com/shurcooL/vfsgen)
* [go-bindata](https://github.com/go-bindata/go-bindata)
* [gobundle](https://github.com/alecthomas/gobundle)
* [parcello](https://github.com/phogolabs/parcello)

## Structure

In this benchmark the libraries have to pack different types of files:
- [test image](https://www.pexels.com/de/foto/bauernhof-bulle-draussen-farm-841303/)
- JSON mock test data
- youtube-dl binary

## Results

Benchmark system: DigitalOcean Droplet with 2GB RAM and 2 vCPUs.

TODO

## Usage

TODO