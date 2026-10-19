## kernel.release.t8103

> `/System/Library/Kernels/kernel.release.t8103`

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
   __TEXT.__const: 0x37bd0
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa5743
+  __TEXT.__cstring: 0xa5702
   __TEXT.__os_log: 0x42597
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310

   __DATA_CONST.__const: 0x12ffc8
   __DATA_CONST.__assert: 0xfa0
   __DATA_CONST.__kalloc_var: 0x7ee0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9bd5ac
+  __TEXT_EXEC.__text: 0x9bd2dc
   __TEXT_EXEC.__hib_text: 0x19a0
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6b74

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x5089d
-  __CTF.__ctf: 0x112e6e
-  Functions: 22947
+  __CTF.__ctf: 0x112e73
+  Functions: 22945
   Symbols:   6951
-  CStrings:  25949
+  CStrings:  25948
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
