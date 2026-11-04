## CallsDialer

> `/System/iOSSupport/System/Library/PrivateFrameworks/CallsDialer.framework/Versions/A/CallsDialer`

```diff

-156.200.131.1.11
-  __TEXT.__text: 0x3b55c
-  __TEXT.__objc_methlist: 0x3ecc
-  __TEXT.__const: 0x16b4
-  __TEXT.__cstring: 0x10ff
+156.300.51.0.0
+  __TEXT.__text: 0x3cafc
+  __TEXT.__objc_methlist: 0x4054
+  __TEXT.__const: 0x16e4
+  __TEXT.__cstring: 0x113f
   __TEXT.__gcc_except_tab: 0x194
-  __TEXT.__oslogstring: 0x24ce
+  __TEXT.__oslogstring: 0x244e
   __TEXT.__dlopen_cstrs: 0x64
   __TEXT.__ustring: 0x178
   __TEXT.__swift5_typeref: 0x89a

   __TEXT.__swift_as_ret: 0x70
   __TEXT.__swift_as_cont: 0xbc
   __TEXT.__swift5_capture: 0x1d0
-  __TEXT.__unwind_info: 0x14e0
+  __TEXT.__unwind_info: 0x1530
   __TEXT.__eh_frame: 0xdbc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x668
-  __DATA_CONST.__objc_classlist: 0x110
+  __DATA_CONST.__const: 0x690
+  __DATA_CONST.__objc_classlist: 0x118
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x33a8
+  __DATA_CONST.__objc_selrefs: 0x34f8
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0xb0
-  __DATA_CONST.__objc_arraydata: 0xe0
-  __DATA_CONST.__got: 0x6f8
+  __DATA_CONST.__objc_superrefs: 0xb8
+  __DATA_CONST.__objc_arraydata: 0xf8
+  __DATA_CONST.__got: 0x718
   __AUTH_CONST.__const: 0xa60
   __AUTH_CONST.__cfstring: 0x15e0
-  __AUTH_CONST.__objc_const: 0x5da0
+  __AUTH_CONST.__objc_const: 0x5f30
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_floatobj: 0x30
-  __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__objc_intobj: 0x150
+  __AUTH_CONST.__objc_arrayobj: 0x48
+  __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0xaa8
-  __AUTH.__objc_data: 0x418
+  __AUTH_CONST.__auth_got: 0xac8
+  __AUTH.__objc_data: 0x468
   __AUTH.__data: 0x1b0
-  __DATA.__objc_ivar: 0x2a8
+  __DATA.__objc_ivar: 0x2b8
   __DATA.__data: 0xb60
   __DATA.__bss: 0xbd0
   __DATA.__common: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1574
-  Symbols:   3363
-  CStrings:  344
+  Functions: 1609
+  Symbols:   3457
+  CStrings:  345
 
Symbols:
+ +[PHHandsetDialerResizableButton digitFontSizeForCategory:]
+ +[PHHandsetDialerResizableButton glyphVerticalOffsetForCategory:]
+ +[PHHandsetDialerResizableButton letterFontSizeForCategory:]
+ -[MPKeypadViewController shouldRespectSafeAreaForDialer:]
+ -[MPKeypadViewController updateBackground:]
+ -[MPKeypadViewController updateDialerSafeAreaInsetIfNeeded:]
+ -[MPKeypadViewController updateDialerTallLayoutForSize:]
+ -[MPKeypadViewController viewIsAppearing:]
+ -[MPKeypadViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[PHBottomBarButton applyIconSymbolConfiguration:]
+ -[PHDialerButtonConfig .cxx_destruct]
+ -[PHDialerButtonConfig initWithVerticalPadding:]
+ -[PHDialerButtonConfig setVerticalPadding:]
+ -[PHDialerButtonConfig verticalPadding]
+ -[PHHandsetDialerLCDView _hostsAddContactButtonExternally]
+ -[PHHandsetDialerLCDView _newImageAddContactButton]
+ -[PHHandsetDialerLCDView _newTitledAddContactButton]
+ -[PHHandsetDialerLCDView headerLayoutGuideHeightConstraint]
+ -[PHHandsetDialerLCDView headerLayoutGuideHeight]
+ -[PHHandsetDialerLCDView headerLayoutGuideTopConstraint]
+ -[PHHandsetDialerLCDView headerTopConstantForSuppress:tallLayout:]
+ -[PHHandsetDialerLCDView screenSizeCategory]
+ -[PHHandsetDialerLCDView setHeaderLayoutGuideHeightConstraint:]
+ -[PHHandsetDialerLCDView setHeaderLayoutGuideTopConstraint:]
+ -[PHHandsetDialerLCDView setTallLayout:]
+ -[PHHandsetDialerLCDView tallLayout]
+ -[PHHandsetDialerLCDView updateForScreenSizeCategoryChange]
+ -[PHHandsetDialerLCDView updateHeaderLayoutGuideTopConstant]
+ -[PHHandsetDialerResizableButton initForCharacter:style:screenSizeCategory:screenSize:config:]
+ -[PHHandsetDialerView _centerAddContactButtonOnLeftKeyColumn:]
+ -[PHHandsetDialerView _createButtonOfClass:forCharacter:category:config:]
+ -[PHHandsetDialerView _currentButtonSize]
+ -[PHHandsetDialerView _updateOpticalCenteringOffset]
+ -[PHHandsetDialerView _verticalPaddingForButtonCategory:screenSize:]
+ -[PHHandsetDialerView lcdViewCenterXConstraint]
+ -[PHHandsetDialerView lcdViewTopConstraint]
+ -[PHHandsetDialerView phonePadViewCenterXConstraint]
+ -[PHHandsetDialerView setLcdViewCenterXConstraint:]
+ -[PHHandsetDialerView setLcdViewTopConstraint:]
+ -[PHHandsetDialerView setPhonePadViewCenterXConstraint:]
+ GCC_except_table45
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _OBJC_CLASS_$_PHDialerButtonConfig
+ _OBJC_CLASS_$_TUPlatformCapabilities
+ _OBJC_CLASS_$_UIFontMetrics
+ _OBJC_IVAR_$_PHDialerButtonConfig._verticalPadding
+ _OBJC_IVAR_$_PHHandsetDialerLCDView._headerLayoutGuideHeightConstraint
+ _OBJC_IVAR_$_PHHandsetDialerLCDView._headerLayoutGuideTopConstraint
+ _OBJC_IVAR_$_PHHandsetDialerLCDView._tallLayout
+ _OBJC_IVAR_$_PHHandsetDialerView._lcdViewCenterXConstraint
+ _OBJC_IVAR_$_PHHandsetDialerView._lcdViewTopConstraint
+ _OBJC_IVAR_$_PHHandsetDialerView._phonePadViewCenterXConstraint
+ _OBJC_METACLASS_$_PHDialerButtonConfig
+ _UIFontTextStyleTitle3
+ __OBJC_$_INSTANCE_METHODS_PHDialerButtonConfig
+ __OBJC_$_INSTANCE_VARIABLES_PHDialerButtonConfig
+ __OBJC_$_PROP_LIST_PHDialerButtonConfig
+ __OBJC_CLASS_RO_$_PHDialerButtonConfig
+ __OBJC_METACLASS_RO_$_PHDialerButtonConfig
+ ___37-[PHHandsetDialerView layoutSubviews]_block_invoke
+ ___77-[MPKeypadViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___block_descriptor_56_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
+ ___block_descriptor_72_e8_32s40s48s_e25_v32?0"NSNumber"8Q16^B24ls32l8u56l8s40l8s48l8
+ _objc_msgSend$_centerAddContactButtonOnLeftKeyColumn:
+ _objc_msgSend$_createButtonOfClass:forCharacter:category:config:
+ _objc_msgSend$_currentButtonSize
+ _objc_msgSend$_hostsAddContactButtonExternally
+ _objc_msgSend$_newImageAddContactButton
+ _objc_msgSend$_newTitledAddContactButton
+ _objc_msgSend$_updateOpticalCenteringOffset
+ _objc_msgSend$_verticalPaddingForButtonCategory:screenSize:
+ _objc_msgSend$animateAlongsideTransition:completion:
+ _objc_msgSend$applyIconSymbolConfiguration:
+ _objc_msgSend$center
+ _objc_msgSend$digitFontSizeForCategory:
+ _objc_msgSend$doubleValue
+ _objc_msgSend$glyphVerticalOffsetForCategory:
+ _objc_msgSend$headerLayoutGuideHeight
+ _objc_msgSend$headerLayoutGuideHeightConstraint
+ _objc_msgSend$headerLayoutGuideTopConstraint
+ _objc_msgSend$headerTopConstantForSuppress:tallLayout:
+ _objc_msgSend$imageByApplyingSymbolConfiguration:
+ _objc_msgSend$imageForCharacter:highlighted:whiteVersion:digitFontSizeOverride:letterFontSizeOverride:
+ _objc_msgSend$imageForState:
+ _objc_msgSend$initForCharacter:style:screenSizeCategory:screenSize:config:
+ _objc_msgSend$initWithVerticalPadding:
+ _objc_msgSend$isDualDisplayDevice
+ _objc_msgSend$lastRecreatedButtonHeight
+ _objc_msgSend$lastRecreatedButtonWidth
+ _objc_msgSend$lcdViewCenterXConstraint
+ _objc_msgSend$lcdViewTopConstraint
+ _objc_msgSend$leftAnchor
+ _objc_msgSend$letterFontSizeForCategory:
+ _objc_msgSend$metricsForTextStyle:
+ _objc_msgSend$phonePadViewCenterXConstraint
+ _objc_msgSend$scaledFontForFont:
+ _objc_msgSend$setCenter:
+ _objc_msgSend$setHeaderLayoutGuideHeightConstraint:
+ _objc_msgSend$setHeaderLayoutGuideTopConstraint:
+ _objc_msgSend$setInsetsLayoutMarginsFromSafeArea:
+ _objc_msgSend$setLargeContentTitle:
+ _objc_msgSend$setLastRecreatedButtonHeight:
+ _objc_msgSend$setLastRecreatedButtonWidth:
+ _objc_msgSend$setLcdViewCenterXConstraint:
+ _objc_msgSend$setLcdViewTopConstraint:
+ _objc_msgSend$setPhonePadViewCenterXConstraint:
+ _objc_msgSend$setTallLayout:
+ _objc_msgSend$setViewRespectsSystemMinimumLayoutMargins:
+ _objc_msgSend$shouldRespectSafeAreaForDialer:
+ _objc_msgSend$updateBackground:
+ _objc_msgSend$updateDialerSafeAreaInsetIfNeeded:
+ _objc_msgSend$updateDialerTallLayoutForSize:
+ _objc_msgSend$updateForScreenSizeCategoryChange
+ _objc_msgSend$updateHeaderLayoutGuideTopConstant
+ _objc_msgSend$viewIfLoaded
- -[PHHandsetDialerView _createButtonOfClass:forCharacter:category:]
- -[PHHandsetDialerView _didSizeChangeSignificantly:newHeight:oldWidth:oldHeight:threshold:]
- -[PHHandsetDialerView _logLayoutSubviewsButtonSizeCheck:currentHeight:newCategory:newButtonDiameter:newVerticalPadding:newHorizontalPadding:newButtonWidth:newButtonHeight:buttonSizeNeedsChange:]
- -[PHHandsetDialerView constraintAddContactButtonForIPad]
- -[PHHandsetDialerView constraintAddContactButtonForNonIPad]
- -[PHHandsetDialerView lastRecreatedPadHeight]
- -[PHHandsetDialerView lastRecreatedPadWidth]
- -[PHHandsetDialerView setLastRecreatedPadHeight:]
- -[PHHandsetDialerView setLastRecreatedPadWidth:]
- GCC_except_table38
- _OBJC_IVAR_$_PHHandsetDialerLCDView._suppressResultButtons
- _OBJC_IVAR_$_PHHandsetDialerView._lastRecreatedPadHeight
- _OBJC_IVAR_$_PHHandsetDialerView._lastRecreatedPadWidth
- ___block_descriptor_64_e8_32s40s_e25_v32?0"NSNumber"8Q16^B24ls32l8u48l8s40l8
- _objc_msgSend$_createButtonOfClass:forCharacter:category:
- _objc_msgSend$_didSizeChangeSignificantly:newHeight:oldWidth:oldHeight:threshold:
- _objc_msgSend$buttons
- _objc_msgSend$constraintAddContactButtonForIPad
- _objc_msgSend$constraintAddContactButtonForNonIPad
- _objc_msgSend$imageForCharacter:highlighted:whiteVersion:
- _objc_msgSend$lastRecreatedPadHeight
- _objc_msgSend$lastRecreatedPadWidth
- _objc_msgSend$setLastRecreatedPadHeight:
- _objc_msgSend$setLastRecreatedPadWidth:
CStrings:
+ "2`"
+ "PHONE_NUMBER_FIELD"
+ "Q"
+ "[PHHandsetDialerView] layoutSubviews: recreated pad, buttonSize={%.1f,%.1f} was={%.1f,%.1f}"
+ "[PHHandsetDialerView] optical centering: bounds=%.1f leadingInset=%.1f trailingInset=%.1f slack=%.1f offset=%.1f"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
- "1`"
- "Phone number"
- "[PHHandsetDialerView] layoutSubviews: NOT recreating pad (width diff=%.1f, height diff=%.1f)"
- "[PHHandsetDialerView] layoutSubviews: RECREATING pad (width diff=%.1f, height diff=%.1f)"
- "[PHHandsetDialerView] layoutSubviews: width=%.1f→%.1f height=%.1f→%.1f newCategory=%lu newButtonSize={%.1f,%.1f} currentButtonSize={%.1f,%.1f}"
```
