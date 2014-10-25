# Migu [![Build Status](https://travis-ci.org/naoina/migu.png?branch=master)](https://travis-ci.org/naoina/migu)

Database schema migration tool for [Go](http://golang.org).

Migu has idempotence like Chef or Puppet.

This tool is inspired by [Ridgepole](https://github.com/winebarrel/ridgepole).

## Installation

    # As library
    go get -u github.com/naoina/migu

## Usage

See files in `_example/simple/`.

## Supported database

* MySQL

## TODO

* Command-line interface
* Struct Tag support for some ORM
* PostgreSQL and SQLite3 support

## License

MIT
