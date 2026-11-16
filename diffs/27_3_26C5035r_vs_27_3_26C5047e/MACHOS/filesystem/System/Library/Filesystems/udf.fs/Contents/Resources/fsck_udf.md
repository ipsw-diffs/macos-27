## fsck_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/fsck_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-331.60.2.0.0
-  __TEXT.__text: 0x10e54
+331.60.4.0.0
+  __TEXT.__text: 0x10eb0
   __TEXT.__auth_stubs: 0x420
   __TEXT.__init_offsets: 0x8
-  __TEXT.__gcc_except_tab: 0x608
-  __TEXT.__cstring: 0x36d6
+  __TEXT.__gcc_except_tab: 0x600
+  __TEXT.__cstring: 0x3787
   __TEXT.__const: 0x4f5c
   __TEXT.__unwind_info: 0x6c8
   __DATA_CONST.__const: 0x348

   - /usr/lib/libc++.1.dylib
   Functions: 366
   Symbols:   84
-  CStrings:  395
+  CStrings:  399
 
Functions:
~ sub_10000a104 : 836 -> 928
CStrings:
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
```
