# PACT
## Abstract

<div align="justify">There is a growing need for low-cost or no-cost monitoring and tracking systems in applications such as Smarter Food and Drug Safety. While backscatter-based communication offers the promise of battery-less tags, it does so at the cost of reduced communication range. In this work, we propose PACT - a scalable communication system that leverages the knowledge asymmetry in the network to improve the communication range of the tags. PACT Tags are battery-less and uses an active radio to communicate over long distances; the Tags operate only on the energy harvested from the PACT Source. A wide-band Reader receives multiple Tag responses concurrently and uploads them to a cloud server, enabling real-time monitoring and tracking. We identify and address the challenges in the practical design of battery-less PACT Tags with active radio and prototype them using off-the-shelf components. We show experimentally that our Tag consumes only 23 muJ energy, which is harvested from an excitation Source that is up to 24 meters away from the Tag. We show that in outdoor deployments, the responses from an estimated 520 Tags can be received by a Reader concurrently while being 400 meters away from the Tags.

## System Design

![PACT Framework](Figures/Block_Diagram_3.jpg)
