## TextInputUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/TextInputUI.framework/Versions/A/TextInputUI`

```diff

-9127.1.13.0.0
-  __TEXT.__text: 0x1129c0
-  __TEXT.__objc_methlist: 0xf6cc
+9127.2.6.0.0
+  __TEXT.__text: 0x11849c
+  __TEXT.__objc_methlist: 0xfb8c
   __TEXT.__const: 0x320e
   __TEXT.__dlopen_cstrs: 0x22c
   __TEXT.__swift5_typeref: 0x19ee

   __TEXT.__swift5_reflstr: 0x895
   __TEXT.__swift5_fieldmd: 0xac0
   __TEXT.__swift5_assocty: 0x2c0
-  __TEXT.__cstring: 0xca56
+  __TEXT.__cstring: 0xcc2b
   __TEXT.__swift5_proto: 0x120
   __TEXT.__swift5_types: 0x108
-  __TEXT.__oslogstring: 0x4d78
+  __TEXT.__oslogstring: 0x5222
   __TEXT.__swift5_capture: 0x480
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x48

   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__swift5_protos: 0xc
   __TEXT.__ustring: 0x258
-  __TEXT.__unwind_info: 0x46c8
+  __TEXT.__unwind_info: 0x47d0
   __TEXT.__eh_frame: 0x11f4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x77a8
-  __DATA_CONST.__objc_classlist: 0x6a8
+  __DATA_CONST.__const: 0x7800
+  __DATA_CONST.__objc_classlist: 0x6b0
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x280
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9e70
+  __DATA_CONST.__objc_selrefs: 0xa170
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x428
-  __DATA_CONST.__objc_arraydata: 0xa50
-  __DATA_CONST.__got: 0x13b8
+  __DATA_CONST.__objc_arraydata: 0xa58
+  __DATA_CONST.__got: 0x13e8
   __AUTH_CONST.__const: 0x27b0
-  __AUTH_CONST.__cfstring: 0xe3e0
-  __AUTH_CONST.__objc_const: 0x18b30
+  __AUTH_CONST.__cfstring: 0xe5a0
+  __AUTH_CONST.__objc_const: 0x19088
   __AUTH_CONST.__objc_intobj: 0x360
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_doubleobj: 0x140
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0xe0
-  __AUTH_CONST.__auth_got: 0x1780
-  __AUTH.__objc_data: 0x3220
+  __AUTH_CONST.__auth_got: 0x1788
+  __AUTH.__objc_data: 0x3270
   __AUTH.__data: 0x8f8
-  __DATA.__objc_ivar: 0x11d0
+  __DATA.__objc_ivar: 0x122c
   __DATA.__data: 0x26b8
-  __DATA.__bss: 0x2868
+  __DATA.__bss: 0x2878
   __DATA.__common: 0x168
   __DATA_DIRTY.__objc_data: 0x1fc8
   __DATA_DIRTY.__data: 0x3c8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6381
-  Symbols:   14603
-  CStrings:  2515
+  Functions: 6484
+  Symbols:   14837
+  CStrings:  2545
 
Symbols:
+ +[TUIKeyplane layoutClassFromScreenDimensions:screenToNativeScaleRatio:]
+ +[TUIKeyplane maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:split:]
+ +[TUIKeyplane variantRowLimitForKey:layoutStyle:variantSelectorType:split:]
+ +[TUIKeyplaneView remoteViewCacheSignatureForKeyplaneName:surface:layoutClass:minorEdgeWidth:handBias:]
+ +[TUIKeyplaneView reuseActionForParentUnchanged:placementUnchanged:appliedAnchorsStillLive:]
+ -[TUIAssistantButtonSizeProvider .cxx_destruct]
+ -[TUIAssistantButtonSizeProvider _fittingWidthForImage:]
+ -[TUIAssistantButtonSizeProvider imageSymbolConfiguration]
+ -[TUIAssistantButtonSizeProvider maximumImageItemWidth]
+ -[TUIAssistantButtonSizeProvider setImageSymbolConfiguration:]
+ -[TUIAssistantButtonSizeProvider setMaximumImageItemWidth:]
+ -[TUIAssistantButtonSizeProvider setSizesImageItemsToFitImage:]
+ -[TUIAssistantButtonSizeProvider sizesImageItemsToFitImage]
+ -[TUICandidateLayout singleRowHeightFittingCollectionView:originY:]
+ -[TUICandidateView arrowButtonHeightFittingBounds:top:]
+ -[TUIHandwritingKeyboardGrabber didMoveToSuperview]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizer:shouldBeRequiredToFailByGestureRecognizer:]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizer:shouldReceiveTouch:]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizerShouldBegin:]
+ -[TUIHandwritingKeyboardGrabber setTranslationAtDragStart:]
+ -[TUIHandwritingKeyboardGrabber translationAtDragStart]
+ -[TUIInputSession _newAutofillContextWithConnectedAppInfo:connection:]
+ -[TUIInputSessionProxy _applicationDidBecomeActive:]
+ -[TUIInputSessionProxy _applicationDidEnterBackground:]
+ -[TUIInputSessionProxy _applicationWillEnterForeground:]
+ -[TUIInputSessionProxy _beginExternalMessageSession]
+ -[TUIInputSessionProxy _endExternalMessageSessionPermanently:]
+ -[TUIInputSessionProxy invalidationHandler]
+ -[TUIInputSessionProxy setInvalidationHandler:]
+ -[TUIKBKeyView _inheritEmojiWideEdgeControlKeyCapsuleHeightForFactory:]
+ -[TUIKBKeyView _setRealBackgroundLayerHidden:animated:]
+ -[TUIKBKeyView installedRemoteContentConstraints]
+ -[TUIKBKeyView setInstalledRemoteContentConstraints:]
+ -[TUIKey isSplitLayout]
+ -[TUIKey setSplitLayout:]
+ -[TUIKeyPopupView isSplitLayout]
+ -[TUIKeyPopupView setSplitLayout:]
+ -[TUIKeyboardAnimationInfo convertedNotificationBeginFrame]
+ -[TUIKeyboardAnimationInfo convertedNotificationEndFrame]
+ -[TUIKeyboardAnimationInfo hasConvertedBeginFrame]
+ -[TUIKeyboardAnimationInfo hasConvertedEndFrame]
+ -[TUIKeyboardAnimationInfo invalidateConvertedFrames]
+ -[TUIKeyboardAnimationInfo setConvertedNotificationBeginFrame:]
+ -[TUIKeyboardAnimationInfo setConvertedNotificationEndFrame:]
+ -[TUIKeyboardAnimationInfo updateBeginFrameForConversion:]
+ -[TUIKeyboardAnimationInfo updateEndFrameForConversion:]
+ -[TUIKeyboardTrackingCoordinator adjustedIAVRectForNotificationRect:iavBounds:]
+ -[TUIKeyboardTrackingCoordinator appScreenRectForNotificationRect:iavBounds:]
+ -[TUIKeyboardTrackingCoordinator updateAnimationInfoIfNeeded:]
+ -[TUIKeyboardTrackingProvider shouldConvertFrameForScene:]
+ -[TUIKeyplane currentOverride]
+ -[TUIKeyplane defaultKeysOrderedByRowForKeyplane:isNumPad:]
+ -[TUIKeyplane duplicateKeyToBeDoubleHeight:atIndex:inRow:type:]
+ -[TUIKeyplane moveControlKey:toRowAtIndex:inRows:]
+ -[TUIKeyplane multiplierTotalCountingSplitDuplicateOnceForRow:]
+ -[TUIKeyplane reconcileConcaveCornerForKey:isMultiRow:]
+ -[TUIKeyplane resolvedRowTreesForType:]
+ -[TUIKeyplane rowSetForOverride:type:]
+ -[TUIKeyplane setCurrentOverride:]
+ -[TUIKeyplane setStackedControlColumnSwitchKey:spanningFromRow:toRow:inRows:]
+ -[TUIKeyplane splitDuplicateKeys]
+ -[TUIKeyplane stackedControlColumnSwitchKeyInRows:]
+ -[TUIKeyplane stringFromRowsetOverride:]
+ -[TUIKeyplane unduplicateDoubleHeightKey:fromRow:type:]
+ -[TUIKeyplane updateStackedControlColumnForRows:]
+ -[TUIKeyplane usesIMButtonsInKeyplaneRowSet]
+ -[TUIKeyplaneRow _needsNarrowerSplitReturnKey:rowLayoutType:]
+ -[TUIKeyplaneView _clampedHandwritingResizeOffset:]
+ -[TUIKeyplaneView _clearStoredVariantViews]
+ -[TUIKeyplaneView _currentRemoteViewCacheSignature]
+ -[TUIKeyplaneView _discardAllRemoteViews]
+ -[TUIKeyplaneView _discardRemoteViewsExcept:]
+ -[TUIKeyplaneView _emojiGridPlacementForHostKeyView:]
+ -[TUIKeyplaneView _installRemoteViewForKeyIfAvailable:liveRemoteViews:]
+ -[TUIKeyplaneView _pushEmojiWideEdgeControlKeyCapsuleHeightToFactory:]
+ -[TUIKeyplaneView _rubberBandedHandwritingResizeOffset:]
+ -[TUIKeyplaneView _vendRemoteViewForKey:cacheID:]
+ -[TUIKeyplaneView _walkSubtreeForRemoteViews:liveRemoteViews:]
+ -[TUIKeyplaneView dockHidesItemsOverlappingEmoji]
+ -[TUIKeyplaneView emojiBottomRowKeyWidth]
+ -[TUIKeyplaneView emojiBottomRowUsesWideEdgeControlKeys]
+ -[TUIKeyplaneView emojiWideEdgeControlKeyCapsuleHeightForWideMultiplier:]
+ -[TUIKeyplaneView emojiWideEdgeControlKeyMultiplierForBottomRowKeyWidth:]
+ -[TUIKeyplaneView emojiWideEdgeControlKeyMultiplier]
+ -[TUIKeyplaneView grabberWillBeginDragging:]
+ -[TUIKeyplaneView maximumRightSplitRowWidth]
+ -[TUIKeyplaneView numberOfRowsForDeterminingKeyplaneInsets]
+ -[TUIKeyplaneView remoteViewCacheSignature]
+ -[TUIKeyplaneView remoteViewPlacementByCacheID]
+ -[TUIKeyplaneView remoteViewsByCacheID]
+ -[TUIKeyplaneView resizeRegionHeightForGrabber:]
+ -[TUIKeyplaneView setDockHidesItemsOverlappingEmoji:]
+ -[TUIKeyplaneView setRemoteViewCacheSignature:]
+ -[TUIKeyplaneView setRemoteViewPlacementByCacheID:]
+ -[TUIKeyplaneView setRemoteViewsByCacheID:]
+ -[TUIKeyplaneView setTraitChangeRegistrations:]
+ -[TUIKeyplaneView splitLayoutGuideContainingKeyView:]
+ -[TUIKeyplaneView traitChangeRegistrations]
+ -[TUIRemoteViewPlacement .cxx_destruct]
+ -[TUIRemoteViewPlacement anchorsStillLive]
+ -[TUIRemoteViewPlacement bottomOffset]
+ -[TUIRemoteViewPlacement hostHadWindow]
+ -[TUIRemoteViewPlacement hostInKeyplaneTree]
+ -[TUIRemoteViewPlacement hostWindow]
+ -[TUIRemoteViewPlacement isEqualToPlacement:]
+ -[TUIRemoteViewPlacement leadingExtent]
+ -[TUIRemoteViewPlacement setBottomOffset:]
+ -[TUIRemoteViewPlacement setHostHadWindow:]
+ -[TUIRemoteViewPlacement setHostInKeyplaneTree:]
+ -[TUIRemoteViewPlacement setHostWindow:]
+ -[TUIRemoteViewPlacement setLeadingExtent:]
+ -[TUIRemoteViewPlacement setTopOffset:]
+ -[TUIRemoteViewPlacement setTrailingExtent:]
+ -[TUIRemoteViewPlacement setVerticalExtent:]
+ -[TUIRemoteViewPlacement topOffset]
+ -[TUIRemoteViewPlacement trailingExtent]
+ -[TUIRemoteViewPlacement verticalExtent]
+ -[TUIVariantSelectorView drawsBackground]
+ _CGSizeNearlyEqualToSizeWithTolerance
+ _OBJC_CLASS_$_CATransaction
+ _OBJC_CLASS_$_TUIRemoteViewPlacement
+ _OBJC_IVAR_$_TUIAssistantButtonSizeProvider._imageSymbolConfiguration
+ _OBJC_IVAR_$_TUIAssistantButtonSizeProvider._maximumImageItemWidth
+ _OBJC_IVAR_$_TUIAssistantButtonSizeProvider._sizesImageItemsToFitImage
+ _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._translationAtDragStart
+ _OBJC_IVAR_$_TUIInputSessionProxy._externalMessageSession
+ _OBJC_IVAR_$_TUIInputSessionProxy._externalMessageSessionDisabled
+ _OBJC_IVAR_$_TUIInputSessionProxy._externalMessageSessionLock
+ _OBJC_IVAR_$_TUIInputSessionProxy._invalidationHandler
+ _OBJC_IVAR_$_TUIKBKeyView._installedRemoteContentConstraints
+ _OBJC_IVAR_$_TUIKey._splitLayout
+ _OBJC_IVAR_$_TUIKeyPopupView._splitLayout
+ _OBJC_IVAR_$_TUIKeyboardAnimationInfo._convertedNotificationBeginFrame
+ _OBJC_IVAR_$_TUIKeyboardAnimationInfo._convertedNotificationEndFrame
+ _OBJC_IVAR_$_TUIKeyplane._currentOverride
+ _OBJC_IVAR_$_TUIKeyplaneView._dockHidesItemsOverlappingEmoji
+ _OBJC_IVAR_$_TUIKeyplaneView._remoteViewCacheSignature
+ _OBJC_IVAR_$_TUIKeyplaneView._remoteViewPlacementByCacheID
+ _OBJC_IVAR_$_TUIKeyplaneView._remoteViewsByCacheID
+ _OBJC_IVAR_$_TUIKeyplaneView._traitChangeRegistrations
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._bottomOffset
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._hostHadWindow
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._hostInKeyplaneTree
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._hostWindow
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._leadingExtent
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._topOffset
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._trailingExtent
+ _OBJC_IVAR_$_TUIRemoteViewPlacement._verticalExtent
+ _OBJC_METACLASS_$_TUIRemoteViewPlacement
+ _TUIViewsShareCommonAncestor
+ _UIApplicationDidBecomeActiveNotification
+ _UIApplicationDidEnterBackgroundNotification
+ _UIApplicationWillEnterForegroundNotification
+ _UIKBTreePropertyRowSetOverride
+ __OBJC_$_INSTANCE_METHODS_TUIRemoteViewPlacement
+ __OBJC_$_INSTANCE_VARIABLES_TUIRemoteViewPlacement
+ __OBJC_$_PROP_LIST_TUIRemoteViewPlacement
+ __OBJC_CLASS_PROTOCOLS_$_TUIHandwritingKeyboardGrabber
+ __OBJC_CLASS_RO_$_TUIRemoteViewPlacement
+ __OBJC_METACLASS_RO_$_TUIRemoteViewPlacement
+ __TUIEmojiSearchFieldHeight
+ __UIDynamicAnimationFrictionHigh
+ ___39-[TUIKeyplane resolvedRowTreesForType:]_block_invoke
+ ___45-[TUIInputSessionProxy _configureConnection:]_block_invoke_2
+ ___65-[TUIKeyboardInputManagerMux newSystemInputManagerWithImplProxy:]_block_invoke
+ ___block_descriptor_40_8_32s_e18_v16?0"UIKBTree"8ls32l8
+ ___block_descriptor_48_8_32s40s_e8_v12?0i8ls32l8s40l8
+ ___block_descriptor_48_8_32w40w_e5_v8?0lw32l8w40l8
+ _kCAFilterColorDodgeBlendMode
+ _objc_msgSend$_beginExternalMessageSession
+ _objc_msgSend$_clampedHandwritingResizeOffset:
+ _objc_msgSend$_clearStoredVariantViews
+ _objc_msgSend$_currentRemoteViewCacheSignature
+ _objc_msgSend$_discardAllRemoteViews
+ _objc_msgSend$_discardRemoteViewsExcept:
+ _objc_msgSend$_emojiGridPlacementForHostKeyView:
+ _objc_msgSend$_endExternalMessageSessionPermanently:
+ _objc_msgSend$_fittingWidthForImage:
+ _objc_msgSend$_inheritEmojiWideEdgeControlKeyCapsuleHeightForFactory:
+ _objc_msgSend$_installRemoteViewForKeyIfAvailable:liveRemoteViews:
+ _objc_msgSend$_needsNarrowerSplitReturnKey:rowLayoutType:
+ _objc_msgSend$_newAutofillContextWithConnectedAppInfo:connection:
+ _objc_msgSend$_pushEmojiWideEdgeControlKeyCapsuleHeightToFactory:
+ _objc_msgSend$_rubberBandedHandwritingResizeOffset:
+ _objc_msgSend$_setRealBackgroundLayerHidden:animated:
+ _objc_msgSend$_vendRemoteViewForKey:cacheID:
+ _objc_msgSend$_walkSubtreeForRemoteViews:liveRemoteViews:
+ _objc_msgSend$adjustedIAVRectForNotificationRect:iavBounds:
+ _objc_msgSend$alignmentRectInsets
+ _objc_msgSend$anchorsStillLive
+ _objc_msgSend$appScreenRectForNotificationRect:iavBounds:
+ _objc_msgSend$applicationState
+ _objc_msgSend$arrowButtonHeightFittingBounds:top:
+ _objc_msgSend$bottomOffset
+ _objc_msgSend$convertedNotificationBeginFrame
+ _objc_msgSend$convertedNotificationEndFrame
+ _objc_msgSend$currentOverride
+ _objc_msgSend$defaultKeysOrderedByRowForKeyplane:isNumPad:
+ _objc_msgSend$disableActions
+ _objc_msgSend$dockHidesItemsOverlappingEmoji
+ _objc_msgSend$duplicateKeyToBeDoubleHeight:atIndex:inRow:type:
+ _objc_msgSend$emojiBottomRowKeyWidth
+ _objc_msgSend$emojiBottomRowUsesWideEdgeControlKeys
+ _objc_msgSend$emojiWideEdgeControlKeyCapsuleHeight
+ _objc_msgSend$emojiWideEdgeControlKeyCapsuleHeightForWideMultiplier:
+ _objc_msgSend$emojiWideEdgeControlKeyMultiplier
+ _objc_msgSend$emojiWideEdgeControlKeyMultiplierForBottomRowKeyWidth:
+ _objc_msgSend$externalMessageSessionController
+ _objc_msgSend$grabberWillBeginDragging:
+ _objc_msgSend$hasConvertedBeginFrame
+ _objc_msgSend$hasConvertedEndFrame
+ _objc_msgSend$hostHadWindow
+ _objc_msgSend$hostInKeyplaneTree
+ _objc_msgSend$imageSymbolConfiguration
+ _objc_msgSend$installedRemoteContentConstraints
+ _objc_msgSend$invalidateConvertedFrames
+ _objc_msgSend$isEqualToPlacement:
+ _objc_msgSend$isSplitLayout
+ _objc_msgSend$keyboardBundleIdentifier
+ _objc_msgSend$layoutClassFromScreenDimensions:screenToNativeScaleRatio:
+ _objc_msgSend$leadingExtent
+ _objc_msgSend$leftSplitLayoutGuide
+ _objc_msgSend$maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:split:
+ _objc_msgSend$maximumImageItemWidth
+ _objc_msgSend$maximumRightSplitRowWidth
+ _objc_msgSend$moveControlKey:toRowAtIndex:inRows:
+ _objc_msgSend$multiplierTotalCountingSplitDuplicateOnceForRow:
+ _objc_msgSend$newExternalMessageSessionWithReason:
+ _objc_msgSend$numberOfRowsForDeterminingKeyplaneInsets
+ _objc_msgSend$reconcileConcaveCornerForKey:isMultiRow:
+ _objc_msgSend$remoteViewCacheSignature
+ _objc_msgSend$remoteViewCacheSignatureForKeyplaneName:surface:layoutClass:minorEdgeWidth:handBias:
+ _objc_msgSend$remoteViewPlacementByCacheID
+ _objc_msgSend$remoteViewsByCacheID
+ _objc_msgSend$removeGestureRecognizer:
+ _objc_msgSend$resizeRegionHeightForGrabber:
+ _objc_msgSend$resolvedRowTreesForType:
+ _objc_msgSend$reuseActionForParentUnchanged:placementUnchanged:appliedAnchorsStillLive:
+ _objc_msgSend$rightSplitLayoutGuide
+ _objc_msgSend$rowSetForOverride:type:
+ _objc_msgSend$screenToNativeScaleRatio
+ _objc_msgSend$setBottomOffset:
+ _objc_msgSend$setConvertedNotificationBeginFrame:
+ _objc_msgSend$setConvertedNotificationEndFrame:
+ _objc_msgSend$setCurrentOverride:
+ _objc_msgSend$setDisableActions:
+ _objc_msgSend$setEmojiWideEdgeControlKeyCapsuleHeight:
+ _objc_msgSend$setHostHadWindow:
+ _objc_msgSend$setHostInKeyplaneTree:
+ _objc_msgSend$setHostWindow:
+ _objc_msgSend$setImageSymbolConfiguration:
+ _objc_msgSend$setInstalledRemoteContentConstraints:
+ _objc_msgSend$setLeadingExtent:
+ _objc_msgSend$setMaximumImageItemWidth:
+ _objc_msgSend$setRefCountedAssertionAttributes:
+ _objc_msgSend$setRemoteViewCacheSignature:
+ _objc_msgSend$setSelfSizingChanged:
+ _objc_msgSend$setSet:
+ _objc_msgSend$setSizesImageItemsToFitImage:
+ _objc_msgSend$setSplitLayout:
+ _objc_msgSend$setStackedControlColumnSwitchKey:spanningFromRow:toRow:inRows:
+ _objc_msgSend$setSystemInputManager:
+ _objc_msgSend$setTopOffset:
+ _objc_msgSend$setTrailingExtent:
+ _objc_msgSend$setTraitChangeRegistrations:
+ _objc_msgSend$setVerticalExtent:
+ _objc_msgSend$shouldConvertFrameForScene:
+ _objc_msgSend$singleRowHeightFittingCollectionView:originY:
+ _objc_msgSend$sizesImageItemsToFitImage
+ _objc_msgSend$splitDuplicateKeys
+ _objc_msgSend$splitLayoutGuideContainingKeyView:
+ _objc_msgSend$splitMode
+ _objc_msgSend$stackedControlColumnSwitchKeyInRows:
+ _objc_msgSend$stringFromRowsetOverride:
+ _objc_msgSend$topOffset
+ _objc_msgSend$trailingExtent
+ _objc_msgSend$traitChangeRegistrations
+ _objc_msgSend$unduplicateDoubleHeightKey:fromRow:type:
+ _objc_msgSend$updateAnimationInfoIfNeeded:
+ _objc_msgSend$updateBeginFrameForConversion:
+ _objc_msgSend$updateEndFrameForConversion:
+ _objc_msgSend$updateStackedControlColumnForRows:
+ _objc_msgSend$usesIMButtonsInKeyplaneRowSet
+ _objc_msgSend$variantRowLimitForKey:layoutStyle:variantSelectorType:split:
+ _objc_msgSend$verticalExtent
+ _type_layout_string So7CGPointV
- +[TUIKeyplane maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:]
- +[TUIKeyplane variantRowLimitForKey:layoutStyle:variantSelectorType:]
- -[TUIHandwritingKeyboardGrabber maximumResizeOffset]
- -[TUIHandwritingKeyboardGrabber minimumResizeOffset]
- -[TUIHandwritingKeyboardGrabber setMaximumResizeOffset:]
- -[TUIHandwritingKeyboardGrabber setMinimumResizeOffset:]
- -[TUIKeyboardTrackingCoordinator adjustedRectForNotificationRect:iavBounds:]
- -[TUIKeyboardTrackingCoordinator postNotificationsWithInfo:type:start:]
- -[TUIKeyplane defaultKeysOrderedByRowForKeyplane:]
- -[TUIKeyplane duplicateKeyToBeDoubleHeight:atIndex:inRow:]
- -[TUIKeyplane moveControlKey:toRowAtIndex:inRowSet:]
- -[TUIKeyplane setStackedControlColumnSwitchKey:spanningFromRow:toRow:inRowSet:]
- -[TUIKeyplane stackedControlColumnSwitchKeyInRowSet:]
- -[TUIKeyplane unduplicateDoubleHeightKey:fromRow:]
- -[TUIKeyplane updateStackedControlColumnForRowSet:]
- -[TUIKeyplaneView _installRemoteViewForKeyIfAvailable:]
- -[TUIKeyplaneView _walkSubtreeForRemoteViews:]
- -[TUIKeyplaneView setSizeClassTraitChangeRegistration:]
- -[TUIKeyplaneView setTraitChangeRegistration:]
- -[TUIKeyplaneView sizeClassTraitChangeRegistration]
- -[TUIKeyplaneView traitChangeRegistration]
- _NSArgumentDomain
- _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._maximumResizeOffset
- _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._minimumResizeOffset
- _OBJC_IVAR_$_TUIKeyplaneView._sizeClassTraitChangeRegistration
- _OBJC_IVAR_$_TUIKeyplaneView._traitChangeRegistration
- ___block_descriptor_56_8_32s_e8_v12?0i8ls32l8
- _objc_msgSend$_installRemoteViewForKeyIfAvailable:
- _objc_msgSend$_walkSubtreeForRemoteViews:
- _objc_msgSend$addSuiteNamed:
- _objc_msgSend$adjustedRectForNotificationRect:iavBounds:
- _objc_msgSend$convertRectFromPairedSceneToKeyboardScene:
- _objc_msgSend$defaultKeysOrderedByRowForKeyplane:
- _objc_msgSend$duplicateKeyToBeDoubleHeight:atIndex:inRow:
- _objc_msgSend$maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:
- _objc_msgSend$maximumResizeOffset
- _objc_msgSend$minimumResizeOffset
- _objc_msgSend$moveControlKey:toRowAtIndex:inRowSet:
- _objc_msgSend$numberOfCachedKeys
- _objc_msgSend$setMaximumResizeOffset:
- _objc_msgSend$setMinimumResizeOffset:
- _objc_msgSend$setPerMessageAssertionAttributes:
- _objc_msgSend$setSizeClassTraitChangeRegistration:
- _objc_msgSend$setStackedControlColumnSwitchKey:spanningFromRow:toRow:inRowSet:
- _objc_msgSend$setTraitChangeRegistration:
- _objc_msgSend$sizeClassTraitChangeRegistration
- _objc_msgSend$stackedControlColumnSwitchKeyInRowSet:
- _objc_msgSend$traitChangeRegistration
- _objc_msgSend$unduplicateDoubleHeightKey:fromRow:
- _objc_msgSend$updateStackedControlColumnForRowSet:
- _objc_msgSend$variantRowLimitForKey:layoutStyle:variantSelectorType:
- _type_layout_string So6CGSizeV
CStrings:
+ "!j"
+ "%@_%@"
+ "%@|%ld|%ld|%ld|%ld"
+ "%s, began external message session"
+ "%s, ending external message session (permanently: %d)"
+ "-[TUIInputSessionProxy _beginExternalMessageSession]"
+ "-[TUIInputSessionProxy _configureConnection:]_block_invoke_2"
+ "-[TUIInputSessionProxy _endExternalMessageSessionPermanently:]"
+ "Duplicate keys found but no split support; number of keys %li number of dupes %li"
+ "EmojiRemoteView Dropped: key %{public}@ was not served on this pass"
+ "EmojiRemoteView Hoisted: key=%{public}@ into containment=%p so its variant selector draws above the search bar"
+ "EmojiRemoteView Host Missing: key=%{public}@ — no host TUIKBKeyView in storedKeyViews; falling back to sibling install"
+ "EmojiRemoteView Installing: key=%{public}@ host=%p hostFrame=%@"
+ "EmojiRemoteView Not Vended: provider returned nil for key %{public}@ displayType=%d"
+ "EmojiRemoteView Reanchored: key=%{public}@ placement changed under a cached remote view — rebuilding its constraints in %p (hadWindow %d→%d, sameWindow %d, inKeyplaneTree %d→%d, extents %ld/%ld/%ld→%ld/%ld/%ld, offsets %.1f/%.1f→%.1f/%.1f)"
+ "EmojiRemoteView Replaced: key=%{public}@ cached remote view can't stay in %p — vending a replacement for %p"
+ "EmojiRemoteView Replaced: key=%{public}@ cached remote view is auto-layout anchored and can't be frame-positioned — vending a replacement"
+ "EmojiRemoteView Window Missing: key=%{public}@ host has no window yet — API fell back to host bounds; a later walk re-anchors it once the host is in a window"
+ "IMButtonsInKeyplane"
+ "KBRowSetOverride"
+ "Number-Alternative-Plane"
+ "Number-Plane"
+ "QWERTY-Lithuanian"
+ "Releasing invalidated system input manager: %@"
+ "Rowset.Override.%@.Row%li"
+ "Rowset.Override.%@.Variant.%@.Row%li"
+ "UIKBTreePropertyRowSetOverride"
+ "W1!"
+ "[Notifications] Converting notification begin frame: %@ to: %@ from: %@"
+ "[Notifications] Converting notification end frame: %@ to: %@ from: %@"
+ "[Notifications] Updating notification info with begin frame: %@ end frame: %@ [%@]"
+ "[Resizing] Keyboard frame %@ does not overlap window %@; posting with the existing notification frame"
+ "[Resizing] Send notifications for size change %@ vs %@"
+ "_%@-%@"
+ "_split_%i"
+ "com.apple.purplebuddy"
+ "keyboard session"
+ "v16@?0@\"UIKBTree\"8"
- "Cached key mismatch but no split support; expected %li vs %li"
- "Provider returned nil for key %{public}@ displayType=%d"
- "W!!"
- "[install-HOIST] key=%{public}@ hoisting grid into containment=%p so its variant selector draws above the search bar"
- "[install-HOST-MISS] key=%{public}@ — no host TUIKBKeyView in storedKeyViews; falling back to sibling install"
- "[install-HOST] key=%{public}@ host=%p hostFrame=%@"
- "[install-WINDOW-MISS] key=%{public}@ host has no window yet — API fell back to host bounds; will retry on next walk"
- "\x8a"
```
