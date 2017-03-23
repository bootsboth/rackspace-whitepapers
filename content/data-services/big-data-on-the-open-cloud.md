---
permalink: big-data-on-the-open-cloud/
audit_date:
title: Big Data on the Open Cloud
type: whitepaper
created_date: '2012-10-19'
created_by: Rackspace Support
last_modified_date: '2017-03-10'
last_modified_by: Cat Lookabaugh
product: Data Services
product_url: data-services
---

### Rackspace<sup>&reg;</sup> Private Cloud, Powered by OpenStack<sup>&reg;</sup>, Helps Reduce Costs and Improve Operational Efficiency

### 1. Introduction

Rackspace<sup>&reg;</sup> Enterprise Business Intelligence group (EBI) is a
central team that aggregates, manages and provides business intelligence on
data from several business-critical data sources. To keep up with Rackspace’s
customer growth and technology infrastructure, EBI wanted to consolidate
the rapidly-growing volumes of data for reporting, trending, and
analytical purposes. This white paper highlights how EBI used [Rackspace
Private Cloud Software](http://www.rackspace.com/cloud/private/) to
power a cloud-based big data solution while reducing costs and improving
operational efficiency.

### 2. Turning Bytes into Business Intelligence

EBI’s legacy data warehouse consists of commercial database vendor
solutions on dedicated servers. Data points included customer account
data, usage and billing information, with business intelligence toolset
interoperability from Informatica and Qlikview. From an operational
level, the overall data became unmanageable once important information
like monitoring, response, and support metrics came in from dedicated,
virtual, and cloud devices.

Daily reporting became a time consuming and resource-intensive process,
only occurring nightly and with a 24-hour data point lag time.
Commercial database licensing and hardware costs were rising in a
disproportionate manner as the EBI team worked with database
administrators to quickly increase capacity during peak hours. Finally,
the legacy set up did not handle unstructured data very well, and the
team wanted to be able to apply different best-of-breed technologies
(e.g. columnar, noSQL, SQL) alone or in combination depending upon the
type and size of data they wanted to store and analyze.

To continue serving the business efficiently and effectively, EBI put
together requirements for a new solution. Named the Analytic Compute
Grid (ACG), the solution would act as the backbone for EBI and needed to
be able to:

-   House an ever-growing set of data collected in different formats,
structured and unstructured, from multiple business units within Rackspace
-   Rapidly and dynamically scale resources up and down to efficiently meet
business demands
-   Add new resources on the fly without waiting for new hardware provisioning
during peak hours
-   Run different, best-of-breed, big data technologies for storing, managing,
analyzing and distributing data on one technology platform
-   Enable the EBI team to move away from rising commercial database licensing
fees
-   Utilize open APIs to facilitate integration and programmatic access with
other enterprise systems and BI tools
-   Support Rackspace security and compliance requirements
-   Embrace open cloud and open source technologies

With those requirements in mind, the Rackspace EBI team then evaluated
the following options:

<img src="{% asset_path data-services/big-data-on-the-open-cloud/ACG_1.png %}" />

#### Option 1: Stay the Course

**Pros**

-   Short-term minimal interruption to existing projects and end-users
-   No additional training necessary
-   Could continue to leverage vendor support

**Cons**

-   Licensing costs that spiked as data volume increase
-   Database administration (DBA) support for resources spread across multiple
OLTP databases and BI databases.
-   Scalability of systems – to grow the current system is very time consuming
in conjunction with growing data volumes
-   Current technologies offer no support for big data
-   Legacy commercial database products do not scale performance with data
volume. Making these products scale would require complex clustered footprints
of servers. In addition, both vendors recommend their own proprietary
infrastructure and database technology.

#### Option 2: Purchase an MPP (Massively Parallel Processing) Appliance

**Pros**

-   High-performance
-   Purpose-built for BI workloads
-   Interoperability with existing BI toolsets
-   Large BI customer base with a rich feature set provided by vendors

**Cons**

-   High costs relative to current environment, including cost to
    acquire appliance, set up fees, licensing, maintenance, training,
    etc.
-   Proprietary hardware configurations and database engines

#### Option 3: Running Legacy BI Apps on Commercial Virtualization Software

**Pros**

-   More efficient than running on physical hardware
-   Some elasticity to “scale up” the VMs and expand footprint
-   Relatively easy migration of legacy BI apps to virtualized
    infrastructure

**Cons**

-   Limited “scale out” capabilities and resource-sharing as compared to a
cloud environment
-   Additional licensing costs
-   Concerns of building on and getting locked into proprietary and licensed
commercial virtualization software

#### Option 4: End-to-end Open Source Solution on Rackspace Private Cloud

**Pros**

-   Enables scaling out and back faster than siloed hardware or virtualized
servers
-   An entire open source technology stack – avoiding vendor lock-in
-   Ability to leverage commodity hardware
-   No software licensing costs
-   Take advantage of faster innovation in open source platforms due to
community participation and contribution
-   Ability to leverage public cloud resources where appropriate

**Cons**

-   Training developers and end users on new technologies
-   Large migration
-   Must build, buy, or find adaptors for BI tools



### 3. The Choice: End-to-end open source solution on Rackspace Private Cloud

<img src="{% asset_path data-services/big-data-on-the-open-cloud/ACG_2.png %}" />

These requirements led EBI to design and build a stack based on open
source technologies – from infrastructure to big data software – to
allow for rapid growth and scale. The underlying infrastructure platform
they selected was Rackspace Private Cloud, powered by
[OpenStack<sup>&reg;</sup>](http://www.openstack.org/), in tandem with Cassandra,
Hadoop, and PostgreSQL. The solution was dubbed as Analytic Compute Grid
or ACG.

ACG is a big data management software platform built on Rackspace
Private Cloud software. As a key benefit, it provides a consolidated and
flexible solution to store, analyze, distribute and present the data
based on the type of the data (structured or unstructured), operation
(storing or analyzing the data) and the consumer’s skillset (data
scientist accessing via APIs or a marketing analyst using BI tools to
run reports.)

### 4. The Results

- The EBI can now process terabytes of data per day in real-time or
on-demand
- Processing tasks that took six days on the legacy system have been
reduced to three hours
- Existing BI tools can be leveraged by custom ANSI SQL APIs, and
additional technologies can be easily added via extensions
- The ACG reduced the need for two additional administrators
- Improved trending and reporting data is currently being utilized to
enhance support capabilities and the Rackspace customer experience

### 5. Conclusion

By creating a single holistic platform utilizing open source
technologies, the Enterprise Business Intelligence team’s Analytic
Compute Grid can handle the storage, analysis and distribution of data
at scale in a timely manner. The big data tools available today helped
solve the problem but required new ways of thinking about the underlying
infrastructure, processes and data structures to make it a reality.
Built using Rackspace Private Cloud, powered by OpenStack, Hadoop,
Cassandra, and other tools, the ACG has resulted in improvement in data
processing speeds and a significant reduction in overall capex and opex.
Multiple business units at Rackspace can now make near real-time
decisions that can directly benefit Rackspace customers.
