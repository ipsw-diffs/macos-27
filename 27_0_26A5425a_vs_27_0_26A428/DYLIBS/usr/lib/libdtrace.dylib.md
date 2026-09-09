## libdtrace.dylib

> `/usr/lib/libdtrace.dylib`

```diff

 416.0.3.0.0
-  __TEXT.__text: 0x4c8d0
+  __TEXT.__text: 0x4c9a0
   __TEXT.__const: 0x5104
   __TEXT.__cstring: 0x9e9c
-  __TEXT.__oslogstring: 0xbfe
+  __TEXT.__oslogstring: 0xc38
   __TEXT.__unwind_info: 0xa18
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x5b88

   - /usr/lib/libc++.1.dylib
   Functions: 817
   Symbols:   1218
-  CStrings:  2018
+  CStrings:  2019
 
Functions:
~ _dtrace_dof_create : 2320 -> 2340
~ _dt_pid_per_sym : 3792 -> 3936
~ _dt_print_int : 472 -> 476
~ _dt_print_ptr : 80 -> 84
~ _dt_print_array : 820 -> 824
~ _dt_print_ptrauth : 80 -> 84
~ _yyparse : 5704 -> 5716
~ __elf64_shdr : 1812 -> 1800
~ __elf64_prepscn : 280 -> 296
~ __elf32_prepscn : 288 -> 300
~ _elf_strptr : 156 -> 160
~ _init_symtab : 848 -> 844
CStrings:
+ "fasttrap probe creation error: failed to read instruction"
```
