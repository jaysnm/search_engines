# Experimenting Search Operations with Solr, ElasticSearch and MeiliSearch

From official definitions:  

- [Solr](https://solr.apache.org/) is highly reliable, scalable and fault tolerant, providing distributed indexing, replication and load-balanced querying, automated failover and recovery, centralized configuration and more. Solr powers the search and navigation features of many of the world's largest internet sites.
- [Elasticsearch](https://www.elastic.co/elasticsearch/) is a distributed, RESTful search and analytics engine capable of addressing a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data for lightning fast search, fineβtuned relevancy, and powerful analytics that scale with ease.
- [MeiliSearch](https://github.com/meilisearch/MeiliSearch) is a powerful, fast, open-source, easy to use and deploy search engine. Both searching and indexing are highly customizable. Features such as typo-tolerance, filters, and synonyms are provided out-of-the-box.

The question is, between the three, which one is best suitable for search operations which can be embended into a website and other applications? Answering this question requires clear and extensive understanding of how both platform operate. Let's take a look into both:

## Solr Notebooks  

- [01-solr-techproducts.ipynb](01-solr-techproducts.ipynb) π Techproducts demo from [solr quickstart tutorial](https://solr.apache.org/guide/8_8/solr-tutorial.html)  
- [02-solr-films.ipynb](02-solr-films.ipynb) π Films demo from [solr quickstart tutorial](https://solr.apache.org/guide/8_8/solr-tutorial.html)  
- [03-schema-api.ipyn](03-schema-api.ipynb) π Solr schema definition using REST API  
- [04-indexing-custom-docs.ipynb](04-indexing-custom-docs.ipynb) π Elaborate guide of how to index custom documents. Composed using details adapted from [Solr Reference Guide](https://solr.apache.org/guide/8_8/)  
- [05-search-api.ipynb](05-search-api.ipynb) π A continuation of `04-indexing-custom-docs.ipynb` with focus on search operations  
- [06-sophisticated-indexing-and-search.ipynb](06-sophisticated-indexing-and-search.ipynb) π Fine tune query results using Solr `analyzers`, `tokenizers` and `filters`.  

## ElasticSearch Notebooks  


## MeiliSearch Notebooks  
