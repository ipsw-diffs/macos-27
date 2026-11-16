## mount_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/mount_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-331.60.2.0.0
-  __TEXT.__text: 0x9f6c
+331.60.4.0.0
+  __TEXT.__text: 0x9fc8
   __TEXT.__auth_stubs: 0x3d0
-  __TEXT.__cstring: 0x1142
-  __TEXT.__gcc_except_tab: 0x304
+  __TEXT.__cstring: 0x11f3
+  __TEXT.__gcc_except_tab: 0x2fc
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x458
   __DATA_CONST.__const: 0x348

   - /usr/lib/libutil.dylib
   Functions: 247
   Symbols:   78
-  CStrings:  152
+  CStrings:  156
 
Functions:
~ sub_10000946c : 836 -> 928
CStrings:
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
```
