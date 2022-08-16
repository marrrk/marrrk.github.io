---
name: Investigating LoRa for use in a Cattle Tracking and Monitoring System
tools: [C/C++, LoRa, Embedded System Design]
image: [/assets/images/time-of-arrival.png]
description: My final year Undergraduate research project undertaken during the thick end of the Covid-19 pandemic. It was a challenge but I thoroughly Enjoyed it!
---

## Abstract and Problem Description
Keeping track of cattle is an important aspect of farming. There are dangers of cattle being stolen or leaving farmlands while grazing. Existing measures to reduce such happening may be expensive or prove to be ineffective. Therefore, farmers have, for many years, been interested in electronic means, to track & monitor their livestock rather than relying on sleepy guards patrolling large vulnerable areas.

In this project, the objective was to prepare a comprehensive analysis of how a LoRa based system, using single central gateway, can be designed around providing a low-cost solution to the need for tracking cattle (in particular cows), in addition to other useful monitoring data that can be gleaned from such a sensor network. This was not planned to be limited to tracking cattle, and reducing stock theft; but to add additional benefits as well – such as the acquisition of sensory data, which can be fed into data science applications, and assist in the planning and management of cattle farming.

The specific challenges involved with animal tracking with networked nodes is in the localisation of the sensor nodes. The project used a Time of Arrival based scheme to calculate distance between two sensor nodes. This required accurate timings between the sensor nodes such that the time of flight can be adequately calculated. In order to achieve this, a synchronization protocol was implemented on both nodes.

## Deliverables
The project <a href="/assets/pdfs/EEE4022S_2020_POSTER_NJRMAR003_NJOROGE_MSN_WINBERG.pdf">poster</a>, video below and <a href="/assets/pdfs/EEE4022S_2020_FINAL_REPORT_NJRMAR003_NJOROGE_MSN_WINBERG.pdf">final report</a> represent the documentation of the work that was undertaken. This includes the design decisions, tests and final results.

<div>
 <iframe width="100%" height="500"
    src="https://www.youtube.com/embed/jrcmsLuAle8">
</iframe> 
</div>
