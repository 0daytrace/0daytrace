<div align="center">

<!-- Animated terminal header -->
<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=0daytrace+%40+null;Independent+Security+Researcher;Memory+Corruption+%7C+Firmware+%7C+Embedded;Responsible+Disclosure+%7C+CVE+Author;CVSS+10.0+%E2%80%94+RCE+chain+confirmed" alt="Typing SVG" />

<br/>

<!-- Divider -->
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

</div>

```
┌─────────────────────────────────────────────────────────────────┐
│  whoami                                                         │
│  > Independent vulnerability researcher · Pakistan             │
│  > Specialization: Memory corruption · Firmware · Embedded      │
│  > Disclosure model: 90-day responsible · CVE author           │
│  > Status: Open to consulting · Research collaboration          │
└─────────────────────────────────────────────────────────────────┘
```

<div align="center">

## `0x00` — Threat Model

</div>

I hunt bugs at the intersection of **C/C++ memory safety**, **embedded firmware**, and **RTOS attack surfaces** — the layer most researchers skip. My work targets real-world impact: RCE chains, privilege escalation, and trust boundary violations in hardware-adjacent code.

- **Core specialties:** Heap/stack corruption · Integer overflows · Path traversal chains · Firmware reverse engineering · Vulnerability chaining
- **Target surfaces:** Embedded Linux · RTOS (RT-Thread, Zephyr, FreeRTOS) · IoT firmware · Native libraries · SDK attack surfaces
- **Methodology:** Static + dynamic analysis · PoC-first · Coordinated disclosure with full write-up

---

<div align="center">

## `0x01` — CVE Portfolio

</div>

| Advisory | Target | Class | CVSS | Status |
|---|---|---|---|---|
| [GHSA-pv8c-p6jf-3fpp](https://github.com/advisories/GHSA-pv8c-p6jf-3fpp) | sipeed/picoclaw | **RCE Chain** (23 findings) | **10.0 Critical** | ✅ Patched · May 2026 |
| INTEL-1NV2EPZP | Intel linux-sgx SDK | Integer Overflow | — | Disclosed |
| INTEL-EQF6ERMM | Intel cve-bin-tool | Path Traversal Bypass | — | Disclosed |
| MSRC-101655 | Microsoft | Under Embargo | — | 🔒 Active |
| MSRC-101664 | Microsoft | Under Embargo | — | 🔒 Active |
| MSRC-107435 | Microsoft | Under Embargo | — | 🔒 Active |

> *All disclosures follow 90-day coordinated timelines aligned with Google Project Zero standards.*

---

<div align="center">

## `0x02` — Active Research

</div>

```python
current_targets = [
    "Embedded RTOS surfaces (RT-Thread · Zephyr · FreeRTOS)",
    "Native library heap internals (LevelDB · RocksDB · SQLite)",
    "Firmware supply chain integrity",
    "SDK / toolchain attack surfaces",
]

programs = ["Google OSS VRP", "MSRC", "Intel/Intigriti", "ZDI (pipeline)"]
```

---

<div align="center">

## `0x03` — Stack

</div>

<div align="center">

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/ASM-525252?style=flat-square&logo=assemblyscript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

![GDB](https://img.shields.io/badge/GDB-FF6600?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square)
![Binwalk](https://img.shields.io/badge/Binwalk-222222?style=flat-square)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=flat-square&logo=qemu&logoColor=white)
![AddressSanitizer](https://img.shields.io/badge/ASan-black?style=flat-square)
![Valgrind](https://img.shields.io/badge/Valgrind-444444?style=flat-square)

</div>

---

<div align="center">

## `0x04` — Stats

</div>

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=0daytrace&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0daytrace&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&langs_count=6" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=0daytrace&theme=chartreuse-dark&hide_border=true&background=0d1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41" />
</div>

---

<div align="center">

## `0x05` — Principles

</div>

```
[!] No PoC, no report.
[!] Vendor silence past 90 days triggers coordinated public disclosure.
[!] Severity is what the attacker can do — not what the vendor wants to hear.
[!] The best bug report is one the engineer can act on in 10 minutes.
```

---

<div align="center">

## `0x06` — Contact

</div>

<div align="center">

[![Email](https://img.shields.io/badge/PGP%20%2F%20Email-contact%20via%20profile-00FF41?style=flat-square&logo=protonmail&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0daytrace-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zeroday-threatintel)

**Open to:** Security consulting · Firmware audit engagements · Coordinated research partnerships

</div>

<div align="center">

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=13&duration=4000&pause=2000&color=00FF41&center=true&vCenter=true&width=500&lines=responsible+disclosure+%7C+no+drama+%7C+just+bugs" alt="footer" />

<br/>

![Profile views](https://komarev.com/ghpvc/?username=0daytrace&color=00ff41&style=flat-square&label=profile+views)

</div>
