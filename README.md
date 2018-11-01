# splunk_cluster
Splunk Multisite cluster (use this even for a single site)

Running multisite even with 1 site orks fine, and allows for future conversion to more sites.

This project contains the Ansible playbooks needed to build a full Splunk cluster including the following:
  - Cluster master / Deployment server / License master / SHC deployer / Monitoring Console
  -- These roles can be combined on a single server or seperated as needed for scale.
  - Clustered Indexers
  - Clustered Search Heads
  - Universal Forwarders

Todo :
  - Cluster master license
  - Search Head clustering
  - UF install
  - UF eventgen 
  - Indexer Discovery
  - Firewall rules

Completed :
  - Splunk Core install
  - Cluster master
  - Indexers
  - Multisite support

  
  
