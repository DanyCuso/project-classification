
# Questions and answeres 
## by Daniel Valdés Artiles

### Silver

**Explain** **why** **a** **developer,** **who** **is** **a** **good** **at** **both** **low-level** **and** **high** **level**
**programming** **languages,** **would** **normally** **use** **a** **high-level** **language** **when** **writing** **programs?**

Becuase a high-level programming language is characterized by expressing algorithms in a way appropriate to
human cognitive capacity, rather than the capacity with which machines execute them. These languages ​​allow
the programmer maximum flexibility when it comes to abstracting or being literal.

**What is a machine code?**

Machine code, also known as machine language, is the elemental language of computers.
It is read by the computer's central processing unit (CPU), is composed of digital binary numbers and looks
like a very long sequence of zeros and ones. Ultimately, the source code of every human-readable programming 
language must be translated to machine language by a compiler or an interpreter,
because binary code is the only language that computer hardware can understand.

**Give an example of a high-level language?**

```sh
High-level
```
```sh
_Python, Visual Basic, Delphi, Perl, PHP, ECMAScript, Ruby, C#, Java_
```
### Gold

**Describe three differences between low-level language and high-level languages?**

```sh
High-Level
```
```sh
1. Instead of dealing with registers, memory addresses, and call stacks, high-level languages ​​deal with
variables, arrays, objects, complex arithmetic or Boolean expressions, subroutines and functions, loops,
threads, locks, and other abstract concepts in computing
```
```sh
2. The abstraction penalty is the cost paid by high-level programming techniques for not being able to optimize
performance or use certain hardware because they do not take advantage of certain low-level architectural
resources.
```
```sh
3. high-level languages ​​have few, if any, language elements that are translated directly into the native
opcodes of a machine.
```
```sh
Low-Level
```
```sh
1. Low-level languages are simple, but are considered difficult to use, due to the numerous technical details
which must be remembered.
```
```sh
2. Low-level languages can be converted to machine code without using a compiler or interpreter,
and the resulting code runs directly on the processor.
```
```sh
3. pointers effectively take the place of general purpose registers in low-level languages such as assembly
language or machine code, but may be in available memory.
```

**What does a translator do?**

A translator is a programming language processor that converts a computer program from one language
to another. It takes a program written in source code and converts it into machine code.
It discovers and identifies the error during translation.

**Identify two types of translators that can turn high-level languages into machine code?**


**Compilers:** A compiler takes the source code as a whole and translates it into machine code all in one go.
Once converted, the object code can be run unassisted at any time. This process is called compilation.


**Assembler:** Assemblers are a third type of translator. The purpose of an assembler is to translate 
assembly language into machine code. Whereas compilers and interpreters generate many machine code 
instructions for each high-level instruction, assemblers create one machine code instruction for each 
assembly instruction.

### Platinum

**What is the difference between an interpreter and a compiler?**

*compilers*
 Compiled programs run quickly, since they have already been translated.

*interpreters*
 Instructions are executed as soon as they are translated.

**What is assembly language?**

An assembly language is a type of low-level programming language that is intended to communicate directly with
a computer’s hardware. Unlike machine language, which consists of binary and hexadecimal characters, assembly
languages are designed to be readable by humans.

**A developer is writing a program.**

1. **The program is written in a high-level language and it is then translated into machine code. Describe two differences between high-level language and machine code?**
In machine code instructions are in binary code. High-level code is designed to be read by human programmers. Machine code is to be read/executed by the computer High level code can be portable/translated for different machines Machine code is specific to a particular machine.*

2. **One type of translator is an interpreter.**

1. *Describe how an interpreter translates high-level language programs into machine code?*
An interpreter translates code into machine code, instruction by instruction - the CPU executes each instruction before the interpreter moves on to translate the next instruction. Interpreted code will show an error as soon as it hits a problem, so it is easier to debug than compiled code.

2. *State the name of a different type of translator that can be used to translate high-level code into machine code?*
PHP, Ruby, Python, and JavaScript

