## EventKitUI

> `/System/iOSSupport/System/Library/Frameworks/EventKitUI.framework/Versions/A/EventKitUI`

```diff

-1573.2.4.0.0
-  __TEXT.__text: 0x1e39e0
+1573.3.3.0.0
+  __TEXT.__text: 0x1e3bf0
   __TEXT.__objc_methlist: 0x2003c
   __TEXT.__const: 0x2e74
   __TEXT.__cstring: 0xc5e4

   __TEXT.__swift_as_entry: 0x48
   __TEXT.__swift_as_ret: 0x3c
   __TEXT.__swift_as_cont: 0xac
-  __TEXT.__unwind_info: 0x96b0
+  __TEXT.__unwind_info: 0x96b8
   __TEXT.__eh_frame: 0xbec
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x638
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf870
+  __DATA_CONST.__objc_selrefs: 0xf878
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x8b8
   __DATA_CONST.__objc_arraydata: 0x1b8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 12318
-  Symbols:   24870
+  Symbols:   24871
   CStrings:  2235
 
Symbols:
+ +[EKUIAvailabilityParticipantList listWidthForCompact:aspectRatioType:safeAreaInsets:]
+ _objc_msgSend$listWidthForCompact:aspectRatioType:safeAreaInsets:
+ _objc_msgSend$setWidthFollowsPreferredContentSizeWhenEdgeAttached:
- +[EKUIAvailabilityParticipantList listWidthForCompact:orientation:]
- _objc_msgSend$listWidthForCompact:orientation:
Functions:
~ -[EKEventProposeNewTimeViewController viewAvailabilityTapped] : 280 -> 316
~ -[EKUIEventInviteesViewController availabilityTapped] : 292 -> 320
~ -[EKEventEditViewControllerModernImpl requestInviteeAvailabilityPresentationWithEvent:] : 280 -> 308
~ +[EKUIAvailabilityViewController presentAvailabilityViewControllerForEvent:fromViewController:] : 176 -> 204
~ -[EKUIAvailabilityViewController sizeWillBeCompact:] : 252 -> 284
~ -[EKUIAvailabilityViewController loadView] : 5252 -> 5276
~ -[EKUIAvailabilityViewController layout] : 1316 -> 1424
~ -[EKUIAvailabilityViewController viewPinched:] : 592 -> 628
~ +[EKUIAvailabilityParticipantList listWidthForCompact:orientation:] -> +[EKUIAvailabilityParticipantList listWidthForCompact:aspectRatioType:safeAreaInsets:] : 48 -> 108
~ sub_1df206308 -> sub_1df72e484 : 112 -> 124
~ sub_1df222fe0 -> sub_1df74b168 : 108 -> 96
~ sub_1df2238dc -> sub_1df74ba58 : 432 -> 460
~ sub_1df2272a4 -> sub_1df74f43c : 300 -> 324
~ sub_1df228038 -> sub_1df7501e8 : 4736 -> 4832
```
