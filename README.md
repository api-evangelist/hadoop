# Apache Hadoop (hadoop)

Apache Hadoop is an open-source framework for distributed storage and processing of large datasets across clusters of computers using simple programming models. It includes HDFS for distributed storage, YARN for resource management, and MapReduce for parallel data processing.

**URL:** [https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Open Source

## Tags:

 - Big Data, Distributed Computing, Data Processing, MapReduce, HDFS, Open Source

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### HDFS REST API (WebHDFS)

RESTful API for Hadoop Distributed File System operations including file operations, directory operations, and file status queries.

**Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html)

**Base URL:** `http://host:port/webhdfs/v1/`

#### Tags:

 - File System, Storage, REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml)

### YARN REST API

RESTful API for Yet Another Resource Negotiator (YARN) for cluster resource management, application submission, and monitoring.

**Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html](https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html)

**Base URL:** `http://rm-http-address:port/ws/v1/`

#### Tags:

 - Resource Management, Cluster Management, REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml)

### MapReduce History Server REST API

REST API for accessing MapReduce job history and statistics.

**Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html)

#### Tags:

 - MapReduce, Job History, REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html)

### HttpFS REST API

HTTP REST API gateway supporting both webhdfs and httpfs operations for HDFS access.

**Human URL:** [https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html](https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html)

**Base URL:** `http://httpfs-host:port/webhdfs/v1/`

#### Tags:

 - File System, Gateway, REST API

#### Properties

- [Documentation](https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html)

## Common Properties

- [Website](https://hadoop.apache.org/)
- [Documentation](https://hadoop.apache.org/docs/stable/)
- [Getting Started](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html)
- [GitHub Organization](https://github.com/apache/hadoop)
- [Community](https://hadoop.apache.org/mailing_lists.html)
- [Change Log](https://hadoop.apache.org/releases.html)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
