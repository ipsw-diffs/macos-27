## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/Versions/A/HealthKit`

```diff

-7027.2.12.0.0
-  __TEXT.__text: 0x45d840
-  __TEXT.__objc_methlist: 0x32c3c
-  __TEXT.__cstring: 0x38242
+7027.2.19.0.0
+  __TEXT.__text: 0x45e080
+  __TEXT.__objc_methlist: 0x32c54
+  __TEXT.__cstring: 0x38252
   __TEXT.__const: 0x1ffec
   __TEXT.__oslogstring: 0xd193
-  __TEXT.__gcc_except_tab: 0x3b5c
+  __TEXT.__gcc_except_tab: 0x3b68
   __TEXT.__dlopen_cstrs: 0x1a8
   __TEXT.__ustring: 0x1d0
   __TEXT.__constg_swiftt: 0x6afc

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x8c68
+  __DATA_CONST.__const: 0x8c70
   __DATA_CONST.__objc_classlist: 0x1d10
   __DATA_CONST.__objc_catlist: 0x1b8
   __DATA_CONST.__objc_protolist: 0x828
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x120b8
+  __DATA_CONST.__objc_selrefs: 0x120d0
   __DATA_CONST.__objc_protorefs: 0x648
   __DATA_CONST.__objc_superrefs: 0x18a8
   __DATA_CONST.__objc_arraydata: 0x69d8
   __DATA_CONST.__got: 0x1ea8
-  __AUTH_CONST.__const: 0x1f359
-  __AUTH_CONST.__cfstring: 0x34540
+  __AUTH_CONST.__const: 0x1f339
+  __AUTH_CONST.__cfstring: 0x34560
   __AUTH_CONST.__objc_const: 0x564a8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x47b8

   __AUTH.__data: 0x3da0
   __DATA.__objc_ivar: 0x3160
   __DATA.__data: 0x10cb0
-  __DATA.__bss: 0x3c0a0
+  __DATA.__bss: 0x3c090
   __DATA.__common: 0x7b8
   __DATA_DIRTY.__objc_data: 0x2860
   __DATA_DIRTY.__data: 0x308

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 32202
-  Symbols:   42624
-  CStrings:  8919
+  Functions: 32200
+  Symbols:   42627
+  CStrings:  8920
 
Symbols:
+ +[HKChartableCodedQuantity _valueFromCodedQuantity:inUnit:unitNameResolver:error:]
+ +[HKChartableCodedQuantity chartableCodedQuantityWithCodings:originalCodedQuantity:originalRangeLowCodedQuantity:originalRangeHighCodedQuantity:unitNameResolver:error:]
+ -[HKCodedValue chartableCodedQuantitySetWithDate:unitNameResolver:error:]
+ -[HKCodedValue chartableCodedQuantityWithUnitNameResolver:error:]
+ ___73-[HKCodedValue chartableCodedQuantitySetWithDate:unitNameResolver:error:]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e22_16?0"HKCodedValue"8l
+ _kHKPairedWatchOverride
+ _objc_msgSend$_valueFromCodedQuantity:inUnit:unitNameResolver:error:
+ _objc_msgSend$chartableCodedQuantitySetWithDate:unitNameResolver:error:
+ _objc_msgSend$chartableCodedQuantityWithCodings:originalCodedQuantity:originalRangeLowCodedQuantity:originalRangeHighCodedQuantity:unitNameResolver:error:
+ _objc_msgSend$chartableCodedQuantityWithUnitNameResolver:error:
- +[HKChartableCodedQuantity _valueFromCodedQuantity:inUnit:error:]
- +[HKChartableCodedQuantity converter]
- ___37+[HKChartableCodedQuantity converter]_block_invoke
- ___56-[HKCodedValue chartableCodedQuantitySetWithDate:error:]_block_invoke
- ___block_descriptor_40_e8_32r_e22_16?0"HKCodedValue"8l
- _objc_msgSend$_valueFromCodedQuantity:inUnit:error:
- _objc_msgSend$chartableCodedQuantityWithCodings:originalCodedQuantity:originalRangeLowCodedQuantity:originalRangeHighCodedQuantity:error:
- _objc_msgSend$chartableCodedQuantityWithError:
CStrings:
+ "kHKPairedWatchOverride"
```
