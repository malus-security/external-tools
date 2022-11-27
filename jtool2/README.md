# jtool2

`jtool` started as an alternative to `otool`.
Along the way, `jtool` absorbed additional Mach-O commands such as
`atos(1)`, `dyldinfo(1)`, `nm(1)`, `segedit(1)`, `pagestuff(1)`,
`strings(1)` , and even `codesign(1)` and the informal `ldid`. Most
importantly, it can be run on a variety of platforms - **OS X, iOS, and
even Linux**, where Apple\'s tools don\'t exist.

But that\'s not all. `jtool` provides many many novel features:

-   in-binary search functionality
-   symbol injection
-   built-in disassembler functionality with (limited but constantly
    improving) emulation capabilities, which already outdo fancy
    commercial GUI disassemblers.
-   Color terminal output, enabled by `JCOLOR=1`

`jtool2` comes as an already compiled binary.
