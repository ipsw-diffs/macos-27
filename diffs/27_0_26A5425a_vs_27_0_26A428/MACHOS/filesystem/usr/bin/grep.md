## grep

> `/usr/bin/grep`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0x33c4
+  __TEXT.__text: 0x33a4
   __TEXT.__auth_stubs: 0x430
   __TEXT.__const: 0x8a
   __TEXT.__cstring: 0x53d
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x630
   __DATA_CONST.__auth_got: 0x218
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100002f08 : 1636 -> 1628
~ sub_1000035e4 -> sub_1000035dc : 88 -> 76
~ sub_10000363c -> sub_100003628 : 288 -> 276
```
