---
layout: post
author: atrakru@bbh-llc.com
title:  "3 Easy Wins to ease upgrade to a next-gen gigabit network"
date:   2020-07-24 8:00:00 -0400
categories: ['gigabit internet', 'FTTH']
tag: ['municipal broadband', 'geojson', 'osp', 'internet', 'service providers']
excerpt_separator: <!--more-->
---
Read this [story on Medium](https://medium.com/@atrakru/3-easy-wins-to-ease-upgrade-to-a-next-gen-gigabit-network-2f66b71134c4)

<!--more-->

<figure>
  <img src="{{site.url}}/assets/img/blog/america.jpg" alt="Network"/>
  <figcaption>Photo by NASA on Unsplash</figcaption>
</figure>

# 3 Easy Wins for next-gen gigabit network upgrade

Today, there are more than 750 small-sized & municipal broadband networks in USA today providing broadband speeds ranging from 256kbps to 1Gbps to their subscribers.
In this [dataset](https://opendata.fcc.gov/Wireline/Fixed-Broadband-Deployment-Data-Jun-2019-Status-V1/sgz3-kiqt), it is interesting to note that even though 10Gbps+ [technology exists today](https://www.cablelabs.com/technologies/pon), no operator provides those service speeds. Why is that?

While the obvious answer may be cost (and perhaps that's a topic for a future post), the main obstacles to deploying next-gen fiber networks usually lie within the current infrastructure & related issues that
an operator might need to address before upgrading to a fiber network.

We want to take a look at some low-hanging fruit ($20-25k range) for providers that are considering doing the next-gen gigabit upgrade. Here are the 3 that we recommend:

### Easy Win 1: Check your Maps

OSP (Outside Plant) as-built maps provide operators with a view on how their network looks (poles, strands, cabinets etc.). Frequently, these are drawn by design firms on [Autocad](https://en.wikipedia.org/wiki/.dwg) and typically provided as pdfs or [Google Earth kmls](https://developers.google.com/kml/documentation/kml_tut). These maps are often terrible for vector analysis - they tend to have an unusably high number of layers (often 10,000+) as an artifact of creation (usually exported from DWG to KML). As a result, none of these [**terrific**](https://geopandas.org/) [open source](https://geojson.org/) [**libraries**](https://leafletjs.com/) are immediately helpful for data-based decisions

>To-Do: Spend $20-$25k to convert your design files to geojson now. Avoid paying $500k+ for FTTTH design later.


### Easy Win 2: Re-rack/stack/wire headend

Data Center planning technology has seen so many energy-efficient changes due to the explosion in cloud/data center needs (hello! [Amazon](https://aws.amazon.com/), [Azure](https://azure.microsoft.com/en-us/)). There's no reason why your headend should still be on a 2000s era layout.

>To-Do: Spend $20k to rewire the headend to take advantage of 'Hot/Cold' aisles. Try putting components on a raised floor, if they are not on one already. That way, the headend is prepped for some heavy duty PON equipmnent to move in

### Easy Win 3: Try moving away from dedicated Earth-station / installing a new Simulsat

This is a transition year - FCC is already asking operators to [vacate the 3.5-4.2 Ghz UHF spectrum](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/35-ghz-band/35-ghz-band-overview). There are significant developments in play, that *will* result in changes in the way terrestrial TV gets transmitted via local satellite stations. You might be pointing to a different pipe to get feeds from by 2022.

>To-Do: Sit tight and hold on to that earth-station maintenance/Simulsat upgrade budget!!

If we add the math, we've definitely saved up $750k+ through the course of this article. We will be publishing more articles in the same vein - and take a deep dive on some emergent trends that we believe will benefit smaller/municipal operators just as much as larger ones and allow them to serve their communities more efficiently.

Ultimately, we all benefit from access to faster broadband internet.