## UniversalAccessCore

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Frameworks/UniversalAccessCore.framework/Versions/A/UniversalAccessCore`

```diff

-780.3.6.0.0
-  __TEXT.__text: 0x2c87c
-  __TEXT.__objc_methlist: 0x2280
-  __TEXT.__const: 0x2fc
-  __TEXT.__dlopen_cstrs: 0x4dc
-  __TEXT.__gcc_except_tab: 0x270
-  __TEXT.__cstring: 0x2e36
-  __TEXT.__oslogstring: 0x12d7
-  __TEXT.__unwind_info: 0x10d8
+780.3.11.0.1
+  __TEXT.__text: 0x2e340
+  __TEXT.__objc_methlist: 0x2390
+  __TEXT.__const: 0x314
+  __TEXT.__dlopen_cstrs: 0x546
+  __TEXT.__gcc_except_tab: 0x280
+  __TEXT.__cstring: 0x3044
+  __TEXT.__oslogstring: 0x1345
+  __TEXT.__unwind_info: 0x1180
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x408
-  __DATA_CONST.__objc_classlist: 0xb8
+  __DATA_CONST.__const: 0x478
+  __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1ba8
+  __DATA_CONST.__objc_selrefs: 0x1c68
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x70
-  __DATA_CONST.__objc_arraydata: 0x1d8
-  __DATA_CONST.__got: 0xd10
-  __AUTH_CONST.__const: 0xa00
-  __AUTH_CONST.__cfstring: 0x22c0
-  __AUTH_CONST.__objc_const: 0x2848
-  __AUTH_CONST.__objc_intobj: 0x780
+  __DATA_CONST.__objc_arraydata: 0x1e8
+  __DATA_CONST.__got: 0xd60
+  __AUTH_CONST.__const: 0xa80
+  __AUTH_CONST.__cfstring: 0x2440
+  __AUTH_CONST.__objc_const: 0x29a0
+  __AUTH_CONST.__objc_intobj: 0x7c8
   __AUTH_CONST.__objc_arrayobj: 0x138
   __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH_CONST.__auth_got: 0x6b8
-  __AUTH.__objc_data: 0x500
-  __DATA.__objc_ivar: 0xf4
+  __AUTH_CONST.__auth_got: 0x6e8
+  __AUTH.__objc_data: 0x550
+  __AUTH.__data: 0x8
+  __DATA.__objc_ivar: 0xf8
   __DATA.__data: 0x2d0
-  __DATA.__bss: 0x2a8
+  __DATA.__bss: 0x2f8
   __DATA_DIRTY.__objc_data: 0x230
   __DATA_DIRTY.__bss: 0xb0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libUniversalAccess.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1343
-  Symbols:   3021
-  CStrings:  534
+  Functions: 1391
+  Symbols:   3113
+  CStrings:  559
 
