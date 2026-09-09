## clocksyncd

> `/usr/libexec/clocksyncd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1501.7.0.0.0
-  __TEXT.__text: 0x3df28
-  __TEXT.__auth_stubs: 0xbd0
-  __TEXT.__objc_stubs: 0x5a00
+  __TEXT.__text: 0x3d3dc
+  __TEXT.__auth_stubs: 0xbe0
+  __TEXT.__objc_stubs: 0x5a40
   __TEXT.__objc_methlist: 0x36b4
   __TEXT.__const: 0x139
-  __TEXT.__cstring: 0x2a66
-  __TEXT.__oslogstring: 0x5abc
-  __TEXT.__gcc_except_tab: 0x1ab8
-  __TEXT.__objc_methname: 0x919d
+  __TEXT.__cstring: 0x2a97
+  __TEXT.__oslogstring: 0x5ad5
+  __TEXT.__gcc_except_tab: 0x1ac4
+  __TEXT.__objc_methname: 0x91d0
   __TEXT.__objc_classname: 0x508
   __TEXT.__objc_methtype: 0x197a
-  __TEXT.__unwind_info: 0xed8
-  __DATA_CONST.__const: 0xa80
-  __DATA_CONST.__cfstring: 0x1f00
+  __TEXT.__unwind_info: 0x1660
+  __DATA_CONST.__const: 0xaa0
+  __DATA_CONST.__cfstring: 0x1f60
   __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x78

   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x600
-  __DATA_CONST.__got: 0x278
+  __DATA_CONST.__auth_got: 0x608
+  __DATA_CONST.__got: 0x288
   __DATA_CONST.__auth_ptr: 0x110
   __DATA.__objc_const: 0x6a28
-  __DATA.__objc_selrefs: 0x1da0
+  __DATA.__objc_selrefs: 0x1db0
   __DATA.__objc_ivar: 0x514
   __DATA.__objc_data: 0xe10
   __DATA.__data: 0x5a8
-  __DATA.__bss: 0x141
+  __DATA.__bss: 0x151
   __DATA.__common: 0x4
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1567
-  Symbols:   259
-  CStrings:  2470
+  Functions: 1569
+  Symbols:   262
+  CStrings:  2477
 
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_TSMSGService
+ __os_feature_enabled_impl
CStrings:
+ "Genlock"
+ "Localizable"
+ "Localized clockName: %@\n"
+ "bundleForClass:"
+ "fall_2026"
+ "genlock-clock-name"
+ "localizedStringForKey:value:table:"
```
