## uuencode

> `/usr/bin/uuencode`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0x2384
+  __TEXT.__text: 0x2354
   __TEXT.__auth_stubs: 0x360
   __TEXT.__const: 0x83
   __TEXT.__cstring: 0x54f
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0x118
   __DATA_CONST.__const: 0x150
   __DATA_CONST.__auth_got: 0x1b0
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100001234 : 200 -> 176
~ sub_100001f50 -> sub_100001f38 : 40 -> 28
~ sub_100001f88 -> sub_100001f64 : 24 -> 12
```
