# Adapting the ARC Cache Management Policy to File Granularity

**Authors:**  
Hocine Mahni, Stéphane Rubini, Sébastien Gougeaud, Philippe Deniel, Jalil Boukhobza

**Presented at:**  
*7th Workshop on Performance and Scalability of Storage Systems (Per3S), May 2023, Paris, France*

**HAL Reference:**  
[hal-04255285](https://hal.science/hal-04255285)

**Poster:**  
[ResearchGate](https://www.researchgate.net/publication/371225858_Adapting_the_ARC_Cache_Management_Policy_to_File_Granularity)

**Simulator:**
[mc_arc GitHub repository](https://github.com/hocinemahni/mc_arc).
---

## Abstract

In this work, we adapt the **Adaptive Replacement Cache (ARC)** policy to a **file-level** granularity.  
Originally designed for **block-level** memory management, ARC offers significant advantages by balancing both **recency** and **frequency** of data accesses. However, it is not directly suitable for **HPC** environments, where data management and eviction typically operate at the **file-level**.

Our proposed **file-level ARC**, evaluated on a **multi-tier storage simulator**, significantly improves performance (hit ratio and response time) compared to reference policies such as **LRU** and **LFU**, while preserving the strengths of ARC.

---

## How to Cite

If you use or reference this work, please cite:

> **Hocine Mahni, Stéphane Rubini, Sébastien Gougeaud, Philippe Deniel, Jalil Boukhobza.**  
> *Adapting the ARC Cache Management Policy to File Granularity.*  
> In *7th Workshop on Performance and Scalability of Storage Systems (Per3S)*, May 2023, Paris, France.  
> [HAL: hal-04255285](https://hal.science/hal-04255285)

---


