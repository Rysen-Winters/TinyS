# TinyS
## Castinelli Leonel

This repository will document the work on the TinyS compiler, written in Java.
---
# Lexer

The first step to process the code, is to analize if the code is valid for the language that is accepted by the compiler. That means we must analize each character and word to see if it's valid in the compiler's language.

This compiler will use a language $L_{TinyS}$, whose alphabet $\Sigma$ is:

$$
\Sigma = [A...Z]+[a...z]+[0...9]+\$+\_+'('+')'+';'+'.'
$$