---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

------------------

Research
=====

I'm broadly interested in the intersection of programming languages and machine learning, to create more secure, privacy-preserving, efficient, performant, and correct software. Specifically, I want to create abstractions that can provide strong guarantees for probabalistic and approximate systems that traditionally lack them. I'm also interested in applying machine learning to challenging problems within programming systems, especially in contexts where simple hand-written heuristics are not sufficient or perfect accuracy is not required.

Projects
=====
------------------

Ithemal
==

Predicting the number of processor clock cycles it takes to execute a block of assembly instructions in steady state (the throughput) is important for both compiler designers and performance engineers. Building an analytical model to do so is especially complicated in modern x86-64 Complex Instruction Set Computer (CISC) machines with sophisticated processor microarchitectures in that it is tedious, error prone, and must be performed from scratch for each processor generation. To this end, we developed Ithemal, a system which learns to predict the throughput of a set of instructions. Ithemal uses a hierarchical LSTM--based approach to predict throughput based on the opcodes and operands of instructions in a basic block. Ithemal is significantly more accurate than state-of-the-art hand-written tools currently used in compiler backends and static machine code analyzers. In particular, our model has less than half the error of state-of-the-art analytic models (LLVM's [`llvm-mca`](https://llvm.org/docs/CommandGuide/llvm-mca.html) and Intel's [`IACA`](https://software.intel.com/en-us/articles/intel-architecture-code-analyzer)).

Joint work with Charith Mendis, Saman Amarasinghe, and Michael Carbin.
[Paper](https://arxiv.org/abs/1808.07412) ([ICML](https://icml.cc) 2019).
[Code](https://github.com/psg-mit/Ithemal).

Opal
==

Opal is a set of language constructs for interfacing with natural language understanding systems. Rather than just providing a better API for any one particular system, Opal provides methods for passing structured data in and handling ambiguous results out of these systems. For instance, Opal provides a construct for safely exploring potential results of ambiguous interpretations rather than commiting to any one interpretation *a priori*; a DSL for jointly specifying a configuration of an NLU engine (e.g. [Wit.ai](https://www.wit.ai)), a type within a target language (e.g. [TypeScript](https://www.typescript.com)), and a function to reconstruct entities of the generated type from output of the NLU engine; methods for requesting access to data and placing computation within a distributed system; and other (WIP) features.

Joint work with Harrison Goldstein, Sarah Bird, Chris Quirk, and Adrian Sampson.
[Website](https://capra.cs.cornell.edu/research/opal).
[Paper Draft](https://arxiv.org/abs/1709.04991).
[Code](https://github.com/cucapra/opal).
