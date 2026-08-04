# Apache Hadoop (hadoop)

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

Apache Hadoop is an open-source framework for distributed storage and processing of large datasets across clusters of computers using simple programming models. It includes HDFS for distributed storage, YARN for resource management, and MapReduce for parallel data processing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Big Data
- Data Processing
- Distributed Computing
- HDFS
- MapReduce
- Open Source

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### HDFS REST API (WebHDFS)

RESTful API for Hadoop Distributed File System operations including file operations, directory operations, and file status queries.

- **Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html)
- **Base URL:** `http://host:port/webhdfs/v1/`

#### Tags

- File System
- REST API
- Storage

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml)
- [Postman Collection](collections/hadoop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hadoop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### YARN REST API

RESTful API for Yet Another Resource Negotiator (YARN) for cluster resource management, application submission, and monitoring.

- **Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html](https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html)
- **Base URL:** `http://rm-http-address:port/ws/v1/`

#### Tags

- Cluster Management
- Resource Management
- REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml)
- [Postman Collection](collections/hadoop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hadoop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapReduce History Server REST API

REST API for accessing MapReduce job history and statistics.

- **Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html)

#### Tags

- Job History
- MapReduce
- REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html)
- [Postman Collection](collections/hadoop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hadoop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HttpFS REST API

HTTP REST API gateway supporting both webhdfs and httpfs operations for HDFS access.

- **Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html](https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html)
- **Base URL:** `http://httpfs-host:port/webhdfs/v1/`

#### Tags

- File System
- Gateway
- REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html)
- [Postman Collection](collections/hadoop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hadoop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/hadoop)
- [Website](https://hadoop.apache.org/)
- [Documentation](https://hadoop.apache.org/docs/stable/)
- [Getting Started](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html)
- [GitHub Organization](https://github.com/apache/hadoop)
- [Community](https://hadoop.apache.org/mailing_lists.html)
- [Changelog](https://hadoop.apache.org/releases.html)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
