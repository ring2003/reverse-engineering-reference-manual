## *<p align='center'>.instruction-sets</p>*

__Interface Between Software And Hardware__
* An instruction set provides an interface for programmer to instruct a re-programmable (general-purpose) computer on how to interact with its underlying hardware while abstracting away the implementation details of those hardware components. Although the idea of a general purpose computer was conceived in 1837 by Charles Babbage, a working general purpose computer (ENIAC) was not built until 1945. Earlier computers such as Atanasoff–Berry (used to solve linear equations) and Bombe (used for deciphering Enigma encrypted messages) are special-purpose computers that are hard-wired to perform a specific task, which means that you are unable to utilize their underlying hardware to do anything else. An instruction set is the gateway to utilize a general purpose computer's flexibility, allowing one to create programs aim at accomplishing varying tasks, from space shuttle guidance to weather prediction. It presents that gateway in human-readable mnemonics (English words), where each mnemonic has an unique set of zeros and ones that corresponds to an operation a CPU with the same instruction set implementation would know how to perform. An instruction set is said to be Turing Complete if it can perform any computational task. The followings instruction sets I will talk about are all Turing Complete. On a funny note, it turns out that [one instruction from x86 is enough to be Turing Complete](https://www.cl.cam.ac.uk/~sd601/papers/mov.pdf).

---
### *<p align='center'> section overview </p>*
---
* [x86](x86.md)
  * [Registers](x86.md#-registers-)
  * [How EIP Can Be Updated](x86.md#-how-eip-can-be-updated-)
  * [Assembly to Machine Code Is Not One-To-One](x86.md#-assembly-to-machine-code-is-not-one-to-one-)
  * [Lost Of Type Information](x86.md#-lost-of-type-information-)
  * [Floating Point Arithmetic](x86.md#-floating-point-arithmetic-)
  * [Variable-Length Instruction](x86.md#-variable-length-instruction-)
  * [Commonly Used But Hard To Remember x86 Instructions With Side Effects](x86.md#-commonly-used-but-hard-to-remember-x86-instructions-with-side-effects-)
* [x86-64](x86-64.md)
  * [Canonical Form](x86-64.md#-canonical-form-)
  * [Registers](x86-64.md#-registers-)
  * [Calling Conventions](x86-64.md#-calling-conventions-)
  * [Exception Handling](x86-64.md#-exception-handling-)
  * [Other Notable Differences From x86](x86-64.md#-other-notable-differences-from-x86-)
* [ARM](ARM.md)
  * [ARM Version](ARM.md#-arm-version-)
  * [Privileges Separation](ARM.md#-privileges-separation-)
  * [Registers](ARM.md#-registers-)
  * [Load/Store Instructions](ARM.md#-loadstore-instructions-)
  * [Instructions For Function Invocation](ARM.md#-instructions-for-function-invocation-)
  * [Conditional Execution](ARM.md#-conditional-execution-)
  * [Importance of Barrel Shifter](ARM.md#-importance-of-barrel-shifter-)

---
### *<p align='center'> further readings </p>*
---
* [Azeria Labs](https://azeria-labs.com/): from ARM assembly to ARM exploitation. If you want to learn about ARM, this is it 

#
<p align='center'><a href="/contents/tools/tools.md">.tools</a> <~ <a href="/README.md#table-of-contents">RERM</a> ~> <a href="/contents/languages/languages.md">.languages</a></p>
