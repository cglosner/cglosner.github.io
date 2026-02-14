---
title: "Adding Spatial Memory Safety to EDK II through Checked C (Experience Paper)"
collection: publications
permalink: /publication/2025-06-24-checked-c-edk2
excerpt: 'This paper presents our experience adding spatial memory safety guarantees to the UEFI firmware reference implementation (EDK II) using Checked C, a backward-compatible extension of C with bounds-checked pointer types.'
date: 2025-06-24
venue: 'ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2025)'
paperurl: 'https://cglosner.github.io/files/Converting_EDK_II_to_Checked_C_with_3C.pdf'
citation: 'Sourag Cherupattamoolayil, Arunkumar Bhattar, Connor Glosner, Aravind Machiry. &quot;Adding Spatial Memory Safety to EDK II through Checked C (Experience Paper).&quot; <i>ISSTA 2025</i>.'
---

We extended 3C — an automated Checked C conversion tool — to operate within UEFI's freestanding environment. This required redesigning bounds models, annotations, and runtime assumptions so that type-safe code could compile and execute within firmware constraints. The results show that strong, automated memory-safety guarantees are achievable even in early-boot software.

[Download paper](/files/Converting_EDK_II_to_Checked_C_with_3C.pdf)