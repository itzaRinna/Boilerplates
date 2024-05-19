TEST
----

A collection of boilerplate "test" programs and apps for various programming
languages and frameworks.

Supports
========

* [X] [Assembly](ASM)
* [X] [C](C)
* [ ] [C#]
* [X] [C++](cpp)
* [X] [Crystal](crystal)
* [X] [Docker](docker)
* [X] [Elixir](elixir)
* [X] [Go](go)
* [ ] Haskell
* [X] [HTML / CSS / JavaScript](html)
* [X] [Java](java)
* [X] [Make](make)
* [X] [Nim](nim)
* [X] [Node.js](node.js)
* [X] [TypeScript](typescript)
* [ ] Perl
* [X] [PHP](php)
* [X] [Python](python)
* [X] [Ruby](ruby)
* [X] [Rust](rust)
* [ ] Scala
* [X] [Shell](shell)
  * [X] [Bash](shell/bash)
  * [X] [ZSH](shell/zsh)
* [X] [XSLT](xslt)
* [X] [Zig](zig)

Contribute
==========

1. Create an appropriately named directory.
2. Add a build file (Makefile or other build file) if language is compiled.
3. Add a file named test with appropriate file extension.
   * If the program can write to stdout, it must print "test" to stdout.
   * May also contain other common boilerplate code.
   * If the file is interpreted, it should begin with a `#!/usr/bin/env ...` and
     be executable (`chmod +x`).
