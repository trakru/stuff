---
layout: post
author: admin@bbh-llc.com
title:  "The definitive guide to 10MBps internet"
date:   2020-10-19 15:11:00 -0400
categories: ['epon', 'ftth', 'gpon']
tags: ['utilities', '5G', 'gigabit', 'internet', 'service providers']
excerpt_separator: <!--more-->
---
# The Definitive guide to providing 10GBps service and beyond
## Comparing next-gen PON (XGSPON vs 10G EPON)

The first step towards providing gigabit services starts with moving to a passive-optical network (PON).  Its architecture implements a point-to-multipoint topology (typically 1x32), in which a single optical fiber serves multiple endpoints (32) by using unpowered (passive) fiber optic splitters to divide the fiber bandwidth among multiple access points. Passive optical networks are often referred to as the "last mile" between an Internet service provider (ISP) and its customers.

<!--more-->

Two major standards groups (IEEE & ITU) have developed standards (EPON & GPON) based on which PON products are currently being produced & deployed. There's an intermediary bridging standard called RFoG (RF over Glass) which was developed by SCTE, though deployments for that never really took off in a major way. For most intents and purposes, if you were going to look at building a 10+ gigabit level of service, your options are limited to the next-gen variants of these standards (XGSPON & 10G EPON)

1. EPON > 10G EPON (10Gbps variant) comes from IEEE: traditionally Cable/Broadband industry controlled
2. GPON > XGSPON (10 Gbps variant) comes from ITU: traditionally Telco-oriented

# Technology comparison

Both technologies are broadly similar at the PON level:

1. Work on the same wavelength (~1500 nm)
2. Work on Dynamic bandwidth allocation architecture allowing for over-subscription for upstream traffic
3. Carry data packets in flows (LLID for EPON & GEM/XGEM for GPON/XGSPON)
4. Avoid the complexities involved in keeping electronic equipment operating outdoors

However - they have differences as well

1. Competing standards bodies with different stakeholders (IEEE & ITU)
2. EPON works with ethernet packets while as GPON targets multiple packet types (ATM, ethernet, etc.)
3. EPON uses Ethernet OAM whereas GPON uses multiple OAM types (OMCI, PLOAM & in-frame)
4. EPON provisioning via DPoE works in L3 & L4 whereas GPON management works on L2
5. Backwards compatibility is touted as a EPON/10G EPON feature while as GPON & 10Gare not expected to be so
6. Technically 10G EPON baudrate is marginally more than 10G GPON (10.3125Gb vs 9.9528Gb)
7. 10G EPON ONUs are designed/certified to be inter-operable with other vendor solutions (because of adherence to the IEEE standard) while as 10G GPON ONU's may or may not.

# What Does this mean - reading between the specs

While it is clear that both technologies would be great for high-speed transport with similar, if not identical feature-sets, 10G EPON does have a made-for-cable stamp to it vs the cross-industry straddling that 10G GPON has to do. If we throw in the standardized DPoE-based control which every operator providing DOCSIS services are using right now, the upgrade seems almost painless. It is also tempting to look in the future with potential 50-100 Gbps versions of both technologies where GPON seems to be going with 40G NGPON2 and a potential 100G version down the line whereas EPON is looking at NGEPON which is going to come in sizes such as 1x25G, 2x25G, 1x50G, 4x25G, 2x50G & 1x100G - seemingly providing more options to fit a provider's need. There's also the additional advantage with 10G EPON providing backwards compatibility (XFP port) and therefore being able to support both Turbo (2.5G) & 10G EPON on the same port. As a result, a provider can support 10/10, 10/1 & 2/1 ONUs simultaneously which makes for a slightly cheaper initial deployment and management of user growth at no extra expense.

Speaking specifically from a broadband provider perspective, 10G EPON does have an added advantage to existing DOCSIS cable operators with DPoE - allowing them to reuse existing deployment models as well as OSS/BSS systems as-is. 10g GPON services would obviously come with their own set of control plane & management applications, which necessitates some adjustments to existing workflows. This isn't inherently good or bad, its only a factor to consider from a resource allocation and availability standpoint. DPoE also has the added advantage that it is able to support symmetric business services on the same fiber as a residential deployment.

The third major factor to consider is the inter-operability of ONUs - this enforcement of interoperability by Cable Labs allows for a variety of combinations of OLT/ONU combinations in a true multi-vendor spectrum. The lack of enforcement for inter-operability in 10G GPON means that the service provider will have to be locked in with the vendor on all current & future needs.

# Let's talk prices

Unarguably, 10G GPON has a *significant* price advantage over comparative 10G EPON equipment. This includes headened electronics (OLTs, cards etc.) to Optical Network Units(ONUs/ONTs) that provide services to end customers in homes/businesses. For example, a brand new 10G GPON headend for 5000 subscribers can be setup for under $400,000 while as the equivalent 10G EPON setup would either breach or be much closer to the $500,000 mark. a barebones ONT with just a 10G EPON ONU with ethernet is atleast 20% higher in cost compared to its service equivalent 10G GPON ONU. Taken over the same 5000 subscribers, we could be looking at anywhere between $100,000 - $250,000 in subscriber costs depending on the final configuration chosen AND with inter-operability allowing us to pick and choose the cheapest possible options available. While DPoE is certainly a cost-benefit for the 10G EPON solution, the equivalent management software from the 10G GPON world would not be more than $10,000 in costs.
