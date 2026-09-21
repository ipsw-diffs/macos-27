## Activity Monitor

> `/System/Applications/Utilities/Activity Monitor.app/Contents/MacOS/Activity Monitor`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

   __TEXT.__text: 0x441d8
   __TEXT.__auth_stubs: 0xe10
   __TEXT.__objc_stubs: 0xcb60
-  __TEXT.__objc_methlist: 0x6360
+  __TEXT.__objc_methlist: 0x6368
   __TEXT.__const: 0x248
   __TEXT.__gcc_except_tab: 0xcac
-  __TEXT.__objc_methname: 0x12a9d
+  __TEXT.__objc_methname: 0x12ac7
   __TEXT.__cstring: 0x359e
   __TEXT.__objc_classname: 0x6dc
   __TEXT.__objc_methtype: 0x309f

   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__auth_got: 0x718
   __DATA_CONST.__got: 0x528
-  __DATA.__objc_const: 0xb3e0
-  __DATA.__objc_selrefs: 0x46e8
+  __DATA.__objc_const: 0xb3e8
+  __DATA.__objc_selrefs: 0x46f0
   __DATA.__objc_ivar: 0xae0
   __DATA.__objc_data: 0x14f0
   __DATA.__data: 0x7f0

   - /usr/lib/libsystemstats.dylib
   Functions: 2014
   Symbols:   416
-  CStrings:  4554
+  CStrings:  4555
 
CStrings:
+ "manager:didStartAbsorbingCache:withError:"
```
