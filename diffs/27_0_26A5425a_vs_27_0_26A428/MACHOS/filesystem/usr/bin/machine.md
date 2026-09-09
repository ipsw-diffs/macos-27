## machine

> `/usr/bin/machine`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x1240
+  __TEXT.__text: 0x1260
   __TEXT.__auth_stubs: 0x420
-  __TEXT.__const: 0x77
-  __TEXT.__cstring: 0x7f4
-  __TEXT.__unwind_info: 0x78
-  __DATA_CONST.__const: 0xc0
+  __TEXT.__const: 0x7f
+  __TEXT.__cstring: 0x807
+  __TEXT.__unwind_info: 0x88
+  __DATA_CONST.__const: 0x138
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__auth_got: 0x210
   __DATA_CONST.__got: 0x28

   - /usr/lib/libSystem.B.dylib
   Functions: 10
   Symbols:   75
-  CStrings:  70
+  CStrings:  72
 
Functions:
~ sub_100001270 : 392 -> 416
~ sub_1000016a4 -> sub_1000016bc : 588 -> 596
CStrings:
+ "arm64.x1"
+ "arm64e.x1"
```
