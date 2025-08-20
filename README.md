# Revealing Programming Language Abstractions

This repo contains a thesis written as part of the Swiss [GymInf program](https://www.unifr.ch/gyminf/). Source code associated with this thesis is stored in the [gt-exploration](https://github.com/zeniko/gt-exploration) repository and teaching materials in the [processing-abstractions](https://github.com/zeniko/processing-abstractions) repository.

## Abstract

This thesis presents an environment to teach programming and computer architecture at high school level that allows students to experience and interactively explore various abstraction levels involved in running a program.

Didactic literature suggests that exploring different abstraction levels improves students' understanding of both programming and the inner workings of a computer system. Such multi-layered exploration is also considered a foundational idea of computer science and has to be taught because, among other reasons, some lower abstraction layers tend to leak through interfaces anyway.

For this, the teaching environment "Processing Abstractions" has been created on the basis of the Smalltalk environment [Glamorous Toolkit](https://gtoolkit.com/). This environment contains an interpreter for a subset of the Processing programming language in its Python form, for which many different views were molded: Tokenization, syntax tree building, transpilation of Processing into Smalltalk, translations to an intermediary language and eventually to Smalltalk bytecode, and finally the program's actual output. These views are tied to source code and updated live for seamless exploration and can be composed into interactive material to teach abstraction levels involved in programming, examples for which are also included.

Processing Abstractions has been used and evaluated during a few lessons. On the basis of the limited data available, the evaluation shows that the live environment does encourage experimentation and allows students to work and profit at their own pace and depth. However, understanding of the various layers has not improved significantly in the short period of time that the environment could be tested.
