---
layout: post
title: "Reasons for and against ProgPoW on Ethereum"
date: 2019-09-18
categories: research
permalink: /:categories/:title.html
---

These are not my views but a summary of other points I have heard made in the community about the benefits and disadvantages of ProgPoW for Ethereum.

Note that the positives for ProgPoW are more clearly defined- and so are more easily and succinctly enumerated. 
Whereas the negatives emphasize places where Ethereum will have a larger theoretical attack surface.
Point being, while the lists are not equal in size, I am not trying to imply that the cons outweigh the pros or vice-versa.

*Will update later to clean up the bullet points and add points I missed*

PROS
* Limits the benefits of specialized ASIC equipment over commodity GPUs
* Limits the ability of ASICs manufacturers to capture control of ethereum
* Stays in line with the Ethereum ethos that mining will be GPU based
* Keeps happy long-term ethereum miners who are primarily GPU
	* This is one of many Ethereum stakeholders, and theoretically they have been around for a long time and invested in Ethereum early

CONS
* Adds significant complexity to the software
	* Few people know how to evaluate the theory before the code
		* While there is no(/highly limited) reason to believe the creators are malicious, the complexity make it difficult to evaluate
	* Few people have the equipment necessary to properly test the code across hardware types
	* Goes against the Ethereum ethos of keeping things simple
* ASICs can still eventually be built for it
	* Because of the complexity, when it is built, only limited manufactures will have the understanding to built ASICs for such a complex algorithm
		* Effectively giving them a monopoly
	* 1.4x-2x is probably still enough (at equilibrium) to make all but the best GPU miners operations unprofitable
* Verification time (/required power) is increased (though capped) requiring more resources from resource limited nodes
* UNCLEAR that GPUs miners are decentralized anyway
	* From my personal contacts in the mining industry, GPU mining operations are monopolized by big organizations/companies. While there may be a minority percent of small miners (possibly mining at a loss) it is unclear at best what benefit the network gets from their existence when they don’t have a total weight great enough to make an impact during important moments (forks, signaling, etc.)
	* A single ASICs machine is easier to setup and run at close to market efficiency than the niche knowledge required to buy, assemble, and calibrate graphics cards
		* This means that the main economy of scale then is sole ability to negotiate power prices instead of also knowledge
* ProgPOW probably requires the greatest number of forks both to implement initially and also to maintain going forward
* Similarly, while the major work is already complete, maintaining and updating requires dev time. Taking focus away from other tasks
	* Each time new commodity graphics cards are released a hardfork may be required to adjust ProgPOW to limit favoring a certain type of holder
	* Putting more focus on PoW when PoS is planned in the future anyway
* Capture of ethereum mining hardware is still controlled by a few big graphics card manufacturers
* Switching to an ASIC friendly algorithm arguable stays closest to the Ethereum ethos of preventing mining centralization

