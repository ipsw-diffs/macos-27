## kernel.release.t8140

> `/System/Library/Kernels/kernel.release.t8140`

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
- `__CTF.__ctf`

```diff

 13432.41.4.0.0
   __TEXT.__const: 0x38850
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xb4caa
+  __TEXT.__cstring: 0xb4c69
   __TEXT.__os_log: 0x4278b
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310

   __DATA_CONST.__assert: 0x1130
   __DATA_CONST.__kalloc_var: 0x8750
   __DATA_CONST.__exclaves_bt: 0xc0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9e9da0
+  __TEXT_EXEC.__text: 0x9e9af4
   __TEXT_EXEC.__hib_text: 0x19cc
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6b04

   __DATA.__lock_grp: 0x17b40
   __DATA.__percpu: 0x78b0
   __DATA.__common: 0x8c5e0
-  __DATA.__bss: 0xab690
+  __DATA.__bss: 0xab680
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108

   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x5089d
   __CTF.__ctf: 0x109075
-  Functions: 23786
+  Functions: 23784
   Symbols:   6951
-  CStrings:  26780
+  CStrings:  26779
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
