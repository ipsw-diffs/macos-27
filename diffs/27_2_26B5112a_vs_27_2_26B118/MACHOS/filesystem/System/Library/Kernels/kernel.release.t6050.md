## kernel.release.t6050

> `/System/Library/Kernels/kernel.release.t6050`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__exclaves_bt`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

 13432.41.4.0.0
   __TEXT.__const: 0x38b10
   __TEXT.__copyio_vectors: 0x340
-  __TEXT.__cstring: 0xb7b4e
+  __TEXT.__cstring: 0xb7b0d
   __TEXT.__os_log: 0x42c0b
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310

   __DATA_CONST.__assert: 0x15cc
   __DATA_CONST.__kalloc_var: 0x8890
   __DATA_CONST.__exclaves_bt: 0xc0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0xa01ce8
+  __TEXT_EXEC.__text: 0xa01a3c
   __TEXT_EXEC.__hib_text: 0x19cc
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6aec

   __DATA.__lock_grp: 0x17b40
   __DATA.__percpu: 0x8730
   __DATA.__common: 0xb3960
-  __DATA.__bss: 0xac8f0
+  __DATA.__bss: 0xac8e0
   __HIBDATA.__data: 0x41
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x5089d
-  __CTF.__ctf: 0x10d45e
-  Functions: 23926
+  __CTF.__ctf: 0x10d461
+  Functions: 23924
   Symbols:   6951
-  CStrings:  27108
+  CStrings:  27107
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
