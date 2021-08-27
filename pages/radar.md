---
layout: default
date: 2020-09-28
title: "Radar"
permalink: /radar.html
---

[/home](/)

## [Linux turns 30](https://twitter.com/linuxfoundation/status/1430539222142885898)
25-August-2021: 30 years ago today Linus Torvalds introduced Linux to the world. Since then, Linux has become the leading operating system widely used in many applications, and in some, this is a de facto monopoly - say, [100% of supercomputers run Linux](https://itsfoss.com/linux-runs-top-supercomputers/). The operating system is constantly improving, new functions appear every release. Such active development has become possible because open licensing model. More than three-quarters of the new changes are committed by corporations. For example, Huawei Technologies [made 6.5% of all changes](https://lwn.net/Articles/860989/) for the latest stable kernel. What's the profit? The use in company products of this large collaborated development brings far more revenue than the cost of changes was made. The development of such a fully proprietary system is much more expensive and consequently would increase the final cost of products. It is clear that an open model of development is more competitive. The world runs on open source.

## [Huawei Release Their First RISC-V Development System – Hi3861](https://www.electropages.com/blog/2021/06/huawei-release-their-first-risc-v-development-system-hi3861)
16-August-2021: Open software has many obvious advantages over proprietary. In general, a free license allows third-party developers - individual programmers and companies - to make their valuable contribution to the development of a product, and consequently, the result obtained has a chance to be more functional and competitive than the same proprietary one. However, open and free can be not only software but also hardware, such as processor architecture. If the [specification](https://riscv.org/technical/specifications/) of such an architecture is available for non-paid and free use, including commercial production of physical chips, such an architecture can as a result have [considerable support](https://riscv.org/members/) from end-producers and programmers, even if its current stage even lags behind the available proprietary solutions. We believe that using open technologies will lead to a more productive result than the development of own or the licensing of third-party proprietary hardware. Not to mention that such an approach is much less affected by the negative impact of unexpected cases such as international sanctions.

## [GitHub’s Engineering Team has moved to Codespaces](https://github.blog/2021-08-11-githubs-engineering-team-moved-codespaces/)
11-August-2021: Improving software quality (this is what we are aiming for at the Code Quality Foundation) is achieved, among other things, by using various tools such as continuous integration, code checkers, automatic testing utilities, and so on. Configuring and supporting such tools for large projects can obviously take significant resources, including money. What is only worth buying and maintenance servers! The use of cloud technologies, where all the necessary tools are already configured and provided to developers (even directly from an IDE) - an obvious path of least resistance for the project manager. Therefore, we need to focus on developing tools that could work with cloud technologies, such as plugins to find and fix defects in the source code.

## [GitHub Previews Copilot, an OpenAI-Powered Coding Assistant](https://www.infoq.com/news/2021/07/github-copilot-pair-programmming/)
07-July-2021: Another tool that uses machine learning to speed up development and improve code quality. Such tools are now being implemented more and more, say, the popular [Codota](https://plugins.jetbrains.com/plugin/7638-codota-ai-autocomplete-for-java-and-javascript) plugin and the recently emerged [Tabnine](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion-js-java-python-ts-rust-go-php--more). We now see that the development of tools that improve code quality and are based on artificial intelligence is increasingly being adopted by major services, GitHub is one of them. We believe that using neural networks as part of code analyzers will be more successful and new amazing methods of code analysis for different scenarios await us.

## [Google is officially releasing its Fuchsia OS](https://9to5google.com/2021/05/25/google-releases-fuchsia-os-nest-hub/)
25-May-2021: What is better - microkernel or monolith? Linus Torvalds asked this question in a [debate](https://en.wikipedia.org/wiki/Tanenbaum%E2%80%93Torvalds_debate) with Andrew Tanenbaum, it was in 1992, and Linux's version was 0.01. Torvalds insisted that monolith is better as overhead costs for the exchange between processes are reduced. However, monolithic applications and kernels have a significant disadvantage - if it crashes, it does it at all. Rather than monolithic applications, the popularity of microservices technology is rapidly growing. According to OReilly Media, Inc. [research](https://www.oreilly.com/radar/microservices-adoption-in-2020), more than three-quarters (77 %) of businesses have now adopted microservices. A microkernel operating system must have a rich interprocess communication solution. Therefore, the overhead costs for microservices in such a system are lower. Now, we observe a new and successful attempt to develop a modern design that implements a proven approach. We believe that releasing such an advanced and open-source system will shift the focus of application development from monolithic to distributed. In this solution, small elegant processes each does a clearly defined task, only one, but does it well.


## [First public working draft from W3C: WebGPU and WebGPU shading language](https://www.w3.org/blog/news/archives/9059)
18-May-2021:
Six more years ago, the HTML5 standard was released, but even before the release, the new technology significantly changed the world of web (and non-web) programming. "[HTML5 Leads a Web Revolution](https://dl.acm.org/doi/pdf/10.1145/2209249.2209256)", - such was articles headers. Indeed, many typical applications are built using this standard now. Also, HTML5 can be used not only for the web. For example, the popular IDE Visual Studio Code is based on the [Monaco editor](https://microsoft.github.io/monaco-editor/), which is implemented using TypeScript, renders the content on HTML5 canvas. So, now the [GPU on the Web Community Group](https://www.w3.org/community/gpu/) is taking the next serious step, namely,  the hardware-accelerated 3d graphical API specification. We presume that after implementing this standard and its support by most modern browsers, the development of 3d applications (mostly games) will be significantly shifted to the web, as it will be a cross-platform and fast-working solution. As a result, more efforts should be made to develop tools to improve JavaScript code quality as a basic language for web applications.

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
