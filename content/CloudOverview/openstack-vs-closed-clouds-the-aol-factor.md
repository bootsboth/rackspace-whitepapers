---
permalink: openstack-vs-closed-clouds-the-aol-factor/
audit_date:
title: OpenStack vs. Closed Clouds  - The AOL Factor
type: whitepaper
created_date: '2012-07-23'
created_by: Rackspace Support
last_modified_date: '2012-09-12'
last_modified_by: Tom Hopkins
product: White Paper
product_url: white-paper
---

***By: Sean Patterson, Solutions Engineering Manager***

### Introduction

[Cloud computing](http://www.rackspace.com/cloud/what_is_cloud_computing/) is
here, and it’s real.  It is, as we hear more often these days, The
Future of Computing.  If you’re not yet leveraging cloud computing to
streamline IT operations, you soon will be, or you’ll be left behind by
your competition.

All of this, in the dizzyingly accelerated pace of IT evolution, is old
news.  The question facing most CIOs today is ***not “should I start
using cloud computing?” but rather “which cloud provider should I
choose?”***  There are now a number of public cloud providers to choose
from, and the list is growing quickly.  There are various criteria that
one might consider.  I urge you to consider two new criteria: history
and the future.

### I. History


First, history.  Let’s go back to the early 1990s and consider the
early days of the internet service provider, (ISP), industry.  There
were three notable players in the consumer mass-market: CompuServe,
Prodigy, and America Online (AOL).  All three began with similar dial-up
services, including email, games, forums, and proprietary “web-like”
pages.  By the mid-90s, due to superior innovation in development, and
focus on ease of use for non-geeks, AOL had handily surpassed its
competitors.  At the time, their myriad of refined features, consistent
and integrated interface, and tight integration of applications combined
to create, quite simply, the best and easiest online portal in the
world.  Even our parents could use AOL, and use it well!  AOL appeared
unstoppable, the clear and dominant market leader, with unparalleled
brand recognition.  Among consumers, the right choice among online
portals looked like a no-brainer: AOL.

However, AOL was utterly defenseless against the greatest threat to its
near-monopoly.  The enemy wasn’t another proprietary player like
CompuServe or Prodigy.  The many-headed monster that relegated AOL to
obscurity was the “open Internet”, initially accessed by tech-savvy
consumers via independent internet service providers (ISPs).  The first
sign that AOL recognized its precarious position came in 1993, before
most non-IT consumers even knew the word “Internet”.  AOL, however, knew
all about the Internet.  Although as the market leader they would not
deign to publically acknowledge their real competition, behind closed
doors they fully recognized that the open standards that drove so many
consumers to ISPs were a force to reckon with.  AOL’s first defensive
tactic was to
[add a USENET feature to their portfolio,](http://en.wikipedia.org/wiki/Eternal_September)
allowing AOL users to mingle with the open Internet and (hopefully) maintain
vendor lock-in, at least among less technical customers.  There soon followed a
parade of incremental incentives and “enhancements”, each one a
desperate attempt to prevent AOL’s inevitable decline at the hands of
open standards:

- A change in pricing, ending the hourly rate in favor of a monthly
flat rate of $19.95, a trend that culminated in the offer of $9.95 per
month for unlimited access
- A massive direct-marketing campaign consisting of millions of CDs
mailed to consumers’ homes
- Ever-increasing amounts of free online hours offered in the first
subscription month
- Free email accounts given to non-AOL users
- The purchase of NetScape and deployment of an integrated,
semi-standard, small browser within the AOL thick client
- The purchase of media behemoth Time Warner, which allowed  AOL’s
remaining customer base to access the portal’s services via
broadband

None of these tactics worked for long.  Consumers weren’t impressed
with the price concessions, and instead found greater value in the open
Internet as it evolved.  The incremental technical improvements were
equally uncompelling.  For example, the integrated web browser was hated
by users and developers alike.  AOL email didn’t play nice with other
email systems (remember the multiple levels of nested attachments for
each step in a long email thread?).  Ultimately, only a [sense of vendor
lock-in](http://en.wikipedia.org/wiki/Aol#Billing_disputes) kept many of
their remaining users on-board and the revenue flowing.  The vast
majority of AOL users, however, left AOL in favor of a standards-based
ISP and the open Internet.

### II. Future

Now, what about the future?  What does AOL’s history in the consumer
market have to do with cloud computing decisions today?  A lot.  In
fact, the parallels between the online portal/ISP market in the 1990s
and the cloud computing market today are unmistakable once one looks
past the hype and grasps the underlying realities.

As of early 2010, the cloud computing market was comprised of a number
of companies running proprietary, closed systems.  The value proposition
of each cloud provider varied widely, but there were a handful of
dominant players with varying levels of brand recognition who got the
bulk of the business, including: Amazon<sup>&reg;</sup>,
Rackspace<sup>&reg;</sup>, Microsoft<sup>&reg;</sup>, Google<sup>&reg;</sup>,
and a few others.  Among these, Amazon’s AWS product was the
market leader with a significant head start, with Rackspace next in
line, and the other major cloud providers trying to carve out as much
market share as they could get.  Driving its market lead, Amazon had a
myriad of refined, nicely-integrated cloud products, driven by an
innovative development machine and unparalleled brand recognition.

Does this sound familiar?  The similarities to the online portal/ISP
market of the 90s don’t stop there.  Enter Amazon’s real
competition: [OpenStack](http://www.openstack.org).  OpenStack is an
open-source cloud platform co-founded in 2010 by Rackspace Hosting and
NASA.  The goal is simple: to level the playing field by providing an
open standard for cloud computing systems to be built on.  Just like
earlier standards such as TCP/IP, HTTP, HTML, and many others, OpenStack
is freely available for anyone to deploy open clouds on.  Any
organization, including Rackspace’s competitors, can build a
massively-scalable cloud on the same technology used by Rackspace and
NASA.  OpenStack can be deployed by any company on-premise, or in a
collocation or managed hosting facility, and workloads can easily be
moved from one OpenStack platform to another.

Unsurprisingly, OpenStack is gaining support in a way eerily
reminiscent of the ascension of the open Internet of the 1990s.  As of
early 2011, the list of [OpenStack community
partners](http://www.openstack.org/community/) has grown to be quite
impressive, including such industry giants as Citrix, Intel, AMD, and
Dell.  On January 19, 2011, Internap became the first of Rackspace’s
competitors to announce that it will launch a cloud service on
OpenStack.  Even Microsoft is joining in, contributing code to enable
its Hyper-V virtualization platform to run in OpenStack clouds.

OpenStack will drive rapid development of standards-based cloud
technologies.  It will do this by enabling any software developer(s) in
the world to submit innovative new technologies to the project, just as
open standards of the past enabled developers to make the open Internet
what it is today.  The IT industry is beginning to recognize that open
standards will drive innovation and freedom in the cloud much more
effectively than closed, proprietary cloud platforms, and they’re
putting their money on OpenStack to be that standard.

Back to Amazon.  As the proprietary market leader, Amazon has had very
little to say in the public arena about OpenStack.  But make no mistake
about it: they know their dominant position is tenuous.  Since Rackspace
and NASA announced the OpenStack initiative, Amazon has lowered its
prices for AWS cloud services, even going so far as to announce a Free
Tier on June 30, 2010.  Again, one is reminded of AOL’s attempts to lock
in market share in their competition against open standards.  Over time
you can also expect Amazon and other proprietary cloud providers to
integrate limited OpenStack functionality into their platforms.  The
likely first concession will be the adoption of OpenStack application
programming interfaces, or APIs, which will attempt to allow their
customers to “play nice” with standards-based cloud systems.  The real
goal, of course, will be to cling to customers.  When the proprietary
cloud providers begin adopting select OpenStack technologies, you can be
sure that their end has begun, and more of AOL’s tactics are probably
soon to follow.

### Conclusions

So what does all this mean to a CIO faced with the decision of which
cloud provider to use today?  Simply put, it means that investing time
and resources in a closed, proprietary platform is a losing strategy.
In order for a company to deploy IT services into a particular cloud,
they have to conform to that cloud’s standards and technologies.  Time
and money must be spent, and the result will be a relationship with a
single provider they can’t easily leave.  However, a decision to deploy
in an OpenStack cloud will result in freedom, mobility, and ultimately
in superior technology.  IT history is repeating itself before our eyes,
and once again, open standards will prevail.

