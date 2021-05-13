# Awesome Formal Languages and Compilers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome programming language design, domain specific languages and homebrew compilers.

## Contents

- [Tutorials](#tutorials)
- [Videos](#videos)
- [Tools](#tools)
- [Homebrew](#homebrew)

## Tutorials

- Writing a C Compiler
  - [Writing a C Compiler - Part 1: Integers](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
  - [Writing a C Compiler - Part 2: Unary Operators](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
  - [Writing a C Compiler - Part 3: Binary Operators](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
  - [Writing a C Compiler - Part 4: Even More Binary Operators](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
  - [Writing a C Compiler - Part 5: Local Variables](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
  - [Writing a C Compiler - Part 6: Conditionals](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
  - [Writing a C Compiler - Part 7: Compound Statements](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
  - [Writing a C Compiler - Part 8: Loops](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
- [PEG parser in Perl](https://docs.perl6.org/language/grammar_tutorial)
- [Build Your Own Lisp](http://www.buildyourownlisp.com)
- [Writing your own programming language and compiler with Python](https://blog.usejournal.com/writing-your-own-programming-language-and-compiler-with-python-a468970ae6df)
- Let's Build A Simple Interpreter
  - [Let's Build A Simple Interpreter - Part 1](https://ruslanspivak.com/lsbasi-part1/)
  - [Let's Build A Simple Interpreter - Part 2](https://ruslanspivak.com/lsbasi-part2/)
  - [Let's Build A Simple Interpreter - Part 3](https://ruslanspivak.com/lsbasi-part3/)
  - [Let's Build A Simple Interpreter - Part 4](https://ruslanspivak.com/lsbasi-part4/)
  - [Let's Build A Simple Interpreter - Part 5](https://ruslanspivak.com/lsbasi-part5/)
  - [Let's Build A Simple Interpreter - Part 6](https://ruslanspivak.com/lsbasi-part6/)
  - [Let's Build A Simple Interpreter - Part 7: Abstract Syntax Trees](https://ruslanspivak.com/lsbasi-part7/)
  - [Let's Build A Simple Interpreter - Part 8](https://ruslanspivak.com/lsbasi-part8/)
  - [Let's Build A Simple Interpreter - Part 9](https://ruslanspivak.com/lsbasi-part9/)
  - [Let's Build A Simple Interpreter - Part 10](https://ruslanspivak.com/lsbasi-part10/)
  - [Let's Build A Simple Interpreter - Part 11](https://ruslanspivak.com/lsbasi-part11/)
  - [Let's Build A Simple Interpreter - Part 12](https://ruslanspivak.com/lsbasi-part12/)
  - [Let's Build A Simple Interpreter - Part 13: Semantic Analysis](https://ruslanspivak.com/lsbasi-part13/)
  - [Let's Build A Simple Interpreter - Part 14: Nested Scopes and a Source-to-Source Compiler](https://ruslanspivak.com/lsbasi-part14/)
  - [Let's Build A Simple Interpreter - Part 15](https://ruslanspivak.com/lsbasi-part15/)
  - [Let's Build A Simple Interpreter - Part 16: Recognizing Procedure Calls](https://ruslanspivak.com/lsbasi-part16/)
  - [Let's Build A Simple Interpreter - Part 17: Call Stack and Activation Records](https://ruslanspivak.com/lsbasi-part17/)
  - [Let's Build A Simple Interpreter - Part 18: Executing Procedure Calls](https://ruslanspivak.com/lsbasi-part18/)
  - [Let's Build A Simple Interpreter - Part 19: Nested Procedure Calls](https://ruslanspivak.com/lsbasi-part19/)
- [Dragon taming with Tailbiter, a bytecode compiler for Python](https://codewords.recurse.com/issues/seven/dragon-taming-with-tailbiter-a-bytecode-compiler)
- [BASIC Interpreter Implemented in a Jupyter Notebook](https://github.com/norvig/pytudes/blob/master/ipynb/BASIC.ipynb)
- [Let's Write a Brainfuck Compiler](https://www.hackdoor.io/articles/BKQMZJzP/let-s-write-a-brainfuck-compiler)
- [Build a JS Interpreter in JavaScript Using Acorn as a Parser](https://blog.bitsrc.io/build-a-js-interpreter-in-javascript-using-acorn-as-a-parser-5487bb53390c)
- [Let's Write an LLVM Specializer for Python!](http://dev.stephendiehl.com/numpile/)
- [Implementing a JIT Compiled Language with Haskell and LLVM](https://www.stephendiehl.com/llvm/)
- [Write You a Haskell- Building a modern functional compiler from first principles.](http://dev.stephendiehl.com/fun/)
- [PEG Parsing Series - Guido van Rossum](https://medium.com/@gvanrossum_83706/peg-parsing-series-de5d41b2ed60)
  - [PEG Parsing Series - Part 1: PEG Parsers](https://medium.com/@gvanrossum_83706/peg-parsers-7ed72462f97c)
  - [PEG Parsing Series - Part 2: Building a PEG Parser](https://medium.com/@gvanrossum_83706/building-a-peg-parser-d4869b5958fb)
  - [PEG Parsing Series - Part 3: Generating a PEG Parser](https://medium.com/@gvanrossum_83706/generating-a-peg-parser-520057d642a9)
  - [PEG Parsing Series - Part 4: Visualizing PEG Parsing](https://medium.com/@gvanrossum_83706/visualizing-peg-parsing-93a36f259423)
  - [PEG Parsing Series - Part 5: Left-recursive PEG Grammars](https://medium.com/@gvanrossum_83706/left-recursive-peg-grammars-65dab3c580e1)
  - [PEG Parsing Series - Part 6: Adding Actions to a PEG Grammar](https://medium.com/@gvanrossum_83706/adding-actions-to-a-peg-grammar-d5e00fa1092f)
  - [PEG Parsing Series - Part 7: A Meta-Grammar for PEG Parsers](https://medium.com/@gvanrossum_83706/a-meta-grammar-for-peg-parsers-3d3d502ea332)
  - [PEG Parsing Series - Part 8: Implementing PEG Features](https://medium.com/@gvanrossum_83706/implementing-peg-features-76caa4b2151f)
  - [PEG Parsing Series - Part 9: PEG at the Core Developer Sprint](https://medium.com/@gvanrossum_83706/peg-at-the-core-developer-sprint-8b23677b91e6)
- [Pyleri - Parsing with Ease](https://tomassetti.me/pyleri-tutorial/)

## Videos

- [Writing a PEG parser for fun and profit - Guido van Rossum](https://www.youtube.com/watch?v=QppWTvh7_sI)

## Tools

- [PyParsing - A Python Parsing Module](https://github.com/pyparsing/pyparsing)
- [Lark - A parsing toolkit for Python](https://github.com/lark-parser/lark)
- [Unicode-friendly lexer generator for OCaml](https://github.com/ocaml-community/sedlex)
- [Menhir - A LR(1) parser generator for OCaml](http://gallium.inria.fr/~fpottier/menhir/)
- [LPeg - Parsing Expression Grammars in Lua with first-class patterns](http://www.inf.puc-rio.br/~roberto/lpeg/)
- [Python Left-Right Parser (Pyleri) - An easy-to-use parser created for SiriDB](https://github.com/transceptor-technology/pyleri)

## Homebrew

- [A C parser and interpreter written in Python](https://github.com/albertz/PyCParser)
