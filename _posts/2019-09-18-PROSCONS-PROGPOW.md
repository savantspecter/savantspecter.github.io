---
layout: post
title: "Pros & Cons of ProgPOW on Ethereum"
date: 2019-09-18
categories: research
permalink: /:categories/:title.html
---

These are not my views but a summary of other points I have heard in the community about the benefits and disadvantages of ProgPOW for Ethereum.

Note that the positives for ProgPOW are more cleanly defined- and so are more easily and succinctly enumerated. 
Whereas, the negatives emphasize numerous places where Ethereum might have a larger theoretical attack surface.
Point being, while the lists are not equal in size, I am not trying to imply that the cons outweigh the pros or vice-versa.

*Will update later to clean up the bullet points and add points I missed*

PROS FOR PROGPOW
* Limits the benefits of specialized ASIC equipment over commodity GPUs
* Limits the ability of ASICs manufacturers to capture control of ethereum
* Stays in line with the Ethereum ethos that mining will be GPU based
* Keeps happy long-term ethereum miners who are primarily GPU
	* Miners are arguably one of many Ethereum stakeholders, and theoretically they have been around for a long time and invested in Ethereum early
* There were 2 arguably imperfect votes conducted- a miner's vote and a carbon (coin) vote. Both which supported moving to ProgPOW

CONS
* Adds significant complexity to the software
	* Few people have the skills/knowledge to evaluate the theory (and the risks) of the code
		* This complexity means the community has concerns about verifying the code and therefore is concerned about having to **trust** the developers
	* Few people have the equipment necessary to properly test the code on different mining hardware
	* Goes against the Ethereum ethos of keeping things simple
* ASICs can still eventually be built for it
	* It is theorized only the most technologically advanced manufacturers will have the understanding to build ASICs for such a complex algorithm
		* Effectively giving them a monopoly
	* 1.4x-2x is might still enough (at equilibrium) to make all but the best GPU miners' operations unprofitable
* Verification time (/required power) is increased requiring more resources from resource limited nodes
* It is unclear how decentralized GPUs miners are anyway
	* GPU mining operations are already monopolized by big organizations/companies. 
	* Hard to measure the existence and impact of small miners and if there is significant benefit to the community to keep them.
	* A single ASICs machine is much easier to setup and run efficiently than the niche knowledge required to buy, assemble, and calibrate graphics cards
		* Widespread ASICs limits the economies of scale of large operations mainly to their improved ability to negotiate power prices instead of also knowledge
* ProgPOW probably requires the greatest number of forks both to implement initially and also to maintain going forward
* Similarly, while the majority of the work is already complete, maintaining and updating requires dev time. Taking focus away from other tasks
	* Each time new commodity graphics cards are released a hardfork may be required to adjust ProgPOW to limit favoring a certain type of hardware holder
	* Putting more focus on PoW when PoS is planned in the future anyway
* Capture of ethereum mining hardware is still controlled by a few big graphics card manufacturers
* Some argue that switching to ASIC friendly algorithm arguably stays closest to the Ethereum ethos of preventing mining centralization
	* ASIC friendly hardware is easy to produce and so can be done by the greatest number of manufacturers.
* There may be IP and copyright issues without any Contribution License Agreements
* It has become a somewhat contentious issue and so could cause a network split

