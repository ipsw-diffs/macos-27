## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

 13432.1.9.0.0
-  __TEXT.__const: 0x375a0
+  __TEXT.__const: 0x37610
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0x9d7e0
+  __TEXT.__cstring: 0x9da62
   __TEXT.__os_log: 0x41d91
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x6b0
   __DATA_CONST.__hib_const: 0x120
-  __DATA_CONST.__const: 0x1a1a38
+  __DATA_CONST.__const: 0x1a2308
   __DATA_CONST.__sdt_cstring: 0x71f2
   __DATA_CONST.__sdt: 0xeb50
   __DATA_CONST.__kalloc_type: 0x178c0
   __DATA_CONST.__assert: 0xe38
   __DATA_CONST.__kalloc_var: 0x7da0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d0
   __DATA_CONST.__auth_ptr: 0x10
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x984634
+  __TEXT_EXEC.__text: 0x984f78
   __TEXT_EXEC.__hib_text: 0x10b8
   __TEXT_EXEC.__commpage_text: 0x334
   __KLD.__text: 0xb118

   __DATA.__lock_grp: 0x16058
   __DATA.__percpu: 0x39d0
   __DATA.__common: 0x89e20
-  __DATA.__bss: 0x49ab0
+  __DATA.__bss: 0x49ad0
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__static_if: 0xca0
+  __BOOTDATA.__static_if: 0xd70
   __BOOTDATA.__init: 0x17c50
-  __BOOTDATA.__init_entry_set: 0x13d88
+  __BOOTDATA.__init_entry_set: 0x13fe0
   __BOOTDATA.__static_ifinit: 0x20
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x50330
-  __CTF.__ctf: 0xf90e3
-  Functions: 22172
+  __CTF.__ctf: 0xf910e
+  Functions: 22173
   Symbols:   6925
-  CStrings:  25170
+  CStrings:  25195
 
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
