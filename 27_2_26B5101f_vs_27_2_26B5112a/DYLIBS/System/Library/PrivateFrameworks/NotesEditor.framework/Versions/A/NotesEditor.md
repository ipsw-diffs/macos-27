## NotesEditor

> `/System/Library/PrivateFrameworks/NotesEditor.framework/Versions/A/NotesEditor`

```diff

-3195.41.14.101.1
-  __TEXT.__text: 0x247214
+3195.42.3.0.0
+  __TEXT.__text: 0x249338
   __TEXT.__delay_helper: 0x114
-  __TEXT.__objc_methlist: 0x124a0
+  __TEXT.__objc_methlist: 0x12600
   __TEXT.__const: 0x9c58
-  __TEXT.__cstring: 0x99a0
-  __TEXT.__gcc_except_tab: 0x1ce4
+  __TEXT.__cstring: 0x9950
+  __TEXT.__gcc_except_tab: 0x1d64
   __TEXT.__ustring: 0x42c
   __TEXT.__oslogstring: 0x522c
-  __TEXT.__constg_swiftt: 0x40c0
-  __TEXT.__swift5_typeref: 0x2928f
+  __TEXT.__constg_swiftt: 0x40b8
+  __TEXT.__swift5_typeref: 0x292d5
   __TEXT.__swift5_builtin: 0x208
-  __TEXT.__swift5_reflstr: 0x396c
-  __TEXT.__swift5_fieldmd: 0x27ec
+  __TEXT.__swift5_reflstr: 0x39aa
+  __TEXT.__swift5_fieldmd: 0x2804
   __TEXT.__swift5_assocty: 0x5e8
   __TEXT.__swift5_proto: 0x280
   __TEXT.__swift5_types: 0x230
-  __TEXT.__swift5_capture: 0x23ac
+  __TEXT.__swift5_capture: 0x23dc
   __TEXT.__swift5_protos: 0x1c
   __TEXT.__swift_as_entry: 0x1ac
   __TEXT.__swift_as_cont: 0x3e8
   __TEXT.__swift_as_ret: 0x1a0
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x99f8
+  __TEXT.__unwind_info: 0x9ad8
   __TEXT.__eh_frame: 0x5e1c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc08
+  __DATA_CONST.__const: 0xc18
   __DATA_CONST.__objc_classlist: 0x5e8
   __DATA_CONST.__objc_catlist: 0x150
   __DATA_CONST.__objc_protolist: 0x418
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc938
+  __DATA_CONST.__objc_selrefs: 0xca38
   __DATA_CONST.__objc_protorefs: 0x118
   __DATA_CONST.__objc_superrefs: 0x370
-  __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0x2740
-  __AUTH_CONST.__const: 0xa4a8
+  __DATA_CONST.__objc_arraydata: 0x30
+  __DATA_CONST.__got: 0x27b8
+  __AUTH_CONST.__const: 0xa608
   __AUTH_CONST.__cfstring: 0x4c80
-  __AUTH_CONST.__objc_const: 0x19fe8
+  __AUTH_CONST.__objc_const: 0x1a0c8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__objc_intobj: 0xa8
-  __AUTH_CONST.__objc_arrayobj: 0x18
+  __AUTH_CONST.__objc_intobj: 0xd8
+  __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x2e50
-  __AUTH.__objc_data: 0x3590
+  __AUTH_CONST.__auth_got: 0x2e60
+  __AUTH.__objc_data: 0x3588
   __AUTH.__data: 0x1658
-  __DATA.__objc_ivar: 0xd88
-  __DATA.__data: 0x681c
+  __DATA.__objc_ivar: 0xd90
+  __DATA.__data: 0x689c
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0x3fd8
   __DATA.__common: 0x68
-  __DATA_DIRTY.__objc_data: 0x32e8
-  __DATA_DIRTY.__data: 0x1ec8
+  __DATA_DIRTY.__objc_data: 0x32f8
+  __DATA_DIRTY.__data: 0x1e98
   __DATA_DIRTY.__bss: 0x1670
   __DATA_DIRTY.__common: 0x110
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11852
-  Symbols:   16082
-  CStrings:  1493
+  Functions: 11909
+  Symbols:   16158
+  CStrings:  1492
 
Symbols:
+ -[ICAttachmentView setServicesRolloverHidden:]
+ -[ICMNoteEditorController announceIndentationLevelForAccessibilityAtIndex:]
+ -[ICMNoteEditorController indentListItemInRange:byAmount:]
+ -[ICMacBaseTextView contextMenuSelectedRangeAtPoint:]
+ -[ICMacBaseTextView isContextMenuSelectionAtPoint:]
+ -[ICMacBaseTextView showsContextMenuForSelectedTextOnLongPress]
+ -[ICMacTextView addListIndentSwipeGestureRecognizers]
+ -[ICMacTextView attachmentViewWithHiddenServicesRollover]
+ -[ICMacTextView canSwipeToIndentListItems]
+ -[ICMacTextView didSwipeToIndentListItem:]
+ -[ICMacTextView draggingSession:endedAtPoint:operation:]
+ -[ICMacTextView isAttributionSidebarClosed]
+ -[ICMacTextView listIndentDeltaForListItemInRange:swipingRight:]
+ -[ICMacTextView listIndentDeltaForSwipe:outRange:]
+ -[ICMacTextView listIndentSwipeGestureRecognizers]
+ -[ICMacTextView listItemRangeForIndentationAtPoint:]
+ -[ICMacTextView setAttachmentViewWithHiddenServicesRollover:]
+ -[ICMacTextView setListIndentSwipeGestureRecognizers:]
+ -[ICMacTextViewGestureRecognizerDelegate gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[ICMacTextViewGestureRecognizerDelegate gestureRecognizerShouldBegin:]
+ -[ICServicesRolloverView setHidden:]
+ -[ICTableAttachmentViewController withUndoCoalescingBreakingDisabled:]
+ -[ICTableColumnTextView showsContextMenuForSelectedTextOnLongPress]
+ GCC_except_table109
+ GCC_except_table132
+ GCC_except_table140
+ GCC_except_table153
+ GCC_except_table159
+ GCC_except_table181
+ GCC_except_table184
+ GCC_except_table192
+ GCC_except_table213
+ GCC_except_table221
+ GCC_except_table237
+ GCC_except_table245
+ GCC_except_table277
+ GCC_except_table282
+ GCC_except_table287
+ GCC_except_table307
+ GCC_except_table346
+ GCC_except_table396
+ GCC_except_table416
+ GCC_except_table425
+ GCC_except_table430
+ GCC_except_table435
+ GCC_except_table44
+ GCC_except_table53
+ GCC_except_table68
+ GCC_except_table72
+ OBJC_IVAR_$_ICMacTextView._attachmentViewWithHiddenServicesRollover
+ OBJC_IVAR_$_ICMacTextView._listIndentSwipeGestureRecognizers
+ _ICTTNamedStyleIsList
+ _OBJC_CLASS_$_ICMousePressGestureRecognizer
+ _OBJC_CLASS_$_ICPressGestureRecognizer
+ _OBJC_CLASS_$_ICTouchSwipeGestureRecognizer
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_NSSwipeGestureRecognizer
+ _TSURangeEnclosesRange
+ ___45-[ICMacTextView attributionSidebarController]_block_invoke
+ ___52-[ICMacTextView listItemRangeForIndentationAtPoint:]_block_invoke
+ ___58-[ICMNoteEditorController indentListItemInRange:byAmount:]_block_invoke
+ ___64-[ICMacTextView listIndentDeltaForListItemInRange:swipingRight:]_block_invoke
+ ___block_descriptor_40_e8_32w_e22_B28?0{CGPoint=dd}8B24l
+ ___block_descriptor_65_e8_32s40r_e46_v24?0"ICTTTextStorage"8"ICTextController"16l
+ ___block_descriptor_65_e8_32s_e46_v24?0"ICTTTextStorage"8"ICTextController"16l
+ ___block_descriptor_72_e8_32s40r48r_e46_v24?0"ICTTTextStorage"8"ICTextController"16l
+ _objc_msgSend$addListIndentSwipeGestureRecognizers
+ _objc_msgSend$announceIndentationLevelForAccessibilityAtIndex:
+ _objc_msgSend$attachmentViewWithHiddenServicesRollover
+ _objc_msgSend$canIndentTextView:byDelta:forRanges:
+ _objc_msgSend$canSwipeToIndentListItems
+ _objc_msgSend$cancelTouchPan
+ _objc_msgSend$contextMenuSelectedRangeAtPoint:
+ _objc_msgSend$direction
+ _objc_msgSend$indentListItemInRange:byAmount:
+ _objc_msgSend$indentRange:byAmount:inTextStorage:textView:forceUpdateAttributes:
+ _objc_msgSend$isAttributionSidebarClosed
+ _objc_msgSend$isContextMenuSelectionAtPoint:
+ _objc_msgSend$listIndentDeltaForListItemInRange:swipingRight:
+ _objc_msgSend$listIndentDeltaForSwipe:outRange:
+ _objc_msgSend$listIndentSwipeGestureRecognizers
+ _objc_msgSend$listItemRangeForIndentationAtPoint:
+ _objc_msgSend$processInfo
+ _objc_msgSend$setAllowedInputs:
+ _objc_msgSend$setAllowedPrimaryMovementSlop:
+ _objc_msgSend$setAttachmentViewWithHiddenServicesRollover:
+ _objc_msgSend$setDirection:
+ _objc_msgSend$setListIndentSwipeGestureRecognizers:
+ _objc_msgSend$setServicesRolloverHidden:
+ _objc_msgSend$setShouldDeferTouchPan:
+ _objc_msgSend$showsContextMenuForSelectedTextOnLongPress
+ _objc_msgSend$systemUptime
+ _objc_msgSend$touchPanGestureRecognizer
+ _objc_msgSend$withUndoCoalescingBreakingDisabled:
+ _symbolic Sb______SbtcSg So7CGPointV
+ _symbolic _____S2bIegnnr_ So7CGPointV
+ _symbolic _____S2bIegyyd_ So7CGPointV
+ _symbolic __________ABIeyByyd_ So7CGPointV 10ObjectiveC8ObjCBoolV
- GCC_except_table118
- GCC_except_table126
- GCC_except_table152
- GCC_except_table158
- GCC_except_table167
- GCC_except_table182
- GCC_except_table191
- GCC_except_table211
- GCC_except_table220
- GCC_except_table228
- GCC_except_table276
- GCC_except_table280
- GCC_except_table285
- GCC_except_table305
- GCC_except_table344
- GCC_except_table394
- GCC_except_table413
- GCC_except_table422
- GCC_except_table427
- GCC_except_table429
- GCC_except_table43
- GCC_except_table96
CStrings:
+ "B28@?0{CGPoint=dd}8B24"
+ "\x81\xd1a"
- "ICAttachmentViewInteraction.touchContextMenu"
- "ICAttachmentViewInteraction.touchPress"
- "\x81\xf01"
```
