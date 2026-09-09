## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__got`
- `__KLDDATA.__init`
- `__KLDDATA.__const`
- `__KLDDATA.__static_ifinit`

```diff

 13432.1.9.0.0
-  __TEXT.__text: 0x905730
+  __TEXT.__text: 0x9055f0
   __TEXT.__const: 0x45780
   __TEXT.__os_log: 0x4c2eb
-  __TEXT.__cstring: 0xa336d
+  __TEXT.__cstring: 0xa356d
   __TEXT.__eh_frame: 0x118
   __DATA.__lock_grp: 0x16578
   __DATA.__data: 0x82bc0
   __DATA.__percpu: 0x3e28
   __DATA.__common: 0x1bddb0
   __DATA.__bss: 0x86930
-  __DATA_CONST.__const: 0xa3498
+  __DATA_CONST.__const: 0xa3948
   __DATA_CONST.__kalloc_type: 0x17b00
   __DATA_CONST.__kalloc_var: 0x7ee0
   __DATA_CONST.__assert: 0xe4c

   __DATA_CONST.__mod_init_func: 0x2c8
   __DATA_CONST.__got: 0x58
   __KLDDATA.__init: 0x11d40
-  __KLDDATA.__init_entry_set: 0x142e0
+  __KLDDATA.__init_entry_set: 0x14448
   __KLDDATA.__const: 0x9470
   __KLDDATA.__static_ifinit: 0x8
   __KLDDATA.__cstring: 0x79c

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4e2fa
-  __CTF.__ctf: 0xd3d96
+  __CTF.__ctf: 0xd3d95
   Functions: 27124
   Symbols:   24380
-  CStrings:  26045
+  CStrings:  26059
 
Functions:
~ sub_ffffff800023a8b0 : 2672 -> 2560
~ _kern_dump_should_enforce_encryption : 240 -> 128
~ _kdp_core_init : 1584 -> 1488
~ _vm_shared_region_enter : 6848 -> 6880
~ sub_ffffff80007d1b10 -> sub_ffffff80007d19f0 : 4576 -> 4544
~ sub_ffffff8000b0770e -> sub_ffffff8000b075ce : 7239922 -> 7240242
CStrings:
+ "Bitmap of other perflevels sharing L2 cache"
+ "Currently active logical CPUs in perflevel2"
+ "Currently active physical CPUs in perflevel2"
+ "L1 data cache size in bytes for perflevel2"
+ "L1 instruction cache size in bytes for perflevel2"
+ "L2 cache size in bytes for perflevel2"
+ "L3 cache size in bytes for perflevel2"
+ "Maximum number of logical CPUs in perflevel2"
+ "Maximum number of physical CPUs in perflevel2"
+ "Name of perflevel2"
+ "Number of CPUs sharing an L2 cache for perflevel2"
+ "Number of CPUs sharing an L3 cache for perflevel2"
+ "Perf level 2 topology and cache geometry parameters"
+ "perflevel2"
+ "sharesl2"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
