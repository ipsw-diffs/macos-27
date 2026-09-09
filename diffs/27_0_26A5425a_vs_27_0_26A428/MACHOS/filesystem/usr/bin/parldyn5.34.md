## parldyn5.34

> `/usr/bin/parldyn5.34`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 105.0.0.0.0
-  __TEXT.__text: 0x2a74
+  __TEXT.__text: 0x2a04
   __TEXT.__auth_stubs: 0x380
   __TEXT.__const: 0x30
   __TEXT.__cstring: 0x3d24
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x1c0
   __DATA_CONST.__got: 0x40
Functions:
~ _xs_init : 84 -> 72
~ _par_dirname : 260 -> 248
~ _par_init_env : 336 -> 324
~ _par_setup_libpath : 204 -> 192
~ _par_mktmpdir : 1612 -> 1600
~ _par_cleanup : 152 -> 140
~ sub_100001c90 -> sub_100001c48 : 152 -> 140
~ _sha_update : 260 -> 256
~ _sha_final : 444 -> 432
~ sub_100003108 -> sub_1000030a4 : 72 -> 60
```
