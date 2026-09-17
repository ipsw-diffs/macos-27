## AccessibilityPlatformTranslation

> `/System/Library/PrivateFrameworks/AccessibilityPlatformTranslation.framework/Versions/A/AccessibilityPlatformTranslation`

```diff

-587.0.0.0.0
-  __TEXT.__text: 0x24968
+591.4.0.0.0
+  __TEXT.__text: 0x24a58
   __TEXT.__objc_methlist: 0x185c
   __TEXT.__const: 0x618
   __TEXT.__dlopen_cstrs: 0xca

   __DATA_CONST.__objc_selrefs: 0x1348
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x4b8
-  __DATA_CONST.__got: 0x818
+  __DATA_CONST.__got: 0x820
   __AUTH_CONST.__const: 0xae0
   __AUTH_CONST.__cfstring: 0x3360
   __AUTH_CONST.__objc_const: 0x17a8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 622
-  Symbols:   1901
+  Symbols:   1903
   CStrings:  539
 
Symbols:
+ _NSAccessibilityIncrementorRole
+ __AXUIElementCopyElementAtPositionInHostedCoordinatesWithParams
Functions:
~ sub_1deae72e8 -> sub_1df9892e8 : 84 -> 88
~ -[AXPMacPlatformElement accessibilityAttributeNames] : 2272 -> 2352
~ -[AXPMacPlatformElement accessibilityActionNames] : 968 -> 992
~ -[AXPMacPlatformElement _convertTranslatorResponse:forAttribute:] : 588 -> 600
~ -[AXPTranslator_iOS _processValueAttributeRequest:error:axpAttribute:useAttributes:] : 460 -> 464
~ -[AXPTranslator_iOS _processRoleAttributeRequest:traits:error:] : 1084 -> 1136
~ -[AXPTranslator_iOS processHitTest:] : 1132 -> 1196
```
