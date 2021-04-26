
Aspect-Oriented Programming
===========================

TODO: Overview

- aspect
- join points
- point cut
- advice

Prior Art
---------

- Moose language
- AspectJ language
- Harmony library

Problems
--------

- control-flow change
- point cut mismatch (target method change, query predicate fails)
- are errors from patcher or patchee?
- poor visibility

Solutions
---------

- strictness, compile time checking
- no ``around`` construct, no control flow changes
- ``sealed class`` to block aspects
- visibility to what aspects are applied
