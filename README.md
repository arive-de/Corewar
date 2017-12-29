# Corewar

Corewar is a programming game created by D. G. Jones and A. K. Dewdney in which two or more battle programs (called "warriors") compete for control of a virtual computer. These battle programs are written in an abstract assembly language called Redcode.

# The Team

• Alix Rive-Decaillot ~ arive-de

• Gaspard Schaetz ~ ggschaetz

• Manon Kantzer ~ makantzer

• Yohann Benoit ~ hindikah

## How to use it ?

First you'll need to write a .s file with a set of assembly instructions. You can just use one of the many warriors in the ./champs directory. Then you'll have to compile it using the asm binary. Then just execute the corewar binary with your warrior(s) as arguments.

This was the final project of the Algorithm branch.

# Compiling and running

`make full`

### Asm

`./asm ./ASM/champs/*.s`

### Corewar

`./corewar ./champs/*.cor ...`

• -d N	: Dumps memory after N cycles then exits

• -n N	: Choose the order in which the warriors will play

• -v 31  N	: All verbosity

