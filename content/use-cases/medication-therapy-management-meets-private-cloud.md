---
permalink: medication-therapy-management-meets-private-cloud/
audit_date:
title: Medication Therapy Management Meets Private Cloud
type: whitepaper
created_date: '2013-08-27'
created_by: Rackspace Support
last_modified_date: '2017-03-28'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="http://www.pharmmd.com/">
   <img src="{% asset_path use-cases/medication-therapy-management-meets-private-cloudy/pharmmd.png %}" width="214" height="130" />
</a>

**CUSTOMER’S BUSINESS:** PharmMD offers a range of medication therapy
management solutions.

**CHALLENGES:** PharmMD needed the benefits of cloud in a private environment.

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Rackspace Private
Cloud](http://www.rackspace.com/cloud/private/)

**BUSINESS OUTCOME:** Rackspace Private Cloud has allowed PharmMD to
double performance and address compliance while reducing costs.

### PharmMD Doubles Performance While Reducing Costs

Founded in 2006 by pharmacists Clayton McWhorter and Fred McWhorter,
PharmMD offers a range of medication therapy management (MTM) solutions.
Through these services, the company assists physicians and pharmacists
in monitoring patient health while cutting down on the problems, risks,
and waste resulting from medication misuse.

After hosting with a major public cloud provider, PharmMD moved to
[Rackspace Private Cloud](http://www.rackspace.com/cloud/private/),
which allows them to automate their infrastructure within a private
cloud where they can address their security concerns while lowering
overall costs.

### Security

PharmMD is one of the first startups in the medication management
therapy space, which is poised for enormous growth thanks to new
government regulations. “As part of Centers for Medicare & Medicaid
Services (CMS) changes, requirements were put in place that all health
plans had to do medication therapy management, which identifies when
people that have drug therapy problems,” chief marketing officer and
former CTO Gregory Green explains. “Our solutions identify patients that
are using incorrect dosages or being prescribed medications that have
negative interactions, suggest generic alternatives to reduce costs, and
intervene on behalf of employers or health plans to correct those gaps
in care.” As a healthcare SaaS dealing with personal health information,
PharmMD has strict security requirements. “When we look to a [public
cloud](http://www.rackspace.com/cloud/public), we need a hosting
provider our customers are satisfied with,” says Green. “Our previous
host wouldn’t sign necessary agreements, so we were forced to look
elsewhere.”

In considering their next move, Green says, “We looked at possible
abstraction and virtualization technologies we could use, and the
general consensus was to move to VMware. We already had it, and I didn’t
want to bring yet another virtualization offering in. However, our
senior systems architect was adamant that we look at
[OpenStack<sup>&reg;</sup>](http://www.rackspace.com/cloud/openstack/).”

After a frustrating first attempt to investigate OpenStack on its
own, PharmMD turned to OpenStack founder, Rackspace for guidance.
Through discussions with Rackspace and an eyeopening business case, the
team realized that purchasing their own hardware and deploying Rackspace
Private Cloud in a colocation facility could satisfy their security
requirements while boosting performance and lowering costs.

### Lower Spend, Greater Stability

In PharmMD’s early days, their sine-wave growth inspired an ad hoc
approach to infrastructure. While public cloud enabled this spontaneity,
senior systems architect James Scollard says the lack of planning also
led to inefficiency and overspending. “A lot of our infrastructure
design was never right-sized or designed for making most efficient use
of hardware,” he says. “We would just spin stuff up and never cull out
older stuff—it caused a lot of cost creep.”

The company also faced stability issues. “Block storage volumes would
vanish, we’d lose elastic IPs, ephemeral disks would just drop…things
like that,” Green says. “We would build RAID 10 arrays with four block
storage volumes to get past performance limitations, but when you lost a
volume it would put your array at risk. The failures we were
experiencing were causing more and more problems.”

PharmMD has begun to migrate their infrastructure—including 100 VMs and
a 30-node analytics platform—to their new environment, which makes use
of [OpenStack Nova
compute](http://docs.rackspace.com/servers/api/v2/cn-gettingstarted/content/novaclient.html),
Cinder block storage, and LDAP integration features. This new
implementation will boost performance and stability without increasing
cost. “We’ve overbuilt to double the amount of performance,” Scollard
says. “For the cost of around eight months of hosting with our previous
provider, we have not only managed to replace our previous
infrastructure entirely, but also gained close to 50% more hardware and
disk capacity. Compared to what we were paying at our previous host, we
are more stable, and our environment will pay for itself.”

### Outsourcing and Automation

Core software support for Rackspace Private Cloud provides PharmMD the
benefits of Rackspace Managed Operations, even in a third-party
facility. Remote login allows Rackspace to handle a variety of
management and operational tasks for the company, including
installation, patching, troubleshooting, bug fixes, and capacity
management for their OpenStack-powered Private Cloud. This 24x7x365
support maximizes stability and performance and saves PharmMD the
additional expense of hiring operations staff.

Besides outsourcing infrastructure management, PharmMD has further
streamlined its process by hiring and training experts in Opscode Chef.
PharmMD’s Chef developers can automate tasks that were once
time-consuming and manual, which allows them to stay on schedule with
tight project timelines. “From the moment we have a contract, we have 90
days to go live,” Green says. “Project plans get built like that. In a
perfect world it’d be 90 days, but historically, it’s usually 3-4
weeks.” Chef allows PharmMD to make productive use of Rackspace Private
Cloud rather than wasting time on manual setup.
