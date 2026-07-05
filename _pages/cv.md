---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. Candidate in Electrical and Computer Engineering**
  * *Northeastern University, Boston, MA, USA* | Expected Graduation: 2026
  * **Specialization:** Low-power Analog, RF, Mixed-Signal, and Photonics IC Design
* **M.Tech. in Electronics & Communication Engineering**
* **B.Tech. in Electronics & Communication Engineering**

---

Professional Experience
======
### **RF Filter Design Co-Op** | Skyworks Solutions Inc.
*California, USA* | *July 2024 – December 2024*
* **High-Frequency RF Module Design:** Spearheaded the architectural design and experimental validation of Bulk Acoustic Wave (BAW) and Surface Acoustic Wave (SAW) filters tailored for next-generation RF front-end modules operating in the **4–10 GHz** regime.
* **Performance Metrics:** Engineering achievements yielded optimized return loss parameters ($S_{11} < -35\text{ dB}$) alongside an insertion loss profiling of $< 2\text{ dB}$.
* **LNA-Filter Integration:** Successfully developed high-performance integrated matching networks and Low-Noise Amplifier (LNA)-filter co-design interfaces, implementing robust wideband linearity and achieving $>30\text{ dB}$ out-of-band isolation.
* **EDA & Validation Workflow:** Leveraged extensive schematic execution, Electromagnetic (EM) modeling, and post-layout parasitic extraction via Keysight ADS, Cadence Virtuoso, and Ansys HFSS, followed by chip-level silicon validation and bench-top RF instrument testing.

### **RF & Signaling Operations Engineer** | Indian Railways
*Chennai, India* | *February 2018 – January 2023*
* **Safety-Critical Networks:** Directed operations, safety enforcement, and system management for high-reliability RF signaling distribution infrastructure, telemetry data frameworks, and complex electromechanical station interlocking modules.
* **Hardware Integration:** Managed the real-time installation and structural maintenance of long-range wireless RF communication networks, electronic hardware data loggers, precision analog sensor loops, and track occupancy analytical sub-systems.
* **Diagnostics & Logistics:** Conducted field-level technical commissioning, safety audits, rapid real-time fault diagnostics, and preventive maintenance architectures on mission-critical electronic components.

---

Technical Skills
======
* **IC Design & Architectures:** Low-power Analog, RF, Mixed-Signal, and Photonics Integrated Circuit Design; RSSI circuits, Limiting Amplifiers, Current-Summing networks, LDOs, Bandgap References (BGR), Charge Pumps, Power Converters, High-Gain Op-Amps.
* **Simulation & Verification:** Cadence Virtuoso (including advanced 200-point Monte Carlo mismatch statistical validation), Keysight ADS, Ansys HFSS, SPICE, MATLAB, RTL2GDS design flows.
* **RF Lab Instrumentation:** Hands-on bench characterization utilizing Digital Storage Oscilloscopes, Vector Network Analyzers (VNAs), DC Power Supplies, High-Frequency Function Generators, and Digital Multimeters (DMMs).

---

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
---

Teaching Experience
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

Talks & Presentations
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
