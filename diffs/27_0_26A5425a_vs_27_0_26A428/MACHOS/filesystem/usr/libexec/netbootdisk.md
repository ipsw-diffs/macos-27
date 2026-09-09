## netbootdisk

> `/usr/libexec/netbootdisk`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 557.0.0.0.0
-  __TEXT.__text: 0x2978
+  __TEXT.__text: 0x2948
   __TEXT.__auth_stubs: 0x530
   __TEXT.__const: 0x38
   __TEXT.__cstring: 0x832
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0x260
   __DATA_CONST.__auth_got: 0x298
Functions:
~ sub_10000102c : 384 -> 372
~ sub_1000011ac -> sub_1000011a0 : 352 -> 340
~ sub_100001814 -> sub_1000017fc : 216 -> 204
~ sub_100001e34 -> sub_100001e10 : 128 -> 116
```
