## kernel.release.t6000

> `/System/Library/Kernels/kernel.release.t6000`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

 13432.1.9.0.0
-  __TEXT.__const: 0x37ac0
+  __TEXT.__const: 0x37b20
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa4e25
+  __TEXT.__cstring: 0xa50a7
   __TEXT.__os_log: 0x420fe
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x7254
   __DATA_CONST.__sdt: 0xeb80
   __DATA_CONST.__kalloc_type: 0x17b40
-  __DATA_CONST.__const: 0x12ff28
+  __DATA_CONST.__const: 0x1307f8
   __DATA_CONST.__assert: 0xe88
   __DATA_CONST.__kalloc_var: 0x7ee0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9bb05c
+  __TEXT_EXEC.__text: 0x9bb884
   __TEXT_EXEC.__hib_text: 0x19a0
   __TEXT_EXEC.__commpage_text: 0x334
-  __TEXT_BOOT_EXEC.__bootcode: 0x6a2c
+  __TEXT_BOOT_EXEC.__bootcode: 0x6b74
   __KLD.__text: 0xb118
   __LASTDATA_CONST.__mod_init_func: 0x8
   __LAST.__pinst: 0x8

   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
-  __DATA.__data: 0x20b89
+  __DATA.__data: 0x20bc9
   __DATA.__lock_grp: 0x16fb8
   __DATA.__percpu: 0x7890
-  __DATA.__common: 0x9f4f0
-  __DATA.__bss: 0x49708
+  __DATA.__common: 0x9f530
+  __DATA.__bss: 0x49808
   __HIBDATA.__data: 0x41
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__static_if: 0xf10
+  __BOOTDATA.__static_if: 0xfe0
   __BOOTDATA.__init: 0x180d8
-  __BOOTDATA.__init_entry_set: 0x14520
+  __BOOTDATA.__init_entry_set: 0x14778
   __BOOTDATA.__static_ifinit: 0x28
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x507dd
-  __CTF.__ctf: 0x112391
-  Functions: 22920
+  __CTF.__ctf: 0x112409
+  Functions: 22923
   Symbols:   6947
-  CStrings:  25869
+  CStrings:  25894
 
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
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
