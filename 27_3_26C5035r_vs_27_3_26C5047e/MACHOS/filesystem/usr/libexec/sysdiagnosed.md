## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1598.60.5.0.0
-  __TEXT.__text: 0x5ad6c
+1598.60.7.0.0
+  __TEXT.__text: 0x5aec4
   __TEXT.__auth_stubs: 0x1460
-  __TEXT.__objc_stubs: 0x8420
+  __TEXT.__objc_stubs: 0x8440
   __TEXT.__objc_methlist: 0x38cc
   __TEXT.__const: 0x1e4
-  __TEXT.__cstring: 0xeaa8
+  __TEXT.__cstring: 0xeae6
   __TEXT.__oslogstring: 0x734b
   __TEXT.__objc_classname: 0x322
   __TEXT.__objc_methtype: 0xf1c
   __TEXT.__gcc_except_tab: 0xd58
-  __TEXT.__objc_methname: 0x8ff1
+  __TEXT.__objc_methname: 0x900e
   __TEXT.__unwind_info: 0x1480
   __DATA_CONST.__const: 0x1150
-  __DATA_CONST.__cfstring: 0x10380
+  __DATA_CONST.__cfstring: 0x10420
   __DATA_CONST.__objc_classlist: 0x120
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x88
-  __DATA_CONST.__objc_arraydata: 0x12f0
+  __DATA_CONST.__objc_arraydata: 0x1300
   __DATA_CONST.__objc_arrayobj: 0x1890
   __DATA_CONST.__objc_intobj: 0x228
   __DATA_CONST.__auth_got: 0xa40
   __DATA_CONST.__got: 0x3c0
   __DATA_CONST.__auth_ptr: 0x60
   __DATA.__objc_const: 0x4bb8
-  __DATA.__objc_selrefs: 0x2450
+  __DATA.__objc_selrefs: 0x2458
   __DATA.__objc_ivar: 0x41c
   __DATA.__objc_data: 0xb40
   __DATA.__data: 0x278

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 1629
+  Functions: 1630
   Symbols:   441
-  CStrings:  4398
+  CStrings:  4404
 
CStrings:
+ "--output"
+ "/.nofollow"
+ "/.nofollow/"
+ "/.resolve/"
+ "RegionalSafetyAnalysisAssetVersion"
+ "logs/RegionalSafetyAnalysis"
+ "rangeOfString:options:range:"
- "/private/var/mobile/tmp/com.apple.audiomxd/"
```
