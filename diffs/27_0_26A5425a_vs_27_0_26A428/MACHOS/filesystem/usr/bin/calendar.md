## calendar

> `/usr/bin/calendar`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 45.0.0.0.0
-  __TEXT.__text: 0x76d8
+  __TEXT.__text: 0x7688
   __TEXT.__auth_stubs: 0x540
   __TEXT.__const: 0x210
   __TEXT.__cstring: 0xc03
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x188
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__auth_got: 0x2a0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000f68 : 28 -> 16
~ sub_100000f84 -> sub_100000f78 : 8136 -> 8128
~ sub_100003e8c -> sub_100003e78 : 216 -> 192
~ sub_100003f64 -> sub_100003f38 : 204 -> 192
~ sub_100004030 -> sub_100003ff8 : 152 -> 140
~ sub_10000614c -> sub_100006108 : 132 -> 120
```
