---
layout: page
title: ADMS
description: Archived Data Management System
img: 
importance: 4
category: current
---

ADMSv2, short for Arhived Data Management System v2, is an end-to-end data-driven system that enables real-time and historical data analytics and machine learning tasks over big, streaming, spatiotemporal data. 
ADMSv2 employs a unified multi-layered architecture that integrates several open-source frameworks to collect, store, manage, and analyze a variety of data sources, including massive traffic sensor data, bus trajectory data, transportation network data, and traffic incidents data. 
ADMSv2 enables numerous applications in intelligent transportation, urban planning, public policy, and emergency response, all of which are critical for city resilience. 

The system has been collecting data from the Los Angeles County transportation network since 2011. This dataset includes:

- Inductive-Loop Traffic Detectors: 16,000+ sensors located on the highways and arterial streets of Los Angeles County (covering 5,400 miles, cumulatively) sensing occupancy, volume, and speed at the rate of 1 reading/sensor/min.

- Ramp meter: 1,800+ ramp meters that regulate the flow of traffic entering into highways according to current traffic conditions.

- Bus: 2,000+ buses operating on 145 different routes in Los Angeles County, with sensors recording the geospatial location of each bus every 1-5 minutes, next-stop information relative to current location, and delay information relative to predefined time-tables.

- Event: event data includes detail free-text format information (e.g., severity, street information, and the number of casualties) about events such as collisions and traffic hazards.

All these data contribute to a cumulative annual growth of 1.5TB.

{% include figure.html path="assets/img/adms_architecture.jpg" title="ADMSv2 Architecture" class="img-fluid rounded z-depth-1" width="75%" %}
