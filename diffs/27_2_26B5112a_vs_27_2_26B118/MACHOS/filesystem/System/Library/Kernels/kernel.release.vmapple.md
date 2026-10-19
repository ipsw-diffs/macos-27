## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`
- `__CTF.__ctf`

```diff

 13432.41.4.0.0
   __TEXT.__const: 0x376c0
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0x9e0a6
+  __TEXT.__cstring: 0x9e065
   __TEXT.__os_log: 0x4222a
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x6b0

   __DATA_CONST.__kalloc_type: 0x17900
   __DATA_CONST.__assert: 0xf50
   __DATA_CONST.__kalloc_var: 0x7da0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d0
   __DATA_CONST.__auth_ptr: 0x10
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x989da8
+  __TEXT_EXEC.__text: 0x989b34
   __TEXT_EXEC.__hib_text: 0x10b8
   __TEXT_EXEC.__commpage_text: 0x334
   __KLD.__text: 0xb118

   __DATA.__lock_grp: 0x16058
   __DATA.__percpu: 0x39d0
   __DATA.__common: 0x89f20
-  __DATA.__bss: 0x49ce0
+  __DATA.__bss: 0x49cd0
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__static_if: 0xd80
   __BOOTDATA.__init: 0x17c68

   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x503f0
   __CTF.__ctf: 0xf9b7e
-  Functions: 22198
+  Functions: 22196
   Symbols:   6929
-  CStrings:  25256
+  CStrings:  25255
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
