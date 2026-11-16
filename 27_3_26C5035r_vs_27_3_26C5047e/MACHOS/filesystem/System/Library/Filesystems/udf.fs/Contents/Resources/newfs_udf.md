## newfs_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/newfs_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-331.60.2.0.0
-  __TEXT.__text: 0x12160
+331.60.4.0.0
+  __TEXT.__text: 0x121bc
   __TEXT.__auth_stubs: 0x5c0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x658
-  __TEXT.__gcc_except_tab: 0x390
-  __TEXT.__cstring: 0x39a6
+  __TEXT.__gcc_except_tab: 0x388
+  __TEXT.__cstring: 0x3a57
   __TEXT.__unwind_info: 0x618
   __DATA_CONST.__const: 0x348
   __DATA_CONST.__cfstring: 0x180

   - /usr/lib/libutil.dylib
   Functions: 342
   Symbols:   115
-  CStrings:  332
+  CStrings:  336
 
Functions:
~ sub_100002bf8 : 836 -> 928
CStrings:
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
```
