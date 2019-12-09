---
title: "A Benchmark Suite for Validating x86-64 Performance Models"
collection: publications
permalink: /publication/iiswc-2019
date: 2019-11-03
venue: IISWC
paperurl: 'https://arxiv.org/abs/1808.07412'
authors:
 - Yishen Chen
 - Ajay Brahmakshatriya
 - Charith Mendis
 - Alex Renda
 - Eric Atkinson
 - Ondřej Sýkora
 - Saman Amarasinghe
 - Michael Carbin
bibtex: /bibtex/iiswc-2019.txt

---

Compilers and performance engineers use hardware performance models to simplify program optimizations. Performance models provide a necessary abstraction over complex modern processors. However, constructing and maintaining a performance model can be onerous, given the numerous microarchitectural optimizations employed by modern processors. Despite their complexity and reported inaccuracy (e.g., deviating from native measurement by more than 30%), existing performance models—such as IACA and llvm-mca—have not been systematically validated, because there is no scalable machine code profiler that can automatically obtain throughput of arbitrary basic blocks while conforming to common modeling assumptions.

In this paper, we present a novel profiler that can profile arbitrary memory-accessing basic blocks without any user intervention. We used this profiler to build BHive, a benchmark for systematic validation of performance models of x86-64 basic blocks. We used BHive to evaluate four existing performance models: IACA, llvm-mca, Ithemal, and OSACA. We automatically cluster basic blocks in the benchmark suite based on their utilization of CPU resources. Using this clustering, our benchmark can give a detailed analysis of a performance model’s strengths and weaknesses on different workloads (e.g., vectorizedvs. scalar basic blocks). We additionally demonstrate that our dataset well captures basic properties of two Google applications: Spanner and Dremel.
