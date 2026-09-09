## applesingle

> `/usr/bin/applesingle`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 183.0.0.0.0
-  __TEXT.__text: 0x2e7c
+  __TEXT.__text: 0x2e80
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0xec5
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__auth_got: 0x168
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x160
Functions:
~ sub_1000006b0 : 9452 -> 9468
~ sub_100002d68 -> sub_100002d78 : 88 -> 76
CStrings:
+ "17:34:18"
+ "Aug  8 2026"
- "02:03:38"
- "Aug 10 2026"
```
