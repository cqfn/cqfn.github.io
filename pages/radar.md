---
layout: default
date: 2020-09-28
title: "Radar"
permalink: /radar.html
---

[/home](/)

## [First public working draft from W3C: WebGPU and WebGPU shading language](https://www.w3.org/blog/news/archives/9059)
18-May-2021:
Six more years ago, the HTML5 standard was released, but even before the release, the new technology significantly changed the world of web (and non-web) programming. "[HTML5 Leads a Web Revolution](https://dl.acm.org/doi/pdf/10.1145/2209249.2209256)", - such was articles headers. Indeed, many typical applications are built using this standard now. Also, HTML5 can be used not only for the web. For example, the popular IDE Visual Studio Code is based on the [Monaco editor](https://microsoft.github.io/monaco-editor/), which is implemented using TypeScript, renders the content on HTML5 canvas. So, now the [GPU on the Web Community Group (https://www.w3.org/community/gpu/) is taking the next serious step, namely,  the hardware-accelerated 3d graphical API specification. We presume that after implementing this standard and its support by most modern browsers, the development of 3d applications (mostly games) will be significantly shifted to the web, as it will be a cross-platform and fast-working solution. As a result, more efforts should be made to develop tools to improve JavaScript code quality as a basic language for web applications.

## [Kickstarting AI for Code: Introducing IBM’s Project CodeNet](https://research.ibm.com/blog/codenet-ai-for-code)

12-May-2021:
IBM announces CodeNet, a [collection](https://developer.ibm.com/technologies/artificial-intelligence/data/project-codenet/)
of 14 million code examples that solve 4053 typical programming problems, a total of 8 GB of archived data.
We presume that the problem of improving the quality of source codes will be constantly and highly relevant.
Also, we believe that the active introduction of machine learning technologies in this problem space attests to the successful results of such research.
Consequently, it will lead to a rapid increase in the share of artificial intelligence in the source codes analysis compared to static methods.

## [QEMU version 6.0.0 released](https://www.qemu.org/2021/04/30/qemu-6-0-0/)

30-Apr-2021:
The undoubted advantage of QEMU is that it allows emulating any architecture on any machine (or server). The new 6.0 version offers [a significant number](https://wiki.qemu.org/ChangeLog/6.0) 
of changes to support modern platforms.
In our opinion, the tool is a sound basis for more in-depth testing of the quality and functionality of the source code,
for example, for building CI/CD systems that simultaneously support several hardware architectures.
As a result, it will simplify the development of system software, compilers, virtual machines, and other platform-dependent code.


## [HPVM v1.0 released](https://lists.llvm.org/pipermail/llvm-dev/2021-April/149693.html)

9-Apr-2021: 
Heterogeneous computing refers to systems that use more than one kind of processor or cores.
Many chip manufacturers offer their solutions, in particular, for the binding of the CPU and neural processors.
The disadvantages of this approach are proprietary source code of compilers and closed interfaces,
which do not allow developers to improve the quality of such applications and implement code analyzers and automatic bug fixing tools. 
The new HPVM compiler is an attempt to find an effective standardized common solution. 
This [solution](https://publish.illinois.edu/hpvm-project/) positioning itself as a more low-level and flexible approach than competitive frameworks such as OpenCL.
We presume that the release of the HPVM backend will encourage the development of high-performance specified programming languages related to heterogeneous computing such as graphics processing, neural algorithms, or neural networks.
