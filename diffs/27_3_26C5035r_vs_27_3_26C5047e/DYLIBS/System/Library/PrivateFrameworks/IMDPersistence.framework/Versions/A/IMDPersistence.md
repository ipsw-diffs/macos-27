## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x307774
-  __TEXT.__objc_methlist: 0xaf2c
-  __TEXT.__const: 0xc284
+1491.300.74.0.0
+  __TEXT.__text: 0x3090e8
+  __TEXT.__objc_methlist: 0xaf4c
+  __TEXT.__const: 0xc354
   __TEXT.__gcc_except_tab: 0xc830
-  __TEXT.__oslogstring: 0x3be2b
-  __TEXT.__cstring: 0x5ffab
+  __TEXT.__oslogstring: 0x3bf2b
+  __TEXT.__cstring: 0x5fffb
   __TEXT.__ustring: 0x434
   __TEXT.__dlopen_cstrs: 0x270
-  __TEXT.__swift5_typeref: 0x5204
-  __TEXT.__constg_swiftt: 0x58d4
+  __TEXT.__swift5_typeref: 0x524e
+  __TEXT.__constg_swiftt: 0x5970
   __TEXT.__swift5_builtin: 0x348
-  __TEXT.__swift5_reflstr: 0x38aa
-  __TEXT.__swift5_fieldmd: 0x3680
+  __TEXT.__swift5_reflstr: 0x38ba
+  __TEXT.__swift5_fieldmd: 0x36d0
   __TEXT.__swift5_assocty: 0x770
-  __TEXT.__swift5_capture: 0x1f7c
+  __TEXT.__swift5_capture: 0x1f9c
   __TEXT.__swift5_mpenum: 0x44
   __TEXT.__swift5_proto: 0x4bc
-  __TEXT.__swift5_types: 0x388
+  __TEXT.__swift5_types: 0x390
   __TEXT.__swift5_protos: 0x4c
-  __TEXT.__swift_as_entry: 0x14c
-  __TEXT.__swift_as_ret: 0x174
-  __TEXT.__swift_as_cont: 0x374
+  __TEXT.__swift_as_entry: 0x160
+  __TEXT.__swift_as_ret: 0x180
+  __TEXT.__swift_as_cont: 0x328
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xd898
-  __TEXT.__eh_frame: 0x9a38
+  __TEXT.__unwind_info: 0xd8e8
+  __TEXT.__eh_frame: 0x99f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x350
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ef0
+  __DATA_CONST.__objc_selrefs: 0x6f28
   __DATA_CONST.__objc_protorefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0x2c0
-  __DATA_CONST.__got: 0x1ca8
-  __AUTH_CONST.__const: 0x12060
+  __DATA_CONST.__got: 0x1cb0
+  __AUTH_CONST.__const: 0x12240
   __AUTH_CONST.__cfstring: 0x13c00
-  __AUTH_CONST.__objc_const: 0x15428
+  __AUTH_CONST.__objc_const: 0x15458
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2770
+  __AUTH_CONST.__auth_got: 0x2788
   __AUTH.__objc_data: 0x13d8
   __AUTH.__data: 0x1bb0
   __DATA.__objc_ivar: 0x628
-  __DATA.__data: 0x3968
+  __DATA.__data: 0x3a48
   __DATA.__bss: 0x5ef0
   __DATA.__common: 0x1f8
   __DATA_DIRTY.__objc_data: 0x3090

   - /usr/lib/swift/libswiftQuartzCore.dylib
   - /usr/lib/swift/libswiftRegexBuilder.dylib
   - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib
   - /usr/lib/swift/libswiftSystem.dylib
   - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14062
-  Symbols:   2877
-  CStrings:  7614
+  Functions: 14090
+  Symbols:   2879
+  CStrings:  7618
 
Symbols:
+ _OBJC_CLASS_$_IMBusinessLogoManager
+ _strlen
CStrings:
+ "Business logo fetched for %@, calling interaction updated handler"
+ "Clearing payload data for message %{public}@, balloonBundleID %{public}@, forceReplace %{BOOL}d"
+ "Dropping retraction stamp for message %{public}@, balloonBundleID %{public}@, forceReplace %{BOOL}d"
+ "INInteraction updated, updating posted notification for message %@"
+ "Not a Check In message from a known chat, leaving the notification untouched"
+ "SELECT date FROM message WHERE date > 0 ORDER BY date ASC LIMIT 1;"
+ "v16@?0@\"IMBusinessLogoFile\"8"
+ "withDisconnectHandling(cancellable:_:)"
- "Not synthesizing notification content from intent, message is a business chat message"
- "Unable to extract URL from Message, supressing the notification"
- "withThrowUponDisconnect(_:)"
- "withThrowingQueryProviderUponDisconnect(_:_:)"
```
