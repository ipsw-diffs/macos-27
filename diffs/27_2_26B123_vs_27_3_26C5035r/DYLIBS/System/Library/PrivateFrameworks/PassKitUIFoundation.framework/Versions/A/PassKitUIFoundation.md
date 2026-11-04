## PassKitUIFoundation

> `/System/Library/PrivateFrameworks/PassKitUIFoundation.framework/Versions/A/PassKitUIFoundation`

```diff

-1696.2.9.0.0
-  __TEXT.__text: 0x20a40
-  __TEXT.__objc_methlist: 0x196c
+1696.3.3.1.0
+  __TEXT.__text: 0x229f0
+  __TEXT.__objc_methlist: 0x1994
   __TEXT.__const: 0x578
   __TEXT.__gcc_except_tab: 0x5fc
-  __TEXT.__cstring: 0xbda
+  __TEXT.__cstring: 0xe50
   __TEXT.__oslogstring: 0x11da
-  __TEXT.__unwind_info: 0xb30
+  __TEXT.__unwind_info: 0xb68
   __TEXT.__eh_frame: 0x38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x17e0
+  __DATA_CONST.__objc_selrefs: 0x1810
   __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0xa8
-  __DATA_CONST.__got: 0x470
-  __AUTH_CONST.__const: 0xe70
-  __AUTH_CONST.__cfstring: 0xaa0
-  __AUTH_CONST.__objc_const: 0x3ff8
+  __DATA_CONST.__got: 0x480
+  __AUTH_CONST.__const: 0xf30
+  __AUTH_CONST.__cfstring: 0xac0
+  __AUTH_CONST.__objc_const: 0x4110
   __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__auth_got: 0x4d0
-  __AUTH.__objc_data: 0x460
-  __DATA.__objc_ivar: 0x448
+  __AUTH_CONST.__auth_got: 0x4d8
+  __AUTH.__objc_data: 0x4b0
+  __DATA.__objc_ivar: 0x464
   __DATA.__data: 0x360
   __DATA.__bss: 0x31
-  __DATA_DIRTY.__objc_data: 0x4b0
+  __DATA_DIRTY.__objc_data: 0x460
   __DATA_DIRTY.__bss: 0x18
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 740
-  Symbols:   2248
-  CStrings:  203
+  Functions: 754
+  Symbols:   2279
+  CStrings:  208
 
Symbols:
+ -[PKAuthenticatorEvaluationContext _createContextWithExternalizedContext:requireExternalizedContext:]
+ -[PKAuthenticatorSharedRootContext _consumeWithCompletion:reset:useSpringBoard:]
+ -[PKAuthenticatorSharedRootContext accessExternalizedContext:]
+ -[PKAuthenticatorSharedRootContext isPending]
+ -[PKDeviceGlyphLayer .cxx_destruct]
+ -[PKDeviceGlyphLayer _applyEffectivePrimaryColorToQRCodeAnimated:]
+ -[PKDeviceGlyphLayer _endPhoneWiggle]
+ -[PKDeviceGlyphLayer _restartPhoneWiggleIfNecessary]
+ -[PKDeviceGlyphLayer _startPhoneWiggle]
+ -[PKDeviceGlyphLayer dealloc]
+ -[PKDeviceGlyphLayer initWithDeviceType:]
+ -[PKDeviceGlyphLayer initWithFrame:package:]
+ -[PKDeviceGlyphLayer init]
+ -[PKDeviceGlyphLayer isHighlighted]
+ -[PKDeviceGlyphLayer layerDidBecomeVisible:]
+ -[PKDeviceGlyphLayer layoutSublayers]
+ -[PKDeviceGlyphLayer setHighlighted:animated:]
+ -[PKDeviceGlyphLayer setPrimaryColor:animated:]
+ -[PKDeviceGlyphLayer setShowQRCode:]
+ -[PKDeviceGlyphLayer showQRCode]
+ -[PKGlyphView _device:positionDeltaWhileShownFromRotationPercentage:toPercentage:]
+ -[PKGlyphView _device:positionWhileShownWithRotationPercentage:]
+ -[PKGlyphView _device:transformDeltaWhileShownFromRotationPercentage:toPercentage:]
+ -[PKGlyphView _updateCoaching]
+ -[PKGlyphView coachingState]
+ GCC_except_table100
+ GCC_except_table173
+ GCC_except_table185
+ GCC_except_table189
+ GCC_except_table200
+ GCC_except_table204
+ GCC_except_table47
+ GCC_except_table48
+ GCC_except_table52
+ GCC_except_table63
+ GCC_except_table64
+ GCC_except_table68
+ GCC_except_table83
+ GCC_except_table86
+ GCC_except_table93
+ _CGRectStandardize
+ _OBJC_CLASS_$_PKDeviceGlyphLayer
+ _OBJC_IVAR_$_PKAuthenticatorSharedRootContext._counter
+ _OBJC_IVAR_$_PKAuthenticatorSharedRootContext._pending
+ _OBJC_IVAR_$_PKAuthenticatorSharedRootContext._pendingAccessors
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._QRCodeColorFilter
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._QRCodeLayer
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._highlightLayer
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._highlightOffscreenPosition
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._highlightOnscreenPosition
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._highlighted
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._phoneWiggleAnimationKey
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._primaryColor
+ _OBJC_IVAR_$_PKDeviceGlyphLayer._showQRCode
+ _OBJC_IVAR_$_PKGlyphView._coachingState
+ _OBJC_IVAR_$_PKGlyphView._currentDevice
+ _OBJC_IVAR_$_PKGlyphView._currentIntentLayer
+ _OBJC_IVAR_$_PKGlyphView._deviceOrientationAnimationKey
+ _OBJC_IVAR_$_PKGlyphView._primaryDevice
+ _OBJC_IVAR_$_PKGlyphView._primaryIntentLayer
+ _OBJC_IVAR_$_PKGlyphView._secondaryDevice
+ _OBJC_IVAR_$_PKGlyphView._secondaryIntentLayer
+ _OBJC_METACLASS_$_PKDeviceGlyphLayer
+ __OBJC_$_INSTANCE_METHODS_PKDeviceGlyphLayer
+ __OBJC_$_INSTANCE_VARIABLES_PKDeviceGlyphLayer
+ __OBJC_$_PROP_LIST_PKAuthenticatorSharedRootContext
+ __OBJC_$_PROP_LIST_PKDeviceGlyphLayer
+ __OBJC_CLASS_RO_$_PKDeviceGlyphLayer
+ __OBJC_METACLASS_RO_$_PKDeviceGlyphLayer
+ ___29-[PKGlyphView initWithStyle:]_block_invoke
+ ___29-[PKGlyphView initWithStyle:]_block_invoke_2
+ ___30-[PKGlyphView _endPhoneWiggle]_block_invoke_2
+ ___37-[PKDeviceGlyphLayer _endPhoneWiggle]_block_invoke
+ ___39-[PKDeviceGlyphLayer _startPhoneWiggle]_block_invoke
+ ___62-[PKGlyphView _updatePhoneLayoutWithTransitionIndex:animated:]_block_invoke
+ ___80-[PKAuthenticatorSharedRootContext _consumeWithCompletion:reset:useSpringBoard:]_block_invoke
+ ___block_descriptor_40_e8_32s_e241_v128?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8I16{?={?={CGPoint=dd}{CGPoint=dd}}ccd}20{CGPoint=dd}68{CGPoint=dd}84{CGPoint=dd}100"NSURL"116I124l
+ ___block_descriptor_41_e8_32s_e146_v16?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=B{?=II}{?=II{?={CGPoint=dd}{CGPoint=dd}}}}}{CGSize=dd}IICC{CGRect={CGPoint=dd}{CGSize=dd}}}8l
+ ___block_descriptor_57_e8_32s40bs48bs_e142_v16?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8l
+ ___block_descriptor_57_e8_32s40s_e55_"CAAnimation"32?0"NSString"8"NSValue"16"NSValue"24l
+ ___destructor_8_s0_s8_s16
+ ___destructor_8_s0_s8_s16_s24
+ _kCAMediaTimingFunctionEaseInEaseOut
+ _objc_msgSend$_createContextWithExternalizedContext:requireExternalizedContext:
+ _objc_msgSend$_device:positionDeltaWhileShownFromRotationPercentage:toPercentage:
+ _objc_msgSend$_device:positionWhileShownWithRotationPercentage:
+ _objc_msgSend$_device:transformDeltaWhileShownFromRotationPercentage:toPercentage:
+ _objc_msgSend$_updateCoaching
+ _objc_msgSend$glyphViewCoachingStateDidChange:
+ _objc_msgSend$initWithSpringState:
+ _objc_msgSend$isHighlighted
+ _objc_msgSend$numberWithDouble:
+ _objc_msgSend$setAutoreverses:
+ _objc_msgSend$setTiming:
- -[PKAuthenticatorEvaluationContext _createContextWithExternalizedContext:]
- -[PKAuthenticatorSharedRootContext _consumeWithCompletion:reset:]
- -[PKGlyphView _phonePositionDeltaWhileShownFromRotationPercentage:toPercentage:]
- -[PKGlyphView _phonePositionWhileShownWithRotationPercentage:]
- -[PKGlyphView _phoneTransformDeltaWhileShownFromRotationPercentage:toPercentage:]
- -[PKGlyphView _updateUserIntentLayerRotation]
- -[PKPhoneGlyphLayer .cxx_destruct]
- -[PKPhoneGlyphLayer _applyEffectivePrimaryColorToQRCodeAnimated:]
- -[PKPhoneGlyphLayer _endPhoneWiggle]
- -[PKPhoneGlyphLayer _restartPhoneWiggleIfNecessary]
- -[PKPhoneGlyphLayer _startPhoneWiggle]
- -[PKPhoneGlyphLayer dealloc]
- -[PKPhoneGlyphLayer initWithFrame:package:]
- -[PKPhoneGlyphLayer init]
- -[PKPhoneGlyphLayer layerDidBecomeVisible:]
- -[PKPhoneGlyphLayer layoutSublayers]
- -[PKPhoneGlyphLayer setHighlighted:animated:]
- -[PKPhoneGlyphLayer setPrimaryColor:animated:]
- -[PKPhoneGlyphLayer setShowQRCode:]
- -[PKPhoneGlyphLayer showQRCode]
- GCC_except_table171
- GCC_except_table183
- GCC_except_table187
- GCC_except_table198
- GCC_except_table202
- GCC_except_table41
- GCC_except_table46
- GCC_except_table55
- GCC_except_table56
- GCC_except_table58
- GCC_except_table81
- GCC_except_table82
- GCC_except_table84
- GCC_except_table98
- _OBJC_CLASS_$_PKPhoneGlyphLayer
- _OBJC_IVAR_$_PKGlyphView._phoneAspectRatio
- _OBJC_IVAR_$_PKGlyphView._phoneLayer
- _OBJC_IVAR_$_PKGlyphView._userIntentArrowLayer
- _OBJC_IVAR_$_PKGlyphView._userIntentDeviceLayer
- _OBJC_IVAR_$_PKGlyphView._userIntentLayer
- _OBJC_IVAR_$_PKPhoneGlyphLayer._QRCodeColorFilter
- _OBJC_IVAR_$_PKPhoneGlyphLayer._QRCodeLayer
- _OBJC_IVAR_$_PKPhoneGlyphLayer._highlightLayer
- _OBJC_IVAR_$_PKPhoneGlyphLayer._highlightOffscreenPosition
- _OBJC_IVAR_$_PKPhoneGlyphLayer._highlightOnscreenPosition
- _OBJC_IVAR_$_PKPhoneGlyphLayer._phoneWiggleAnimationKey
- _OBJC_IVAR_$_PKPhoneGlyphLayer._primaryColor
- _OBJC_IVAR_$_PKPhoneGlyphLayer._showQRCode
- _OBJC_METACLASS_$_PKPhoneGlyphLayer
- __OBJC_$_INSTANCE_METHODS_PKPhoneGlyphLayer
- __OBJC_$_INSTANCE_VARIABLES_PKPhoneGlyphLayer
- __OBJC_$_PROP_LIST_PKPhoneGlyphLayer
- __OBJC_CLASS_RO_$_PKPhoneGlyphLayer
- __OBJC_METACLASS_RO_$_PKPhoneGlyphLayer
- ___36-[PKPhoneGlyphLayer _endPhoneWiggle]_block_invoke
- ___38-[PKPhoneGlyphLayer _startPhoneWiggle]_block_invoke
- ___65-[PKAuthenticatorSharedRootContext _consumeWithCompletion:reset:]_block_invoke
- _objc_msgSend$_consumeWithCompletion:reset:
- _objc_msgSend$_createContextWithExternalizedContext:
- _objc_msgSend$_phonePositionDeltaWhileShownFromRotationPercentage:toPercentage:
- _objc_msgSend$_phonePositionWhileShownWithRotationPercentage:
- _objc_msgSend$_phoneTransformDeltaWhileShownFromRotationPercentage:toPercentage:
- _objc_msgSend$_updateUserIntentLayerRotation
CStrings:
+ "@\"CAAnimation\"32@?0@\"NSString\"8@\"NSValue\"16@\"NSValue\"24"
+ "Payment_glyph_phone-D73"
+ "v128@?0^{?=@@@@{?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8I16{?={?={CGPoint=dd}{CGPoint=dd}}ccd}20{CGPoint=dd}68{CGPoint=dd}84{CGPoint=dd}100@\"NSURL\"116I124"
+ "v16@?0^{?=@@@@{?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8"
+ "v16@?0^{?=@@@{?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=B{?=II}{?=II{?={CGPoint=dd}{CGPoint=dd}}}}}{CGSize=dd}IICC{CGRect={CGPoint=dd}{CGSize=dd}}}8"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x81"
- "\xf0\xe1"
```
