---
permalink: rackspace-hybrid-cloud-helps-aftercollege-grow/
audit_date:
title: Rackspace Hybrid Cloud Helps AfterCollege Grow
type: whitepaper
created_date: '2013-08-27'
created_by: Rackspace Support
last_modified_date: '2017-03-31'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="https://www.aftercollege.com/">
   <img src="{% asset_path use-cases/rackspace-hybrid-cloud-helps-aftercollege-grow/aftercollege.png %}" width="282" height="131" />
</a>

**CUSTOMER’S BUSINESS:** AfterCollege is a job discovery service that enables
students and new grads to explore jobs and internships based on their field of
study.

**CHALLENGES:** AfterCollege’s datasets grew too large for their
dedicated servers, but not all workloads ran best in cloud.

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Rackspace<sup>&reg;</sup> Hybrid
Cloud](http://www.rackspace.com/cloud/hybrid/),
[RackConnect<sup>&reg;</sup>](http://www.rackspace.com/hosting_solutions/hybrid_hosting/rackconnect/),
[Managed
Hosting](http://www.rackspace.com/managed_hosting/dedicated_servers/),
[Cloud Servers](http://www.rackspace.com/cloud/servers/)

**BUSINESS OUTCOME:** AfterCollege can leverage the best of cloud
technology without needing to move applications whose resource
requirements make them better suited to dedicated servers.

### Job Discovery Simplified for Students and New Grads ackspace Hybrid Cloud Helps AfterCollege Grow

AfterCollege is a job discovery service that enables students and new
grads to skip the job search and explore jobs and internships based on
their field of study. The site helps half a million people per month and
features over 400,000 job and internship listings from over 25,000
employers.

The company has trusted Rackspace since 2006 and began using a [Hybrid
Cloud](http://www.rackspace.com/cloud/hybrid/) in 2010 to support its
growth. The combination of Hybrid Cloud and a continuous deployment
model has allowed AfterCollege to put off making multiple hires for IT
Operations by granting developers greater autonomy. It also allows them
to leverage the best of cloud technology without needing to move
applications whose resource requirements make them better suited to
dedicated servers.

### Adding Cloud

“We started hosting with Rackspace in 2006. Back then, it was just
[dedicated
services](http://www.rackspace.com/managed_hosting/dedicated_servers/),
just three servers,” says AfterCollege VP of engineering Steve Girolami.
“In 2010 we started using the
[cloud](http://www.rackspace.com/cloud/public), integrating it with our
existing dedicated configuration, largely for development activities.
Before then, we were doing a lot of development on our local
workstations, but our data sets got so big that it was really hard to
replicate things internally in the office.
[RackConnect](http://www.rackspace.com/hosting_solutions/hybrid_hosting/rackconnect/)
technology allowed us to push all of our staging and review and even
some production services into the hybrid cloud.” When the
second-generation, hybridenabling RackConnect was released in 2011,
AfterCollege moved its front-end web services into the cloud as well.
“We haven’t looked back since,” Girolami says. “All our front-end
services are there—we have a lot of Solr indexes and Mongo instances all
replicated in various [cloud
servers](http://www.rackspace.com/cloud/servers/). It’s very elastic,
and when we want to try something new, it’s pretty easy for the
developers to do that in a cloud server.”

### Empowering Developers

This ability has allowed the company to hold off on hiring IT staff by
empowering developers to take on projects and experiment autonomously.
Girolami says, “The nice thing about the hybrid configuration is that
all the developers have accounts and are on a relatively long leash to
do whatever they feel is necessary in production. It empowers them with
the freedom and responsibility they need to work through the product
backlog, and it unblocks any of the resourcing problems they might have
because there’s no procurement process. If there’s a computing resource
they need to do their job, they go get it.”

Because they don’t need permission to spin up a new server, developers
are free to try out new technologies in a low-risk way. “The other day,
one of the developers brought up using Redis possibly. In the past,
you’d have to have servers set up to try out Redis,” he says, “but with
hybrid, they can just spin up a Redis server to try it out. If they
don’t like the way it’s going, they can just delete the server. It only
takes a few hours, and there isn’t the hubbub of procuring a server,
monthly costs, any of that.”

The ability to delete servers that aren’t cooperating can also be an
alternative to troubleshooting, says Girolami. “During a routine
production release,” he recalls, “one of the application servers just
wasn’t taking the updates and we had to roll back. In a dedicated
environment, the protocol would’ve been to figure out why it wasn’t
releasing correctly on this one server because we’d need the one server
in production for the amount of traffic we have. In cloud, we just
deleted the server and created a new one off the gold image and released
again, and then everything released fine. It took about 10 minutes to
do.”

### The Best Of Both Worlds

While the cloud provides AfterCollege numerous benefits, they also
appreciate that their hybrid infrastructure has allowed them to keep
appropriate workloads on dedicated servers.

For example, says Girolami, “Our [MySQL
database](http://www.rackspace.com/cloud/sites/web-hosting/mysql/) layer
is masterslave on dedicated servers. Each server is 64-bit, 64 GB of
RAM, with 600GB of RAID storage on 15K fast drives and a 200GB SSD drive
for caching, swap, locking, et cetera. By running our MySQL databases on
a predictable, powerful physical environment, we attain less than 10ms
response times at our production database layer for all query types.”

“We also do all our own bulk mailing because all the mail we send to our
users is specific for that user,” he says. “It’s millions of messages a
month, and we do that on one of our dedicated servers. There are a
number of static IP addresses assigned to that server, and if you know
anything about bulk mailing, reputation matters a great deal. We can’t
move those IP addresses willy-nilly, so those services are locked in on
a dedicated machine as well.”

The ability to keep some workloads on dedicated also saves
AfterCollege’s staff from having to migrate ungainly legacy
applications. “We have one old legacy ColdFusion application that we
still need to use,” says Girolami. “The thing is a pain to configure,
and I don’t think anybody wants to spend their time moving it to a cloud
server, so it’s stuck on one of our original dedicated servers.
Nevertheless, it still needs to have access to a lot of the cloud
services, like the Solr index and the Mongo tables. The Rackspace Hybrid
Cloud makes that possible.”

### Trusted Advisors

Throughout its evolution, AfterCollege has relied on Rackspace for
expert advice. Girolami cites the recent example of a MySQL migration.
“That was a major migration from the old hardware to the new hardware
and I think it went beautifully,” he says. “I don’t think it could have
gone better. Aside from planning and setting it up from the beginning,
the MySQL DBAs at Rackspace pretty much took the lead and exceeded
expectations.”

Girolami found the advisory process easy. “They organically brought up
all the different migration pathways we could take and the different
hardware configurations,” he says. “There were pros and cons to each, so
there was no bias, and they certainly didn’t push any one specific
solution or one process on me. It felt really empowering to be able to
get all of the information so we could make decisions and keep moving
forward. From quote to production it was under 45 days. It was pretty
seamless.”

The company sees its hybrid configuration as a perfect fit. “Hybrid is
beautiful because we’re not under the gun to migrate everything,” he
says. “The parts of the application stack that are the most important
can go to cloud, but the things that we don’t think add a great deal of
business value, but nevertheless we still need to have running, stay on
dedicated. Not needing to drop dedicated and go straight to cloud
creates a really nice migration path for us.”
