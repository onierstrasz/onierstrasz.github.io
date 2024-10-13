---
title: "Moldable Exceptions"
collection: publications
permalink: /publication/2024-10-23-Chis24a-MoldableExceptions
excerpt: 'In this paper we introduce "moldable exceptions", a lightweight mechanism to adapt a debugger's interface based on contextual information provided by a raised exception.'
date: 2024-10-23
paperurl: 'https://arxiv.org/abs/2409.00465'
venue: 'Proceedings of Onward! 2024'
citation: 'Andrei Chiş and Oscar Nierstrasz and Tudor Gîrba, Moldable Exceptions, Proceedings of Onward! 2024'
---

[PDF download](http://scg.unibe.ch/archive/papers/Chis24aMoldableExceptions.pdf)
| [SCG bib citation](https://scg.unibe.ch/scgbib/?query=Chis24a&filter=Year)

# Abstract

Debugging is hard. Interactive debuggers are mostly the same. They
show you a stack, a way to sample the state of the stack, and, if the debugger
is live, a way to step through execution. The standard interactive debugger for a
general-purpose programming language provided by a mainstream IDE mostly offers a
low-level interface in terms of generic language constructs to track down and fix
bugs. A custom debugger, such as those developed for specific application domains,
offers alternative interfaces more suitable to the specific execution context of
the program being debugged. Custom debuggers offering contextual debugging views
and actions can greatly improve our ability to reason about the current problem.
Implementing such custom debuggers, however, is non-trivial, and poses a barrier
to improving the debugging experience. In this paper we introduce "moldable
exceptions", a lightweight mechanism to adapt a debugger's interface based on
contextual information provided by a raised exception. We present, through a
series of examples, how moldable exceptions can enhance a live programming
environment.


