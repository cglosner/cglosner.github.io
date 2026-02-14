---
title: "FuzzUEr: UEFI Firmware Fuzzer"
excerpt: "A fuzzing framework for UEFI firmware interfaces on EDK-2, with firmware-adapted sanitizers, discovering 20 zero-day vulnerabilities. Published at NDSS 2025."
collection: portfolio
---

## FuzzUEr: Enabling Fuzzing of UEFI Interfaces on EDK-2

UEFI firmware remains difficult to analyze because of its atypical execution environment. FuzzUEr targets UEFI components and SMM communication paths, uncovering unsafe data flows and isolation flaws exploitable before the OS loads.

### Key Contributions
- Designed and implemented a fuzzing harness capable of testing UEFI protocol interfaces
- Adapted compiler-based sanitizers (e.g., AddressSanitizer) to UEFI by introducing firmware-compatible shadow memory and custom runtime support
- Discovered **20 zero-day security vulnerabilities** in the latest version of EDK-II
- Published at **NDSS 2025**

### Technologies
- C, QEMU, AFL++, EDK-II/UEFI, LLVM, AddressSanitizer

[[Paper]](/files/FuzzUEr__Enabling_Fuzzing_of_UEFI_Interfaces__on__EDK2.pdf)
