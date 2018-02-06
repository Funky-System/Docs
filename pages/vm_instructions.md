---
title: Funky VM Instructions
keywords: minimachine
tags: [vm, bytecode, instructions]
sidebar: sidebar
permalink: /vm_instructions.html
toc: false
datatable: true
summary: This table will help you get an overview of all instructions that are supported in Funky Bytecode.
---

## Bytecode instructions

Opcode  | Instruction       | Description                       | Category
------- | -----------       | --------------------------------- | --------
0x00    | `nop`             | No-operation: do nothing          | Basic
0x01    | `halt`            | Halt execution                    | Basic
0x02    | `trap` _int_      | Invoke VM special routines        | Basic
0x03    | `int`             | Halt execution                    | Basic
0x04    | `break`           | Halt execution                    | Basic
0x05    | `link`            | Halt execution                    | Basic
0x10    | `ld.int` _int_    | Halt execution                    | Basic
0x11    | `ld.uint` _uint_  | Halt execution                    | Basic
0x12    | `ld.float`_float_ | Halt execution                    | Basic
0x13    | `ld.str` _string_ | Halt execution                    | Basic
0x14    | `ld.map`          | Halt execution                    | Basic
0x15    | `ld.local` _int_  | Halt execution                    | Basic
0x16    | `ld.reg` _%reg_   | Halt execution                    | Basic
0x17    | `ld.stack` _int_  | Halt execution                    | Basic
0x18    | `ld.sref` _int_   | Halt execution                    | Basic
0x1A    | `ld.lref` _int_   | Halt execution                    | Basic
0x1B    | `ld.ref` _int_    | Halt execution                    | Basic
0x1C    | `pop`             | Halt execution                    | Basic
0x1D    | `st.reg` _%reg_   | Halt execution                    | Basic
0x19    | `st.stack` _int_  | Halt execution                    | Basic
0x1E    | `st.local` _int_  | Halt execution                    | Basic
0x1F    | `st.ref` _int_    | Halt execution                    | Basic
0x77    | `st.addr` _int_   | Halt execution                    | Basic
0x78    | `swp`             | Swap top two items on the stack   | Basic

