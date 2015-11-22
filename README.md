# docker-compose-solrcloud

Stackfile for deploying solrcloud containers with tutum

*THIS REPOSITORY IS IN ALPHA QUALITY!*

## Required Nodes

* 3 2GB or larger instances

## How to use

Deploy it using tutum as a stack. Afterwords, exec following command on solr-1 terminal.

    /opt/solr/bin/solr create_collection -c collection1 -shards 2 -p 8983

Then you will be seen solrcloud replication graph on http://your-solr-1-hosts:8983/solr/#/~cloud
