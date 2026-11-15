# Vinay Kumar

**Backend engineering · Java & Spring Boot · Distributed systems · Observability**

I build Java and Spring Boot APIs and PostgreSQL-backed features at micro1. At Crossing Hurdles, I design reproducible Go and Rust coding benchmarks for database and distributed-systems failures. I’m an M.Tech student at SRM University-AP, graduating in June 2028.

**Available for Summer 2027 software engineering and application engineering internships in India.** Open to international opportunities with visa sponsorship. [Portfolio](https://portfolio-sandy-mu-fn7vwjg3pe.vercel.app) · [LinkedIn](https://www.linkedin.com/in/themanvk) · [Email](mailto:vkslog69@gmail.com)

## Merged open-source contributions

- **Microsoft Kiota Java.** Fixed a Microsoft Graph deserialization failure when an enum set contains only unknown values. Added regression coverage for both unknown-only and mixed responses. [PR #2246](https://github.com/microsoft/kiota-java/pull/2246)
- **OpenTelemetry Java.** Fixed W3C baggage parsing so a malformed percent-encoded member no longer drops valid entries that follow it. Added a regression test. [PR #8480](https://github.com/open-telemetry/opentelemetry-java/pull/8480)
- **fmt.** Fixed a 32-bit C++ build failure in the fallback unsigned 128-bit type and verified the change on i686 and x86-64. [PR #4813](https://github.com/fmtlib/fmt/pull/4813)

## Selected projects

- **Distributed Job Scheduler** · Java, Spring Boot, PostgreSQL, Kafka, Redis. Implemented worker leases, backoff, dead-letter handling, and a transactional outbox. A local load test completed **10,000 jobs across 100 simulated workers with zero failures**. [Repository](https://github.com/Vcode2407/distributed-job-scheduler) · [Benchmark report](https://github.com/Vcode2407/distributed-job-scheduler/blob/main/docs/benchmark-report.md)
- **CloudDrive** · Java, Spring Boot, PostgreSQL, Redis, S3, Elasticsearch. Built a file-storage API with resumable uploads, versioning, sharing, and metadata search. Covered core workflows with integration tests. [Repository](https://github.com/Vcode2407/Cloud-Drive)
- **ScoutSearch** · Python, SQLite, React. Built a positional document index with explainable BM25 ranking and atomic updates. On a local workload of **1,654 CPython documentation passages**, broad-query median latency fell from **13.91 ms to 2.42 ms** and all **27 query results** matched the full-scan reference. [Repository](https://github.com/Vcode2407/ScoutSearch) · [Benchmark methodology](https://github.com/Vcode2407/ScoutSearch/blob/main/docs/real-corpus.md)

## Open pull requests

- **OpenTelemetry Java Instrumentation.** Preserve matched Spring MVC route templates in server spans and verify the behavior with Spring Cloud Gateway MVC. [PR #21304](https://github.com/open-telemetry/opentelemetry-java-instrumentation/pull/21304)
- **Google Cloud Pub/Sub Java.** Fix a cancellation deadlock in hedged publishing with regression tests for both losing-hedge and caller cancellation. [PR #15020](https://github.com/googleapis/google-cloud-java/pull/15020)
- **Meta RocksDB.** Keep blob compression metadata consistent with stored values when compression is disabled. Added a regression test and verified the baseline on Windows. [PR #15686](https://github.com/meta/rocksdb/pull/15686)

[Codeforces Expert](https://codeforces.com/profile/vickiease) · [LeetCode](https://leetcode.com/u/vkodes)
