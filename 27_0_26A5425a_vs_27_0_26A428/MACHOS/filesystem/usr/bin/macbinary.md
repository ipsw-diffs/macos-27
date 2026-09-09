## macbinary

> `/usr/bin/macbinary`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`

```diff

 183.0.0.0.0
-  __TEXT.__text: 0x3154
+  __TEXT.__text: 0x3128
   __TEXT.__auth_stubs: 0x370
   __TEXT.__cstring: 0x11b1
   __TEXT.__const: 0x200
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__auth_got: 0x1b8
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x180
Functions:
~ sub_1000006b0 : 10124 -> 10104
~ sub_10000302c -> sub_100003018 : 88 -> 76
~ sub_1000035cc -> sub_1000035ac : 136 -> 124
CStrings:
+ "17:34:12"
+ "Aug  8 2026"
- "02:03:35"
- "Aug 10 2026"
```
