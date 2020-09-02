Languages
=========

This repository is for exploring different programming languages. What
are the various strengths and weaknesses for our bioinformatics work?

## Features ##

| Name   | Type | Scope | Block | End | Garb | Var |
|:------:|:----:|------:|:-----:|:---:|:----:|:---:|
| C      | comp | block | brace |  ;  | man  | sta |
| C++    | comp | block | brace |  ;  | man  | sta |
| C#     | vm   | block | brace | \n  | auto | sta |
| Go     | comp | block | brace | \n  | auto | sta |
| Java   | vm   | block | brace |  ;  | auto | sta |
| JS     | vm   | func  | brace |  ;  | auto | dyn |
| Julia  | com  | block | tab   | \n  | auto | d+s |
| Lua    | int  | block | tab   | \n  | auto | dyn |
| Perl   | int  | lex   | brace |  ;  | auto | dyn |
| Python | int  | func  | tab   | \n  | auto | dyn |
| R      | int  |       |       |     | auto |     |
| Ruby   | int  | mixed | tab   | \n  | auto | dyn |
| Rust   | comp | block | brace |  ;  | man  | sta |
| TS     | vm   | f & b | brace |  ;  | auto | sta |

## Testing ##

+ C - fast, but not friendly
+ Go - a better C?
+ Julia - high performance with modern features
+ Perl - the old standard
+ Python - the new standard
+ Rust - memory safe, high performance

The following languages will not be tested

- C++ - don't need the complexity
- C# - not used in bioinformatics
- Java - yucky
- JavaScript - popular, but not used in bioinformatics
- Lua - cool, but not use in bioinformatics
- R - not general purpose
- Ruby - OOP Perl, but not used in bioinformatics
- TypeScript - JS++, but still not used in field

## Benchmarks ##

+ hello_world - the usual
+ hello_fasta - iteratively step through fasta
+ hello_codons - report longest ORF in each sequence
+ hello_gff3 - import gff3, output genes as json
+ hello_histogram - descriptive stats and plot a histogram
+ hello_data - something typical of data science
+ hello_sw - Smith-Waterman algorithm
+ hello_dl - deep learning example
+ hello_math - some standard math problems

## Installation ##

How hard is it to install and configure?

### C

+ Mac-10.15.6: gcc aliased to clang 11.0.3
+ Linux-Debian-10.5.0: gcc 8.3.0
+ Linux-Ubuntu-20.04.1:
	+ `sudo apt install gcc` # 9.3.0

### Go

+ Mac-10.15.6:
	+ `brew install go`
+ Linux-Debian-10.5.0:
	+ `root# apt install golang`
+ Linux-Ubuntu-20.04.1:
	+ `sudo apt install golang`

	
### Perl

+ Mac-10.15.6: 5.18
+ Linux-Debian-10.5.0: 5.28
+ Linux-Ubuntu-20.04.1: 5.30

### Python

+ Mac-10.15.6: 2.7, 3.8
+ Linux-Debian-10.5.0: 2.7, 3.7
+ Linux-Ubuntu-20.04.1: 3.8

### Julia

+ Mac-10.15.6:
	+ `brew install cask julia`
	+ took 2 attempts
+ Linux-Debian-10.5.0:
	+ `root# apt install julia`
+ Linux-Ubuntu-20.04.1:
	+ `sudo apt install julia`

### Rust

+ Mac-10.15.6:
	+ `brew install rust`
	+ Some non-fatal errors
	+ Long build time, many dependencies
+ Linux-Debian-10.5.0:
	+ `root# apt install rustc`
+ Linux-Ubuntu-20.04.1:
	+ `sudo apt install rustc`

## Distribution ##

+ How do you get other peoples' libraries?
+ How hard is it for other people to use your programs and libraries?
+ What are the documentation standards?
+ What are the unit testing standards?




