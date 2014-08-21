Chapter 12: Fundamental Data Types
==================================

Checklist: Fundamental Data
---------------------------

### Numbers in General

- Does the code avoid magic numbers?

- Does the code anticipate divide-by-zero errors?

- Are type conversions obvious?

- If variables with two different types are used in the same expression, will the expression be evaluated as you intend it to be?

- Does the code avoid mixed-type comparisons?

- Does the program compile with no warnings?

### Integers

- Do expressions that use integer division work the way they’re meant to?

- Do integer expressions avoid integer-overflow problems?

### Floating-Point Numbers

- Does the code avoid additions and subtractions on numbers with greatly different magnitudes?

- Does the code systematically prevent rounding errors?

- Does the code avoid comparing floating-point numbers for equality?

### Characters and Strings

- Does the code avoid magic characters and strings?

- Are references to strings free of off-by-one errors?

- Does C code treat string pointers and character arrays differently?

- Does C code follow the convention of declaring strings to be length constant+1?

- Does C code use arrays of characters rather than pointers, when appropriate?

- Does C code initialize strings to NULLs to avoid endless strings?

- Does C code use strncpy() rather than strcpy()? And strncat() and strncmp()?

### Boolean Variables

- Does the program use additional boolean variables to document conditional tests?

- Does the program use additional boolean variables to simplify conditional tests?


Footnote
--------
This material is copied and/or adapted from the Code Complete 2 Website at cc2e.com. This material is Copyright (c) 1993-2004 Steven C. McConnell. Permission is hereby given to copy, adapt, and distribute this material as long as this notice is included on all such materials and the materials are not sold, licensed, or otherwise distributed for commercial gain.
