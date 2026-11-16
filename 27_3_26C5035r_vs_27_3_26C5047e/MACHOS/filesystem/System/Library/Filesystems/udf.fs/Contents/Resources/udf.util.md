## udf.util

> `/System/Library/Filesystems/udf.fs/Contents/Resources/udf.util`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-331.60.2.0.0
-  __TEXT.__text: 0xa1d8
+331.60.4.0.0
+  __TEXT.__text: 0xa234
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0x1056
-  __TEXT.__gcc_except_tab: 0x328
+  __TEXT.__cstring: 0x1107
+  __TEXT.__gcc_except_tab: 0x320
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x478
   __DATA_CONST.__const: 0x360

   - /usr/lib/libc++.1.dylib
   Functions: 255
   Symbols:   70
-  CStrings:  139
+  CStrings:  143
 
Functions:
~ sub_10000945c : 836 -> 928
CStrings:
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
```
