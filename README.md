# Elasticsearch

Elastic Search is an open source, RESTful distributed and scalable search engine. Elastic search is extremely fast in fetching results for simple or complex queries on large amounts of data (Petabytes) because of it’s simple design and distributed nature. It is also much easier to work with than a conventional database constrained by schemas, tables.

Elastic Search provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents.

Elasticsearch is document oriented, meaning that it stores entire object or documents. It not only stores them, but also indexes the content of each document in order to make them searchable. In Elasticsearch you index, search,sort and filter documents.
Elasticsearch uses JSON as the serialisation format for the documents.

The act of storing data in Elasticsearch is called indexing. An Elasticsearch cluster can contain multiple indices, which in turn contain multiple types. These types hold multiple documents, and each document has multiple fields.

### A few notable features of the product include:

* Speed: Elasticsearch is really fast. It can process queries far more quickly than MySQL or other relational databases, especially for full-text searching. This faster performance is due to Elasticsearch’s document-based approach to indexing, which is very different from a typical relational database structure of tables made up of columns and rows.

* Scalability: You can run Elasticsearch on a single laptop, or you can set up a cluster with a few hundred nodes. Elasticsearch's horizontal scaling allows the system to handle as much load as you can throw at it; the system’s ability to automatically manage and distribute queries across a cluster keeps operations running smoothly at all times.

* Resiliency: Even the most well-maintained systems occasionally have problems. Fortunately, Elasticsearch is able to detect failures and take action to keep your data safe. You can take advantage of cross-cluster replication to have a secondary cluster ready as a backup as needed.

## Use Cases for Elasticsearch

* Full-text search: Traditional relational database management systems aren't always the best choice for applications that are heavy on text searching, but this is an area where Elasticsearch really shines. The ability to handle fuzzy searches and “search as you type” autocomplete functionality improves overall search quality even more.

* Logging and analysis: Elasticsearch is widely used by organizations to store and analyze log data. For example, the SaaS company Paylocity was having difficulty keeping up with their logs as their business underwent massive growth. With the help of the Elastic Stack, they’re now able to index and analyze 500 million logs per day.

* Scraping remote data from multiple sources: Scraping and indexing public data is a breeze with the Elastic Stack. Elasticsearch’s document-based approach, which lacks the strict schema found in relational databases, makes it easy to pull in data from a wide variety of sources while keeping it all searchable. With the help of Elasticsearch, you can analyze and make sense of large volumes of data scraped from the web.

* Metrics analysis: Another area where Elasticsearch really stands out is metrics. The National Energy Research Computing Center (NERCC) made good use of the Elastic Stack to crunch through over 1.2 billion documents per day, analyzing metrics on system load, power usage KPIs, building air temperature, and much more. The Elastic Stack even has machine learning capabilities that can spot anomalies. Once it learns what’s normal in your data, it can identify issues and alert you when anomalies are detected.
