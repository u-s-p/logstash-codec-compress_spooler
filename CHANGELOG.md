## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully, 
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0

# 0.2.1

* Fixes data loss that happen for each even of each new round after the
  first one.

# 0.2.0

* Refactoring the Json and Timestamp usage
* Make usage of mri/jruby dependencies in each platform
* Add support for tests spec
