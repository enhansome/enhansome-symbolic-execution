# Awesome Symbolic Execution with stars

> A curated list of awesome symbolic execution resources including essential research papers, lectures, videos, and tools.

## Table of Contents

* [Papers](#papers)
* [Courses](#courses)
* [Videos](#videos)
* [Tools](#tools)

## Papers

* [Symbolic Execution and Program Testing](https://doi.org/10.1145/360248.360252), James C. King.
* [A system to generate test data and symbolically execute programs](https://doi.org/10.1109/TSE.1976.233817), L. A. Clarke.
* [All You Ever Wanted to Know about Dynamic Taint Analysis and Forward Symbolic Execution (but Might Have Been Afraid to Ask)](https://doi.org/10.1109/SP.2010.26), Edward J. Schwartz, Thanassis Avgerinos, David Brumley.
* [Symbolic Execution for Software Testing: Three Decades Later](https://dl.acm.org/doi/10.1145/2408776.2408795), Cristian Cadar and Koushik Sen
* [A Survey of Symbolic Execution Techniques](https://arxiv.org/pdf/1610.00502.pdf), Roberto Baldoni, Emilio Coppa, Daniele Cono D’Elia, Camil Demetrescu, and Irene Finocchi.
* ***Collection of symbolic execution papers:** [XMUsuny/symbolic-execution-papers](https://github.com/XMUsuny/symbolic-execution-papers) ⭐ 186 | 🐛 6 | 📅 2025-05-16*

## Courses

* [Symbolic Execution Lecture at Harvard](http://www.seas.harvard.edu/courses/cs252/2011sp/slides/Lec13-SymExec.pdf).
* [Symbolic Execution Lecture at Iowa State University](http://web.cs.iastate.edu/~weile/cs641/9.SymbolicExecution.pdf).
* [Symbolic Execution Lecture at University of Maryland](https://www.cs.umd.edu/class/spring2013/cmsc631/lectures/symbolic-exec.pdf).

## Videos

* [Symbolic Execution Lecture at MIT](https://www.youtube.com/watch?v=mffhPgsl8Ws).
* [Symbolic Execution Lecture (part of Software Security course on Coursera)](https://www.coursera.org/learn/software-security/lecture/agCNF/introducing-symbolic-execution).
* Program Analysis course by Prof. Dr. Michael Pradel at University of Stuttgart
  * [Symbolic and Concolic Testing (Part 1, Symbolic)](https://youtu.be/wOO5jpoFIss)
  * [Symbolic and Concolic Testing (Part 2, Challenges)](https://youtu.be/K_Q32ar1g6g)
  * [Symbolic and Concolic Testing (Part 3, Concolic)](https://youtu.be/TlEjgqSXYNE)
  * [Symbolic and Concolic Testing (Part 4, Applications)](https://youtu.be/WSL0Oac2VNc)

## Tools

### Rust

* [Owi](https://github.com/OCamlPro/owi) ⭐ 323 | 🐛 153 | 🌐 OCaml | 📅 2026-08-19 - Parallel (dynamic) symbolic execution engine built on WebAssembly (Wasm) that can run Rust code.

### Java

* [LimeTB](http://www.tcs.hut.fi/Software/lime/) - Concolic execution tool that uses [Soot](https://github.com/soot-oss/soot) ⭐ 3,098 | 🐛 349 | 🌐 Java | 📅 2026-08-17 for instrumentation. Supports [Yices](http://yices.csl.sri.com/) and [Boolector](http://fmv.jku.at/boolector/). Concolic execution can be distributed.
* [Acteve](https://code.google.com/archive/p/acteve/) - Concolic execution tool that uses [Soot](https://github.com/soot-oss/soot) ⭐ 3,098 | 🐛 349 | 🌐 Java | 📅 2026-08-17 for instrumentation. Originally for Android analysis. Supports [Z3](https://github.com/Z3Prover/z3) ⭐ 12,572 | 🐛 61 | 🌐 C++ | 📅 2026-08-19.
* [jCUTE](http://osl.cs.illinois.edu/software/jcute/) - Concolic execution tool that uses [Soot](https://github.com/soot-oss/soot) ⭐ 3,098 | 🐛 349 | 🌐 Java | 📅 2026-08-17 for instrumentation. Supports [lp\_solve](http://lpsolve.sourceforge.net/).
* [Symbolic PathFinder (SPF)](https://github.com/SymbolicPathFinder/jpf-symbc) ⭐ 171 | 🐛 60 | 🌐 Java | 📅 2026-02-26 - Symbolic execution tool built on [Java PathFinder](https://github.com/javapathfinder). Supports multiple constraint solvers, lazy initialization, etc.
* [JDart](https://github.com/psycopaths/jdart) ⭐ 128 | 🐛 18 | 🌐 Java | 📅 2019-06-02 - Dynamic symbolic execution tool built on [Java PathFinder](https://github.com/javapathfinder). Supports multiple constraint solvers using [JConstraints](https://github.com/psycopaths/jconstraints) ⭐ 21 | 🐛 1 | 🌐 Java | 📅 2023-04-16.
* [CATG](https://github.com/ksen007/janala2) ⭐ 106 | 🐛 5 | 🌐 Java | 📅 2018-02-20 - Concolic execution tool that uses [ASM](http://asm.ow2.org/) for instrumentation. Uses CVC4.
* [SWAT](https://github.com/SWAT-project/SWAT) ⭐ 47 | 🐛 11 | 🌐 Java | 📅 2026-08-18 - Loosely coupled dynamic symbolic execution using [ASM](https://asm.ow2.io) for instrumentation, [JavaSMT](https://github.com/sosy-lab/java-smt) ⭐ 243 | 🐛 146 | 🌐 SMT | 📅 2026-08-16 for formula generation and currently [Z3](https://github.com/Z3Prover/z3) ⭐ 12,572 | 🐛 61 | 🌐 C++ | 📅 2026-08-19 as a solver.
* [JFuzz](http://people.csail.mit.edu/akiezun/jfuzz/) - Concolic execution tool built on [Java PathFinder](https://github.com/javapathfinder).
* [JBSE](http://pietrobraione.github.io/jbse/) - Symbolic execution tool that uses a custom JVM. Supports CVC3, CVC4, Sicstus, and Z3.
* [Key](https://www.key-project.org/) - Theorem Prover that uses specifications written in Java Modeling Language (JML).

### LLVM

* [SymCC](https://github.com/eurecom-s3/symcc) ⭐ 875 | 🐛 58 | 🌐 C++ | 📅 2026-03-16 - A compiler wrapper which embeds symbolic execution into the program during compilation, and an associated run-time support library.
* [Owi](https://github.com/OCamlPro/owi) ⭐ 323 | 🐛 153 | 🌐 OCaml | 📅 2026-08-19 - Parallel (dynamic) symbolic execution engine built on WebAssembly (Wasm) that can run LLVM code.
* [GenSym](https://github.com/Generative-Program-Analysis/GenSym) ⭐ 147 | 🐛 8 | 🌐 LLVM | 📅 2026-08-18 - A compiler for parallel fork-based symbolic execution.
* [KLEE](http://klee.github.io/) - Symbolic execution engine built on LLVM.
* [Cloud9](https://dslab.epfl.ch/research/cloud9) - Parallel symbolic execution engine built on KLEE.
* [Kite](http://www.cs.ubc.ca/labs/isd/Projects/Kite/) - Based on KLEE and LLVM.

### .NET

* [PEX](http://pex4fun.com/About.aspx) - Dynamic symbolic execution tool for .NET.
* [VSharp](https://github.com/VSharp-team/VSharp) ⭐ 56 | 🐛 43 | 🌐 C++ | 📅 2025-01-06 - Symbolic execution engine for .NET assemblies.

### C

* [Owi](https://github.com/OCamlPro/owi) ⭐ 323 | 🐛 153 | 🌐 OCaml | 📅 2026-08-19 - Parallel (dynamic) symbolic execution engine built on WebAssembly (Wasm) that can run C code.
* [CREST](https://github.com/jburnim/crest) ⭐ 161 | 🐛 11 | 🌐 C | 📅 2020-07-05 - is an open-source tool for concolic testing of C programs.
* [Otter](https://bitbucket.org/khooyp/otter/) - is a pure, source-level symbolic executor for C that can be used to test programs.
* [CIVL](http://vsl.cis.udel.edu/civl/) - A framework that includes the CIVL-C programming language, a model checker and a symbolic execution tool.

### JavaScript

* [Jalangi2](https://github.com/Samsung/jalangi2) ⭐ 492 | 🐛 72 | 🌐 JavaScript | 📅 2026-01-10 - Dynamic analysis framework for JavaScript.
* [SymJS](https://doi.org/10.1145/2635868.2635913) - Automatic symbolic testing of JavaScript web applications.

### Python

* [CrossHair](https://github.com/pschanely/CrossHair) ⭐ 1,316 | 🐛 76 | 🌐 Python | 📅 2026-08-19 - Symbolic execution tool for verifying properties of Python functions.
* [PyExZ3](https://github.com/thomasjball/PyExZ3) ⭐ 344 | 🐛 9 | 🌐 HTML | 📅 2025-12-12 - Symbolic execution of Python functions. A rewrite of the [NICE](https://code.google.com/archive/p/nice-of) project's symbolic execution tool.
* [APEX](https://github.com/allexdav2/apex) - Concolic execution engine for Python with coverage-guided test generation. Built in Rust.

### Ruby

* [Rubyx](https://www.cs.umd.edu/~avik/papers/ssarorwa.pdf) - Symbolic execution tool for Ruby on Rails web apps.

### Android

* [SymDroid](http://www.cs.umd.edu/~jfoster/papers/cs-tr-5022.pdf) - A Symbolic Executor to Identify Activity Permission in Android Application.

### Binaries

* [miasm](https://github.com/cea-sec/miasm) ⭐ 3,928 | 🐛 178 | 🌐 Python | 📅 2026-08-10 - Reverse engineering framework. Includes symbolic execution.
* [manticore](https://github.com/trailofbits/manticore) ⚠️ Archived - Symbolic execution tool for binaries (x86, x86\_64 and ARMV7) and Ethereum smart contract bytecode.
* [BAP](https://github.com/BinaryAnalysisPlatform/bap) ⭐ 2,249 | 🐛 43 | 🌐 OCaml | 📅 2026-05-07 - Binary Analysis Platform provides a framework for writing program analysis tools.
* [BinCAT](https://github.com/airbus-seclab/bincat) ⭐ 1,871 | 🐛 18 | 🌐 OCaml | 📅 2025-02-25 - Binary code static analyser, with IDA integration. Performs value and taint analysis, type reconstruction, use-after-free and double-free detection.
* [MAAT](https://github.com/trailofbits/maat) ⭐ 650 | 🐛 32 | 🌐 C++ | 📅 2026-05-22 - Low-level symbolic execution tool, uses Ghidra's p-code.
* [Owi](https://github.com/OCamlPro/owi) ⭐ 323 | 🐛 153 | 🌐 OCaml | 📅 2026-08-19 - Parallel symbolic execution engine built on WebAssembly (Wasm).
* [pysymemu](https://github.com/feliam/pysymemu/) ⭐ 313 | 🐛 4 | 🌐 Python | 📅 2021-08-28 - Supports x86/x64 binaries.
* [PathGrind](https://github.com/codelion/pathgrind) ⭐ 118 | 🐛 0 | 🌐 C | 📅 2017-03-25 - Path-based dynamic analysis for 32-bit programs.
* [SymEx-VP](https://github.com/agra-uni-bremen/symex-vp) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2023-10-04 - Symbolic execution for RISC-V embedded firmware with accurate SystemC peripheral models.
* [Mayhem](http://dx.doi.org/10.1109/SP.2012.31).
* [SAGE](https://patricegodefroid.github.io/public_psfiles/ndss2008.pdf) - Whitebox file fuzzing tool for X86 Windows applications.
* [DART](https://doi.org/10.1145/1064978.1065036) - is the first concolic testing tool that combines dynamic test generation.
* [BitBlaze](http://bitblaze.cs.berkeley.edu/) - Binary Analysis for Computer Security.
* [FuzzBALL](http://bitblaze.cs.berkeley.edu/fuzzball.html) - Symbolic execution tool built on the BitBlaze Vine component.
* [S2E](http://s2e.systems/) - Symbolic execution platform supporting x86, x86-64, or ARM software stacks.
* [angr](http://angr.io/) - Python framework for analyzing binaries. Includes a symbolic execution tool.
* [Triton](https://triton.quarkslab.com/) - Dynamic binary analysis platform that includes a dynamic symbolic execution tool.
* [Sydr-Fuzz](https://sydr-fuzz.github.io/) - Continuous Hybrid Fuzzing and Dynamic Analysis for Security Development Lifecycle.

### Misc

* [OSS-Sydr-Fuzz](https://github.com/ispras/oss-sydr-fuzz) ⭐ 152 | 🐛 4 | 🌐 C | 📅 2026-08-07 - Hybrid Fuzzing for Open Source Software
* [Symbooglix](https://github.com/symbooglix/symbooglix) ⭐ 29 | 🐛 20 | 🌐 C# | 📅 2021-12-27 - Symbolic execution tool for Boogie programs.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
