# Gosu is like Kotlin

[Gosu](https://github.com/gosu-lang/gosu-lang) is an industry-specific programming language that shares a lot in common with other "Java, but improved" languages from the 2010s. This page aims to "show, not tell"; but if you want a more descriptive, technical read, see the [official documentation](https://gosu-lang.github.io/docs.html).

I forked the [swift-is-like-kotlin](https://github.com/Nilhcem/swift-is-like-kotlin) project (itself a fork of [swift-is-like-go](https://github.com/tiye/swift-is-like-go)) and made some modifications. Most notably, this is a static website now. And I began to replace the swift examples with Gosu examples, though there is still much to do:

## Roadmap

In no particular order:

* Verify the code snippets in [Gosu Lab](https://gosu-lang.github.io/quickstart.html)
  * Native types: equivalents to Kotlin's `Double` and `BigDecimal`?
  * Doublecheck in particular: Subclass, Extensions, and Function Type
  * Add results for Range Operator and Extensions (and clarify Named Arguments equivalency)
* Modify the [highlightjs](https://highlightjs.org/) (currently set to Swift's syntax) for Gosu's (not supported)
* Fix the horizontal overflow in 'String Interpolation', 'Downcasting', and 'Subclass'