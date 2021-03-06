---
id: sg-release-notes
title: SG release notes
---

## 1.5 release

__Enhancements__

- [__#1462__](https://github.com/couchbase/sync_gateway/issues/1462) Sync Gateway Accelerator is reporting itself as Sync Gateway
- [__#2151__](https://github.com/couchbase/sync_gateway/issues/2151) The /{db}/\_changes?include_docs=true request shouldn't return _user/user docs
- [__#2626__](https://github.com/couchbase/sync_gateway/issues/2626) Possibility of notifications being skipped which can result in sequence numbers to be wrongly allocated

__Bugs__

- [__#2367__](https://github.com/couchbase/sync_gateway/issues/2367) Omitting the logFilePath property in the logging configuration of Sync Gateway results in a null pointer exception crash
- [__#2381__](https://github.com/couchbase/sync_gateway/issues/2381) SG Replicate stops when an attachment with no content type is replicated
- [__#2400__](https://github.com/couchbase/sync_gateway/issues/2400) SG collect info is not case sensitive on the config's logFilePath property
- [__#2421__](https://github.com/couchbase/sync_gateway/issues/2421) Discard new rev sequence if it is less than a docs current rev sequence, to avoid issues with caching
- [__#2500__](https://github.com/couchbase/sync_gateway/issues/2500) Webhook event not fired when using bucket shadowing