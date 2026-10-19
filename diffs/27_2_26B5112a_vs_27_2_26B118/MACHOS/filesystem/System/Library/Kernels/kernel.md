## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__mod_init_func`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

 13432.41.4.0.0
-  __TEXT.__text: 0x90ac00
+  __TEXT.__text: 0x90aaa0
   __TEXT.__const: 0x45830
   __TEXT.__os_log: 0x4c81b
-  __TEXT.__cstring: 0xa3acd
+  __TEXT.__cstring: 0xa3a8d
   __TEXT.__eh_frame: 0x118
   __DATA.__lock_grp: 0x16578
   __DATA.__data: 0x82c00

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4e3ba
-  __CTF.__ctf: 0xd47b6
+  __CTF.__ctf: 0xd47b5
   Functions: 27156
   Symbols:   24400
-  CStrings:  26114
+  CStrings:  26113
 
Functions:
~ sub_ffffff800023a890 : 2672 -> 2560
~ _kern_dump_should_enforce_encryption : 240 -> 128
~ _kdp_core_init : 1584 -> 1488
~ sub_ffffff80007d5de0 -> sub_ffffff80007d5ca0 : 4576 -> 4544
~ sub_ffffff8000b0cbde -> sub_ffffff8000b0ca7e : 7222306 -> 7222658
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
