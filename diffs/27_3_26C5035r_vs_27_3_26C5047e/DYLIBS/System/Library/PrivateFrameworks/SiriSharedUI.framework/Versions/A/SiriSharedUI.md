## SiriSharedUI

> `/System/Library/PrivateFrameworks/SiriSharedUI.framework/Versions/A/SiriSharedUI`

```diff

-3610.10.1.0.0
-  __TEXT.__text: 0x149398
-  __TEXT.__objc_methlist: 0x909c
-  __TEXT.__const: 0x84a4
-  __TEXT.__cstring: 0x92f2
-  __TEXT.__oslogstring: 0x19da
+3610.17.1.0.0
+  __TEXT.__text: 0x149c74
+  __TEXT.__objc_methlist: 0x90f4
+  __TEXT.__const: 0x84b4
+  __TEXT.__cstring: 0x9382
+  __TEXT.__oslogstring: 0x1a1a
   __TEXT.__gcc_except_tab: 0x3c4
   __TEXT.__ustring: 0x1a
   __TEXT.__constg_swiftt: 0x439c

   __TEXT.__swift_as_ret: 0xb4
   __TEXT.__swift_as_cont: 0x1b0
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x56e0
+  __TEXT.__unwind_info: 0x56f8
   __TEXT.__eh_frame: 0x29a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x348
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5480
+  __DATA_CONST.__objc_selrefs: 0x54b8
   __DATA_CONST.__objc_protorefs: 0x118
   __DATA_CONST.__objc_superrefs: 0x180
   __DATA_CONST.__objc_arraydata: 0xd0
   __DATA_CONST.__got: 0x1638
   __AUTH_CONST.__const: 0x5090
   __AUTH_CONST.__cfstring: 0x11e0
-  __AUTH_CONST.__objc_const: 0xfbe0
+  __AUTH_CONST.__objc_const: 0xfd50
   __AUTH_CONST.__objc_intobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0xd0
   __AUTH_CONST.__objc_arrayobj: 0x90
-  __AUTH_CONST.__auth_got: 0x2098
+  __AUTH_CONST.__auth_got: 0x20a0
   __AUTH.__objc_data: 0x1f70
   __AUTH.__data: 0x17e0
-  __DATA.__objc_ivar: 0x64c
+  __DATA.__objc_ivar: 0x674
   __DATA.__data: 0x49b0
   __DATA.__bss: 0x3c30
   __DATA.__common: 0xc8

   - /System/Library/PrivateFrameworks/TemplateKit.framework/Versions/A/TemplateKit
   - /System/Library/PrivateFrameworks/ToolKit.framework/Versions/A/ToolKit
   - /System/Library/PrivateFrameworks/_IconServices_SwiftUI.framework/Versions/A/_IconServices_SwiftUI
-  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7138
-  Symbols:   7140
-  CStrings:  980
+  Functions: 7146
+  Symbols:   7163
+  CStrings:  983
 
Symbols:
+ -[SiriSharedUICompactUserUtteranceView _flushPendingStreamingTextApply]
+ -[SiriSharedUICompactUserUtteranceView _scheduleStreamingTextApplyWithWords:showEditImage:carousel:preferredLeadingIconBundleIdentifier:]
+ -[SiriSharedUICompactUserUtteranceView setStreamingTextDeferWindow:]
+ -[SiriSharedUICompactUserUtteranceView streamingTextDeferWindow]
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._hasPendingStreamingTextApply
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._lastAppliedStreamingTransitionFadesGlyphs
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._lastAppliedStreamingWords
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._lastStreamingTextApplyTime
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._pendingStreamingCarousel
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._pendingStreamingLeadingIconBundleIdentifier
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._pendingStreamingShowEditImage
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._pendingStreamingWords
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._streamingTextApplyGeneration
+ _OBJC_IVAR_$_SiriSharedUICompactUserUtteranceView._streamingTextDeferWindow
+ _SRUIClassifyUtteranceWordsTransition
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PHPickerViewControllerDelegate
+ ___137-[SiriSharedUICompactUserUtteranceView _scheduleStreamingTextApplyWithWords:showEditImage:carousel:preferredLeadingIconBundleIdentifier:]_block_invoke
+ _dispatch_after
+ _dispatch_time
+ _objc_msgSend$_flushPendingStreamingTextApply
+ _objc_msgSend$_scheduleStreamingTextApplyWithWords:showEditImage:carousel:preferredLeadingIconBundleIdentifier:
+ _objc_msgSend$adjustTextFieldLeadingPadding
+ _objc_msgSend$allowsTrailingSafeAreaAdjustment
+ _objc_msgSend$setTextFieldViewCenterXConstraint:
+ _objc_msgSend$setTextFieldViewLeftConstraint:
+ _objc_msgSend$setTextFieldViewRightConstraint:
- GCC_except_table14
- _MGGetProductType
- _objc_msgSend$adjustTrailingSafeArea
CStrings:
+ "%s user utterance deferring setWords by %f to let fade-out finish"
+ "-[SiriSharedUICompactUserUtteranceView _scheduleStreamingTextApplyWithWords:showEditImage:carousel:preferredLeadingIconBundleIdentifier:]"
+ "\xd1"
```
