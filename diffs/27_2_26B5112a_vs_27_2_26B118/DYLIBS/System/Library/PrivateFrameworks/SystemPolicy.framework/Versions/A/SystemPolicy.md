## SystemPolicy

> `/System/Library/PrivateFrameworks/SystemPolicy.framework/Versions/A/SystemPolicy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 823.40.13.0.0
-  __TEXT.__text: 0x19370
-  __TEXT.__objc_methlist: 0x19f0
-  __TEXT.__const: 0xd8
+  __TEXT.__text: 0x197a4
+  __TEXT.__objc_methlist: 0x19f8
+  __TEXT.__const: 0xe0
   __TEXT.__cstring: 0x1826
   __TEXT.__gcc_except_tab: 0x218
-  __TEXT.__oslogstring: 0x166c
+  __TEXT.__oslogstring: 0x173c
   __TEXT.__dlopen_cstrs: 0x62
-  __TEXT.__unwind_info: 0xab0
+  __TEXT.__unwind_info: 0xac0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfb8
+  __DATA_CONST.__objc_selrefs: 0xfc0
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0x4a0
   __DATA_CONST.__got: 0x2e8
   __AUTH_CONST.__const: 0x930
   __AUTH_CONST.__cfstring: 0x2220
-  __AUTH_CONST.__objc_const: 0x3818
+  __AUTH_CONST.__objc_const: 0x3858
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__auth_got: 0x4c0
-  __DATA.__objc_ivar: 0x2b0
+  __DATA.__objc_ivar: 0x2b8
   __DATA.__data: 0x248
   __DATA.__bss: 0xd0
   __DATA_DIRTY.__objc_data: 0xb40

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 825
-  Symbols:   1815
-  CStrings:  467
+  Functions: 829
+  Symbols:   1818
+  CStrings:  472
 
Symbols:
+ -[PolicyScanTarget openVerifiedDescriptorWithError:]
+ OBJC_IVAR_$_PolicyScanTarget._objectDev
+ OBJC_IVAR_$_PolicyScanTarget._objectIno
CStrings:
+ "Failed to stat target: %s error: %s"
+ "Target identity is not verified on %s: %s"
+ "Target is not the object that was scanned: (%d,%llu) != (%d,%llu), %s"
+ "Unable to open target: %d, %s"
+ "Unable to stat target: %d, %s"
```
