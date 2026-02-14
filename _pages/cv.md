---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[[Download CV (PDF)]](/files/Connor_Glosners_Resume.pdf) | [[Research Statement]](/files/Connor_Glosner_Research_Statement.pdf)

Education
======
* **Ph.D. in Electrical and Computer Engineering**, Purdue University, 2022 – 2027 (expected)
  * Advisor: [Prof. Aravind Machiry](https://machiry.github.io/)
  * Lab: [PurS3 Lab](https://purs3lab.github.io/) (Purdue Systems and Software Security Lab)
  * Focus: Systems Security, Firmware Security, Vulnerability Detection

* **B.E. in Computer and Systems Engineering**, Rensselaer Polytechnic Institute, 2018 – 2022

Research Experience
======
* **Graduate Research Assistant**, PurS3 Lab, Purdue University (2022 – Present)
  * Developed FuzzUEr, a novel fuzzing framework for UEFI firmware interfaces on EDK-II, discovering 20 zero-day security vulnerabilities
  * Extended 3C (automated Checked C conversion tool) to operate within UEFI's freestanding environment, enabling automated memory-safety guarantees for firmware
  * Adapted compiler-based sanitizers (e.g., AddressSanitizer) to UEFI by introducing firmware-compatible shadow memory and custom runtime support
  * Contributing to kernel CVE analysis research for Linux and Android kernel exploitation

* **Researcher**, Rensselaer Polytechnic Institute (Fall 2019 – Spring 2020)
  * Implemented machine learning in power grid systems to optimize load distribution during oscillation or source failure

Industry Experience
======
* **Systems Engineering Intern**, Northrop Grumman (Summer 2024 – 2025, Remote)
  * Worked on full spectrum systems security

* **Systems Engineering Intern**, Northrop Grumman (Summer 2022 – 2023, Cincinnati, OH)
  * Worked on full spectrum systems security

* **Systems Engineering Intern**, Northrop Grumman (Summer 2021, Remote)
  * Applied machine learning techniques using acoustic data for oyster reef identification

* **Systems Engineering Intern**, Northrop Grumman (Summer 2020, Remote)
  * Researched vehicle-to-everything (V2X) communication systems and identified vulnerabilities

* **Software Developer**, Near Field Magnetics Inc. (Summer 2020, Remote)
  * Developed an application to configure sensors for wireless networks
  * Implemented synchronization of sensors for data transmission and real-time display

* **Systems Engineering Intern**, Northrop Grumman (Summer 2019, Baltimore, MD)
  * Performed modeling and simulation on ground radars
  * Developed computer vision software with machine learning

Skills
======
* **Programming Languages:** C, C++, Python, Rust, MATLAB
* **Security Tools:** AFL++, Syzkaller, kAFL, Ghidra, Radare2, QEMU, AddressSanitizer
* **Systems & Platforms:** UEFI/EDK-II, Linux Kernel, Android, Bootloaders, Firmware
* **Techniques:** Fuzzing, Program Analysis, Reverse Engineering, Memory Safety, Compiler Instrumentation
* **Infrastructure:** LLVM, GCC, Git, Docker

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Awards & Fellowships
======
* NDSS Student Fellowship, 2025

Projects
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service
======
* Member, PurS3 Lab weekly reading group on computer security topics
