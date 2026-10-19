## HearingModeService_Private

> `/System/Library/PrivateFrameworks/HearingModeService_Private.framework/Versions/A/HearingModeService_Private`

```diff

 41.7.0.0.0
-  __TEXT.__text: 0x13770
-  __TEXT.__objc_methlist: 0xc7c
+  __TEXT.__text: 0x13a38
+  __TEXT.__objc_methlist: 0xc84
   __TEXT.__const: 0x86
   __TEXT.__gcc_except_tab: 0x514
-  __TEXT.__cstring: 0x505f
-  __TEXT.__unwind_info: 0x7a8
+  __TEXT.__cstring: 0x51b6
+  __TEXT.__unwind_info: 0x7c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1f0
+  __DATA_CONST.__const: 0x210
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xea8
+  __DATA_CONST.__objc_selrefs: 0xec0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x30
-  __DATA_CONST.__got: 0x1f8
+  __DATA_CONST.__got: 0x200
   __AUTH_CONST.__const: 0x8e0
   __AUTH_CONST.__cfstring: 0x740
   __AUTH_CONST.__objc_const: 0x14a8

   - /System/Library/PrivateFrameworks/ToneLibrary.framework/Versions/A/ToneLibrary
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 482
-  Symbols:   1076
-  CStrings:  451
+  Functions: 487
+  Symbols:   1081
+  CStrings:  456
 
Symbols:
+ -[HMDeviceManager _hearingAssistEligibleViaTINDomain]
+ GCC_except_table123
+ _OBJC_CLASS_$_OSEligibilityQuery
+ _objc_msgSend$_hearingAssistEligibleViaTINDomain
+ _objc_msgSend$answer
+ _objc_msgSend$initWithDomain:error:
- GCC_except_table122
CStrings:
+ "### OSEligibility TIN domain query failed: %@"
+ "-[HMDeviceManager _hearingAssistEligibleViaTINDomain]"
+ "HearingAidV2 region status upgraded to Supported via OSEligibility TIN domain (HealthKit reported %s)"
+ "HearingAssist region status upgraded to Supported via OSEligibility TIN domain (HealthKit reported %s)"
+ "OSEligibility TIN domain eligible: %d"
```
