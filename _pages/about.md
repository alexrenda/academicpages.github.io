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

Opal
==

Opal is a set of language constructs for interfacing with natural language understanding systems. Rather than just providing a better API for any one particular system, Opal provides methods for passing structured data in and handling ambiguous results out of these systems. For instance, Opal provides a construct for safely exploring potential results of ambiguous interpretations rather than commiting to any one interpretation *a priori*; a DSL for jointly specifying a configuration of an NLU engine (e.g. [Wit.ai](https://www.wit.ai)), a type within a target language (e.g. [TypeScript](https://www.typescript.com)), and a function to reconstruct entities of the generated type from output of the NLU engine; methods for requesting access to data and placing computation within a distributed system; and other (WIP) features.

Joint work with Harrison Goldstein, Sarah Bird, Chris Quirk, and Adrian Sampson.
[Opal Website](https://capra.cs.cornell.edu/research/opal).
