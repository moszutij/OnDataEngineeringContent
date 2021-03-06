---
title: Thoughts on Hortonworks DataPlane
tags: [Hortonworks DataPlane, Cloudera SDX]
date: 2018-09-28 07:45
---
*Updated 05/10/18 to reflect the fact that the DataPlane source code has been publshed on GitHub - thanks to Olivier from the comments* 

I've spent the last week digging a little further into [Hortonworks DataPlane](/technologies/hortonworks-dataplane/), and here are my thoughts..
<!--more-->

We talked last week about how Hadoop was changing away from being a single shared physical platform to a more logical platform that's better aligned with the emerging standard cloud technologies for storage and compute.  What we didn't talk about was the other shared goodness that went alongside the shared compute and storage - the shared metadata and single management, security and governance points that the Hadoop vendors have baked into their offerings.  Because the move to the cloud and being a more logical platform is going to impact this as well - they will need to adapt to this change.

Cloudera have addressed this with SDX - a conceptual architecture (although now baked into [Altus](/technologies/cloudera-altus/) and [Altus Director](/technologies/cloudera-altus/director/)) that delivers a single instance of all their governance, management and security products across Hadoop jobs and services running on multiple clusters over a multiple heterogenous storage.

And as as we noted when we last looked at DataPlane (and SDX) [late last year]({% post_url 2017-11-03-thoughts-on-hortonworks-dataplane-and-cloudera-sdx %}), Hortonworks were positioning DataPlane to be the same, however their stated ambition was much grander - to be the standard management layer across your entire data ecosystem by being a pluggable framework that other vendors could exploit.  It feels like that vision is a little way off however - at the moment the platform only supports Hortonworks Hadoop clusters (and only generally only Hive on those), and although there was a suggestion at one point that DataPlane would run as a cloud service, this doesn't currently appear to be the case.

And let's just note that the idea of having a single point of governance, management and security across your entire data ecosystem is not new - the big Data Integration vendors (Informatica, IBM etc.) have been banging on about elements of this for ever, and Forrester have now started talking about what they call the Big Data Fabric (score one for analysts introducing new terminology to make themselves sound clever).  Definitely something for us to dive into in a big for detail in the future.

Back to DataPlane then, and the new applications are coming thick and fast. [Data Lifecycle Manager](/technologies/hortonworks-dataplane/data-lifecycle-manager/) looks like a pretty convenient way of configuring backup and replication of Hive and HDFS data, [Data Steward Studio](/technologies/hortonworks-dataplane/data-steward-studio/) could be the start of an interesting metadata management solution, [Data Analytics Studio](/technologies/hortonworks-dataplane/data-analytics-studio/) looks useful for enabling users to run queries and understand performance and for techies to understand the load on their Hive tables and what needs optimising, and [Streams Messaging Manager](/technologies/hortonworks-dataplane/streams-messaging-manager/) is undoubtedly going to be invaluable if you're running Kafka with HDF.

And since we last looked, a bunch of DataPlane source code has been published on GitHub.  They're only publishing (development looks like it's still being done internally) and some of the source code is missing, but they're holding up their commitment to open source.

It's still early days, and as I noted when we last looked at DataPlane, it's going to be interesting to see where this goes, both in terms of what it means for Atlas and parts of Ambari, but also whether Hortonworks are really serious about this being a wider data ecosystem tool.