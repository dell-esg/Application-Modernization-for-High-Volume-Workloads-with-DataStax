
This README explains the YAML configuration files included in the associated directory, which are referenced in the white paper entitled "Application Modernization for High-Volume Workloads with DataStax". The white paper, jointly written by DataStax, Dell Technologies, and Intel, can be found on the Dell Technologies Info Hub for Data Analytics located here: 
https://infohub.delltechnologies.com/t/data-analytics/. 


cassandra-schema.yaml
===========
This file defines the database schema used for all the databases.  This is the same file found distributed through DataStax and Opensource Cassandra, typically found in cassandra/tools/cqlstress-insanity-example.yaml.  

cassandra-ocp-sata-config.yaml
====================
This file defines the Kubernetes Cassandra configuration used on OpenShift with SATA devices. 

cassandra-ocp-nvme-config.yaml
====================
This file defines the Kubernetes Cassandra configuration used on OpenShift with NVME devices.

cassandra-ocp-pmem-config.yaml
====================
This file defines the Kubernetes Cassandra configuration used on OpenShift with PMEM devices in Block mode.

cassandra-tanzu-sata-config.yaml
======================
This file defines the Kubernetes Cassandra configuration used on Tanzu with SATA devices.

cassandra-tanzu-nvme-config.yaml
======================
This file defines the Kubernetes Cassandra configuration used on Tanzu with NVME devices.
