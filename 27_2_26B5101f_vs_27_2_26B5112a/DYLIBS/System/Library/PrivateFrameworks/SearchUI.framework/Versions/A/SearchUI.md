## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/Versions/A/SearchUI`

```diff

-685.1.8.0.0
-  __TEXT.__text: 0xce0bc
-  __TEXT.__objc_methlist: 0xf7bc
-  __TEXT.__const: 0x2f74
-  __TEXT.__cstring: 0x3514
+685.1.10.100.0
+  __TEXT.__text: 0xcee90
+  __TEXT.__objc_methlist: 0xf8cc
+  __TEXT.__const: 0x2f84
+  __TEXT.__cstring: 0x3544
   __TEXT.__oslogstring: 0x2685
   __TEXT.__gcc_except_tab: 0x7d0
   __TEXT.__ustring: 0xa8

   __TEXT.__swift_as_ret: 0xdc
   __TEXT.__swift_as_cont: 0x164
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4758
+  __TEXT.__unwind_info: 0x47b8
   __TEXT.__eh_frame: 0x1a20
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__const: 0x6a0
   __DATA_CONST.__objc_classlist: 0x9d0
   __DATA_CONST.__objc_catlist: 0x408
-  __DATA_CONST.__objc_protolist: 0x2e0
+  __DATA_CONST.__objc_protolist: 0x2e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x86d8
+  __DATA_CONST.__objc_selrefs: 0x87b0
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x1e20
+  __DATA_CONST.__got: 0x1e70
   __AUTH_CONST.__const: 0x3ca0
-  __AUTH_CONST.__cfstring: 0x3660
-  __AUTH_CONST.__objc_const: 0x1ae60
+  __AUTH_CONST.__cfstring: 0x36a0
+  __AUTH_CONST.__objc_const: 0x1af10
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_arrayobj: 0x9c0
   __AUTH_CONST.__objc_dictobj: 0x28

   __AUTH_CONST.__auth_got: 0x1418
   __AUTH.__objc_data: 0x2d88
   __AUTH.__data: 0x3c8
-  __DATA.__objc_ivar: 0xbb0
-  __DATA.__data: 0x25b0
+  __DATA.__objc_ivar: 0xbbc
+  __DATA.__data: 0x2670
   __DATA.__bss: 0xa78
   __DATA.__common: 0xe8
   __DATA_DIRTY.__objc_data: 0x4138
-  __DATA_DIRTY.__data: 0xba8
+  __DATA_DIRTY.__data: 0xbb8
   __DATA_DIRTY.__bss: 0x1830
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5951
-  Symbols:   13518
-  CStrings:  802
+  Functions: 5978
+  Symbols:   13564
+  CStrings:  804
 
Symbols:
+ -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:backgroundStyle:]
+ -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_maximumNumberOfVisibleCardSectionsForWidth:]
+ -[SFLinkPresentationCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:backgroundStyle:]
+ -[SearchUICollectionView executeCommandForGesture:]
+ -[SearchUICollectionView gestureRecognizer:shouldAttemptToRecognizeWithEvent:]
+ -[SearchUICollectionView gestureRecognizer:shouldReceiveTouch:]
+ -[SearchUICollectionView gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[SearchUICollectionView searchui_executeCommandForClickAtPoint:triggerEvent:]
+ -[SearchUICollectionView searchui_handleClick:]
+ -[SearchUICollectionView searchui_handleDoubleClick:]
+ -[SearchUICollectionView searchui_handleDragSelect:]
+ -[SearchUICollectionView searchui_handleTouchTap:]
+ -[SearchUICollectionView searchui_installGestureRecognizers]
+ -[SearchUICollectionView searchui_isActionControlAtPoint:]
+ -[SearchUICollectionView searchui_singleTapRuns]
+ -[SearchUICollectionView selectIndexPathAtPoint:scrollToVisible:]
+ -[SearchUICollectionViewController applySelectionSideEffectsForIndexPaths:scrollToVisible:]
+ -[SearchUICollectionViewController executeCommandForIndexPath:triggerEvent:]
+ -[SearchUICollectionViewDataSource truncatedVisibleCardSectionsAsyncSectionModel:]
+ -[SearchUICollectionViewDataSource updatePositionalStylingForCell:atIndexPath:]
+ -[SearchUIGridSectionModel maximumNumberOfVisibleCardSectionsForWidth:]
+ -[SearchUISectionModel maximumNumberOfVisibleCardSectionsForWidth:]
+ GCC_except_table31
+ OBJC_IVAR_$_SearchUICollectionView._dragSelectRecognizer
+ OBJC_IVAR_$_SearchUICollectionView._prototypeDefaults
+ OBJC_IVAR_$_SearchUICollectionView._touchTapRecognizer
+ _OBJC_CLASS_$_NSPressGestureRecognizer
+ _OBJC_CLASS_$_NSUserDefaults
+ _SearchUINoMaximumVisibleCardSections
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSGestureRecognizerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSGestureRecognizerDelegate
+ __OBJC_$_PROTOCOL_REFS_NSGestureRecognizerDelegate
+ __OBJC_LABEL_PROTOCOL_$_NSGestureRecognizerDelegate
+ __OBJC_PROTOCOL_$_NSGestureRecognizerDelegate
+ _objc_msgSend$applySelectionSideEffectsForIndexPaths:scrollToVisible:
+ _objc_msgSend$convertPoint:toView:
+ _objc_msgSend$executeCommandForGesture:
+ _objc_msgSend$executeCommandForIndexPath:triggerEvent:
+ _objc_msgSend$hitTest:
+ _objc_msgSend$indexPathsForVisibleItems
+ _objc_msgSend$initWithSuiteName:
+ _objc_msgSend$locationInView:
+ _objc_msgSend$searchUIGridSectionModel_groupInsetFor:backgroundStyle:
+ _objc_msgSend$searchUIGridSectionModel_maximumNumberOfVisibleCardSectionsForWidth:
+ _objc_msgSend$searchui_executeCommandForClickAtPoint:triggerEvent:
+ _objc_msgSend$searchui_installGestureRecognizers
+ _objc_msgSend$searchui_isActionControlAtPoint:
+ _objc_msgSend$searchui_singleTapRuns
+ _objc_msgSend$selectIndexPathAtPoint:scrollToVisible:
+ _objc_msgSend$setAllowableMovement:
+ _objc_msgSend$setAllowedTouchTypes:
+ _objc_msgSend$setButtonMask:
+ _objc_msgSend$setDelaysPrimaryMouseButtonEvents:
+ _objc_msgSend$setNumberOfClicksRequired:
+ _objc_msgSend$setNumberOfTouchesRequired:
+ _objc_msgSend$truncatedVisibleCardSectionsAsyncSectionModel:
+ _objc_msgSend$updatePositionalStylingForCell:atIndexPath:
- -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:]
- -[SFLinkPresentationCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:]
- -[SearchUICollectionView mouseDown:]
- -[SearchUICollectionView mouseDragged:]
- -[SearchUICollectionView mouseUp:]
- -[SearchUICollectionView selectIndexPathForEvent:scrollToVisible:]
- GCC_except_table29
- _objc_msgSend$clickCount
- _objc_msgSend$rightMouseDown:
- _objc_msgSend$searchUIGridSectionModel_groupInsetFor:
- _objc_msgSend$selectIndexPathForEvent:scrollToVisible:
CStrings:
+ "SearchUISingleTapToRun"
+ "com.apple.spotlight.prototype"
```
