## TextInputUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/TextInputUI.framework/Versions/A/TextInputUI`

```diff

-9127.1.6.0.0
-  __TEXT.__text: 0x11203c
-  __TEXT.__objc_methlist: 0xf49c
-  __TEXT.__const: 0x31de
+9127.1.7.0.0
+  __TEXT.__text: 0x11306c
+  __TEXT.__objc_methlist: 0xf684
+  __TEXT.__const: 0x321e
   __TEXT.__dlopen_cstrs: 0x22c
-  __TEXT.__swift5_typeref: 0x1a10
-  __TEXT.__constg_swiftt: 0x1518
+  __TEXT.__swift5_typeref: 0x1a1c
+  __TEXT.__constg_swiftt: 0x13fc
   __TEXT.__swift5_builtin: 0x12c
   __TEXT.__swift5_reflstr: 0x895
-  __TEXT.__swift5_fieldmd: 0xac0
+  __TEXT.__swift5_fieldmd: 0xad0
   __TEXT.__swift5_assocty: 0x2c0
-  __TEXT.__cstring: 0xca03
+  __TEXT.__cstring: 0xcae5
   __TEXT.__swift5_proto: 0x120
-  __TEXT.__swift5_types: 0x108
+  __TEXT.__swift5_types: 0x10c
   __TEXT.__oslogstring: 0x4e83
   __TEXT.__swift5_capture: 0x484
   __TEXT.__swift_as_entry: 0x50

   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__swift5_protos: 0xc
   __TEXT.__ustring: 0x258
-  __TEXT.__unwind_info: 0x46c8
-  __TEXT.__eh_frame: 0x11fc
+  __TEXT.__unwind_info: 0x46a0
+  __TEXT.__eh_frame: 0x11f4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7760
-  __DATA_CONST.__objc_classlist: 0x698
+  __DATA_CONST.__const: 0x77a8
+  __DATA_CONST.__objc_classlist: 0x6b0
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x278
+  __DATA_CONST.__objc_protolist: 0x280
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9ce0
+  __DATA_CONST.__objc_selrefs: 0x9e48
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x428
-  __DATA_CONST.__objc_arraydata: 0xa20
-  __DATA_CONST.__got: 0x1350
-  __AUTH_CONST.__const: 0x2770
-  __AUTH_CONST.__cfstring: 0xe360
-  __AUTH_CONST.__objc_const: 0x18700
+  __DATA_CONST.__objc_arraydata: 0xa50
+  __DATA_CONST.__got: 0x1390
+  __AUTH_CONST.__const: 0x27b0
+  __AUTH_CONST.__cfstring: 0xe3c0
+  __AUTH_CONST.__objc_const: 0x18b90
   __AUTH_CONST.__objc_intobj: 0x360
-  __AUTH_CONST.__objc_arrayobj: 0x270
-  __AUTH_CONST.__objc_doubleobj: 0x110
+  __AUTH_CONST.__objc_arrayobj: 0x2a0
+  __AUTH_CONST.__objc_doubleobj: 0x140
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0xe0
-  __AUTH_CONST.__auth_got: 0x1780
-  __AUTH.__objc_data: 0x31b0
-  __AUTH.__data: 0x8f8
-  __DATA.__objc_ivar: 0x119c
-  __DATA.__data: 0x2608
-  __DATA.__bss: 0x2648
+  __AUTH_CONST.__auth_got: 0x1790
+  __AUTH.__objc_data: 0x32c8
+  __AUTH.__data: 0x918
+  __DATA.__objc_ivar: 0x11d4
+  __DATA.__data: 0x2678
+  __DATA.__bss: 0x2868
   __DATA.__common: 0x168
-  __DATA_DIRTY.__objc_data: 0x20d8
+  __DATA_DIRTY.__objc_data: 0x1fc0
   __DATA_DIRTY.__data: 0x3c8
-  __DATA_DIRTY.__bss: 0x588
+  __DATA_DIRTY.__bss: 0x598
   __DATA_DIRTY.__common: 0x68
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6365
-  Symbols:   14467
-  CStrings:  2513
+  Functions: 6375
+  Symbols:   14635
+  CStrings:  2518
 
Symbols:
+ +[TUICandidateCell candidateFontForCandidate:style:]
+ +[TUIKeyboardHitDebugTouchChannel _deliverSample:]
+ +[TUIKeyboardHitDebugTouchChannel _isRepeatOfRecentSample:]
+ +[TUIKeyboardHitDebugTouchChannel _observers]
+ +[TUIKeyboardHitDebugTouchChannel addObserver:]
+ +[TUIKeyboardHitDebugTouchChannel publishTouchEvent:]
+ +[TUIKeyboardHitDebugTouchChannel removeObserver:]
+ -[TUIKeyboardHitDebugOverlay _applyMarkerPathForSample:trail:toMarker:]
+ -[TUIKeyboardHitDebugOverlay _beginTapMarkerAtSample:pathKey:]
+ -[TUIKeyboardHitDebugOverlay _closeOutTapMarkerForPathKey:]
+ -[TUIKeyboardHitDebugOverlay _evictableTapMarker]
+ -[TUIKeyboardHitDebugOverlay _extendTapMarkerWithSample:pathKey:isFinal:]
+ -[TUIKeyboardHitDebugOverlay _removeAllTapMarkers]
+ -[TUIKeyboardHitDebugOverlay _removeTapMarker:]
+ -[TUIKeyboardHitDebugOverlay _restartFadeForMarker:]
+ -[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay _stopObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay _updateTapMarkerColors]
+ -[TUIKeyboardHitDebugOverlay didReceiveTouchSample:]
+ -[TUIKeyboardHitDebugOverlay setShowsKeyHitGeometry:]
+ -[TUIKeyboardHitDebugOverlay setShowsTouchPointMarkers:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerContainerLayer:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerFadeGeneration:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerReferenceSize:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkers:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkersByPathIndex:]
+ -[TUIKeyboardHitDebugOverlay setTapTrailsByPathIndex:]
+ -[TUIKeyboardHitDebugOverlay showsKeyHitGeometry]
+ -[TUIKeyboardHitDebugOverlay showsTouchPointMarkers]
+ -[TUIKeyboardHitDebugOverlay stopObserving]
+ -[TUIKeyboardHitDebugOverlay tapMarkerContainerLayer]
+ -[TUIKeyboardHitDebugOverlay tapMarkerFadeGeneration]
+ -[TUIKeyboardHitDebugOverlay tapMarkerReferenceSize]
+ -[TUIKeyboardHitDebugOverlay tapMarkersByPathIndex]
+ -[TUIKeyboardHitDebugOverlay tapMarkers]
+ -[TUIKeyboardHitDebugOverlay tapTrailsByPathIndex]
+ -[_TUITapMarkerTrail .cxx_destruct]
+ -[_TUITapMarkerTrail lastDotLocation]
+ -[_TUITapMarkerTrail lastFadeRestartTimestamp]
+ -[_TUITapMarkerTrail linePath]
+ -[_TUITapMarkerTrail sampleLayer]
+ -[_TUITapMarkerTrail samplePath]
+ -[_TUITapMarkerTrail setLastDotLocation:]
+ -[_TUITapMarkerTrail setLastFadeRestartTimestamp:]
+ -[_TUITapMarkerTrail setLinePath:]
+ -[_TUITapMarkerTrail setSampleLayer:]
+ -[_TUITapMarkerTrail setSamplePath:]
+ -[_TUITapMarkerTrail setStartLocation:]
+ -[_TUITapMarkerTrail startLocation]
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._showsKeyHitGeometry
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._showsTouchPointMarkers
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerContainerLayer
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerFadeGeneration
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerReferenceSize
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkers
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkersByPathIndex
+ OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapTrailsByPathIndex
+ OBJC_IVAR_$__TUITapMarkerTrail._lastDotLocation
+ OBJC_IVAR_$__TUITapMarkerTrail._lastFadeRestartTimestamp
+ OBJC_IVAR_$__TUITapMarkerTrail._linePath
+ OBJC_IVAR_$__TUITapMarkerTrail._sampleLayer
+ OBJC_IVAR_$__TUITapMarkerTrail._samplePath
+ OBJC_IVAR_$__TUITapMarkerTrail._startLocation
+ TIGetShowTouchPointDebugUIValue.onceToken
+ _OBJC_CLASS_$_CAKeyframeAnimation
+ _OBJC_CLASS_$_CALayer
+ _OBJC_CLASS_$_TUIKeyboardHitDebugTouchChannel
+ _OBJC_CLASS_$__TUITapMarkerTrail
+ _OBJC_CLASS_$__TtC11TextInputUI26AttributedSearchResultItem
+ _OBJC_METACLASS_$_TUIKeyboardHitDebugTouchChannel
+ _OBJC_METACLASS_$__TUITapMarkerTrail
+ _OBJC_METACLASS_$__TtC11TextInputUI26AttributedSearchResultItem
+ _TUICandidateFont
+ _TUICandidateRowHeight
+ _TUIKeyboardHitDebugTouchChannelHasObservers
+ _TUIMinimumCandidateLabelHeight
+ __DATA__TtC11TextInputUI26AttributedSearchResultItem
+ __INSTANCE_METHODS__TtC11TextInputUI26AttributedSearchResultItem
+ __METACLASS_DATA__TtC11TextInputUI26AttributedSearchResultItem
+ __OBJC_$_CLASS_METHODS_TUIKeyboardHitDebugTouchChannel
+ __OBJC_$_INSTANCE_METHODS__TUITapMarkerTrail
+ __OBJC_$_INSTANCE_VARIABLES__TUITapMarkerTrail
+ __OBJC_$_PROP_LIST__TUITapMarkerTrail
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUIKeyboardHitDebugTouchObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUIKeyboardHitDebugTouchObserver
+ __OBJC_$_PROTOCOL_REFS_TUIKeyboardHitDebugTouchObserver
+ __OBJC_CLASS_PROTOCOLS_$_TUIKeyboardHitDebugOverlay
+ __OBJC_CLASS_RO_$_TUIKeyboardHitDebugTouchChannel
+ __OBJC_CLASS_RO_$__TUITapMarkerTrail
+ __OBJC_LABEL_PROTOCOL_$_TUIKeyboardHitDebugTouchObserver
+ __OBJC_METACLASS_RO_$_TUIKeyboardHitDebugTouchChannel
+ __OBJC_METACLASS_RO_$__TUITapMarkerTrail
+ __OBJC_PROTOCOL_$_TUIKeyboardHitDebugTouchObserver
+ __TUITapMarkerTrailColor
+ ___44-[TUIKeyboardHitDebugOverlay initWithFrame:]_block_invoke
+ ___45+[TUIKeyboardHitDebugTouchChannel _observers]_block_invoke
+ ___52-[TUIKeyboardHitDebugOverlay _restartFadeForMarker:]_block_invoke
+ ___53+[TUIKeyboardHitDebugTouchChannel publishTouchEvent:]_block_invoke
+ ___59-[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]_block_invoke
+ ___59-[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]_block_invoke_2
+ ___TIGetShowTouchPointDebugUIValue_block_invoke
+ ___block_descriptor_56_8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_88_e5_v8?0l
+ _isRepeatOfRecentSample:.nextSlot
+ _isRepeatOfRecentSample:.recentPathIndices
+ _isRepeatOfRecentSample:.recentTimestamps
+ _kCAFillRuleEvenOdd
+ _kCALineCapRound
+ _kCALineJoinRound
+ _kCAMediaTimingFunctionEaseIn
+ _objc_msgSend$_applyMarkerPathForSample:trail:toMarker:
+ _objc_msgSend$_beginTapMarkerAtSample:pathKey:
+ _objc_msgSend$_closeOutTapMarkerForPathKey:
+ _objc_msgSend$_deliverSample:
+ _objc_msgSend$_evictableTapMarker
+ _objc_msgSend$_extendTapMarkerWithSample:pathKey:isFinal:
+ _objc_msgSend$_isRepeatOfRecentSample:
+ _objc_msgSend$_observers
+ _objc_msgSend$_removeAllTapMarkers
+ _objc_msgSend$_removeTapMarker:
+ _objc_msgSend$_restartFadeForMarker:
+ _objc_msgSend$_startObservingEngineChannels
+ _objc_msgSend$_stopObservingEngineChannels
+ _objc_msgSend$_updateTapMarkerColors
+ _objc_msgSend$addObserver:
+ _objc_msgSend$allKeysForObject:
+ _objc_msgSend$candidateFontForCandidate:style:
+ _objc_msgSend$didReceiveTouchSample:
+ _objc_msgSend$lastDotLocation
+ _objc_msgSend$lastFadeRestartTimestamp
+ _objc_msgSend$linePath
+ _objc_msgSend$location
+ _objc_msgSend$publishTouchEvent:
+ _objc_msgSend$radius
+ _objc_msgSend$removeObjectIdenticalTo:
+ _objc_msgSend$sampleLayer
+ _objc_msgSend$samplePath
+ _objc_msgSend$setFillRule:
+ _objc_msgSend$setKeyTimes:
+ _objc_msgSend$setLastDotLocation:
+ _objc_msgSend$setLastFadeRestartTimestamp:
+ _objc_msgSend$setLineCap:
+ _objc_msgSend$setLineJoin:
+ _objc_msgSend$setLinePath:
+ _objc_msgSend$setSampleLayer:
+ _objc_msgSend$setSamplePath:
+ _objc_msgSend$setShowsKeyHitGeometry:
+ _objc_msgSend$setShowsTouchPointMarkers:
+ _objc_msgSend$setStartLocation:
+ _objc_msgSend$setTapMarkerContainerLayer:
+ _objc_msgSend$setTapMarkerFadeGeneration:
+ _objc_msgSend$setTapMarkerReferenceSize:
+ _objc_msgSend$setTapMarkers:
+ _objc_msgSend$setTapMarkersByPathIndex:
+ _objc_msgSend$setTapTrailsByPathIndex:
+ _objc_msgSend$setTimingFunctions:
+ _objc_msgSend$setValues:
+ _objc_msgSend$showsKeyHitGeometry
+ _objc_msgSend$showsTouchPointMarkers
+ _objc_msgSend$stage
+ _objc_msgSend$startLocation
+ _objc_msgSend$stopObserving
+ _objc_msgSend$tapMarkerContainerLayer
+ _objc_msgSend$tapMarkerFadeGeneration
+ _objc_msgSend$tapMarkerReferenceSize
+ _objc_msgSend$tapMarkers
+ _objc_msgSend$tapMarkersByPathIndex
+ _objc_msgSend$tapTrailsByPathIndex
+ _objc_msgSend$timestamp
+ _observers.observers
+ _observers.onceToken
+ _sHasObservers
+ _symbolic Say_____G 11TextInputUI26AttributedSearchResultItemC
+ _symbolic So29TUIAttributedSearchResultItemC
+ _symbolic _____ 11TextInputUI26AttributedSearchResultItemC
+ _type_layout_string So7CGPointV
- -[TUIKeyboardHitDebugOverlay startObservingEngineChannels]
- -[TUIKeyboardHitDebugOverlay stopObservingEngineChannels]
- ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke
- ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke_2
- _objc_msgSend$startObservingEngineChannels
- _objc_msgSend$stopObservingEngineChannels
- _symbolic SaySo29TUIAttributedSearchResultItemCG
- _type_layout_string So6CGSizeV
CStrings:
+ "8"
+ "ShowTouchPointDebugUI"
+ "TUITapMarkerFade"
+ "TUITapMarkerFadeGeneration"
+ "TextInputUI.AttributedSearchResultItem"
+ "init(value:sourceBundleIdentifier:sourceItemIdentifier:contactLabel:attribute:isSelf:contactName:appName:)"
- "4"
```
