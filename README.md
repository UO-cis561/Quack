# Quack
Documentation for Quack, a small language for novice compiler builders 

## To build

```
xelatex quack_grammar.tex
xelatex quack_grammar.tex
```
Two runs of LaTeX are required to get cross-references right.  Xelatex
(not pdflatex) is required by the "font-spec" library.  It is probably
easy to remove that dependency, but I have not tested it.  LuaTeX may
also work; I have tested only with Xelatex. 

## Contents: Main files

```quack_grammar.tex``` briefly describes the lexical and syntactic
structure of Quack.  Types and dynamic semantics are described only
through examples, just to keep it short.

```quacktypes.tex``` incomplete working document to describe type
checking and type inference for Quack.   This document needs major
revision before it is ready for distribution as a class handout.

## Other files

```grammar.sty``` and ```quackman.sty``` are LaTeX support code for
the main documents.

```img``` contains graphics or inclusion in the documents.  The
Tenniel illustrations are in the public domain. 

```samples``` is an early collection of sample Quack programs.  I
currently have too many copies of the the samples collection, which
means that there are surely inconsistencies and that a bug fixed in
one copy will remain in others, so in future this needs to be a
separate shared repo.

## Copying

Initially I cribbed some parts of Quack from Aiken's Cool  (classroom
object oriented language).  Some cribbed text may remain, although I
think I've rewritten most (and certainly all errors are mine).
Anyone teaching a compiler construction course is welcome to take any
part of this they find useful.  If you do, I would appreciate a note.
Corrections and suggestions are also welcome.

If I were doing this again from scratch, I might make Quack a subset
of Kotlin.

Notes to:  michal@cs.uoregon.edu


