## 1.2.0 [unreleased]

### Features
1. [#23](https://github.com/influxdata/influxdb-client-ruby/issues/23): Added DeleteApi to delete time series data from InfluxDB.
1. [#24](https://github.com/influxdata/influxdb-client-ruby/issues/24): Added jitter_interval and retry_interval to WriteApi
1. [#26](https://github.com/influxdata/influxdb-client-ruby/issues/26): Set User-Agent to influxdb-client-ruby/VERSION for all requests

### Security
1. [#29](https://github.com/influxdata/influxdb-client-ruby/pull/29): Upgrade rake to version 12.3.3 - [CVE-2020-8130](https://github.com/advisories/GHSA-jppv-gw3r-w3q8)

### Bugs
1. [#22](https://github.com/influxdata/influxdb-client-ruby/pull/22): Fixed batch write
1. [#28](https://github.com/influxdata/influxdb-client-ruby/pull/28): Correctly parse CSV where multiple results include multiple tables

## 1.1.0 [2020-02-14]

### Features
1. [#14](https://github.com/influxdata/influxdb-client-ruby/issues/14): Added QueryApi
2. [#17](https://github.com/influxdata/influxdb-client-ruby/issues/17): Added possibility to stream query result
3. [#19](https://github.com/influxdata/influxdb-client-ruby/issues/19): Added WriteOptions and possibility to batch write
 
## 1.0.0.beta [2020-01-17]

### Features
1. [#4](https://github.com/influxdata/influxdb-client-ruby/pull/4): Added WriteApi that will be used for Fluentd plugin
 
