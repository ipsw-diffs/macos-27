## kernel.release.t8140

> `/System/Library/Kernels/kernel.release.t8140`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__exclaves_bt`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

 13432.1.9.0.0
-  __TEXT.__const: 0x38740
+  __TEXT.__const: 0x387a0
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xb3d61
+  __TEXT.__cstring: 0xb3fff
   __TEXT.__os_log: 0x422be
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x7254
   __DATA_CONST.__sdt: 0xeb80
   __DATA_CONST.__kalloc_type: 0x18300
-  __DATA_CONST.__const: 0x137df0
+  __DATA_CONST.__const: 0x1386c0
   __DATA_CONST.__assert: 0xf78
   __DATA_CONST.__kalloc_var: 0x85c0
   __DATA_CONST.__exclaves_bt: 0xc0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9e432c
+  __TEXT_EXEC.__text: 0x9e4de0
   __TEXT_EXEC.__hib_text: 0x19cc
   __TEXT_EXEC.__commpage_text: 0x334
-  __TEXT_BOOT_EXEC.__bootcode: 0x69d4
+  __TEXT_BOOT_EXEC.__bootcode: 0x6b04
   __KLD.__text: 0xb040
   __LASTDATA_CONST.__mod_init_func: 0x8
   __LAST.__pinst: 0x8

   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
-  __DATA.__data: 0x20b51
+  __DATA.__data: 0x20b91
   __DATA.__lock_grp: 0x179f8
   __DATA.__percpu: 0x78b0
-  __DATA.__common: 0x8c4c0
-  __DATA.__bss: 0xab4e0
+  __DATA.__common: 0x8c500
+  __DATA.__bss: 0xab580
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__static_if: 0x10a0
+  __BOOTDATA.__static_if: 0x1170
   __BOOTDATA.__init: 0x181e0
-  __BOOTDATA.__init_entry_set: 0x147d8
+  __BOOTDATA.__init_entry_set: 0x14a30
   __BOOTDATA.__static_ifinit: 0x20
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x507dd
-  __CTF.__ctf: 0x10652e
-  Functions: 23726
+  __CTF.__ctf: 0x106567
+  Functions: 23732
   Symbols:   6947
-  CStrings:  26676
+  CStrings:  26702
 
CStrings:
+ "Bitmap of other perflevels sharing L2 cache"
+ "Currently active logical CPUs in perflevel2"
+ "Currently active physical CPUs in perflevel2"
+ "FEAT_CPA"
+ "FEAT_CPA2"
+ "FEAT_FAMINMAX"
+ "FEAT_FP8"
+ "FEAT_FPMR"
+ "FEAT_LUT"
+ "FEAT_PAuth_LR"
+ "FEAT_SME_F8F16"
+ "FEAT_SME_F8F32"
+ "FEAT_SME_LUTv2"
+ "L1 data cache size in bytes for perflevel2"
+ "L1 instruction cache size in bytes for perflevel2"
+ "L2 cache size in bytes for perflevel2"
+ "L3 cache size in bytes for perflevel2"
+ "LR"
+ "Maximum number of logical CPUs in perflevel2"
+ "Maximum number of physical CPUs in perflevel2"
+ "Name of perflevel2"
+ "Number of CPUs sharing an L2 cache for perflevel2"
+ "Number of CPUs sharing an L3 cache for perflevel2"
+ "Perf level 2 topology and cache geometry parameters"
+ "perflevel2"
+ "sharesl2"
+ "unknown device state @%s:%d"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
