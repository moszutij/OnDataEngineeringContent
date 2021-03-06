---
title: "MapR Converged Data Platform"
description: "A data platform built that provides Hadoop compatibility (via YARN and the MapR-FS HDFS compatible API), NoSQL and streaming data storage via MapR-DB and MapR-ES respectively, and a bundle of open source Hadoop projects via the MapR Ecosystem Pack.  Comes with an installer (MapR Installer), a web based user interface for management (MapR Control System), and a monitoring and alerting solution (MapR Monitoring).  Available as a free community edition (which excludes some enterprise features such as snapshots, high availability, disaster recovery and replication), a full commercial edition, and as MapR Edge (a small footprint edition that can run on low power and embedded hardware close to data sources to perform initial data filtering and processing before forwarding data on to a central cluster via MapR replication), MapR-XD (an edition that focuses on MapR-FS plus the Orbit Cloud Suite to provide web scale file and container storage), MapR Converged Data Platform for Docker (a marketing name for using the Converged Data Platform as persistent storage for docker containers) and MapR Data Fabric for Kubernetes (ditto but for Kubernetes).  Supports a number of add-ons, including the Persistent Application Client Container (PACC, a docker image containing the client libraries required to connect to a MapR Converged Data Platform), MapR Orbit Cloud Suite (which adds support for deployment of cloud infrastructure along with MapR, integration with cloud object stores, plus mirroring and replication, with support for multi-tenancy, object tiering and OpenStack integration announced) and MapR Data Science Refinery (a docker based analytics notebook powered by Apache Zeppelin that fully integrates with the MapR Converged Data Platform).  Supports deployment in the cloud (AWS and Azure), and is available as a managed service. First released as MapR v1.0 in 2010"
alt-titles: [MapR Edge, MapR-XD, MapR Converged Data Platform for Docker, MapR Data Fabric for Kubernetes]
vendors: [MapR]
categories: [Hadoop Distributions]
tech-relationships: [[packages, MapR-FS, MapR-DB, MapR-ES, YARN, MapReduce, ZooKeeper, MapR Ecosystem Pack], [manageable via, MapR Installer, MapR Control System, MapR Monitoring], [add ons, Persistent Application Client Container, MapR Orbit Cloud Suite, MapR Data Science Refinery]]
type: "Commercial"
date: 2017-05-03 07:30
last_updated: 2018-10-10
version: "6.1"
---
## Release History

| version | release date | release links | release comment
| 5.2 | 2016-08-19 | 
| 6.0 | 2017-11-21 | [what's new](https://mapr.com/products/whats-new/6-0/); [release notes](https://mapr.com/docs/60/ReleaseNotes/whatsnew_60.html) | New MapR Control System; MapR-DB new features
| 6.1 | 2018-10-03 | [blog post](https://mapr.com/blog/mapr-6-1-new-horizons/); [GA announcement](https://mapr.com/blog/mapr-6-1-release-with-mep-6-0-is-now-generally-available/); [what's new](https://mapr.com/products/whats-new/6-1/); [release notes](https://mapr.com/docs/home/ReleaseNotes/whatsnew.html) | S3 compatible API; object tiering; enryption at rest

## Links

* <https://mapr.com/products/mapr-converged-data-platform/> - homepage
* <http://maprdocs.mapr.com/home/MapROverview/c_overview_intro.html> - overview
* <http://maprdocs.mapr.com/home/ReleaseNotes/c_relnotes_intro.html> - release notes
* <http://maprdocs.mapr.com/home/InteropMatrix/r_release_dates.html> - release history
* <http://doc.mapr.com/> - documentation for previous releases (prior to 5.0)
* <https://mapr.com/services/managed-services/> - managed service homepage
* MapR Control System
  * <https://mapr.com/products/mapr-control-system/> - MapR Control System home page
  * <https://mapr.com/blog/introducing-new-mapr-control-system/> - MapR Control System intro blog post
* MapR Edge
  * <https://mapr.com/products/edge> - MapR Edge home page
  * <https://community.mapr.com/community/products/blog/2017/03/14/introducing-mapr-edge> - introduction to MapR Edge
* MapR-XD
  * <https://mapr.com/products/mapr-xd/> - MapR-XD home page
  * <https://mapr.com/blog/intro-mapr-xd/> - introduction to MapR-XD
* MapR Converged Data Platform for Docker
  * <https://community.mapr.com/community/products/blog/2017/02/07/persistence-in-the-age-of-microservices-introducing-mapr-converged-data-platform-for-docker> - introduction to MapR Converged Data Platform for Docker
* MapR Data Fabric for Kubernetes
  * <https://mapr.com/solutions/data-fabric/kubernetes/> - homepage
  * <https://community.mapr.com/community/products/blog/2018/03/06/announcing-mapr-data-fabric-for-kubernetes> - announcement
* Persistent Application Client Container
  * <https://mapr.com/products/persistent-application-client-container/> - PACC homepage
* MapR Orbit Cloud Suite
  * <https://mapr.com/products/orbit-cloud/> - Orbit Cloud Suite home page
  * <https://community.mapr.com/community/products/blog/2017/08/29/introducing-the-mapr-orbit-cloud-suite> - introduction to Orbit Cloud Suite
* MapR Data Science Refinery
  * <https://mapr.com/products/data-science-refinery/> - Data Science Refinery home page
  * <https://mapr.com/blog/introducing-mapr-data-science-refinery/> - Data Science Refinery intro blog post

## News

* Announcements via the MapR product announcements blog