Symbols:
+ +[UASidecarTouchDisableManager sharedInstance]
+ +[UASpeechSettings keyPathsForValuesAffectingSpeakItemOnTouch]
+ +[UAZoomSettings keyPathsForValuesAffectingSidecarModalZoomEnabled]
+ +[UAZoomSettings keyPathsForValuesAffectingSidecarOneFingerPanEnabled]
+ +[UAZoomSettings keyPathsForValuesAffectingSidecarPanningSensitivity]
+ -[UASidecarTouchDisableManager setSidecarTouchInputDisabled:]
+ -[UASidecarTouchDisableManager sidecarTouchInputDisabled]
+ -[UASpeechSettings setSpeakItemOnTouch:]
+ -[UASpeechSettings speakItemOnTouch]
+ -[UAZoomSettings _setSidecarModalZoomPreviouslyEnabled:]
+ -[UAZoomSettings _sidecarModalZoomPreviouslyEnabled]
+ -[UAZoomSettings canSetSidecarGestureZoomEnabled]
+ -[UAZoomSettings canSetSidecarModalZoomEnabled]
+ -[UAZoomSettings canSetSidecarOneFingerPanEnabled]
+ -[UAZoomSettings canSetSidecarPanningSensitivity]
+ -[UAZoomSettings setSidecarModalZoomEnabled:]
+ -[UAZoomSettings setSidecarOneFingerPanEnabled:]
+ -[UAZoomSettings setSidecarPanningSensitivity:]
+ -[UAZoomSettings sidecarModalZoomEnabled]
+ -[UAZoomSettings sidecarOneFingerPanEnabled]
+ -[UAZoomSettings sidecarPanningSensitivity]
+ GCC_except_table1000
+ GCC_except_table1116
+ GCC_except_table1122
+ GCC_except_table1128
+ GCC_except_table1129
+ GCC_except_table1301
+ GCC_except_table190
+ GCC_except_table256
+ GCC_except_table258
+ GCC_except_table262
+ GCC_except_table273
+ GCC_except_table282
+ GCC_except_table296
+ GCC_except_table370
+ GCC_except_table397
+ GCC_except_table711
+ GCC_except_table720
+ GCC_except_table725
+ GCC_except_table732
+ GCC_except_table737
+ GCC_except_table749
+ GCC_except_table787
+ GCC_except_table835
+ GCC_except_table837
+ GCC_except_table929
+ _AXRuntimeCheck_AssistiveTouchSidecar
+ _AXRuntimeCheck_SidecarQFATouchAccommodations
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_UASidecarTouchDisableManager
+ _OBJC_IVAR_$_UAZoomSettings._canSetSidecarGestureZoomEnabled
+ _OBJC_METACLASS_$_UASidecarTouchDisableManager
+ _SkyLightLibrary.sLib
+ _SkyLightLibrary.sOnce
+ _UAAXFeatureIDAssistiveTouch
+ _UAAXFeatureIDTouchAccommodations
+ _UADomainSidecarSettingsDidChangeNotification
+ _UAHoverColorSetSidecarModalEnabled
+ _UAHoverColorSidecarModalEnabledKey
+ _UAHoverColorSidecarModalIsEnabled
+ _UAHoverTextSetSidecarModalEnabled
+ _UAHoverTextSetSidecarScrollSpeed
+ _UAHoverTextSidecarModalEnabledKey
+ _UAHoverTextSidecarModalIsEnabled
+ _UAHoverTextSidecarScrollSpeed
+ _UAHoverTextSidecarScrollSpeedKey
+ _UAPreferencesSynchronize
+ _UASidecarModalZoomEnabledKey
+ _UASidecarModalZoomIsEnabled
+ _UASidecarModalZoomPreviouslyEnabledKey
+ _UASidecarModalZoomSetEnabled
+ _UASidecarModalZoomSetWasPreviouslyEnabled
+ _UASidecarModalZoomWasPreviouslyEnabled
+ _UASidecarTouchDisableActive
+ _UASidecarTouchDisableApply
+ _UASidecarTouchDisableLog
+ _UASidecarTouchDisableLog._log
+ _UASidecarTouchDisableLog.onceToken
+ _UASidecarTouchDisableRequestApply
+ _UASidecarTouchDisableSuspend
+ _UASidecarTouchDisableToggleAccessibilityIdentifier
+ _UASidecarTouchInputDisabledKey
+ _UASpeechSettingsSpeakItemOnTouchKey
+ _UATouchSettingsSupported
+ __AXSAssistiveTouchEnabled
+ __OBJC_$_CLASS_METHODS_UASidecarTouchDisableManager
+ __OBJC_$_INSTANCE_METHODS_UASidecarTouchDisableManager
+ __OBJC_$_PROP_LIST_UASidecarTouchDisableManager
+ __OBJC_CLASS_RO_$_UASidecarTouchDisableManager
+ __OBJC_METACLASS_RO_$_UASidecarTouchDisableManager
+ __SetTouchEnabled
+ __TouchEnablementIsAvailable.available
+ __TouchEnablementIsAvailable.onceToken
+ ___46+[UASidecarTouchDisableManager sharedInstance]_block_invoke
+ ___61-[UASidecarTouchDisableManager setSidecarTouchInputDisabled:]_block_invoke
+ ___SkyLightLibrary_block_invoke
+ ___UASidecarTouchDisableLog_block_invoke
+ ____TouchEnablementIsAvailable_block_invoke
+ ___block_descriptor_32_e35_B24?0"NSNumber"8"NSDictionary"16l
+ ___block_descriptor_33_e19_"NSDictionary"8?0l
+ _dlopen
+ _initSLSSetAccessibilityTouchEnabled
+ _objc_msgSend$_setSidecarModalZoomPreviouslyEnabled:
+ _objc_msgSend$_sidecarModalZoomPreviouslyEnabled
+ _objc_msgSend$assistiveTouchEnabled
+ _objc_msgSend$canSetSidecarModalZoomEnabled
+ _objc_msgSend$isCurrentSessionOnConsole
+ _objc_msgSend$setAssistiveTouchEnabled:
+ _objc_msgSend$setSidecarModalZoomEnabled:
+ _objc_msgSend$setTouchAccommodationsEnabled:
+ _objc_msgSend$sidecarModalZoomEnabled
+ _objc_msgSend$sidecarOneFingerPanEnabled
+ _objc_msgSend$sidecarPanningSensitivity
+ _objc_msgSend$sidecarTouchInputDisabled
+ _objc_msgSend$speakItemOnTouch
+ _softLinkSLSSetAccessibilityTouchEnabled
- GCC_except_table1084
- GCC_except_table1090
- GCC_except_table1096
- GCC_except_table1097
- GCC_except_table1253
- GCC_except_table180
- GCC_except_table246
- GCC_except_table248
- GCC_except_table252
- GCC_except_table263
- GCC_except_table272
- GCC_except_table286
- GCC_except_table358
- GCC_except_table385
- GCC_except_table684
- GCC_except_table693
- GCC_except_table698
- GCC_except_table705
- GCC_except_table710
- GCC_except_table721
- GCC_except_table759
- GCC_except_table807
- GCC_except_table897
- GCC_except_table968
CStrings:
+ "/System/Library/PrivateFrameworks/SkyLight.framework/SkyLight"
+ "@\"NSDictionary\"8@?0"
+ "AX_SIDECAR_TOUCH_DISABLED"
+ "Localizable-Sidecar"
+ "NO"
+ "SLSSetAccessibilityTouchEnabled"
+ "SidecarTouchDisable"
+ "YES"
+ "asking universalaccessd to apply"
+ "closeViewSidecarModalZoomEnabled"
+ "closeViewSidecarModalZoomPreviouslyEnabled"
+ "closeViewSidecarOneFingerPanEnabled"
+ "closeViewSidecarPanningSensitivity"
+ "com.apple.accessibility.sidecar.touchInputDisabled"
+ "disabled"
+ "feature.assistiveTouch"
+ "hand.point.up.left"
+ "hand.point.up.left.fill"
+ "preference off"
+ "preference on"
+ "service unavailable"
+ "session off console"
+ "set touch enabled=%{public}s (%{public}s) err=%{public}d"
+ "softlink:r:path:/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities"
+ "speakItemOnTouch"
```
