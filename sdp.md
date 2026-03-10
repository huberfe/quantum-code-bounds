---
layout: default
---

# SDP bounds on quantum codes

Maximum code size $$K$$ of nonadditive quantum codes for a given $$n$$ and $$\delta$$. 
Lower and upper bounds are separated by a dash $$-$$.  Upper and lower bounds meet if only one number is shown. 
A stronger SDP bound is highlighted in bold with the previous bound in parenthesis.


| **n** \ **d** | **2**          | **3**                      | **4**                   | **5**                   | **6**         | **7** | **8**         |
|-----------------------------|----------------|----------------------------|-------------------------|-------------------------|---------------|-------|---------------|
| **7**                       | 24 - 26        | 2 - 3                      | 0                       | 0                       | 0             | 0     | 0             |
| **8**                       | 64             |    **8**(9)              | 1                       | 0                       | 0             | 0     | 0             |
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


## For pure codes the bounds marked with $$\alpha$$ strenghten to:

$$
\begin{align}\label{eq:pure_inf}
 &(\!(6,1,3)\!)_2 \,,  \quad  (\!(11,41,3)\!)_2 \,,  \quad  (\!(14,290,3)\!)_2 \,,  \nn \\
 &(\!(14,8,5)\!)_2 \,,   \quad  (\! (15,135,4)\!)_2\,, \quad (\!(17,57,5)\!)_2 \,, \quad (\!(19,7314,3)\!)_2 \,.
\end{align}
$$


## Some comments to specific codes:
(add)

## Updates since 5 March 2026:
(none)

## References

Upper bounds are based on the SDP framework developed in 

** [MNH24]** Gerard Anglès Munné, Andrew Nemec, Felix Huber, *SDP bounds on quantum codes*, 
[https://arxiv.org/abs/2408.10323](https://arxiv.org/abs/2408.10323)

** [MH46]** Gerard Anglès Munné, Felix Huber, *SDP bounds on quantum codes: Exact certificates*, on arXiv soon

Lower bounds based on constructions. (Exhaustive list see below TODO)
