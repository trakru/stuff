---
layout: post
author: atrakru@bbh-llc.com
title:  "The last-minute guide to C-Band transition"
date:   2020-09-14 8:00:00 -0400
categories: ['5G', 'internet']
tag: ['broadband', '5G', 'C-Band', 'internet', 'service providers', 'internetofthings', 'C-Band']
excerpt_separator: <!--more-->
---

Read this [story on Medium](https://medium.com/@atrakru/the-last-minute-guide-to-c-band-transition-dca1c2845f9)

<!--more-->
<figure>
  <img src="{{site.url}}/assets/img/blog/cband.jpg" alt="cband"/>
  <figcaption>Photo by Ben Wicks on Unsplash</figcaption>
</figure>

<!---
<span>Photo by <a href="https://unsplash.com/@profwicks?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Ben Wicks</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
-->

### What it is

The FCC's deadline for C-Band Relocation Lump Sum payment is today (Sept 14) - basically operators who use this 500Mhz block of radio spectrum to distribute video content will be vacating it in order to enable 5G operations ([More here](https://www.bbh-llc.com/5g/internet/2020/08/24/Connecting-dots-RDOF.html)). Since the intersection between video content providers and 5G operators is vanishingly small, it makes sense to create new licenses rather than try to retrofit licensing terms.


### Interactive Map of all eligible Earthstations (Locations & Providers)
<!-- Copy and Paste Me -->
<div class="glitch-embed-wrap" style="height: 420px; width: 100%;">
  <iframe
    src="https://glitch.com/embed/#!/embed/endurable-elite-finch?path=index.html&previewSize=100&attributionHidden=true"
    title="Eligible ESS on Glitch"
    allow="encrypted-media"
    style="height: 100%; width: 100%; border: 0;">
  </iframe>
</div>


### FCC perspective
the C-band order gives service providers either of the two options as a result of having to vacate the spectrum:

1. Maintain satellite reception and receive reimbursement for the actual relocation costs incurred
2. Receive a _lump sum reimbursement for all of their incumbent earth stations_ and decide for themselves how to use that money to accommodate the C-Band repacking.  In this case, they are reimbursed _based on the average, estimated costs of relocating all of their incumbent earth stations_

The FCC is providing a choice between sticking to the existing design—where each headend has equipment capable of receiving C-Band transmissions—or using that same amount of money to perform upgrades (such as fiber)

#### Lumpsum Payout Categories

|Category |	Average Estimated payout |
| :--- | :---:|
|Receive-Only Earth Station (ES) Single-feed Antenna  | 	$8,948.00|
|Receive-Only ES Multi-feed Antenna | $16,997.00|
|Small Multi-beam (2-4 beams) ES Antenna|  $42,062.00|
|Large Multi-beam (5+ beams) ES Antenna| 	$51,840.00|
|Gateway ES Antenna| 	$20,854.00|
|Temporary Fixed ES Antenna (e.g. News trucks)| 	$3,060.00|
|MVPD Per Site Technology Upgrade Installation Lump Sum Payment| 	$47,598.00|

### Cable Providers' perspective
Organizations such as [ACA Connects](https://acaconnects.org/#countdown) have tried to appeal the order on the basis that FCC has not provided enough time to Cable Operators to viably look for sourcing/pricing in order to retain current levels of service with their customers. This includes the pricing for integrated receivers/decoders that are used to (as the name suggests) - receive & decode satellite signals and provide them to their customers as video services.

Cable Providers who opt for lumpsum payment could consolidate (collapse) their current headend with others and leverage fiber connectivity to make so-called regional "super-headends" that could potentially provide signal for existing services to a network of local providers. The key roadblock here being that Content Agreements tend to be really restrictive in terms of being able to carry signal over pre-identified geographical territories and the idea of the consolidated regional headend might not be allowed to operate.

The other option is to move to a IP-based service, which could replace the existing TV services with OTT or in-network offerings.

<figure>
  <img src="{{site.url}}/assets/img/blog/iptv.png" alt="iptv"/>
  <figcaption>IPTV Options for C-band order impacted operators</figcaption>
</figure>

Basically operators can either choose to:

1. Migrate existing network to IPTV via
    * Installing new hardware at headend
    * Use vendor-provided cloud services to stream to subscribers
2. Deploy vendor streaming IP services to end customers without any customization
    * Revenue –sharing via  Bounty Model (1-time payment/sub) or monthly/sub fee

In either scenarios, the settops/CPE that existing subscribers are using will have to be changed/modified - which represents another capital expenditure to support this activity.

### Jails & Churches are in it too...

If we try to look at the data provided by the FCC on the 16000+ stations that are eligible for this payment, the list is obviously dominated by Satellite Providers, Television/Radio stations and Multiple Service Operators (MSOs) (at around 70%). However, the single biggest block of licenses in this spectrum is held by _Corporation of the Presiding Bishop of The Church_ a.k. [Church of Latter Day Saints](www.lds.com) with nearly **21% share** (one in five) of antennas. Other Christian evangelical entities comprise another **2%** share.

Another non-intuitive entity with large licenses is the [Buford Satellite Systems](https://bufordsatellitesystems.com/) which is the nation's largest provider of Television services to Correctional Facilities (**2% share**), with around 330 antennas, which is similar to Comcast Corporation (**2% share**).


### Resources

[FCC Ruling](https://docs.fcc.gov/public/attachments/FCC-20-22A1.pdf)
