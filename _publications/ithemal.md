---
title: "Ithemal: Accurate, Portable and Fast Basic Block Throughput Estimation using Deep Neural Networks"
collection: publications
permalink: /publication/ithemal
date: 2019-06-11
venue: ICML
paperurl: 'https://arxiv.org/abs/1808.07412'
codeurl: 'https://github.com/psg-mit/Ithemal'
authors:
 - Charith Mendis
 - Alex Renda
 - Saman Amarasinghe
 - Michael Carbin
---

Predicting the number of processor clock cycles it takes to execute a block of assembly instructions in steady state (the throughput) is important for both compiler designers and performance engineers. Building an analytical model to do so is especially complicated in modern x86-64 Complex Instruction Set Computer (CISC) machines with sophisticated processor microarchitectures in that it is tedious, error prone, and must be performed from scratch for each processor generation. In this paper, we present Ithemal, the first tool which learns to predict the throughput of a set of instructions. Ithemal uses a hierarchical LSTM--based approach to predict throughput based on the opcodes and operands of instructions in a basic block. We show that Ithemal is more accurate than state-of-the-art hand-written tools currently used in compiler backends and static machine code analyzers. In particular, our model has less than half the error of state-of-the-art analytic models (LLVM's [`llvm-mca`](https://llvm.org/docs/CommandGuide/llvm-mca.html) and Intel's [`IACA`](https://software.intel.com/en-us/articles/intel-architecture-code-analyzer)). Ithemal is also able to predict these throughput values at a faster rate than the aforementioned tools, and is easily ported across a variety process microarchitectures with minimal developer effort.
