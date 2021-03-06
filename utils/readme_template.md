# Lex Samples

This repository contains sample problems solved using lex/flex utility.

## Prerequisites

`Lex` is a lexical analyser tool mostly used with `Yacc` parse generator. It lexically analyses (i.e. matches) the patterns (regular expressions) given as input string or as a file.

Following are the `Lex` predefined functions and variables :-

1. `yyin`: the input stream pointer (i.e it points to an input file which is to be scanned or tokenised), however the default input of default main() is stdin.
2. `yylex()`: implies the main entry point for lex, reads the input stream generates tokens, returns zero at the end of input stream. It is called to invoke the lexer (or scanner) and each time yylex() is called, the scanner continues processing the input from where it last left off.
3. `yytext`: a buffer that holds the input characters that actually match the pattern (i.e lexeme) or say a pointer to the matched string.
4. `yyleng`: the length of the lexeme.
5. `yylval`: contains the token value.
6. `yyval`: a local variable.
7. `yyout`: the output stream pointer (i.e it points to a file where it has to keep the output), however the default output of default main() is stdout.
8. `yywrap()`: it is called by lex when input is exhausted (or at EOF). default yywrap always return 1.
9. `yymore()`: returns the next token.
10. `yyless(k)`: returns the first k characters in yytext.
11. `yyparse()`: it parses (i.e builds the parse tree) of lexeme.

## Problem Statements

{statements}

## Facing a Issue

If you are in this situation _first and foremost_ Don't panic :cry: I'm here to help you get over it. Simply click [this](https://github.com/Hoosier-Daddy/lex-samples/issues) and properly state your issue (be as verbose as you can be), After that sit tight and watch :movie_camera: the movie you have been postponing for so long while I :construction_worker: fix the issue.

## Want to Contribute

I will be glad :smiley: to work with you on a new idea or fixing a invisible bug :bug: or if you have already done the work :hammer: just create a pull request and I will merge it asap.

Well that's all for now but before you close this browser tab hit the star :star: button (it motivates me to make new stuff).

Have a great day :sunglasses:.
