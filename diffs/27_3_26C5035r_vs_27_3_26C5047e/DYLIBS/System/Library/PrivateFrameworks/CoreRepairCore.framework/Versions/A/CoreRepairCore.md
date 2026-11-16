## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/Versions/A/CoreRepairCore`

```diff

-1307.60.20.0.0
-  __TEXT.__text: 0x85c78
-  __TEXT.__objc_methlist: 0x472c
-  __TEXT.__const: 0x886
-  __TEXT.__cstring: 0x6982
-  __TEXT.__oslogstring: 0xa0f1
+1307.60.23.0.0
+  __TEXT.__text: 0x8693c
+  __TEXT.__objc_methlist: 0x477c
+  __TEXT.__const: 0x896
+  __TEXT.__cstring: 0x69e9
+  __TEXT.__oslogstring: 0xa2eb
   __TEXT.__gcc_except_tab: 0x1984
-  __TEXT.__unwind_info: 0x2308
+  __TEXT.__unwind_info: 0x2348
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x268
-  __DATA_CONST.__objc_classlist: 0x2e0
+  __DATA_CONST.__const: 0x290
+  __DATA_CONST.__objc_classlist: 0x2e8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2988
+  __DATA_CONST.__objc_selrefs: 0x29b8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x1c8
   __DATA_CONST.__objc_arraydata: 0x7b8
-  __DATA_CONST.__got: 0x578
-  __AUTH_CONST.__const: 0x1310
-  __AUTH_CONST.__cfstring: 0x7980
-  __AUTH_CONST.__objc_const: 0x6740
+  __DATA_CONST.__got: 0x580
+  __AUTH_CONST.__const: 0x1400
+  __AUTH_CONST.__cfstring: 0x7a40
+  __AUTH_CONST.__objc_const: 0x67d8
   __AUTH_CONST.__objc_intobj: 0x3a8
   __AUTH_CONST.__objc_dictobj: 0x320
   __AUTH_CONST.__objc_arrayobj: 0x528
-  __AUTH_CONST.__auth_got: 0xad8
-  __AUTH.__objc_data: 0x1400
+  __AUTH_CONST.__auth_got: 0xae0
+  __AUTH.__objc_data: 0x1450
   __DATA.__objc_ivar: 0x3bc
   __DATA.__data: 0x658
   __DATA.__bss: 0x1d8

   - /usr/lib/libauthinstall.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2601
-  Symbols:   617
-  CStrings:  2363
+  Functions: 2620
+  Symbols:   621
+  CStrings:  2376
 
Symbols:
+ _CRShipModeDDMStateWireValue
+ _IOPSShippingChargeLimitGetState
+ _OBJC_CLASS_$_CRShipModeDDMStatus
+ _OBJC_METACLASS_$_CRShipModeDDMStatus
CStrings:
+ "CRShipModeBatteryClient: fetch ship-mode undo-in-progress plumbing failure: %s"
+ "CRShipModeDDMStatus: fetchShipModeResumeState failed (attempt %lu/%lu): %{public}s"
+ "CRShipModeDDMStatus: fetchShipModeUndoInProgress failed (attempt %lu/%lu): %{public}s"
+ "CRShipModeDDMStatus: no ship-charge-limit state (0x%08x); ship mode not applicable"
+ "CRShipModeDDMStatus: reporting state=%{public}@"
+ "CRShipModeDDMStatus: shipped=%d chainInFlight=%d chainFailed=%d cannotShip=%d undoInProgress=%d → reporting state=%{public}@"
+ "Unable to get ClaimDataClasses"
+ "normal"
+ "notApplicable"
+ "preparing"
+ "reverting"
+ "shippable"
+ "v20@?0B8@\"NSError\"12"
```
