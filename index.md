---
layout: page
title: FPT-4: FLOATING POINT TRANSFORMERS 4
#permalink: /index/
---

[![image](/images/fpt4_workflow.png){: height="240" align="right" }]


<br> 
<br> 
<br> 


[comment]: <> (https://anr.fr/Projet-ANR-24-CE46-7572)

### Hypotheses
In the realm of High-Performance Computing (HPC), the conventional standards for representing floating-point numbers, binary32 and binary64, have held sway for decades. These formats have been the bedrock of numerical precision in supercomputers and HPC clusters, leading to billions of lines of legacy code, catering to the intricate calculations required by scientific simulations, weather modeling, and nuclear research (Code Saturne, Code Aster, Salome, ...). However, the landscape of HPC has to shift toward considering other formats, compelling us to reevaluate these well-established norms.

In today's fast-paced technological landscape, where new hardware (very long vectors, matrix units), new floating-point representation format (fp24, fp8, fp4) and new software arise every year, precision in computational processes holds a critical role in shaping the efficiency, scalability, and energy consumption. The quest for adapting the precision used during computation has emerged as a paramount concern in the field of HPC, driven by a convergence of factors that span hardware limitations, computational demands, and environmental considerations. This shift toward reducing precision is no longer just an academic curiosity but a practical necessity, underpinning advancements in fields as diverse as artificial intelligence, scientific research, and edge computing.

Legacy HPC codes are often finely tuned for performance and accuracy, with countless dependencies on the existing precision formats, undocumented numerical tricks and missing developer’s expertise. Transitioning to new, more compact representation formats would require not only rewriting a colossal amount of code but also extensive testing and validation to ensure that critical scientific simulations and calculations remain accurate and reliable. Furthermore, the process must be undertaken with meticulous care to avoid introducing subtle errors or disruptions in the vast ecosystem of HPC software and libraries, which could have far-reaching consequences.

Generative AI has recently proven to be of significant help in the management of such legacy code by offering innovative solutions to several common challenges associated with maintaining and modernizing legacy code by helping in code refactoring, documentation generation, bug detection and testing, and knowledge preservation.


### Objectives
 This project aims at leveraging generative AI to alleviate the urgent needs to assist HPC developers in adopting low-precision formats for legacy code in order to reduce computational needs while guaranteeing result accuracy. By analyzing legacy code, we propose to empower a Large Language Model with numerical knowledge to  identify precision reduction opportunities and automatically suggest code modifications (Task2). Crucially, we propose to explore how accuracy reduction and mixed precision techniques could alleviate frugal computing (Task3) while not sacrificing computational integrity thanks to the use of certified algorithms and numerical tools when needed (Task4-5). This approach empowers developers to embrace efficiency without compromising reliability, fostering sustainable and energy-efficient computing solutions.
 

[![image](/images/anr.png){: height="60" align="center" }](https://anr.fr/fileadmin/aap/2024/selection/aapg-2024-selection.pdf)
