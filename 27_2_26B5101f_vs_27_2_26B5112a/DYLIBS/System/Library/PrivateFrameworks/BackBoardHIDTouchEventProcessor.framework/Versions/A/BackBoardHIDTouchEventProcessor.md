## BackBoardHIDTouchEventProcessor

> `/System/Library/PrivateFrameworks/BackBoardHIDTouchEventProcessor.framework/Versions/A/BackBoardHIDTouchEventProcessor`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-877.2.2.0.0
-  __TEXT.__text: 0x3c0c8
+877.2.2.101.0
+  __TEXT.__text: 0x3c484
   __TEXT.__objc_methlist: 0x27e0
   __TEXT.__const: 0x400
   __TEXT.__constg_swiftt: 0x124

   __TEXT.__cstring: 0x1e4f
   __TEXT.__swift5_types: 0x14
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__gcc_except_tab: 0x3f2c
-  __TEXT.__oslogstring: 0x2cc2
+  __TEXT.__gcc_except_tab: 0x3fb4
+  __TEXT.__oslogstring: 0x2d13
   __TEXT.__ustring: 0xc
   __TEXT.__unwind_info: 0x1638
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1ae8
+  __DATA_CONST.__objc_selrefs: 0x1af0
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x168
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x560
   __AUTH_CONST.__const: 0x19c0
   __AUTH_CONST.__cfstring: 0x2020
-  __AUTH_CONST.__objc_const: 0x6f20
+  __AUTH_CONST.__objc_const: 0x6f40
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x6c0
   __AUTH.__objc_data: 0x988
   __AUTH.__data: 0xb8
-  __DATA.__objc_ivar: 0x54c
+  __DATA.__objc_ivar: 0x550
   __DATA.__data: 0xcc8
   __DATA.__bss: 0xf8
   __DATA.__common: 0x1

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 1125
-  Symbols:   3508
-  CStrings:  573
+  Symbols:   3510
+  CStrings:  574
 
Symbols:
+ OBJC_IVAR_$_BKTouchContact._alwaysSendDestinationsNotFoundByHitTest
+ _objc_msgSend$unionSet:
Functions:
~ ___63-[BKHIDDirectTouchEventProcessor cancelTouchesWithIdentifiers:]_block_invoke_2 : 160 -> 696
~ -[BKDirectTouchStateHitTester determineHitTestDestinationsForPathCollection:contacts:hitTestRegions:destinationsByTargetID:contactsByTargetID:] : 8576 -> 8776
~ -[BKDirectTouchState handlePathCollectionEvent:] : 8392 -> 8404
~ -[BKDirectTouchState _appendSubsetOfHIDCollection:forDestination:toEventPoster:systemGestureIsPossible:pathLocations:initialTouchTimestamp:] : 4444 -> 4640
~ -[BKTouchContact .cxx_destruct] : 128 -> 140
CStrings:
+ "Filtering pathIndex:%d from ctx:%{public}@ because it was cancelled by a gesture"
```
