## trustd

> `/usr/libexec/trustd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-62460.1.2.0.0
-  __TEXT.__text: 0x5d044
+62460.1.3.0.0
+  __TEXT.__text: 0x5c368
   __TEXT.__auth_stubs: 0x2360
-  __TEXT.__objc_stubs: 0x33c0
+  __TEXT.__objc_stubs: 0x33e0
   __TEXT.__objc_methlist: 0xe14
   __TEXT.__const: 0xdd20
   __TEXT.__dlopen_cstrs: 0x54
   __TEXT.__objc_classname: 0x1b4
-  __TEXT.__objc_methname: 0x3020
+  __TEXT.__objc_methname: 0x3036
   __TEXT.__objc_methtype: 0xc6b
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x17

   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0xbe0
-  __TEXT.__cstring: 0x5cc4
+  __TEXT.__cstring: 0x5d16
   __TEXT.__oslogstring: 0x5e5c
-  __TEXT.__unwind_info: 0x1058
-  __DATA_CONST.__const: 0x4308
-  __DATA_CONST.__cfstring: 0x5980
+  __TEXT.__unwind_info: 0x14a8
+  __DATA_CONST.__const: 0x4320
+  __DATA_CONST.__cfstring: 0x59e0
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__got: 0x900
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x1750
-  __DATA.__objc_selrefs: 0xe70
+  __DATA.__objc_selrefs: 0xe78
   __DATA.__objc_ivar: 0xd0
   __DATA.__objc_data: 0x5b8
-  __DATA.__data: 0x428
+  __DATA.__data: 0x430
   __DATA.__bss: 0x538
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 1268
+  Functions: 1270
   Symbols:   876
-  CStrings:  2190
+  CStrings:  2194
 
CStrings:
+ "PhotoRevocationCheck"
+ "com.apple.private.trustd.prl-access"
+ "isPhotoRevoked:error:"
+ "photoID must be 32 bytes"
```
