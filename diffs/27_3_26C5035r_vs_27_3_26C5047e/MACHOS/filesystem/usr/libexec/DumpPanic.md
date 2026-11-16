## DumpPanic

> `/usr/libexec/DumpPanic`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`

```diff

-41.60.2.0.0
-  __TEXT.__text: 0x2ef80
-  __TEXT.__auth_stubs: 0x1070
+41.60.3.0.0
+  __TEXT.__text: 0x2fc14
+  __TEXT.__auth_stubs: 0x10d0
   __TEXT.__objc_stubs: 0x2660
-  __TEXT.__objc_methlist: 0x914
+  __TEXT.__objc_methlist: 0x944
   __TEXT.__cstring: 0x2b3b
   __TEXT.__objc_classname: 0x12c
-  __TEXT.__objc_methtype: 0x56b
-  __TEXT.__objc_methname: 0x20ac
-  __TEXT.__const: 0x2e0
+  __TEXT.__objc_methtype: 0x580
+  __TEXT.__objc_methname: 0x216c
+  __TEXT.__const: 0x3b0
   __TEXT.__gcc_except_tab: 0xc78
-  __TEXT.__oslogstring: 0x5548
-  __TEXT.__constg_swiftt: 0x90
-  __TEXT.__swift5_typeref: 0x8b
-  __TEXT.__swift5_reflstr: 0x27
-  __TEXT.__swift5_fieldmd: 0x34
-  __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0xe48
+  __TEXT.__oslogstring: 0x5578
+  __TEXT.__constg_swiftt: 0xdc
+  __TEXT.__swift5_typeref: 0xc3
+  __TEXT.__swift5_reflstr: 0x60
+  __TEXT.__swift5_fieldmd: 0x4c
+  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_assocty: 0x18
+  __TEXT.__swift5_proto: 0xc
+  __TEXT.__swift5_types: 0x8
+  __TEXT.__unwind_info: 0xe78
   __TEXT.__eh_frame: 0xa0
-  __DATA_CONST.__const: 0x7d8
+  __DATA_CONST.__const: 0x7f8
   __DATA_CONST.__cfstring: 0x22c0
   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_protolist: 0x10

   __DATA_CONST.__objc_arrayobj: 0xc0
   __DATA_CONST.__objc_dictobj: 0xa0
   __DATA_CONST.__objc_intobj: 0x78
-  __DATA_CONST.__auth_got: 0x850
-  __DATA_CONST.__got: 0x278
-  __DATA_CONST.__auth_ptr: 0x68
-  __DATA.__objc_const: 0x1170
-  __DATA.__objc_selrefs: 0xb10
+  __DATA_CONST.__auth_got: 0x880
+  __DATA_CONST.__got: 0x288
+  __DATA_CONST.__auth_ptr: 0xc0
+  __DATA.__objc_const: 0x11d0
+  __DATA.__objc_selrefs: 0xb30
   __DATA.__objc_ivar: 0xb0
-  __DATA.__objc_data: 0x528
-  __DATA.__data: 0x3d8
+  __DATA.__objc_data: 0x568
+  __DATA.__data: 0x400
   __DATA.__common: 0x28
-  __DATA.__bss: 0xaa8
+  __DATA.__bss: 0xc28
   __INFO_FILTER.__disable: 0x0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 932
-  Symbols:   379
-  CStrings:  1400
+  Functions: 949
+  Symbols:   399
+  CStrings:  1409
 
Symbols:
+ _$s15CoreDiagnostics18PanicPatternActionO21collectFullLogArchiveyA2CmFWC
+ _$s8RawValueSYTl
+ _$sBi64_WV
+ _$sSH13_rawHashValue4seedS2i_tFTq
+ _$sSH4hash4intoys6HasherVz_tFTq
+ _$sSH9hashValueSivgTq
+ _$sSHMp
+ _$sSHSQTb
+ _$sSQ2eeoiySbx_xtFZTq
+ _$sSQMp
+ _$sSSN
+ _$sSY8rawValue03RawB0QzvgTq
+ _$sSY8rawValuexSg03RawB0Qz_tcfCTq
+ _$sSYMp
+ _$ss6HasherV5_seedABSi_tcfC
+ _$ss6HasherV8_combineyySuF
+ _$ss6HasherV9_finalizeSiyF
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
CStrings:
+ "Full log archive requested by %s"
+ "No matched panic pattern with a donate type"
+ "Tq,N,VcollectionLevel"
+ "collectionLevel"
+ "collectionPatternUUIDs"
+ "q"
+ "q16@0:8"
+ "setCollectionLevel:"
+ "setCollectionPatternUUIDs:"
+ "v24@0:8q16"
- "Failed to find matched panic pattern"
```
