## parl

> `/usr/bin/parl`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 105.0.0.0.0
-  __TEXT.__text: 0x277c
+  __TEXT.__text: 0x2730
   __TEXT.__auth_stubs: 0x260
   __TEXT.__cstring: 0x2c2
   __TEXT.__const: 0x20
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x130
   __DATA_CONST.__got: 0x18
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__data: 0x6155d3
+  __DATA.__data: 0x629606
   __DATA.__bss: 0x8001
   - /usr/lib/libSystem.B.dylib
   Functions: 21
Functions:
~ _par_dirname : 264 -> 252
~ _par_init_env : 336 -> 324
~ _par_setup_libpath : 204 -> 192
~ _par_mktmpdir : 1612 -> 1600
~ _par_cleanup : 152 -> 140
~ _sha_update : 260 -> 256
~ _sha_final : 444 -> 432
```
