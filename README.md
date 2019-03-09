# gdb-load-symbols
Automates the process of 'add-symbol-file [path] [text] [[-s section_name address]...]'

## Syntax
```
load-symbols [Arbitrary address in ELF] [Path to ELF]
```

## Import to gdb
```
(gdb) source [path-to-load-symbols]
```
