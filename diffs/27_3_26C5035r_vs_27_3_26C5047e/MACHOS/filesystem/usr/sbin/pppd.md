## pppd

> `/usr/sbin/pppd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-1045.0.0.0.0
-  __TEXT.__text: 0x2e608
+1045.0.0.0.1
+  __TEXT.__text: 0x2e52c
   __TEXT.__auth_stubs: 0x1190
   __TEXT.__const: 0x708
-  __TEXT.__cstring: 0x9be1
+  __TEXT.__cstring: 0x9bc5
   __TEXT.__oslogstring: 0x3
   __TEXT.__unwind_info: 0xa48
   __DATA_CONST.__const: 0x3b8

   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
-  Functions: 636
-  Symbols:   959
-  CStrings:  1488
+  Functions: 635
+  Symbols:   958
+  CStrings:  1485
 
Symbols:
- _options_from_user
Functions:
~ _main : 4580 -> 4572
- _options_from_user
CStrings:
- "%s/%s"
- ".ppprc"
- "init file name"
```
