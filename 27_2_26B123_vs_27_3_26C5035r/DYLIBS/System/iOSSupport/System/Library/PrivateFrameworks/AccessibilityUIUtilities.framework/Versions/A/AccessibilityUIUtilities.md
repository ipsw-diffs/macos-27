## AccessibilityUIUtilities

> `/System/iOSSupport/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/Versions/A/AccessibilityUIUtilities`

```diff

-3245.8.6.2.0
-  __TEXT.__text: 0x33480
-  __TEXT.__objc_methlist: 0x3124
+3245.8.14.0.0
+  __TEXT.__text: 0x33a20
+  __TEXT.__objc_methlist: 0x3174
   __TEXT.__dlopen_cstrs: 0x156
   __TEXT.__const: 0x9e8
   __TEXT.__constg_swiftt: 0x730

   __TEXT.__swift5_fieldmd: 0x214
   __TEXT.__swift5_proto: 0x38
   __TEXT.__swift5_types: 0x40
-  __TEXT.__cstring: 0x31af
+  __TEXT.__cstring: 0x31b2
   __TEXT.__swift5_assocty: 0xc8
   __TEXT.__swift5_capture: 0x138
-  __TEXT.__oslogstring: 0x95f
+  __TEXT.__oslogstring: 0x988
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x44
   __TEXT.__gcc_except_tab: 0x2f4
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x1240
+  __TEXT.__unwind_info: 0x1248
   __TEXT.__eh_frame: 0x330
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__const: 0x8d0
   __DATA_CONST.__objc_classlist: 0x1d8
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x80
+  __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2b80
+  __DATA_CONST.__objc_selrefs: 0x2be8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x100
   __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0xa60
+  __DATA_CONST.__got: 0xa88
   __AUTH_CONST.__const: 0x808
-  __AUTH_CONST.__cfstring: 0x37e0
-  __AUTH_CONST.__objc_const: 0x4dc8
+  __AUTH_CONST.__cfstring: 0x3800
+  __AUTH_CONST.__objc_const: 0x4e20
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0xf10
+  __AUTH_CONST.__auth_got: 0xf20
   __AUTH.__objc_data: 0x1130
   __AUTH.__data: 0x488
-  __DATA.__objc_ivar: 0x294
-  __DATA.__data: 0x970
+  __DATA.__objc_ivar: 0x298
+  __DATA.__data: 0x9d0
   __DATA.__bss: 0x850
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1e0

   - /System/Library/PrivateFrameworks/AXAssetLoader.framework/Versions/A/AXAssetLoader
   - /System/Library/PrivateFrameworks/AXCoreUtilities.framework/Versions/A/AXCoreUtilities
   - /System/Library/PrivateFrameworks/AXRuntime.framework/Versions/A/AXRuntime
+  - /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Versions/A/AccessibilitySharedSupport
   - /System/Library/PrivateFrameworks/AccessibilityUtilities.framework/Versions/A/AccessibilityUtilities
   - /System/Library/PrivateFrameworks/AppSupport.framework/Versions/A/AppSupport
   - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1378
-  Symbols:   3660
-  CStrings:  576
+  Functions: 1383
+  Symbols:   3689
+  CStrings:  578
 
Symbols:
+ -[AXUIFloatingViewPresenter _updateAvoidanceForMagicPose:]
+ -[AXUIFloatingViewPresenter followsHingePose]
+ -[AXUIFloatingViewPresenter hingePoseMonitor:didUpdateMagicPose:]
+ -[AXUIFloatingViewPresenter setFollowsHingePose:]
+ GCC_except_table435
+ GCC_except_table558
+ GCC_except_table559
+ GCC_except_table560
+ GCC_except_table621
+ GCC_except_table758
+ GCC_except_table899
+ GCC_except_table916
+ GCC_except_table941
+ _AXHingeFoldAxisForMagicPose
+ _AXLogUI
+ _AXUIDisplayConfigurationForDisplayID
+ _AXUIScreenForDisplayIDWithFallback
+ _OBJC_CLASS_$_AXHingePoseMonitor
+ _OBJC_CLASS_$_CADisplay
+ _OBJC_CLASS_$_FBSDisplayConfiguration
+ _OBJC_IVAR_$_AXUIFloatingViewPresenter._followsHingePose
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AXHingePoseObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AXHingePoseObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AXHingePoseObserver
+ __OBJC_CLASS_PROTOCOLS_$_AXUIFloatingViewPresenter
+ __OBJC_LABEL_PROTOCOL_$_AXHingePoseObserver
+ __OBJC_PROTOCOL_$_AXHingePoseObserver
+ ___58-[AXUIFloatingViewPresenter _updateAvoidanceForMagicPose:]_block_invoke
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
+ _objc_msgSend$_isEmbeddedScreen
+ _objc_msgSend$_updateAvoidanceForMagicPose:
+ _objc_msgSend$addObserver:
+ _objc_msgSend$displayId
+ _objc_msgSend$displays
+ _objc_msgSend$initWithCADisplay:
+ _objc_msgSend$isAvailable
+ _objc_msgSend$isIncoming
+ _objc_msgSend$isScreening
+ _objc_msgSend$sharedMonitor
- -[AXUIFloatingViewPresenter _avoidanceRegionDidChange:]
- GCC_except_table433
- GCC_except_table553
- GCC_except_table554
- GCC_except_table555
- GCC_except_table616
- GCC_except_table753
- GCC_except_table894
- GCC_except_table911
- GCC_except_table936
- ___55-[AXUIFloatingViewPresenter _avoidanceRegionDidChange:]_block_invoke
CStrings:
+ "Answering call being screened, status: %lu"
+ "Floating view fold avoidance: %{public}@"
+ "horizontal"
+ "vertical"
- "AXFloatingUIAvoidanceRegionDidChangeNotification"
- "isVertical"
```
