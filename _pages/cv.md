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

Core Technical Expertise & Circuit Blocks
======
* **RF & Microwave Front-End Architectures:** Low-Noise Amplifiers (LNAs), Power Amplifiers (PAs), Active/Passive Mixers, Gilbert Cell Multipliers, Voltage-Controlled Oscillators (VCOs), Ring Oscillators, LC Tank Cavities, Injection-Locked Oscillators, Phase Shifters, Attenuators, High-Frequency RF Filters (BAW/SAW), RF Front-End Modules (FEM), and Wideband Impedance Matching Networks.
* **Analog Core Blocks & Circuits:** High-Gain Operational Amplifiers (Op-Amps) with advanced frequency compensation networks, Operational Transconductance Amplifiers (OTAs), Instrumentation Amplifiers, Differential Pairs, Active/Passive Filters, Programmable Gain Amplifiers (PGAs), Variable Gain Amplifiers (VGAs), Precision Current Mirrors, and Stable Voltage References.
* **Mixed-Signal & Data Conversion Blocks:** High-Speed Latching Comparators, Dynamic Latches, Sample-and-Hold (S/H) circuits, Track-and-Hold (T/H) amplifiers, Analog-to-Digital Converters (ADCs: SAR, Sigma-Delta, Pipelined, Flash), and Digital-to-Analog Converters (DACs: Current-Steering, R-2R).
* **Clock Generation & PLL Systems:** Phase-Locked Loops (PLLs), Charge Pumps, Phase-Frequency Detectors (PFD), Frequency Dividers/Prescalers, Loop Filters, Clock and Data Recovery (CDR) architectures, and High-Speed Clock Distribution Networks.
* **Power Management IC (PMIC) Blocks:** Low-Dropout Regulators (LDOs), Bandgap References (BGR) with startup mechanics, Charge Pumps, Buck/Boost Switching Power Converters, Voltage Clamps, and Rectifiers.
* **High-Speed Serial Links & Signaling:** SerDes (Serializer/Deserializer) architectures, Equalizers (CTLE, DFE, FFE), High-Speed Transmitter Drivers, Optical Modulator Drivers, Transimpedance Amplifiers (TIAs), and Integrated Optical/Photonics Interconnects.
* **Simulation-to-Lab Silicon Validation:** Advanced expertise translating complex transistor-level schematics into verified physical layouts, performing pre- and post-layout parasitic extraction validation, executing complex on-chip statistical validation (200-point Monte Carlo mismatch verification), and conducting final bench-level chip characterization.
* **EDA Software & Tools:** Cadence Virtuoso Suite, Keysight Advanced Design System (ADS), Ansys HFSS, COMSOL Multiphysics, Synopsys RTL2GDS Digital Flow, SPICE Simulation Engines, and MATLAB numerical computing environments.
* **RF Lab Instrumentation:** Benchtop testing using Vector Network Analyzers (VNAs), Digital Storage Oscilloscopes, DC Power Supplies, High-Frequency Function Generators, and Digital Multimeters (DMMs).

---

Sponsored Research Projects (DARPA/NSF Grant)
======
* **Energy-Detection RF Architectures** | *June 2025 – Present*
  * Designing energy detection-based radio frequency (RF) circuits tailored for ultra-low power operation and enhanced hardware security of next-generation IoT devices.
* **Energy-Efficient PLL-Based Frequency Synthesizer** | *October 2024 – June 2025*
  * Developed energy-efficient Phase-Locked Loop (PLL)-based frequency synthesizers optimized for distributed beamforming networks and next-generation wireless communications systems.
* **Protecting Analog and Mixed-Signal Circuits Using Switch-Mode Time-Domain Locking** | *May 2023 – March 2024*
  * Researched and developed advanced methodologies for safeguarding sensitive analog and mixed-signal integrated circuits using custom switch-mode time-domain locking state frameworks.
* **Sub-microwatt RF Energy Harvesting Integrated Circuit** | *January 2023 – November 2023*
  * Built ultra-low power sub-microwatt RF energy harvesting integrated circuits featuring high-efficiency rectifiers and intelligent power management architectures for battery-free IoT nodes and biomedical implant applications.

---

Silicon Design & Academic Projects
======
* **45nm CMOS Bandgap Reference (BGR):** Modeled and designed a precision 45nm CMOS bandgap reference circuit achieving a highly stable temperature drift profile of less than 1 mV/°C for high-accuracy on-chip biasing networks.
* **65nm CMOS Low-Dropout (LDO) Regulator:** Implemented a 65nm CMOS LDO regulator achieving 100 mV load regulation and a rapid sub-5 microsecond transient recovery response across a variable 1–50 mA load envelope.
* **9-bit Differential SAR ADC:** Fabricated and designed a 9-bit differential charge-redistribution Successive Approximation Register (SAR) Analog-to-Digital Converter in TSMC 65nm technology, achieving 50.5 dB SNDR and 59.5 dB SFDR at an ultra-low power consumption of 233 microwatts under a 1 V supply.
* **Logarithmic RSSI Transceiver Chain:** Configured a high-dynamic-range Received Signal Strength Indicator (RSSI) current-summing architecture coupled with multi-stage limiting amplifiers for integrated spectrum sensor blocks.

---

Professional Experience
======
### **RF Filter Design Co-Op** | Skyworks Solutions Inc.
*California, USA* | *July 2024 – December 2024*
* **High-Frequency Filter Synthesis:** Spearheaded the architectural design, EM modeling, and physical validation of Bulk Acoustic Wave (BAW) and Surface Acoustic Wave (SAW) filters tailored for next-generation RF front-end modules operating across the **4–10 GHz** regime.
* **Performance Metrics:** Achieved state-of-the-art return loss optimization (**S11 < -35 dB**) alongside an insertion loss profiling of **< 2 dB** across active bands.
* **Co-Design Interfaces:** Developed integrated matching networks and Low-Noise Amplifier (LNA)-filter co-design topologies, implementing strict wideband linearity constraints and achieving **> 30 dB** out-of-band isolation.
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
