## applesingle

> `/usr/bin/applesingle`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA.__data`

```diff

-187.0.0.0.0
-  __TEXT.__text: 0x2e80
+188.0.0.0.0
+  __TEXT.__text: 0x2ef4
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__const: 0x20
-  __TEXT.__cstring: 0xec5
+  __TEXT.__cstring: 0xeed
   __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__auth_got: 0x168
   __DATA_CONST.__got: 0x28

   - /usr/lib/libSystem.B.dylib
   Functions: 20
   Symbols:   52
-  CStrings:  94
+  CStrings:  95
 
Functions:
~ sub_1000006b0 : 9468 -> 9580
~ sub_100002ee0 -> sub_100002f50 : 340 -> 344
CStrings:
+ "%s: no file name or fork data in \"%s\".\n"
+ "02:34:06"
+ "Nov 10 2026"
- "01:39:11"
- "Oct 29 2026"
```
