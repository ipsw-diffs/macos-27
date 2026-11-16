## NewDeviceOutreachMacExtension

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/PlugIns/NewDeviceOutreachMacExtension.appex/Contents/MacOS/NewDeviceOutreachMacExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-624.40.22.0.0
-  __TEXT.__text: 0x15cc
-  __TEXT.__auth_stubs: 0xf0
-  __TEXT.__objc_stubs: 0x460
-  __TEXT.__objc_methlist: 0x454
-  __TEXT.__const: 0x38
-  __TEXT.__cstring: 0x3e5
-  __TEXT.__objc_methname: 0xbc3
-  __TEXT.__oslogstring: 0x1d0
+624.60.5.0.0
+  __TEXT.__text: 0x1cb0
+  __TEXT.__auth_stubs: 0x100
+  __TEXT.__objc_stubs: 0x540
+  __TEXT.__objc_methlist: 0x46c
+  __TEXT.__const: 0x48
+  __TEXT.__cstring: 0x59f
+  __TEXT.__objc_methname: 0xcb9
+  __TEXT.__oslogstring: 0x298
   __TEXT.__objc_classname: 0x37
   __TEXT.__objc_methtype: 0x5bf
-  __TEXT.__unwind_info: 0xd0
-  __DATA_CONST.__const: 0x150
-  __DATA_CONST.__cfstring: 0x280
+  __TEXT.__unwind_info: 0xf0
+  __DATA_CONST.__const: 0x1b0
+  __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x80
-  __DATA_CONST.__got: 0x30
+  __DATA_CONST.__auth_got: 0x88
+  __DATA_CONST.__got: 0x40
   __DATA.__objc_const: 0x430
-  __DATA.__objc_selrefs: 0x398
+  __DATA.__objc_selrefs: 0x3d0
   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x50
   __DATA.__data: 0xc0

   - /System/Library/PrivateFrameworks/NewDeviceOutreachMacUI.framework/Versions/A/NewDeviceOutreachMacUI
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 35
-  Symbols:   33
-  CStrings:  223
+  Functions: 42
+  Symbols:   36
+  CStrings:  243
 
Symbols:
+ _OBJC_CLASS_$_NSArray
+ ___stack_chk_fail
+ ___stack_chk_guard
CStrings:
+ "%s: Failed to reject follow up %{private}@: %@"
+ "%s: Rejected follow up %{private}@"
+ "%s: Rejecting follow up %{private}@"
+ "%s: Server does not require an ack for action %{public}@ of follow up %{private}@"
+ "-[NDOACExtentionViewController acknowledgeFollowUpItem:selectedAction:]"
+ "-[NDOACExtentionViewController processRejectActionForFollowUpItem:completion:]"
+ "-[NDOACExtentionViewController processRejectActionForFollowUpItem:completion:]_block_invoke"
+ "acknowledgeFollowUpItem:selectedAction:"
+ "acknowledgeFollowUpWithIdentifier:ackSource:userActionType:acknowledgeData:"
+ "arrayWithObjects:count:"
+ "dismissFollowUps:completion:"
+ "integerValue"
+ "ndo-follow-up-action-ack-source"
+ "ndo-follow-up-action-acknowledge-data"
+ "ndo-follow-up-action-requires-ack"
+ "ndo-follow-up-action-user-action-type"
+ "ndo-follow-up-reject-action-identifier"
+ "processRejectActionForFollowUpItem:completion:"
+ "uniqueIdentifier"
+ "v16@?0@\"NSError\"8"
```
