# go-mysql

This repo contains Go packages to help build tools for MySQL. For example, there's a [slow log parser](https://github.com/percona/go-mysql/tree/master/log/slow) and a [query fingerprinter](https://github.com/percona/go-mysql/tree/master/query). Feedback, pull requests, and bug reports are welcome.

## Docs

http://godoc.org/github.com/percona/go-mysql

## Overview

Package|Contains
-------|--------
[event](http://godoc.org/github.com/percona/go-mysql/event)|Aggregator and metric stats
[log](http://godoc.org/github.com/percona/go-mysql/log)|Event struct and log parser interface
[log/slow](http://godoc.org/github.com/percona/go-mysql/log/slow)|Slow log parser
[query](http://godoc.org/github.com/percona/go-mysql/query)|Fingerprinter and ID
test|Sample data

## Versioning

Packages are not versioned. Interfaces, data structures, and overall usage are subject to change without notice.

## Testing

To test these packages locally, you'll need:
* github.com/go-test/test
* gopkg.in/check.v1
