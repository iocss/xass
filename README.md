Xass: simple but powerful & flexible
====================================

**Naming Convention for Sass library:** https://gist.github.com/whizark/803834304d0ff34e99af

OOP-like CSS component definition library including features of fluent API, Dependency Injection etc.

I consider whether I should still use Sass as a preprocessor.
The feature that allows us to handle parent selector in 3.3.0 rc will come back as new Selector Functions in 3.4.0.

Features
========

  * OOP-like component definition (encapsulation, extending, polymorphism)
  * OOP-like property handling
  * Fluent API
  * Dependency Injection
  * Conflict proof mixins & functions
  * Accessor/Mutator/Listener, Custom type hinting (as ideas)

Requirement
===========

  * Sass 3.4.0+ (considering support of SassC)
  * or considering of use of AbsurdJS (better than Sass, I feel)

Ideas
=====

 * Core
 * Configuration (storage)
 * Object
 * Container
   * Injection
 * Provider
 * Type (Constraint), Validator
 * Ruleset (placeholder definition)
   * Accessor/Mutator
   * Injection
