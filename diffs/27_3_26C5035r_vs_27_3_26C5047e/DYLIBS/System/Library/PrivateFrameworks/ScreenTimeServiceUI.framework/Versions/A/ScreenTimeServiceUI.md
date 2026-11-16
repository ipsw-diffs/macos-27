## ScreenTimeServiceUI

> `/System/Library/PrivateFrameworks/ScreenTimeServiceUI.framework/Versions/A/ScreenTimeServiceUI`

```diff

-655.2.7.0.0
-  __TEXT.__text: 0x1820
-  __TEXT.__objc_methlist: 0x30c
-  __TEXT.__const: 0x60
+655.2.12.100.0
+  __TEXT.__text: 0x2250
+  __TEXT.__objc_methlist: 0x364
+  __TEXT.__const: 0x84
   __TEXT.__gcc_except_tab: 0x2c
-  __TEXT.__cstring: 0xf6
-  __TEXT.__oslogstring: 0x187
-  __TEXT.__unwind_info: 0x128
+  __TEXT.__cstring: 0x10b
+  __TEXT.__oslogstring: 0x408
+  __TEXT.__unwind_info: 0x148
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x248
+  __DATA_CONST.__objc_selrefs: 0x330
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__got: 0x78
+  __DATA_CONST.__got: 0x88
   __AUTH_CONST.__const: 0x180
   __AUTH_CONST.__cfstring: 0xa0
-  __AUTH_CONST.__objc_const: 0xe40
+  __AUTH_CONST.__objc_const: 0xea0
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0xc
+  __DATA.__objc_ivar: 0x14
   __DATA.__data: 0x1e8
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 53
-  Symbols:   209
-  CStrings:  15
+  Functions: 62
+  Symbols:   254
+  CStrings:  21
 
Symbols:
+ -[STBlockingRemoteViewController _logGeometryWithEvent:requestedSize:]
+ -[STBlockingRemoteViewController _updateServiceSizeConstraintsWithSize:]
+ -[STBlockingRemoteViewController serviceHasRequestedResizeTo:]
+ -[STBlockingRemoteViewController serviceHeightConstraints]
+ -[STBlockingRemoteViewController serviceWidthConstraints]
+ -[STBlockingRemoteViewController setServiceHeightConstraints:]
+ -[STBlockingRemoteViewController setServiceWidthConstraints:]
+ GCC_except_table24
+ _NSStringFromClass
+ _NSStringFromRect
+ _NSStringFromSize
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSLayoutConstraint
+ _OBJC_IVAR_$_STBlockingRemoteViewController._serviceHeightConstraints
+ _OBJC_IVAR_$_STBlockingRemoteViewController._serviceWidthConstraints
+ _STServiceSizeConstraints
+ _objc_msgSend$_logGeometryWithEvent:requestedSize:
+ _objc_msgSend$_updateServiceSizeConstraintsWithSize:
+ _objc_msgSend$activateConstraints:
+ _objc_msgSend$arrayByAddingObjectsFromArray:
+ _objc_msgSend$arrayWithObjects:count:
+ _objc_msgSend$autoresizingMask
+ _objc_msgSend$constraintEqualToConstant:
+ _objc_msgSend$constraintGreaterThanOrEqualToConstant:
+ _objc_msgSend$contentCompressionResistancePriorityForOrientation:
+ _objc_msgSend$contentHuggingPriorityForOrientation:
+ _objc_msgSend$contentView
+ _objc_msgSend$frame
+ _objc_msgSend$heightAnchor
+ _objc_msgSend$inLiveResize
+ _objc_msgSend$intrinsicContentSize
+ _objc_msgSend$layoutIfNeeded
+ _objc_msgSend$remoteViewIdentifier
+ _objc_msgSend$serviceHeightConstraints
+ _objc_msgSend$serviceWidthConstraints
+ _objc_msgSend$setConstant:
+ _objc_msgSend$setFrameSize:
+ _objc_msgSend$setPriority:
+ _objc_msgSend$setServiceHeightConstraints:
+ _objc_msgSend$setServiceWidthConstraints:
+ _objc_msgSend$superview
+ _objc_msgSend$translatesAutoresizingMaskIntoConstraints
+ _objc_msgSend$widthAnchor
+ _objc_msgSend$windowNumber
+ _objc_opt_class
+ _objc_setProperty_atomic_copy
- GCC_except_table20
CStrings:
+ "STUI:: STBlockingRemoteViewController %{public}s requested size %{public}@ for %{public}@: view frame %{public}@, intrinsic size %{public}@, hugging (%.0f, %.0f), compression resistance (%.0f, %.0f), superview %{public}@ frame %{public}@, window %ld frame %{public}@, isContentView %{BOOL}d, translatesAutoresizingMask %{BOOL}d, autoresizingMask %#lx, inLiveResize %{BOOL}d"
+ "STUI:: STBlockingRemoteViewController ignoring invalid requested size %{public}@"
+ "STUI:: STBlockingRemoteViewController ignoring requested size %{public}@ as content view of window %ld"
+ "STUI:: STBlockingRemoteViewController ignoring setPreferredContentSize: %{public}@"
+ "did apply"
+ "will apply"
```
