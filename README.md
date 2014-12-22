Xass: simple but powerful & flexible
====================================

OOP-like CSS component definition library including features of fluent API, Dependency Injection etc.

I consider whether I should still use Sass as a preprocessor.
The feature that allows us to handle parent selector in 3.3.0 rc will come back as new Selector Functions in 3.4.0.

Ideas
=====
* [**HTML/CSS Class Naming Convention for Scalable/Modular CSS.**](https://gist.github.com/whizark/92ed70d90d262a44db84)
* [**Naming Convention for Sass library**](https://gist.github.com/whizark/803834304d0ff34e99af)
* [**Map getter & overridding**](https://gist.github.com/whizark/9001629e7e2ab45e79a4)
* [**A flexible component definition**](https://gist.github.com/whizark/5e28e164afdfa6bb3117)
* [**Polymorphic placeholder & mixins**](https://gist.github.com/whizark/97c8713818870f7a7c47)
* [**Generating decoupled color schemes**](https://gist.github.com/whizark/f0eca27359406936e9af)
* [**Typed value factory & validator using Map**](https://gist.github.com/whizark/b42f5d52c3caa2ad5f43) ([with descriptor](https://gist.github.com/whizark/40a9cf55b62edb01e572))
* [**Passing/Getting property value(s) into/inside mixins/functions**](https://gist.github.com/whizark/5dd0db8d8c0d46391a59)
* [**Dependency Injection into Mixins**](https://gist.github.com/whizark/e2281eadfa6b3a22caf0)
* [**Resolving component dependencies**](https://gist.github.com/whizark/51ccdfbf57dbcb73953f) ([Improved](https://gist.github.com/whizark/98328c6c26a298b68e4a))
* [**Creating new Scope & Instance Variable/Method**](https://gist.github.com/whizark/344cd819e8a45f2acb4a) ([Another Example](https://gist.github.com/whizark/7c9d9c26314bf9a9f006))
* [**Placeholder Factory(Mixin) based on the argumetns**](https://gist.github.com/whizark/1a7e587e447eb38e8a3b)
* [**Automatically reducing duplicated declarations**](https://gist.github.com/whizark/720ffec139368fa61932)
* [**Back-slash as the namespace separator in HTML/CSS**](https://gist.github.com/whizark/ea2ba0ff3f47956fda0f)
* [**The Way to Define Robust CSS Module/Component**](https://gist.github.com/whizark/6355c4060cb1a35165d7)
* [**Element-type-based Conditional Styles Inside Mixin**](https://gist.github.com/whizark/db2327790b7ce4f1f575)
* [**placeholder-exists()**](https://gist.github.com/whizark/86751f1fbcd132ec8c52)

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
