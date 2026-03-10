---
layout: default
title: SDP bounds on quantum codes
---

## SDP bounds on quantum codes

Upper and lower bounds on quantum error correcting codes. Maximum code size $K$ of nonadditive quantum codes for a given $n$ and $\delta$. 
Lower and upper bounds are separated by a dash $-$.  If one number is shown only, upper and lower bounds meet. A $0$ implies that such code do not exist. When our SDP improves a known bound, the stronger SDP bound it highlighted in bold with the previous bound in parenthesis.


| **n** \ **d** | **2**          | **3**                      | **4**                   | **5**                   | **6**         | **7** | **8**         |
|-----------------------------|----------------|----------------------------|-------------------------|-------------------------|---------------|-------|---------------|
| **7**                       | 24 - 26        | 2 - 3                      | 0                       | 0                       | 0             | 0     | 0             |
| **8**                       | 64             |    8**(9)              | 1                       | 0                       | 0             | 0     | 0             |
| **9**                       | 96 - 112       | 12 - 13                    | 1                       | 0                       | 0             | 0     | 0             |
| **10**                      | 256            | 24                         | **4**(5)           | 0                       | 0             | 0     | 0             |
| **11**                      | 386 - 460      | 32 - **42**(53)       | 4 - 7                   | 2                       | 0             | 0     | 0             |
| **12**                      | 1024           | 64 - 89                    | 16 - 20                 | 2                       | 1             | 0     | 0             |
| **13**                      | 1586 - 1877    | 128 - 204                  | 16 - 40                 | 2 - 3                   | **0**(1) | 0     | 0             |
| **14**                      | 4096           | 256 - **295**(324)    | 64 - 102                | 4 - **9**(10)      | 1             | 0     | 0             |
| **15**                      | 6476 - 7606    | 512 - 580                  | 64 - **138**(150)  | 8 - 18                  | 1             | 0     | 0             |
| **16**                      | 16384          | 1024 - **1170**(1260) | 128 - 256               | 32 - 42                 | 4 - 6         | 0     | 0             |
| **17**                      | 16384 - 30720  | 2048 - 2145                | 512                     | 32 - **59**(64)    | 4 - 8         | 2     | 0             |
| **18**                      | 65536          | 2048 - 4096                | 512 - **921**(986) | 64 - 113                | 16 - 22       | 2     | 1             |
| **19**                      | 65536 - 123790 | 4096 - **7420**(8426) | 1024 - 1804             | 128 - **249**(296) | 32 - 47       | 2 - 3 | **0**(1) |


#### For pure codes the above bounds are strenghtened to:
(add)

#### Some comments to specific codes:
(add)

#### Updates since 5 March 2026:
(none)

#### Origin of bounds

Upper bounds are based on the SDP framework developed in 

- Gerard Anglès Munné, Andrew Nemec, Felix Huber, *SDP bounds on quantum codes*, 
https://arxiv.org/abs/2408.10323
- Gerard Anglès Munné, Felix Huber, *SDP bounds on quantum codes: Exact certificates*, on arXiv soon

Lower bounds based on constructions. (Exhaustive list see below TODO)
