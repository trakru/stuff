---
layout: post
author: atrakru@bbh-llc.com
title:  "Connecting the dots on RDOF"
date:   2020-08-24 8:00:00 -0400
categories: ['5G', 'internet']
tag: ['municipal broadband', '5G', 'RDOF', 'internet', 'service providers', 'internetofthings']
excerpt_separator: <!--more-->
---

Read this [story on Medium](https://medium.com/@atrakru/connecting-the-dots-on-rdof-61dbb0091bcd)

<!--more-->
<figure>
  <img src="{{site.url}}/assets/img/blog/rdof-1.jpeg" alt="rdof"/>
  <figcaption>Photo by Jen Theodore on Unsplash</figcaption>
</figure>

### What it is

THE RDOF is FCC's [proposed answer](https://www.fcc.gov/implementing-rural-digital-opportunity-fund-rdof-auction) to the question of how to fund the development & deployment of broadband networks in rural America. Overall, the aim is to raise around $20.4Bn over 10 years via auctions to connect homes to a minimum of 25/3 Mbps (downstream speed/upstream speed).

#### Proposed Speed tiers

| Tier      | Downstream/Upstream Mbps | Usage Allowance |
| :--- | :----: | :---|
| Minimum      | 25/3     | ≥ 250 GB or U.S. average|
| Baseline   | 50/10        |   ≥ 250 GB or U.S. average|
| Above Baseline   | 100/20        |    ≥ 2 TB |
| gigabit  | 1000/500        |    ≥ 2 TB

In addition to performance tiers, the other key criteria that bears notice is the requirement for Latency

#### Proposed Latency tiers

| Latency | Requirement | Weight |
| :--- | :--- | :----: |
| Low Latency | ≤ 100 ms | 0 |
| High Latency | ≤ 750 ms & MOS ≥ 4 | 40 |

While this may not seem significant, these latency tiers have played a crucial part in excluding some providers, as discussed in later sections

### Other programs

RDOF is not the only program that the federal government is funding - agencies such as USDA Rural Utilities Service (RUS) are supposed to provide infrastructure improvements to rural communities. [ReConnect](https://www.rd.usda.gov/page/telecom-programs) is a $1Bn+ fund that would provide broadband speeds of 25Mbps whereas the [Electric Loan Program](https://www.rd.usda.gov/page/electric-programs) for Smart Grid/metering etc. is slated for ~ $5.5Bn/year.

In terms of scope and potential to dramatically improve internet access for all communities, the RDOF represents an incredible and unique opportunity. The central premise for the award dollars is that providers must offer  at least one voice and one broadband service meeting the relevant service requirements to ALL locations within the awarded area. As an example, here are the locations in Ohio (with reserve prices/county between $0–700,00)

<figure>
  <img src="{{site.url}}/assets/img/blog/ohio-rdof-904.png" alt="Ohio RDOF locations"/>
  <figcaption>Ohio RDOF Locations</figcaption>
</figure>

The recently concluded [Auction 904 procedures](https://www.fcc.gov/auction/904) signaled the start of this process - private entities who wished to participate in this buildout process had till July 31, 2020 to file an application.

<figure>
  <img src="{{site.url}}/assets/img/blog/rdof-timeline.png" alt="Timeline"/>
  <figcaption>RDOF Timeline View</figcaption>
</figure>

### Satellite Internet?

 One of the highlighted/much speculated areas for deploying high speed internet in rural areas has been [low-earth orbit satellites](https://en.wikipedia.org/wiki/Low_Earth_orbit) - recently in the news because of news about [Tesla's Starlink](https://www.starlink.com/) & [Amazon's Project Kuiper](https://blog.aboutamazon.com/company-news/amazon-receives-fcc-approval-for-project-kuiper-satellite-constellation) setting up LEO constellations in orbit. Even though FCC has specifically barred Starlink from participation in the RDOF process [pdf-here] (https://docs.fcc.gov/public/attachments/FCC-20-77A1.pdf), citing impossibility of going below 100ms latency with the technology at present, there's entities such as Telesat who claim 30-50ms on their systems - [pdf] (https://www.telesat.com/wp-content/uploads/2020/07/Real-Time-Latency-Rethinking-Remote-Networks.pdf)

At the speed of light (300,000 km/s), signals back & forth to any LEO satellite in orbit has a built in signal latency of 13ms  - the other adders of business logic (provisioning, load, interconnects etc.) are computational problems that will eventually be resolved. The FCC has taken a skeptical view of the whole thing working out, and hence most providers will not be able to use LEO technology as it exists at present in their RDOF deployments.

Regardless of whether we get internet from satellites or not, it is clear that 2020 is going to be a huge transition & access policy year that is going to shape internet access and how it is defined for the next 5-6 years. The public eye should be turned on this.
