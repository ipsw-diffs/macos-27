## PassKitUIFoundation

> `/System/iOSSupport/System/Library/PrivateFrameworks/PassKitUIFoundation.framework/Versions/A/PassKitUIFoundation`

```diff

-1696.2.9.0.0
-  __TEXT.__text: 0x1b7a8
-  __TEXT.__objc_methlist: 0x1864
-  __TEXT.__const: 0x5a0
-  __TEXT.__cstring: 0xbd6
+1696.3.3.1.0
+  __TEXT.__text: 0x1d358
+  __TEXT.__objc_methlist: 0x187c
+  __TEXT.__const: 0x5a8
+  __TEXT.__cstring: 0xe49
   __TEXT.__oslogstring: 0xabb
   __TEXT.__gcc_except_tab: 0x484
-  __TEXT.__unwind_info: 0x990
+  __TEXT.__unwind_info: 0x9b8
   __TEXT.__eh_frame: 0x38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x8b8
+  __DATA_CONST.__const: 0x958
   __DATA_CONST.__objc_classlist: 0xe8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1738
+  __DATA_CONST.__objc_selrefs: 0x1760
   __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0xa8
-  __DATA_CONST.__got: 0x3e8
+  __DATA_CONST.__got: 0x3f8
   __AUTH_CONST.__const: 0xa0
-  __AUTH_CONST.__cfstring: 0xd60
-  __AUTH_CONST.__objc_const: 0x3ca8
+  __AUTH_CONST.__cfstring: 0xd80
+  __AUTH_CONST.__objc_const: 0x3d48
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__auth_got: 0x5c0
-  __AUTH.__objc_data: 0x460
-  __DATA.__objc_ivar: 0x3d4
+  __AUTH_CONST.__auth_got: 0x5c8
+  __AUTH.__objc_data: 0x4b0
+  __DATA.__objc_ivar: 0x3e4
   __DATA.__data: 0x420
   __DATA.__bss: 0x80
-  __DATA_DIRTY.__objc_data: 0x4b0
+  __DATA_DIRTY.__objc_data: 0x460
   __DATA_DIRTY.__bss: 0x18
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/iOSSupport/System/Library/Frameworks/UIKit.framework/Versions/A/UIKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 652
-  Symbols:   2110
-  CStrings:  190
+  Functions: 665
+  Symbols:   2136
+  CStrings:  195
 
Symbols:
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
+ GCC_except_table47
+ GCC_except_table48
+ GCC_except_table50
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table63
+ GCC_except_table82
+ _CGRectStandardize
+ _OBJC_CLASS_$_PKDeviceGlyphLayer
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
+ __OBJC_$_PROP_LIST_PKDeviceGlyphLayer
+ __OBJC_CLASS_RO_$_PKDeviceGlyphLayer
+ __OBJC_METACLASS_RO_$_PKDeviceGlyphLayer
+ ___29-[PKGlyphView initWithStyle:]_block_invoke_4
+ ___29-[PKGlyphView initWithStyle:]_block_invoke_5
+ ___30-[PKGlyphView _endPhoneWiggle]_block_invoke_2
+ ___36-[PKDeviceGlyphLayer setShowQRCode:]_block_invoke
+ ___37-[PKDeviceGlyphLayer _endPhoneWiggle]_block_invoke
+ ___39-[PKDeviceGlyphLayer _startPhoneWiggle]_block_invoke
+ ___47-[PKGlyphView _updateUserIntentLayoutAnimated:]_block_invoke_3
+ ___62-[PKGlyphView _updatePhoneLayoutWithTransitionIndex:animated:]_block_invoke
+ ___block_descriptor_40_e8_32s_e241_v128?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8I16{?={?={CGPoint=dd}{CGPoint=dd}}ccd}20{CGPoint=dd}68{CGPoint=dd}84{CGPoint=dd}100"NSURL"116I124ls32l8
+ ___block_descriptor_41_e8_32s_e146_v16?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=B{?=II}{?=II{?={CGPoint=dd}{CGPoint=dd}}}}}{CGSize=dd}IICC{CGRect={CGPoint=dd}{CGSize=dd}}}8ls32l8
+ ___block_descriptor_57_e8_32s40bs48bs_e142_v16?0^{?={?={?={?={CGPoint=dd}{CGPoint=dd}}ccd}{?=cd}{?={CGPoint=dd}{CGPoint=dd}}{?={CGPoint=dd}{CGPoint=dd}}}{CGSize=dd}{CGSize=dd}IIC}8ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s_e55_"CAAnimation"32?0"NSString"8"NSValue"16"NSValue"24ls32l8s40l8
+ ___destructor_8_s0_s8_s16
+ ___destructor_8_s0_s8_s16_s24
+ _kCAMediaTimingFunctionEaseInEaseOut
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
- GCC_except_table42
- GCC_except_table43
- GCC_except_table45
- GCC_except_table52
- GCC_except_table53
- GCC_except_table54
- GCC_except_table74
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
- ___35-[PKPhoneGlyphLayer setShowQRCode:]_block_invoke
- ___36-[PKPhoneGlyphLayer _endPhoneWiggle]_block_invoke
- ___38-[PKPhoneGlyphLayer _startPhoneWiggle]_block_invoke
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
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0a"
- "\xf0\xc1"
```
