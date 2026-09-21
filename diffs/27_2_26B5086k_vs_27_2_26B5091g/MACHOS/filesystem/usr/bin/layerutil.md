## layerutil

> `/usr/bin/layerutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1011.2.0.0.0
-  __TEXT.__text: 0xa4344
-  __TEXT.__auth_stubs: 0x2440
+1011.3.0.0.0
+  __TEXT.__text: 0xa4474
+  __TEXT.__auth_stubs: 0x2490
   __TEXT.__objc_stubs: 0xbee0
   __TEXT.__objc_methlist: 0x7dc0
   __TEXT.__const: 0x2c68
-  __TEXT.__gcc_except_tab: 0x1a80
+  __TEXT.__gcc_except_tab: 0x1ab0
   __TEXT.__objc_methname: 0x12293
   __TEXT.__objc_classname: 0x119f
   __TEXT.__objc_methtype: 0x4411
-  __TEXT.__cstring: 0x105b8
+  __TEXT.__cstring: 0x106a8
   __TEXT.__oslogstring: 0x28
   __TEXT.__swift5_typeref: 0x8a
   __TEXT.__swift5_capture: 0x68

   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_proto: 0x10
   __TEXT.__swift5_types: 0x20
-  __TEXT.__unwind_info: 0x3940
+  __TEXT.__unwind_info: 0x3948
   __DATA_CONST.__const: 0x49f0
   __DATA_CONST.__cfstring: 0x4b40
   __DATA_CONST.__objc_classlist: 0x420

   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_arraydata: 0x270
   __DATA_CONST.__objc_arrayobj: 0x168
-  __DATA_CONST.__auth_got: 0x1238
+  __DATA_CONST.__auth_got: 0x1260
   __DATA_CONST.__got: 0x670
   __DATA_CONST.__auth_ptr: 0xb8
   __DATA.__objc_const: 0xc6b8

   __DATA.__objc_data: 0x2940
   __DATA.__data: 0x528
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x858
+  __DATA.__bss: 0x868
   __DATA.__common: 0x10
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/Versions/A/HIServices

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   Functions: 4353
-  Symbols:   782
-  CStrings:  5331
+  Symbols:   787
+  CStrings:  5335
 
Symbols:
+ ___cxa_guard_abort
+ ___cxa_guard_acquire
+ ___cxa_guard_release
+ _newlocale
+ _snprintf_l
Functions:
~ sub_100062e24 : 1040 -> 1144
~ sub_100063234 -> sub_10006329c : 220 -> 216
~ sub_1000807c0 -> sub_100080824 : 172 -> 284
~ sub_1000907f8 -> sub_1000908cc : 1056 -> 1160
~ sub_100090c18 -> sub_100090d54 : 284 -> 272
CStrings:
+ "CoreUI: Deepmap 2.0 block length %zu is smaller than its header"
+ "CoreUI: Deepmap 2.0 compressedBytes %llu exceeds block length %zu"
+ "CoreUI: Deepmap block length %zu is smaller than its header"
+ "CoreUI: Deepmap compressedBytes %llu exceeds block length %zu"
```
