Language Design Goal
=======================

 * C# like grammar (because its type-safe nature)
   * strong DSL support: can even emmbed another language!
 * may target at JVM or CLI, as futher will even go native.
   * can embed in JVM or CLI
   * can host JVM or CLI
 * do we need a run-time?
 * type-safe as default but fully support dynamic, and even support meta as well.
 * extensible syntactic sugar like boo groovy etc. and build-in common patterns
 * closures like groovy
 * dynamics like javascript but not the same
 * interpret and/or compile at run-time
 * programmable compile pipe-line like boo
 * common lang enhancement like array literal etc.
 * Tooling
   * scafolded
   * 
 * philosophy
   * outstanding
   * DRY(Don't repeate yourself)
   * lean
   * DSL as first citizen
   * highly strict orgnized community
     * modeling
     * patterns
     * snippet
     * DSL
     * tooling
   * enterprise product level quality and performance


Motivation
===========

This is 2013. Languages today are **f** hard to use. Dynamic languages like groovy or ruby are too slow, hybrid languages like C# are too verbose and hard to extend, functional languages like Scala or F# are hard for OO guys and newbies, gramma looks ugly and lack support. Almost all of them also lack portability.

Have all that said, we need a language that is super-fast, beautiful, easy to understand, human intuitive, super easy to extend, fully portable and integratable with existing runtimes like CRT, JVM or CLI etc. Here comes the eEn language.

eEn language is not intended to compete with languages like C/C++ but dedicated to write applications.
