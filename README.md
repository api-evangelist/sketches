# Sketches (sketches)
Sketches are probabilistic data structures used in computing and data engineering to approximate answers to queries over large data streams with controlled error bounds and dramatically reduced memory requirements. Common sketches include Count-Min Sketch (frequency estimation), HyperLogLog (cardinality estimation), Bloom Filter (membership testing), and T-Digest (quantile estimation).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/apis.yml)

## Tags:

 - Approximate Query Processing, Big Data, Data Structures, Probabilistic Algorithms, Real-Time Analytics, Streaming Analytics

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-02

## APIs

### Apache DataSketches API
Apache DataSketches is the leading open-source library of production-quality sketch implementations (Theta, HLL, Quantiles, Frequency) widely integrated into Apache Druid, Amazon Redshift, and Spark.

**Human URL:** [https://datasketches.apache.org](https://datasketches.apache.org)

#### Tags:
 - Analytics, Apache, Data Structures, Open Source, Probabilistic Algorithms

#### Properties
- [Documentation](https://datasketches.apache.org)
- [GitHubOrg](https://github.com/apache/datasketches-java)

---

### Redis Probabilistic Data Structures API
Redis Stack (RedisBloom) provides native Bloom Filter, Cuckoo Filter, Count-Min Sketch, Top-K, and HyperLogLog implementations as server-side Redis commands.

**Human URL:** [https://redis.io/docs/data-types/probabilistic/](https://redis.io/docs/data-types/probabilistic/)

#### Tags:
 - In-Memory, Probabilistic Data Structures, Real-Time, Redis

#### Properties
- [Documentation](https://redis.io/docs/data-types/probabilistic/)
- [Website](https://redis.io)

---

### Amazon Redshift Approximate Query API
Amazon Redshift provides native HyperLogLog SQL functions for fast cardinality estimation on billions of rows with controlled error bounds.

**Human URL:** [https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html](https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html)

#### Tags:
 - Analytics, AWS, HyperLogLog, Redshift, SQL

#### Properties
- [Documentation](https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html)

---

## Common Properties

- [Website](https://datasketches.apache.org)

## Artifacts

### JSON Schemas
- [sketches-sketch-schema.json](json-schema/sketches-sketch-schema.json) — Probabilistic sketch configuration and result schema

### JSON Structures
- [sketches-structure.json](json-structure/sketches-structure.json) — Sketch types and algorithm documentation

### JSON-LD
- [sketches-context.jsonld](json-ld/sketches-context.jsonld) — Linked data context

### Vocabulary
- [sketches-vocabulary.yml](vocabulary/sketches-vocabulary.yml) — Domain terminology for probabilistic data structures

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
