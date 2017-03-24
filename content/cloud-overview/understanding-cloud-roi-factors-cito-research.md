---
permalink: understanding-cloud-roi-factors-cito-research/
audit_date:
title: Understanding Cloud ROI Factors - CITO Research
type: whitepaper
created_date: '2012-12-20'
created_by: Rackspace Support
last_modified_date: '2012-12-20'
last_modified_by: Liz Staplefoote
product: Cloud Overview
product_url: cloud-overview
---

### Introduction

The cloud can save you money. That’s a statement almost everyone agrees
with. But exactly how does that work? CITO Research has been examining
the ROI of the cloud for several years. In this paper, we share the
insights from our research so far, helping you understand the factors
that influence the ROI of the cloud and its implications for your
organization.

In calculating cloud ROI, you must consider factors that are relevant to
your enterprise application portfolio and computing needs. While this
paper is not a step-by-step guide to determining cloud ROI, it is
possible to calculate cloud ROI by examining the factors analyzed in
this white paper and determining how they apply to your situation.

### Cloud ROI Considerations

Switching from traditional on-premise data centers to a cloud-computing
model can produce cost savings for enterprises. The cloud decomposes the
traditional hard-wired relationships between application, server,
hardware, network, and storage, freeing these resources from their
traditional constraints. Cloud providers tend to deploy low-cost
commodity hardware, with a layer of software-based management, which
allows for many alternative configurations. Because of this, moving to
the cloud will generally increase the return on your technology
investment. However, it also opens the door to new activities that may
not fit into a standard ROI calculation.

For example, let’s say that you spend $100,000 per month on
self-hosting an e-commerce site that generates $110,000 per month.
That’s a 10% ROI. By outsourcing hosting to a cloud provider, and
lowering monthly expenses by $20,000 per month, that same $110,000
could still be generated if the application performs at the same level.
That’s a 37.5% ROI. In addition, it frees up capital to redeploy
resources formerly dedicated to maintaining infrastructure to
higher-value activities such as research and development. It’s up to
your organization to determine the value of this new freedom.

#### Analysis of cloud ROI should take several broad considerations into account:

**Units of Measure:** A common measure of productivity is cost per unit
of computing power. It generally costs less per unit of computing power
to run an application in the cloud than it does on premise.

However, many cloud operators define computing power differently. Some
look at a virtual machine as an equivalent of a CPU with a certain GHz
of processing speed. Others create units that are comprised of the
entire “stack” of assets that go into the cloud—networking speed,
storage input/output operations per second, memory speed, and processing
speed. It is imperative for your enterprise to obtain an explicit
definition of how your intended cloud provider measures productivity or
cost on a unit basis.

**Tradeoffs:** Cloud computing reduces the management time and capital
costs associated with maintaining on-premise equipment. Assuming an
application is “operationally intelligent,” in other words, designed to
work around performance variations common in the cloud, this usually
translates to a net savings.

However, many applications were not designed to operate in a cloud
environment and cannot run properly unless components such as app
servers and databases are highly optimized and perform at levels beyond
those common in the cloud. These applications may need to be refactored
to work in the cloud.

The decision about whether to move that application into the cloud
depends on an assessment of its total capital and operating cost,
including computing hardware, software, and human resources, weighed
against the cloud’s utility pricing and self-service model combined with
the amount of labor necessary to redesign the application.

**Intangibles, Expressed as Time:** Cloud computing can create outcomes
that are subjectively important but may not have a readily determined
monetary value or an easy way of accounting for financial impact; using
a weighting scale can make these factors work in an equation.

Intangibles can be expressed in terms of time. This could include time
for innovative software design that would formerly have been dedicated
to “keeping the lights on.” A qualitative benefit such as “ease of use”
may need to be turned into a quantitative expression—how many clicks
does it take to accomplish the same task in the cloud vs. on-premise?
How long did it take to complete the simplified task?

### Investment (Cost) Factors

Moving to the cloud adds new factors for calculating cost or
investment—the denominator of the equation. This affects several
dimensions of how organizations think about the cost of computing.

#### Traditional Factors Changed by the Cloud

Expanded use of the cloud transforms the nature of many different forms
of cost savings or potential lower investment, which are central to the
determination of ROI:

**Economies of scale:** When you pay a cloud provider, you benefit from
economies of scale. The provider houses multiple customers’ computing
assets in large, highly scalable data centers, providing savings for all
of the customers that would otherwise have occurred individually.

**Avoiding building for peak loads:** Consider what goes into planning a
directly owned and operated data center—you must purchase enough
equipment and establish enough space and connectivity for that equipment
to accommodate peak loads, such as the holiday shopping season or an IPO
on Wall Street. The consequences of not doing this are too grave to
consider. The disadvantage of overprovisioning is that you almost
certainly end up with wasted or redundant capacity.

