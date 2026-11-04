## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/Versions/A/CoreUI`

```diff

 1011.4.0.0.0
-  __TEXT.__text: 0x125664
+  __TEXT.__text: 0x125f00
   __TEXT.__delay_stubs: 0x140
   __TEXT.__delay_helper: 0xa4
   __TEXT.__objc_methlist: 0xb618
   __TEXT.__const: 0xa858
   __TEXT.__gcc_except_tab: 0x30bc
-  __TEXT.__cstring: 0x2c162
+  __TEXT.__cstring: 0x2c1c2
   __TEXT.__oslogstring: 0x250
   __TEXT.__swift5_typeref: 0x3b0
   __TEXT.__swift5_capture: 0x168

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1b69d0
+  __DATA_CONST.__const: 0x1b69d8
   __DATA_CONST.__objc_classlist: 0x5b8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x80

   __DATA_CONST.__objc_arraydata: 0x17f0
   __DATA_CONST.__got: 0xc88
   __AUTH_CONST.__const: 0x50b8
-  __AUTH_CONST.__cfstring: 0x15080
+  __AUTH_CONST.__cfstring: 0x15120
   __AUTH_CONST.__objc_const: 0x11248
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x1578

   __AUTH_CONST.__objc_arrayobj: 0x4c8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1960
+  __AUTH_CONST.__auth_got: 0x1978
   __AUTH.__objc_data: 0x1fe8
   __AUTH.__data: 0x160
   __DATA.__objc_ivar: 0xdd0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 6745
-  Symbols:   13906
-  CStrings:  6229
+  Symbols:   13909
+  CStrings:  6234
 
Symbols:
+ _CGPathCreateMutableCopy
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
Functions:
~ -[CUINamedRenditionInfo attributePresent:withValue:] : 1552 -> 1600
~ -[CUINamedRenditionInfo incrementIndex:inValues:forAttribute:] : 3192 -> 3288
~ -[CUINamedRenditionInfo setAttributePresent:withValue:] : 1548 -> 1596
~ -[CUINamedRenditionInfo decrementValue:forAttribute:] : 3120 -> 3216
~ _CUICreateDisplayShapeAndComputeCornerRadius : 2084 -> 2664
~ ___CUISubtypeFromIndex : 344 -> 384
~ -[CUINamedRenditionInfo clearAttributePresent:withValue:] : 1548 -> 1596
~ +[CUINamedRenditionInfo subtypeToIndexWithPlatform:andInput:] : 1288 -> 1336
~ _CUIValidateIdiomSubtypes : 644 -> 660
~ sub_18f0966a0 -> sub_18f1fca9c : 908 -> 2092
CStrings:
+ "inner-bezel-island"
+ "island-outer-bottom"
+ "island-outer-left"
+ "island-outer-right"
+ "island-outer-top"
```
