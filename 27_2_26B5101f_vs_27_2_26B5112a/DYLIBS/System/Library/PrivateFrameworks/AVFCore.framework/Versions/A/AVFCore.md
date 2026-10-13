## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/Versions/A/AVFCore`

```diff

-2475.12.1.0.0
-  __TEXT.__text: 0x1b5078
-  __TEXT.__objc_methlist: 0x1bf8c
-  __TEXT.__gcc_except_tab: 0x98c0
+2475.13.5.1.0
+  __TEXT.__text: 0x1b5400
+  __TEXT.__objc_methlist: 0x1bf94
+  __TEXT.__gcc_except_tab: 0x98d8
   __TEXT.__const: 0x1f2c
   __TEXT.__cstring: 0x2713b
-  __TEXT.__oslogstring: 0x4a3b
+  __TEXT.__oslogstring: 0x4ab6
   __TEXT.__ustring: 0x18
   __TEXT.__swift5_typeref: 0x41a
   __TEXT.__constg_swiftt: 0x290

   __TEXT.__swift5_proto: 0x6c
   __TEXT.__swift5_types: 0x48
   __TEXT.__swift5_capture: 0x60
-  __TEXT.__unwind_info: 0xc3a0
+  __TEXT.__unwind_info: 0xc3a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb1f0
+  __DATA_CONST.__objc_selrefs: 0xb1f8
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0xd88
   __DATA_CONST.__objc_arraydata: 0x308

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12002
-  Symbols:   28092
-  CStrings:  4284
+  Functions: 12003
+  Symbols:   28094
+  CStrings:  4285
 
Symbols:
+ -[AVPlayerItemIntegratedTimelinePeriodicObserver _doesTimeResideInPrimarySegment:atTime:timeMappingOut:]
+ _objc_msgSend$_doesTimeResideInPrimarySegment:atTime:timeMappingOut:
Functions:
~ -[AVPlayerItemIntegratedTimelinePeriodicObserver rescheduleObserverWithSnapshot:itemToSchedule:] : 1984 -> 2120
~ -[AVSampleBufferVideoRenderer _setRequiresFlushToResumeDecoding:] : 708 -> 1104
~ ___65-[AVSampleBufferVideoRenderer _setRequiresFlushToResumeDecoding:]_block_invoke : 44 -> 112
+ -[AVPlayerItemIntegratedTimelinePeriodicObserver _doesTimeResideInPrimarySegment:atTime:timeMappingOut:]
CStrings:
+ "<<<< AVSampleBufferVideoRenderer >>>> %s: <%{public}@|%p> Waking a suspended Swift enqueue because a flush is now required"
```