**Reduced data center capital expenses:** Cloud ROI calculations should
take into account reduced need for data center space and all the costs
associated with it.

In the cloud, there are no up-front costs associated with building a
data center, such as land acquisition, design, and construction. Cloud
providers have already made and are amortizing that investment by
acquiring numerous customers and capitalizing on economies of scale. You
can avoid building or at least defer expanding your data center using
the cloud.

**Reduced data center operational expense:** Cloud providers also save
you the cost of operating a data center. Paying energy bills, IT staff,
and security personnel to maintain the center all go away when you
transfer those responsibilities to the cloud. Again, the economies of
scale that come from shared premises mean that operating costs borne by
the cloud provider are amortized across a large customer base.

**Reduced disaster recovery risk:** You can also significantly reduce
risk by using the cloud for disaster recovery, which is a new challenge.
Cloud providers have made the investment in multiple, redundant data
centers and backup policies that protect their customers. If the
unthinkable happens, all of your eggs won’t be in one basket.
Additionally, you can further reduce risks by retaining more than one
cloud provider for your most critical applications and services.
Nevertheless, ownership considerations may come into play that would not
be an issue in standard disaster-recovery scenarios and should be
discussed with your cloud provider: Who owns content synchronization and
failover responsibility? Who determines recovery time objective (RTO)
and recovery point objective (RPO)?

#### New Factors Introduced by the Cloud

Cloud computing introduces new factors into the ROI equation that
require thinking outside the box of capital acquisition, licensing of
software, and depreciation:

**Paying only for what you use:** Switching to the cloud means you only
pay for what you use, and you can scale up and down as needed.

**Moving from CapEx to OpEx:** When switching to a pay-as-you-go model,
many companies find that savings accrue from changing their financial
accounting for computing assets from capital expenditures (CapEx) to
operating expenditures (OpEx). With CapEx, the full cost of an asset is
levied right away, but the expense of the asset is depreciated over
time. With OpEx, the expense can be deducted in full in the year it
occurs.

<img src="{% asset_path cloud-overview/understanding-cloud-roi-factors-cito-research/ROI_1.png %}" width="337" height="341" />

**New levels of transparency into cost and computing resource use:**
Through a cloud provider’s interface, you can see exactly how many CPUs
are being used to support each application, what that power is costing
you, and how well your application makes use of those resources. That
means you can better manage your existing applications, as well as make
decisions about rolling out new applications with much greater
confidence than before.

**Increased control and automation:** When your enterprise switches to
the cloud, you can instantly gain benefits from greater control and
precision over your resources. When your application needs more
computing power, direct application programming interfaces (APIs) can
seamlessly automate the assignment of that power by implementing rules
you have set.

#### OpenStack and the Open Cloud

