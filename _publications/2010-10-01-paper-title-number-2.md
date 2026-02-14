---
title: "FuzzUEr: Enabling Fuzzing of UEFI Interfaces on EDK-2"
collection: publications
permalink: /publication/2025-02-24-fuzzuer
excerpt: 'FuzzUEr is a novel fuzzing framework for testing UEFI firmware interfaces on EDK-2, which discovered 20 zero-day security vulnerabilities in the latest version of EDK-II.'
date: 2025-02-24
venue: 'Network and Distributed System Security Symposium (NDSS 2025)'
paperurl: 'https://cglosner.github.io/files/FuzzUEr__Enabling_Fuzzing_of_UEFI_Interfaces__on__EDK2.pdf'
citation: 'Connor Glosner, Aravind Machiry. &quot;FuzzUEr: Enabling Fuzzing of UEFI Interfaces on EDK-2.&quot; <i>NDSS 2025</i>.'
---

FuzzUEr is a novel fuzzing framework designed to test UEFI firmware interfaces on EDK-2. UEFI firmware remains difficult to analyze because of its atypical execution environment. We developed fuzzers targeting UEFI components and SMM communication paths, uncovering unsafe data flows and isolation flaws exploitable before the OS loads. This work also adapted compiler-based sanitizers (e.g., AddressSanitizer) to UEFI by introducing firmware-compatible shadow memory and custom runtime support, enabling reliable detection of memory errors during development.

Our approach resulted in the discovery of **20 zero-day security vulnerabilities** in the latest version of EDK-II.

[Download paper](/files/FuzzUEr__Enabling_Fuzzing_of_UEFI_Interfaces__on__EDK2.pdf)