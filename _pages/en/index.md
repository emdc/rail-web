---
layout: en/page
permalink: /en/
---

> ## **Warning!**
> ### This is a draft documentation. The design is still ongoing, so information can vary greatly over time.
> ### If you have any suggestions or comments, please, <a href="mailto:proposals@rail-lang.org">report them</a>

**Rail** — fast system programming language with extensive compile-time computation capabilities. Design has started after understanding many problems of C language for the development of embedded systems, as well as the excessive complexity of the C ++ language. The goal of the development — expressive language that will allow to create software of any complexity, not just system software.

The main theses that are used in the design:
* The syntax is read-oriented and easy to understand code.
* Modularity and zero-cost abstractions.
* Strict typing with the ability to automatically types calculations.
* Maximize computations at compile time.
* Minimize undefined behaviours.
* Multiparadigms:
  * procedural;
  * object-oriented;
  * functional;
  * generic;
  * metaprogramming.
* Efficiency and safety tools for working with memory directly.
* Accounting for the weak capabilities of microcontrollers and work without any OS (bare-metal).

The development takes into account the experience of such languages:
* C — simple syntax and ease to use bare-metal.
* C++ — object-oriented, template features.
* Rust — static code analyzer, emphasis on security operations.
* JavaScript — expressiveness and simplicity, the speed of achieving results.
* C♯ — object-oriented, semantic load and rich standard library.
* Haskell — functional, expressiveness, optimization.