In one respect, cloud technology is exactly like all previous
generations of technology: if you are not careful, you may end up locked
into a particular vendor and lose options. The first generation of the
cloud has been dominated by Amazon Web Services, a proprietary cloud
implementation controlled by one company.
[OpenStack](http://www.rackspace.com/cloud/openstack/resources/), the
open-cloud initiative co-founded by
[Rackspace](http://www.rackspace.com/), created cloud infrastructure
software created and distributed as open source. The largest service
providers in the world, companies like IBM, HP, Dell, and others have
all committed to building clouds using OpenStack. While these vendors
will compete on levels of service and other aspects, the cloud software
will run the same in each cloud, meaning the customers have choices and
avoid lock-in.

**Avoiding vendor lock-in:** The open cloud (see above) can also
increase your choices of vendors for any number of services, reducing
the risks associated with vendor lock-in and propelling maximum savings
potential, as well as driving returns.

**Scale quickly:** A prime cost benefit of the cloud’s economy of scale
lies in customers’ ability to scale up and down quickly, across a number
of investments. If your company acquires or sells a division or another
company, typically it inherits the contract obligations of that company,
which include hardware, software, data centers, and support contracts
for all of the above. With more companies joining the cloud, an
acquisition or divestiture doesn’t carry that burden. You can add or
delete redundant services associated with the acquired or sold asset,
generally with fewer obligations than with traditional, on-premise
computing resources.

**Increase Resource Efficiency:** By moving to an outsourced cloud
provider, your non-computing resources (people!) also become more
efficient. Enterprises can:

-   Reassign employees formerly dedicated to low-level IT tasks, such as
supporting hardware updates and administering servers, and offer them more
challenging work.
-   Start a new business or a new line of business. You may be able to do so
without investing in any additional staff or computing resources.
-   Eliminate employees who were formerly required to support on-premise
computing services and data centers, affording a new range of flexibility for
investments.

### Return Factors

Now we examine the numerator of the ROI equation, the return on
investment.

#### Traditional Return Factors Changed By the Cloud

Cloud computing repeals the “curiosity tax” imposed by the need for
expensive infrastructure to support innovation. The cloud enables you to
run experiments internally or in the marketplace. The ability to shut
down the resources associated with an idea that tests poorly means less
risk when funding new ideas. Companies can be much more fearless in
their innovation. The flexibility to preserve capital when needed is
critical in an uncertain economy.

#### New Factors Introduced by the Cloud**

New factors connected with returns on investment include:

**Better agility, faster time to market:** If your marketing department
used to take three months to launch an online campaign using in-house IT
and now takes a week, that’s a significant advantage. You’re getting
better ROI from your marketing team, because they produce more projects
in a given timeframe. On the other hand, how do you measure success of a
marketing campaign—does it have a direct revenue impact? Could other
lines of business benefit? Assigning a numerical value to this benefit
could help it become a more useful factor in making cloud-related
decisions.

**Gain green advantage:** The tremendous efficiency of the cloud’s
economies of scale, derived from meticulously organizing space and
services in shared data centers, means it takes less energy to run and
cool those data centers. Not only does this lower costs; it boosts the
credibility of your company’s green efforts.

At what price, innovation? One of the greatest advantages of moving to
the cloud is also the most difficult to quantify. What is the cost of
innovation? It’s much cheaper to experiment when you don’t have to make
a long-term commitment.

**Reduced dependence on IT:** Cloud computing means products can move
from a back-of-the-napkin sketch to the marketplace in far less time.
Because of the ease of assigning and moving assets to support new
endeavors, it also means that more people can create those
solutions—everyday business users can get to work right away,
provisioning and using computing assets as needed without the need for
IT intervention.

**Redesign business processes:** The revolutionary promise of cloud
computing is akin to that of every previous advance in computing. Huge
waves of productivity opened up when enterprises moved from mainframes
(a few of the “best and brightest” working on arcane calculations in an
isolated room) to desktop computing (everyone can contribute to
organizational value through computing). Cloud computing bursts the
hierarchical operating model once again. Now, you can deploy smart
people on innovation, not infrastructure. In a world where computing
power scarcity is no longer a critical limiting factor, the return on
your investment could extend far past savings for IT into redesigned
business processes that are only being imagined now.

### The Cloud as Business Transformer

The cloud enables a transformation of your organization and the way you
do business—not just computing power consumption. The benefits are
great, but so are the challenges. It is a fallacy to suggest that moving
to the cloud is as simple as transferring IT costs from one place to
another.

Most applications were built with the assumption that they would run on
traditional client/server architecture inside a corporate firewall. Some
applications may need to be radically altered in order to function in
the cloud, representing an initial cost that must be justified by
expected returns down the road.

Often, cloud computing instigates organizational change, not just IT
change. A review of organizational interdependencies and dynamics is
advisable before taking the plunge. Procurement and security protocols
may need to be reviewed and changed before proceeding. For example, in
the cloud, computing power can be purchased on a whim with a credit card
and may not be part of the purchasing workflow, unless policy is written
to accommodate this possibility. Departments can create their own
resources in the cloud without IT supervision. If your organization
transfers risk to a vendor with whom you do not have a master services
agreement, you could be placing terms of liability for sensitive data
back on your shoulders.

Cloud computing is one of several factors playing into the changing role
of the IT department. IT needs to take an active role in developing a
“service catalog” that includes in- and outsourced services, reflecting
the flexibility and reduced timescales that cloud computing enables.

In other words, the speed of the cloud must be matched by the speed of
your organization.

### Conclusion

Cloud computing can create significant return on investment, affording
energy, licensing, and administrative cost savings for many applications
enterprises run today, as well as providing the flexibility to invent
new applications. By leveraging economies of scale, it frees up capital
and personnel to innovate new ideas quickly, with limited financial
penalties. But moving to the cloud is not a decision to be made lightly,
or without a trusted advisor. As with any worthwhile investment, cloud
computing has an organizational impact that must be carefully
considered, not only for IT, but for the entire business. Moving to the
cloud is a transformational investment, in every sense of the word—but
it’s a move that many of today’s organizations find compelling.

*[CITO Research](http://www.citoresearch.com/)is a source of news,
analysis, research, and knowledge for CIOs, CTOs, and other IT and
business professionals. CITO Research engages in a dialogue with its
audience to capture technology trends that are harvested, analyzed, and
communicated in a sophisticated way to help practitioners solve
difficult business problems.*
