## uncd

> `/System/Library/CoreServices/uncd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 5027.0.53.0.0
-  __TEXT.__text: 0x3324
+  __TEXT.__text: 0x32dc
   __TEXT.__auth_stubs: 0x3d0
   __TEXT.__const: 0x60
   __TEXT.__oslogstring: 0x10b0
   __TEXT.__cstring: 0x12d
-  __TEXT.__unwind_info: 0xf0
+  __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x2b0
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x1e8
Functions:
~ sub_100001ce4 : 268 -> 256
~ sub_10000208c -> sub_100002080 : 80 -> 68
~ sub_1000020dc -> sub_1000020c4 : 68 -> 56
~ sub_1000028c8 -> sub_1000028a4 : 28 -> 16
~ sub_100002920 -> sub_1000028f0 : 32 -> 20
~ sub_100002964 -> sub_100002928 : 32 -> 20
```
