## kernel.release.t6030

> `/System/Library/Kernels/kernel.release.t6030`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

 13432.41.4.0.0
   __TEXT.__const: 0x37c10
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa6f4f
+  __TEXT.__cstring: 0xa6f0e
   __TEXT.__os_log: 0x42597
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310

   __DATA_CONST.__const: 0x130448
   __DATA_CONST.__assert: 0xfa0
   __DATA_CONST.__kalloc_var: 0x7ee0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9a5390
+  __TEXT_EXEC.__text: 0x9a50b8
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6ae0

   __DATA.__lock_grp: 0x17248
   __DATA.__percpu: 0x78d0
   __DATA.__common: 0x8cea0
-  __DATA.__bss: 0x49138
+  __DATA.__bss: 0x49128
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x5089d
-  __CTF.__ctf: 0x102f11
-  Functions: 22982
+  __CTF.__ctf: 0x102f10
+  Functions: 22980
   Symbols:   6951
-  CStrings:  26096
+  CStrings:  26095
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
