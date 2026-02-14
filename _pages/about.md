---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in the [School of Electrical and Computer Engineering](https://engineering.purdue.edu/ECE) at [Purdue University](https://www.purdue.edu/), advised by [Prof. Aravind Machiry](https://machiry.github.io/). I am a member of the [PurS3 Lab](https://purs3lab.github.io/) (Purdue Systems and Software Security Lab).

Modern computer systems rely on a layered sequence of hardware and firmware components that execute long before any operating system appears. These early stages establish all subsequent security guarantees, yet remain some of the least protected parts of computer systems. My research focuses on **securing this hardware-firmware boundary** by studying how systems establish trust from the first instruction executed at power on. I combine systems security, firmware analysis, and hardware-software interface reasoning to uncover vulnerabilities and strengthen isolation across diverse device classes.

I pursue this through three directions:
1. **Boot-chain security** — studying how early boot components establish platform trust
2. **Analysis and vulnerability discovery tooling** — developing fuzzers, sanitizers, and verification methods for early-boot environments
3. **Improving firmware security** — building deployable mitigations such as compiler-backed defenses, hardened memory isolation, and safer hardware-software interfaces

[[Research Statement]](/files/Connor_Glosner_Research_Statement.pdf) | [[CV]](/files/Connor_Glosners_Resume.pdf)

## Recent News

- **Jan 2025:** Received 2025 NDSS Student Fellowship.
- **2025:** Our paper on *Adding Spatial Memory Safety to EDK II through Checked C* was accepted to **ISSTA 2025**.
- **Nov 2024:** Our paper *FuzzUEr* was accepted to **NDSS 2025**.
- **2025:** Paper on Bootloader and Boot-Chain Security (SoK) under review.

## Selected Publications

- **Connor Glosner**, Aravind Machiry. *FuzzUEr: Enabling Fuzzing of UEFI Interfaces on EDK-2.* **NDSS 2025**.  
  [[pdf]](/files/FuzzUEr__Enabling_Fuzzing_of_UEFI_Interfaces__on__EDK2.pdf)

- Sourag Cherupattamoolayil, Arunkumar Bhattar, **Connor Glosner**, Aravind Machiry. *Adding Spatial Memory Safety to EDK II through Checked C (Experience Paper).* **ISSTA 2025**.  
  [[pdf]](/files/Converting_EDK_II_to_Checked_C_with_3C.pdf)

## Research Interests

- Boot-Chain and Firmware Security (UEFI/EDK-II)
- Fuzzing and Vulnerability Detection
- Memory Safety and Compiler-Based Defenses
- Hardware-Software Interface Security
- Program Analysis
