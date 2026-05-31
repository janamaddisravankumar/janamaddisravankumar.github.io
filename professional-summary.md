---
layout: default
title: Professional Summary
permalink: /professional-summary/
---

[🏠 Home](/) | [💼 Professional Summary](/professional-summary/) | [📚 Reading](/reading/) | [📝 Publications](/publications/)

# Professional Summary

{{ site.description }}

---

## Technical Expertise

{% for skill in site.skills %}
### {{ skill.category }}
{{ skill.items }}
{% endfor %}

---

## Professional Experience

### **MathWorks** | Principal Engineer / Team Lead
*Hyderabad, India (2019 - Present)*  
* Responsible for efficient and optimized code deployments to various cores/backends of the Qualcomm chipset using MATLAB/Simulink tools.
* Responsible for audio algorithms deployment to Qualcomm Hexagon DSPs using MATLAB/Simulink.
* Gained immense knowledge on Deep Learning deployment workflows to Qualcomm NPUs.
* Authoring CRLs and optimizing DSP blocks and math functions to various commercially available targets.
* Leveraging Model-Based Design (MBD) for optimal code generation workflows.
* Drove simulation infrastructure and speed enhancements for the 'DSP System Toolbox' using AVX2-SIMD, Halide Programming, and C/C++.

### **PathPartner Technology** | Senior Software Engineer
*Bengaluru, India (2014 - 2019)*  
* Integrated, ported, and deployed Dolby (TrueHD, MAT, DAP) decoders and managed Dolby's commercial certification on Qualcomm audio DSPs.
* Optimized multi-channel fixed-point compliance for AAC decoders to meet ISO standards.
* Designed, developed, and ported core audio pre/post-processing modules (AEC, Noise Cancellation, VAD, AGC, Beam-forming) onto Analog Devices SHARC processors.

---

## Education

* **M.S. in Computer Science** – The University of Texas at Austin
* **B.Tech. in Electrical, Electronics and Communications Engineering** – Vellore Institute of Technology
