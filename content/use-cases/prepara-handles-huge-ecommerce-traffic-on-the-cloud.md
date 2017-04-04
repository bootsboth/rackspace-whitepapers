---
permalink: prepara-handles-huge-ecommerce-traffic-on-the-cloud/
audit_date:
title: Prepara Handles Huge Ecommerce Traffic on the Cloud
type: whitepaper
created_date: '2012-09-28'
created_by: Laurel Wamsley
last_modified_date: '2017-03-31'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="http://www.prepara.com/">
   <img src="{% asset_path use-cases/prepara-handles-huge-ecommerce-traffic-on-the-cloud/prepara_logo_1.png %}" width="361" height="80" />
</a>

**BUSINESS:** Designing and manufacturing innovative kitchen gadgets

**CHALLENGES:** With one of their products about to be featured on a
popular TV show, the small company needed to prepare for huge traffic to
their ecommerce website

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Cloud Servers with a Managed
Operations](http://www.rackspace.com/cloud/managed_cloud/), [Cloud
Files](http://www.rackspace.com/cloud/cloud_hosting_products/files/)

**OUTCOME:** A flexible, affordable solution that allowed them to easily
handle 150,000 customers an hour

[**Click here to download the full case
study.**](http://c1776742.r42.cf0.rackcdn.com/downloads/pdfs/CaseStudy_Prepara.pdf)

### Customer Overview

Prepara is a designer and manufacturer of innovative kitchen utensils
and accessories. The company is helmed by two industrial designers, Dean
Chapman and Ed Kilduff, whose industrial design consulting firm, the
SoHo-based Pollen Design, was founded in 1997.

The company has 20 employees, and Prepara’s goods can be found in stores
including Williams Sonoma and Bed Bath & Beyond, as well as stores
throughout Europe.

To design and manage its website, Prepara calls on Sound-n-Vision, a
creative agency providing professional website design, search engine
optimization, and internet marketing. Sound-n-Vision has been a
Rackspace customer since 2002.

###  The Opportunity: Big Exposure, Huge Traffic

In November 2010, Prepara found out that one of their products, the Herb
Savor, was going to be featured on a popular national television
program. The show’s producers warned Ed Kilduff, co-founder of Prepara,
that in order to be featured on the program, they needed to be ready to
handle huge demand. Prepara would need to have a lot of stock on hand,
and their website would need to withstand a serious spike in traffic —
as many as a few million hits in the first 24 hours.

At the time, Prepara was hosted on Rackspace dedicated servers, along
with Sound-n-Vision’s other clients. Prepara’s footprint was small: they
used only a single server with minimal RAM. Kilduff called Marc Ensign,
CEO at Sound-n-Vision, and asked if his team could help prepare them for
this big opportunity, only two weeks away.

The opportunity demanded the scalability of the cloud, but Prepara also
needed managed operations. Sound-n-Vision has a team of developers, but
outsourcing their IT hosting to Rackspace lets them focus on the
agency’s projects, not on managing servers. Prepara’s high-profile
exposure would require hands-on monitoring and rapid response.

Ensign reached out to Rackspace about a dedicated solution for Prepara.
But the cost of enough dedicated servers to handle the projected traffic
was unreasonable for a one-time event. “That just wasn’t an option,”
says Ensign.

Fortunately for Prepara, Rackspace was just launching the pilot program
of Cloud Servers with Managed Operations. “Paul Sims at the Rackspace
Cloud reached out to me, and he said, ‘We can build this in a cloud
environment, and we’ll manage the servers for you,’ ” says Ensign. “The
Cloud option was much more in line with our budget, and it was totally
scalable — a perfect fit.”

### The Solution: Cloud Servers, Cloud Files, and an External Payment Gateway

Prepara had a short timeframe to get ready, and within 12 hours,
Rackspace engineers had Prepara’s servers set up on Rackspace Cloud
Servers with Managed Operations, ready for whatever traffic the Herb
Savor’s television stardom would bring their way.

Ryan Walker was one of the Rackspace engineers who helped set up
Prepara’s configuration. “Prepara used seven 2GB CentOS Cloud Servers
for production,” says Walker. “They also used two Cloud Servers running
HAProxy for load balancing between the Web servers, and two database
servers with Master/Master replication.”

Prepara also used Cloud Files to serve static files and images from the
website, alleviating the load on the servers. To avoid issues with PCI
compliance, Prepara used an external payment gateway to handle their
credit card transactions. This meant that they handed off credit card
traffic to a third party, instead of having to process them on their own
servers.

“We also used a Varnish caching layer that was right in front of the
load balancers,” says Paul Sims, who was the lead tech working with the
Prepara account at Rackspace. “Varnish proxies the request and stores
them in RAM, so it will serve dynamic content that doesn’t need to be
generated every time. We also used Memcached for session persistence
across the Web servers. If we were doing this today, we’d also be able
to use Rackspace Cloud Load Balancers, instead of using HAProxy.”

### “It Went Off Without a Hitch”

Before the television appearance, Prepara’s products had been featured
in many magazines and newspapers, but as a growing company, they’d had
only moderate traffic to their website. All that changed the moment they
appeared on the television program. “We got 150,000 visitors within the
first hour of the program airing,” says Kilduff. The site consistently
handled 100,000-150,000 visitors at a time for four straight days after
the show aired.

Not only did the Cloud Servers handle the influx of new visitors to
Prepara’s site, but the Rackspace Cloud also made it possible for
Prepara to make all those sales. Indeed, Prepara sold out of their
entire stock of Herb Savors-including two shipping containers’ worth of
extra stock they had ordered — after the first airing of the show.

Ensign and the Rackspace team then spun down to four Cloud Servers once
the initial traffic burst leveled off. A month later, the show’s
producers called and said the episode was going to air again. Ensign had
the servers spun up again, and the site handled the second wave of
traffic without issue, just as it had the first time. “The whole thing
went off without a hitch,” said Kilduff. “It was a great experience for
us. I’d recommend the Rackspace Cloud to anyone.”

Ensign at Sound-n-Vision agreed. “It was an incredible experience,
working with Paul Sims and the whole team,” he says. “It could not have
gone better. Without the ability to spin servers up and down as we
needed them, and without the team at Rackspace, I can guarantee it would
have been a disaster.”

### A Great Solution for Ecommerce

For Ensign and Prepara, Cloud Servers were a perfect fit for a demanding
ecommerce problem. The opportunity to have their product featured on a
popular show called for scalability, flexibility, and utility-based
pricing that matched the amount of server space they needed.

“Managed cloud was an extremely cost-effective solution for us,” says
Ensign. “Dedicated servers would have been 20 times the cost of using
the Cloud. And we got an even better result than we would have on
dedicated, because it was scalable. We could have added another 30
servers if we needed them.”

For Ensign, it was an experience that he’s going to repeat. “We have
another client right now that we’re developing on the managed cloud,” he
explains. “They’re going to need a similar solution to Prepara — and I’m
glad to use the Rackspace Cloud again.”
