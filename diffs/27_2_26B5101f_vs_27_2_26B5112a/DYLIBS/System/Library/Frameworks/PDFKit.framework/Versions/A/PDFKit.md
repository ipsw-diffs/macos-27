## PDFKit

> `/System/Library/Frameworks/PDFKit.framework/Versions/A/PDFKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1537.1.2.0.0
-  __TEXT.__text: 0xdd7cc
-  __TEXT.__objc_methlist: 0xc8d0
-  __TEXT.__const: 0x9d4
-  __TEXT.__gcc_except_tab: 0x84d8
+1537.1.4.0.0
+  __TEXT.__text: 0xde7c8
+  __TEXT.__objc_methlist: 0xc9d0
+  __TEXT.__const: 0x9b4
+  __TEXT.__gcc_except_tab: 0x8410
   __TEXT.__cstring: 0x8074
   __TEXT.__dlopen_cstrs: 0x257
   __TEXT.__ustring: 0xc2

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x18
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x4e80
+  __TEXT.__unwind_info: 0x4eb8
   __TEXT.__eh_frame: 0x128
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x188
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7998
+  __DATA_CONST.__objc_selrefs: 0x7a40
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x378
   __DATA_CONST.__objc_arraydata: 0x1d0
   __DATA_CONST.__got: 0xdd0
   __AUTH_CONST.__const: 0x2308
   __AUTH_CONST.__cfstring: 0x8880
-  __AUTH_CONST.__objc_const: 0x11900
+  __AUTH_CONST.__objc_const: 0x119e0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_intobj: 0x5e8

   __AUTH_CONST.__auth_got: 0x18a8
   __AUTH.__objc_data: 0x19a0
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0xe80
+  __DATA.__objc_ivar: 0xe9c
   __DATA.__data: 0x1310
   __DATA.__bss: 0x630
   __DATA_DIRTY.__objc_data: 0x1c20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4492
-  Symbols:   11812
+  Functions: 4509
+  Symbols:   11857
   CStrings:  1426
 
Symbols:
+ -[PDFKitTextView _beginEditingSession]
+ -[PDFKitTextView _commitStringToModel:]
+ -[PDFKitTextView _replacementOverflowsWidget:inRange:forTextView:]
+ -[PDFKitTextView textDidBeginEditing:]
+ -[PDFKitTextView textView:shouldChangeTextInRange:replacementString:]
+ -[PDFView _alignArrivingPageViews:goingToNextPage:]
+ -[PDFView _beginTouchPageSwipeWithTranslation:gesture:]
+ -[PDFView _completePageTransitionWithSuccess:]
+ -[PDFView _detachPageViewInPlace:]
+ -[PDFView _finishInFlightPageTransitionImmediately]
+ -[PDFView _finishTouchPageSwipeForGesture:state:]
+ -[PDFView _pageTransitionTravelDistance]
+ -[PDFView _readingOriginForPageFrame:visibleRect:steppingBack:]
+ -[PDFView _reattachPageViewInPlace:]
+ -[PDFView _scrollForPassedThroughTouchDrag:]
+ -[PDFView _scrollToReadingStartOfCurrentPageComingFromPage:]
+ -[PDFView _shouldHandleScannerResultAtPagePoint:onPage:]
+ -[PDFView _touchDragShouldTurnPage:]
+ -[PDFView _updatePageTransitionWithAmount:]
+ -[PDFView _updateTouchPageSwipeForChangedGesture:]
+ -[PDFView isAtPageTurnEdgeForHorizontalScroll:goingToNextPage:]
+ GCC_except_table325
+ GCC_except_table332
+ GCC_except_table377
+ GCC_except_table385
+ OBJC_IVAR_$_PDFKitTextViewPrivate.isCommittingOwnEdit
+ OBJC_IVAR_$_PDFKitTextViewPrivate.preEditValue
+ OBJC_IVAR_$_PDFKitTextViewPrivate.sessionUndoRegistered
+ OBJC_IVAR_$_PDFViewPrivate.isPassingTouchDragToScrollView
+ OBJC_IVAR_$_PDFViewPrivate.pageTransitionGeneration
+ OBJC_IVAR_$_PDFViewPrivate.pageTransitionSucceeded
+ OBJC_IVAR_$_PDFViewPrivate.suppressScrollOffsetRestoreOnResize
+ OBJC_IVAR_$_PDFViewPrivate.touchPassThroughStartOrigin
+ OBJC_IVAR_$_PDFViewPrivate.touchSwipeTranslationOffset
+ __49-[PDFView _finishTouchPageSwipeForGesture:state:]_block_invoke
+ ___49-[PDFView _finishTouchPageSwipeForGesture:state:]_block_invoke
+ ___block_descriptor_49_e8_32w_e5_v8?0l
+ ___block_descriptor_66_e8_32w_e18_v36?0d8Q16B24^B28l
+ _objc_msgSend$_alignArrivingPageViews:goingToNextPage:
+ _objc_msgSend$_beginEditingSession
+ _objc_msgSend$_beginTouchPageSwipeWithTranslation:gesture:
+ _objc_msgSend$_commitStringToModel:
+ _objc_msgSend$_completePageTransitionWithSuccess:
+ _objc_msgSend$_detachPageViewInPlace:
+ _objc_msgSend$_finishInFlightPageTransitionImmediately
+ _objc_msgSend$_finishTouchPageSwipeForGesture:state:
+ _objc_msgSend$_pageTransitionTravelDistance
+ _objc_msgSend$_readingOriginForPageFrame:visibleRect:steppingBack:
+ _objc_msgSend$_reattachPageViewInPlace:
+ _objc_msgSend$_replacementOverflowsWidget:inRange:forTextView:
+ _objc_msgSend$_scrollForPassedThroughTouchDrag:
+ _objc_msgSend$_scrollToReadingStartOfCurrentPageComingFromPage:
+ _objc_msgSend$_shouldHandleScannerResultAtPagePoint:onPage:
+ _objc_msgSend$_touchDragShouldTurnPage:
+ _objc_msgSend$_updatePageTransitionWithAmount:
+ _objc_msgSend$_updateTouchPageSwipeForChangedGesture:
+ _objc_msgSend$isAtPageTurnEdgeForHorizontalScroll:goingToNextPage:
+ _objc_msgSend$stringByReplacingCharactersInRange:withString:
+ _objc_msgSend$textContainerInset
- GCC_except_table320
- GCC_except_table327
- GCC_except_table366
- GCC_except_table371
- OBJC_IVAR_$_PDFViewPrivate.originalCurrentPageViewFrames
- OBJC_IVAR_$_PDFViewPrivate.originalTopPageViewFrames
- __32-[PDFView handleTouchPageSwipe:]_block_invoke
- ___32-[PDFView handleTouchPageSwipe:]_block_invoke
- ___block_descriptor_89_e8_32s40s48s56w_e5_v8?0l
- ___block_descriptor_98_e8_32s40s48s56s64w_e18_v36?0d8Q16B24^B28l
- ___copy_helper_block_e8_32s40s48s56s64w
- ___copy_helper_block_e8_32s40s48s56w
- ___destroy_helper_block_e8_32s40s48s56s64w
- ___destroy_helper_block_e8_32s40s48s56w
```
