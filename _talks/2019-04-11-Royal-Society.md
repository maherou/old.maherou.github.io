---
title: "Accelerated Sparse Linear Algebra: Emerging Challenges and Capabilities for Numerical Algorithms and Software"
collection: talks
type: "Invited Talk"
permalink: /talks/2019-04-11-Royal-Society
venue: "Royal Society Meeting on Numerical Linear Algebra"
date: 2019-04-11
location: "London, UK"
---

For the foreseeable future, the performance potential for most high-performance scientific software will require effective use of hosted accelerator processors, characterized by massive concurrency, high bandwidth memory and stagnant latency.  These accelerators will also typically have a backbone of traditional networked multicore processors that serve as the starting point for porting applications and the default execution environment for non-accelerated computations.

In this presentation we briefly characterize experiences with these platforms for sparse linear algebra computations.  We discuss requirements for sparse computations that are distinct from dense computations and how these requirements impact algorithm and software design.  We also discuss programming environment trends that can impact design and implementation choices.  In particular, we discuss strategies and practical challenges of increasing performance portability across the diverse node architectures that continue to emerge, as computer system architects innovate to keep improving performance in the presence of stagnant latencies, and simultaneously add capabilities that address the needs of data science.

Finally, we discuss the role and potential for resilient computations that may eventually be required as we continue to push the limits of system reliability.  While system designers have managed to preserve the illusion of a “reliable digital machine” for scientific software developers, the cost of doing so continues to increase, as does the risk that a future leadership platform may never reach acceptable reliability levels.  If we can develop resilient algorithms and software that survives failure events, we can reduce the cost, schedule delays and complexity challenges of future systems.

