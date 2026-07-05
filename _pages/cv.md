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
  * **Research Specialization:** Low-power Analog, RF, Mixed-Signal, and Photonics IC Design
* **M.Tech. in Electronics & Communication Engineering** | Graduation Year: 2016
* **B.Tech. in Electronics & Communication Engineering** | Graduation Year: 2013

---

Core Technical Expertise
======
* **Featured IC Design Projects:** High-Dynamic-Range Received Signal Strength Indicator (RSSI) architectures, multi-stage Limiting Amplifiers, and precision Current-Summing logarithmic topologies tailored for low-power transceivers.
* **Power Management & Analog Blocks:** Low-Dropout Regulators (LDOs), Bandgap References (BGR), Charge Pumps, Power Converters, High-Gain Operational Amplifiers (Op-Amps), Differential Pairs, Current Mirrors, and Active/Passive Filters.
* **Photonics & Advanced Interfaces:** Integrated Optical/Photonics Interfaces and electro-optical co-design.
* **Simulation-to-Lab Silicon Validation:** Advanced expertise in translating theoretical design to silicon reality through robust schematic capture, physical layout implementation, pre-/post-layout parasitic extraction validation, complex on-chip statistical validation (including 200-point Monte Carlo mismatch verification), and final bench-level chip characterization.
* **EDA Software & Tools:** Cadence Virtuoso Suite, Keysight Advanced Design System (ADS), Ansys HFSS, COMSOL Multiphysics, Synopsys RTL2GDS Digital Flow, SPICE Simulation Engines, and MATLAB numerical computing environments.
* **RF Lab Instrumentation:** Benchtop testing using Vector Network Analyzers (VNAs), Digital Storage Oscilloscopes, DC Power Supplies, High-Frequency Function Generators, and Digital Multimeters (DMMs).

---

Professional Experience
======
### **RF Filter Design Co-Op** | Skyworks Solutions Inc.
*California, USA* | *July 2024 – December 2024*
* **High-Frequency Filter Synthesis:** Spearheaded the architectural design, EM modeling, and physical validation of Bulk Acoustic Wave (BAW) and Surface Acoustic Wave (SAW) filters tailored for next-generation RF front-end modules operating across the **4–10 GHz** regime.
* **Performance Metrics:** Achieved state-of-the-art return loss optimization ($S_{11} < -35\text{ dB}$) alongside an insertion loss profiling of $< 2\text{ dB}$ across active bands.
* **Co-Design Interfaces:** Developed integrated matching networks and Low-Noise Amplifier (LNA)-filter co-design topologies, implementing strict wideband linearity constraints and achieving $>30\text{ dB}$ out-of-band isolation.
* **Verification Workflow:** Managed complete schematic engineering, multi-layer electromagnetic (EM) modeling, and post-layout parasitic extraction in Keysight ADS, Cadence Virtuoso, and Ansys HFSS, correlating simulation models with on-chip silicon bench testing.

### **RF & Signaling Operations Engineer** | Indian Railways
*Chennai, India* | *February 2018 – January 2023*
* **Critical Infrastructure Systems:** Monitored and optimized mission-critical, high-reliability RF signaling distribution networks, telemetry data links, and complex electromechanical interlocking platforms.
* **Hardware Integration:** Managed the deployment, testing, and field maintenance of long-range wireless RF links, multi-channel hardware data loggers, analog sensor loops, and track-level sub-systems.
* **Diagnostics & Logistics:** Performed field-level technical commissioning, strict safety audits, real-time rapid troubleshooting, and preventive maintenance scheduling on critical signaling components.

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
