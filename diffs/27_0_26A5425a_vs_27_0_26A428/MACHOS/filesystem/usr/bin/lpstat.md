## lpstat

> `/usr/bin/lpstat`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 532.0.0.0.0
-  __TEXT.__text: 0x366c
+  __TEXT.__text: 0x363c
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__const: 0x8
   __TEXT.__cstring: 0xd89
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__auth_got: 0x178
   __DATA_CONST.__got: 0x20
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_100001d28 : 256 -> 244
~ sub_1000033ac -> sub_1000033a0 : 152 -> 128
~ sub_10000393c -> sub_100003918 : 48 -> 36
```
