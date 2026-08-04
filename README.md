# Sketches (sketches)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
