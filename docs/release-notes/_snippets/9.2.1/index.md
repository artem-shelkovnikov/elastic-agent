## 9.2.1 [elastic-agent-release-notes-9.2.1]



### Features and enhancements [elastic-agent-9.2.1-features-enhancements]


* Add sample config files for Windows ES and mOTLP ingestion. [#10728](https://github.com/elastic/elastic-agent/pull/10728) [#10540](https://github.com/elastic/elastic-agent/issues/10540)

* Run self-monitoring as otel receivers by default. [#10594](https://github.com/elastic/elastic-agent/pull/10594) 

  The inputs used for Elastic Agent&#39;s self-monitoring now run as receivers inside a managed otel collector.
  This can be switched back by setting `agent.monitoring._runtime_experimental: process`.
  


### Fixes [elastic-agent-9.2.1-fixes]


* Fix issue where switching to OTEL runtime would cause data to be re-ingested. [#10857](https://github.com/elastic/elastic-agent/pull/10857) 
* Fix signal handling for the EDOT Collector. [#10908](https://github.com/elastic/elastic-agent/pull/10908) 
* Reload agent binary source settings as configured in Fleet. [#10993](https://github.com/elastic/elastic-agent/pull/10993) 

