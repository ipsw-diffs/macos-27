## TextInputUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/TextInputUI.framework/Versions/A/TextInputUI`

```diff

-9127.2.6.0.0
-  __TEXT.__text: 0x11849c
-  __TEXT.__objc_methlist: 0xfb8c
-  __TEXT.__const: 0x320e
+9127.2.11.0.0
+  __TEXT.__text: 0x119598
+  __TEXT.__objc_methlist: 0xfb9c
+  __TEXT.__const: 0x321e
   __TEXT.__dlopen_cstrs: 0x22c
-  __TEXT.__swift5_typeref: 0x19ee
+  __TEXT.__swift5_typeref: 0x19f6
   __TEXT.__constg_swiftt: 0x13d8
   __TEXT.__swift5_builtin: 0x12c
   __TEXT.__swift5_reflstr: 0x895

   __TEXT.__cstring: 0xcc2b
   __TEXT.__swift5_proto: 0x120
   __TEXT.__swift5_types: 0x108
-  __TEXT.__oslogstring: 0x5222
+  __TEXT.__oslogstring: 0x52b3
   __TEXT.__swift5_capture: 0x480
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x48

   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__swift5_protos: 0xc
   __TEXT.__ustring: 0x258
-  __TEXT.__unwind_info: 0x47d0
+  __TEXT.__unwind_info: 0x47e8
   __TEXT.__eh_frame: 0x11f4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x280
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa170
+  __DATA_CONST.__objc_selrefs: 0xa180
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x428
   __DATA_CONST.__objc_arraydata: 0xa58
-  __DATA_CONST.__got: 0x13e8
+  __DATA_CONST.__got: 0x1400
   __AUTH_CONST.__const: 0x27b0
   __AUTH_CONST.__cfstring: 0xe5a0
   __AUTH_CONST.__objc_const: 0x19088

   __AUTH_CONST.__objc_doubleobj: 0x140
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0xe0
-  __AUTH_CONST.__auth_got: 0x1788
+  __AUTH_CONST.__auth_got: 0x17a0
   __AUTH.__objc_data: 0x3270
   __AUTH.__data: 0x8f8
   __DATA.__objc_ivar: 0x122c
-  __DATA.__data: 0x26b8
+  __DATA.__data: 0x26c8
   __DATA.__bss: 0x2878
   __DATA.__common: 0x168
   __DATA_DIRTY.__objc_data: 0x1fc8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6484
-  Symbols:   14837
-  CStrings:  2545
+  Functions: 6490
+  Symbols:   14841
+  CStrings:  2546
 
Symbols:
+ +[TUIKeyplaneView reuseActionForParentUnchanged:placementUnchanged:appliedConstraintsActive:appliedAnchorsStillLive:]
+ -[TUIKeyboardTrackingProvider sceneSizesMatch]
+ -[TUIKeyplane widenLeftControlColumnInKeyRow:]
+ -[TUISystemInputAssistantView cancelledTransitionToState:]
+ _objc_msgSend$reuseActionForParentUnchanged:placementUnchanged:appliedConstraintsActive:appliedAnchorsStillLive:
+ _objc_msgSend$sceneSizesMatch
+ _objc_msgSend$setCurrentPrompt:
+ _objc_msgSend$widenLeftControlColumnInKeyRow:
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV6PolicyV
- +[TUIKeyplaneView reuseActionForParentUnchanged:placementUnchanged:appliedAnchorsStillLive:]
- -[TUIKeyboardTrackingProvider screenBoundsMatch]
- _CGSizeNearlyEqualToSizeWithTolerance
- _objc_msgSend$reuseActionForParentUnchanged:placementUnchanged:appliedAnchorsStillLive:
- _objc_msgSend$screenBoundsMatch
CStrings:
+ "EmojiRemoteView Reanchored: key=%{public}@ placement changed or constraints deactivated under a cached remote view — rebuilding its constraints in %p (constraintsActive %d, hadWindow %d→%d, sameWindow %d, inKeyplaneTree %d→%d, extents %ld/%ld/%ld→%ld/%ld/%ld, offsets %.1f/%.1f→%.1f/%.1f)"
+ "GenerativeModelsAvailability: China policy detected, disabling generative suggestions"
- "EmojiRemoteView Reanchored: key=%{public}@ placement changed under a cached remote view — rebuilding its constraints in %p (hadWindow %d→%d, sameWindow %d, inKeyplaneTree %d→%d, extents %ld/%ld/%ld→%ld/%ld/%ld, offsets %.1f/%.1f→%.1f/%.1f)"
```
