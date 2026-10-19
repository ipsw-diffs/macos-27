## kernel.release.t8112

> `/System/Library/Kernels/kernel.release.t8112`

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
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__CTF.__ctf`

```diff

 13432.41.4.0.0
   __TEXT.__const: 0x37c00
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa58b7
+  __TEXT.__cstring: 0xa5876
   __TEXT.__os_log: 0x42597
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310

   __DATA_CONST.__const: 0x12ffb8
   __DATA_CONST.__assert: 0xfa0
   __DATA_CONST.__kalloc_var: 0x7ee0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9a3820
+  __TEXT_EXEC.__text: 0x9a3548
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6ae0

   __DATA.__lock_grp: 0x16fb8
   __DATA.__percpu: 0x78b0
   __DATA.__common: 0x8c8a0
-  __DATA.__bss: 0x49128
+  __DATA.__bss: 0x49118
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108

   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x5089d
   __CTF.__ctf: 0x107d90
-  Functions: 22953
+  Functions: 22951
   Symbols:   6951
-  CStrings:  25959
+  CStrings:  25958
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
