## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/Versions/A/UnifiedAssetFramework`

```diff

-3610.9.1.0.0
-  __TEXT.__text: 0x7de90
-  __TEXT.__objc_methlist: 0x3680
+3610.12.1.0.0
+  __TEXT.__text: 0x7e0d8
+  __TEXT.__objc_methlist: 0x3688
   __TEXT.__const: 0x1a8
   __TEXT.__constg_swiftt: 0x48
   __TEXT.__swift5_typeref: 0x67
   __TEXT.__swift5_reflstr: 0x9
   __TEXT.__swift5_fieldmd: 0x1c
-  __TEXT.__cstring: 0xb79e
-  __TEXT.__oslogstring: 0xf499
+  __TEXT.__cstring: 0xb832
+  __TEXT.__oslogstring: 0xf4ba
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0xe34
   __TEXT.__unwind_info: 0x1640

   __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2648
+  __DATA_CONST.__objc_selrefs: 0x2650
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0x128
   __DATA_CONST.__got: 0x598
   __AUTH_CONST.__const: 0x1d98
-  __AUTH_CONST.__cfstring: 0x5500
-  __AUTH_CONST.__objc_const: 0x4630
+  __AUTH_CONST.__cfstring: 0x5520
+  __AUTH_CONST.__objc_const: 0x4660
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x1e0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x7d8
   __AUTH.__objc_data: 0x98
-  __DATA.__objc_ivar: 0x320
+  __DATA.__objc_ivar: 0x324
   __DATA.__data: 0x298
   __DATA.__bss: 0x40
   __DATA.__common: 0x8

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1523
-  Symbols:   3764
-  CStrings:  2161
+  Functions: 1524
+  Symbols:   3768
+  CStrings:  2165
 
Symbols:
+ +[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:]
+ +[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:]
+ -[UAFOSEligibility isMainlandChina]
+ _OBJC_IVAR_$_UAFOSEligibility._isMainlandChina
+ _objc_msgSend$_eligibilityCountryPolicyStringIsChina:
+ _objc_msgSend$_emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:
+ _objc_msgSend$isMainlandChina
+ _objc_msgSend$logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:
- +[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]
- +[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]
- _objc_msgSend$_emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:
- _objc_msgSend$logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:
CStrings:
+ "%s No country policy value found"
+ "+[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:]"
+ "+[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:error:]"
+ "-[UAFOSEligibility _updateCountryPolicy:]"
+ "EligibleAppleIntelligenceIsMainlandChina"
+ "OS_ELIGIBILITY_CONTEXT_COUNTRY_POLICY"
+ "com.apple.MobileAsset.CN.Guardrail"
- "+[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]"
- "+[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]"
- "CAReportingAssetSet"
```
