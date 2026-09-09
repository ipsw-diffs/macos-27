## binhex

> `/usr/bin/binhex`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`

```diff

 183.0.0.0.0
-  __TEXT.__text: 0x3ccc
+  __TEXT.__text: 0x3cb4
   __TEXT.__auth_stubs: 0x350
   __TEXT.__const: 0x358
   __TEXT.__cstring: 0x10a8
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__auth_got: 0x1a8
   __DATA_CONST.__got: 0x30
   __DATA.__data: 0x3a0
Functions:
~ sub_1000006b0 : 9400 -> 9396
~ sub_100002d4c -> sub_100002d48 : 88 -> 76
~ sub_100003b08 -> sub_100003af8 : 444 -> 440
~ sub_100003cc4 -> sub_100003cb0 : 444 -> 440
CStrings:
+ "17:34:14"
+ "Aug  8 2026"
- "02:03:36"
- "Aug 10 2026"
```
