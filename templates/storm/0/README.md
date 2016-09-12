# Apache Zookeeper + Storm Clustter


### Info:

 This template creates, scale in and scale out a multinodes zk (zookeeper) cluster Connected with Storm Cluster ( Nimbus, Storm, Supervisor) on top of Rancher. The configuration is generated with confd from Rancher metadata. 
 
### Usage:

 Select zoo+storm from catalog. 
 
 Enter the number of nodes, mem and refresh interval for the zk cluster and storm components.

 Note: When you scale the cluster, zero downtime is not guaranteed..yet..
 
 Click deploy.
 
 Zookeeper+Storm can now be accessed over the Rancher network. 

