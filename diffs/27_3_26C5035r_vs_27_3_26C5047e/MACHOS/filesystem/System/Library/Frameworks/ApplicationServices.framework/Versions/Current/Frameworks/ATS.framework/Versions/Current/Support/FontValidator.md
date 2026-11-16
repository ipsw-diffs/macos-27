## FontValidator

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/Current/Frameworks/ATS.framework/Versions/Current/Support/FontValidator`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-604.0.0.0.0
-  __TEXT.__text: 0x24950
+605.0.0.0.0
+  __TEXT.__text: 0x24b28
   __TEXT.__auth_stubs: 0xe10
   __TEXT.__objc_stubs: 0xf40
   __TEXT.__init_offsets: 0x4

   __TEXT.__objc_classname: 0x6f
   __TEXT.__objc_methname: 0xef0
   __TEXT.__objc_methtype: 0xf6
-  __TEXT.__unwind_info: 0x7a8
+  __TEXT.__unwind_info: 0x7b0
   __DATA_CONST.__const: 0x1260
   __DATA_CONST.__cfstring: 0x3b60
   __DATA_CONST.__objc_classlist: 0x38

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 414
-  Symbols:   1247
+  Functions: 415
+  Symbols:   1248
   CStrings:  1114
 
Symbols:
+ __ZN12_GLOBAL__N_113IsCFF2TopDICTEPKhm
Functions:
~ _Type1SniffURL : 1076 -> 1092
~ _Type1ValidateURL : 3116 -> 3144
~ __ZN12_GLOBAL__N_18Type1Doc8ValidateEv : 14272 -> 14300
+ __ZN12_GLOBAL__N_113IsCFF2TopDICTEPKhm
CStrings:
+ "3.5.3"
- "3.5.2"
```
