---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. Candidate in Electrical and Computer Engineering** | Northeastern University, Boston, USA
  * *Expected 2026*
* **M.Tech. in Electronics & Communication Engineering**
* **B.Tech. in Electronics & Communication Engineering**

Work Experience
======
* **RF Filter Design Co-Op** | Skyworks Solutions Inc., California, USA
  * *July 2024 – Dec 2024*
  * Designed and validated bulk acoustic wave (BAW) and surface acoustic wave (SAW) filters for high-frequency RF front-end modules operating from 4–10 GHz, successfully achieving $S_{11} < -35\text{ dB}$ and insertion loss $< 2\text{ dB}$.
  * Developed integrated matching networks and low-noise amplifier (LNA)-filter co-design interfaces, yielding $>30\text{ dB}$ out-of-band isolation while maintaining strict system linearity across wideband frequencies.
  * Conducted comprehensive schematic, electromagnetic (EM), and post-layout parasitic simulations using Keysight ADS, Cadence Virtuoso, and Ansys HFSS, followed up by bench-level RF laboratory instrument characterization and silicon validation.

* **RF & Signaling Operations Engineer** | Indian Railways, Chennai, India
  * *Feb 2018 – Jan 2023*
  * Managed high-reliability RF signaling networks, telemetry data modules, and complex electromechanical interlocking systems for safety-critical transportation infrastructure.
  * Integrated long-range RF communication links, hardware data loggers, analog sensor interfaces, and track occupancy detection sub-systems for real-time network command and control.
  * Performed field-level system commissioning, real-time fault diagnostics, preventive maintenance scheduling, and reliability engineering operations on mission-critical electronics.

Skills
======
* **Integrated Circuit Design (IC Design):** Analog, RF, Mixed-Signal, and Photonics IC Design
* **Circuit Architectures:** RSSI circuits, Limiting Amplifiers, Current-Summing architectures, LDOs, BGRs, Charge Pumps, Power Converters, Op-Amps
* **Simulation & EDA Tools:** Cadence Virtuoso (including Monte Carlo mismatch validation), Keysight ADS, Ansys HFSS, SPICE frameworks, MATLAB
* **Testing & Laboratory Instrumentation:** Digital storage oscilloscopes, DC Power Supplies, Function Generators, Digital Multimeters (DMMs)

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
