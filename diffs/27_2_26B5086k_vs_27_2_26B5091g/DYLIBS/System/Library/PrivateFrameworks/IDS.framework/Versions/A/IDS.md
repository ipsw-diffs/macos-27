## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/Versions/A/IDS`

```diff

-2003.200.33.1.5
-  __TEXT.__text: 0x1c3150
-  __TEXT.__objc_methlist: 0xdbd4
+2003.200.44.0.0
+  __TEXT.__text: 0x1c3a5c
+  __TEXT.__objc_methlist: 0xdbf4
   __TEXT.__const: 0x60f8
-  __TEXT.__cstring: 0x10b36
-  __TEXT.__oslogstring: 0x1bc18
+  __TEXT.__cstring: 0x10b96
+  __TEXT.__oslogstring: 0x1bee8
   __TEXT.__gcc_except_tab: 0x3e04
   __TEXT.__ustring: 0xac
   __TEXT.__dlopen_cstrs: 0x102

   __TEXT.__swift5_mpenum: 0x28
   __TEXT.__swift5_protos: 0x28
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__unwind_info: 0x8f78
+  __TEXT.__unwind_info: 0x8f80
   __TEXT.__eh_frame: 0x33d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd18
+  __DATA_CONST.__const: 0xd30
   __DATA_CONST.__objc_classlist: 0x5f8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6cf0
+  __DATA_CONST.__objc_selrefs: 0x6d08
   __DATA_CONST.__objc_protorefs: 0x128
   __DATA_CONST.__objc_superrefs: 0x478
   __DATA_CONST.__got: 0x1ab8
   __AUTH_CONST.__const: 0xa2e8
-  __AUTH_CONST.__cfstring: 0x75e0
-  __AUTH_CONST.__objc_const: 0x3d690
+  __AUTH_CONST.__cfstring: 0x7640
+  __AUTH_CONST.__objc_const: 0x3d6a0
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__objc_intobj: 0x588
+  __AUTH_CONST.__objc_intobj: 0x5b8
   __AUTH_CONST.__auth_got: 0x1cc0
-  __AUTH.__objc_data: 0x2118
+  __AUTH.__objc_data: 0x1bf0
   __AUTH.__data: 0x1580
   __DATA.__objc_ivar: 0xdf0
   __DATA.__data: 0x28b8
   __DATA.__bss: 0x99c0
   __DATA.__common: 0x10
-  __DATA_DIRTY.__objc_data: 0x1bd0
+  __DATA_DIRTY.__objc_data: 0x20f8
   __DATA_DIRTY.__bss: 0x3ca
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9528
-  Symbols:   1788
-  CStrings:  3821
+  Functions: 9531
+  Symbols:   1791
+  CStrings:  3837
 
Symbols:
+ _IDSDataChannelDrainingLinkKey
+ _IDSDataChannelDrainingReasonKey
+ _IDSDataChannelPreferenceSupportsLinkDrainingKey
CStrings:
+ "<%@> Can't find the linkContext of draining linkID %u"
+ "<%@> Can't find the linkContext of un-draining linkID %u"
+ "<%@> IDSDataChannelPreferenceSupportsLinkDrainingKey - client %s link draining"
+ "<%@> sent IDSDataChannelEventLinkDrainCancelled, linkID %u"
+ "<%@> sent IDSDataChannelEventLinkDraining, linkID %u, reason: %d"
+ "cancelDrainOfIDSDataChannelLinkContext: connection already closed"
+ "does not support"
+ "drainIDSDataChannelLinkContext: connection already closed"
+ "draining-link-key"
+ "draining-reason"
+ "got drain-cancelled linkID %d, linkUUID %@ (reason byte %d, unused)"
+ "got drainingLinkID %d, linkUUID %@, reason: %d"
+ "kClientChannelMetadataType_LinkDrainCancelled should be %d byte, not %u bytes, field: %u"
+ "kClientChannelMetadataType_LinkDraining should be %d byte, not %u bytes, field: %u"
+ "preference-supports-link-draining"
+ "supports"
```
