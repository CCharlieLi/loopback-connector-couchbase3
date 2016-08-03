# loopback-connector-couchbase3

[![Build Status](https://travis-ci.org/CCharlieLi/loopback-connector-couchbase3.svg?branch=master)](https://travis-ci.org/CCharlieLi/loopback-connector-couchbase3)
[![Coverage Status](https://coveralls.io/repos/github/CCharlieLi/loopback-connector-couchbase3/badge.svg?branch=master)](https://coveralls.io/github/CCharlieLi/loopback-connector-couchbase3?branch=master)

This is a Couchbase connector node module for [Loopback](http://loopback.io/) with [loopback-datasource-juggler](https://github.com/strongloop/loopback-datasource-juggler). Without N1QL for now.

## How to use

### Install

```
npm install loopback-connector-couchbase3 --save
```

### Config

```
# datasources.json
{
  "couchbaseTestBucket": {
    "name": "couchbaseTestBucket",
    "connector": "couchbase3",
    "cluster": {
      "url": "couchbase://localhost",
      "options": {}
    },
    "bucket": {
      "name": "test_bucket",
      "password": ""
    }
  }
}
```

## Test

precheck: couchbase server is runing with two buckets named `test_bucket`, `test_ping` and enabled its flush feature.
run: `npm test`

## Git Summary

```
 project  : loopback-connector-couchbase3
 repo age : 12 months
 active   : 44 days
 commits  : 88
 files    : 34
 authors  : 
    47  Makara Wang        53.4%
    25  CCharlieLi         29.5%
     7  chopperlee         8.0%
     3  Leo Zhou           3.4%
     3  wwayne             3.4%
     2  greenkeeperio-bot  2.3%
```
