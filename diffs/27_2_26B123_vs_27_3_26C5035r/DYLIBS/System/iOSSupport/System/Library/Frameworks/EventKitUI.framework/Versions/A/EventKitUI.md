## EventKitUI

> `/System/iOSSupport/System/Library/Frameworks/EventKitUI.framework/Versions/A/EventKitUI`

```diff

-1573.2.2.0.0
-  __TEXT.__text: 0x1e38a4
+1573.2.4.0.0
+  __TEXT.__text: 0x1e39e0
   __TEXT.__objc_methlist: 0x2003c
   __TEXT.__const: 0x2e74
   __TEXT.__cstring: 0xc5e4

   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x638
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf850
+  __DATA_CONST.__objc_selrefs: 0xf870
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x8b8
   __DATA_CONST.__objc_arraydata: 0x1b8

   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x17b0
+  __AUTH_CONST.__auth_got: 0x17b8
   __AUTH.__objc_data: 0x7cb0
   __AUTH.__data: 0x1048
   __DATA.__objc_ivar: 0x2594

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 12318
-  Symbols:   24864
+  Symbols:   24870
   CStrings:  2235
 
Symbols:
+ _CalCompositeViewsEnabled
+ _OBJC_IVAR_$_EKSubscribedCalendarDescriptionHeader._lastLabelWidth
+ _objc_msgSend$_setNavigationBarSafeAreaAdjustment:
+ _objc_msgSend$_setPreferredAxis:
+ _objc_msgSend$_verticalBarEdge
+ _objc_msgSend$searchBarPlacementBarButtonItem
+ _objc_msgSend$setHidesPrimaryDate:
- _OBJC_IVAR_$_EKSubscribedCalendarDescriptionHeader._lastParentWidth
Functions:
~ -[EKDayViewWithGutters initWithFrame:dayView:sizeClass:showWeekDayLabel:showWeekNumberLabel:] : 1696 -> 1712
~ -[EKEventViewControllerDefaultImpl _updateNavBarAnimated:] : 552 -> 640
~ -[EKCalendarSubscriptionDetailsViewController viewWillLayoutSubviews] : 88 -> 160
~ -[EKSubscribedCalendarDescriptionHeader updateLayoutForWidth:] : 240 -> 308
~ -[EKEventDetailLocationDisambiguationContentViewController viewDidLoad] : 1372 -> 1416
~ -[UITraitCollection(EventKitUI) ekui_hasLeadingOrTrailingVerticalBar] : 8 -> 36
```
