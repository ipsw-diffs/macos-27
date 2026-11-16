## IMDPersistence

> `/System/iOSSupport/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x2f05b8
-  __TEXT.__objc_methlist: 0xa97c
-  __TEXT.__const: 0xc198
-  __TEXT.__cstring: 0x5eec4
-  __TEXT.__oslogstring: 0x3bfd4
-  __TEXT.__gcc_except_tab: 0xc588
+1491.300.74.0.0
+  __TEXT.__text: 0x2f1fcc
+  __TEXT.__objc_methlist: 0xa99c
+  __TEXT.__const: 0xc2a8
+  __TEXT.__cstring: 0x5ef14
+  __TEXT.__oslogstring: 0x3c0d4
+  __TEXT.__gcc_except_tab: 0xc590
   __TEXT.__ustring: 0x434
   __TEXT.__dlopen_cstrs: 0x21a
-  __TEXT.__swift5_typeref: 0x5204
-  __TEXT.__swift5_capture: 0x1f7c
-  __TEXT.__constg_swiftt: 0x58d4
+  __TEXT.__swift5_typeref: 0x524e
+  __TEXT.__swift5_capture: 0x1f9c
+  __TEXT.__constg_swiftt: 0x5970
   __TEXT.__swift5_builtin: 0x348
-  __TEXT.__swift5_reflstr: 0x3899
-  __TEXT.__swift5_fieldmd: 0x3680
+  __TEXT.__swift5_reflstr: 0x38b9
+  __TEXT.__swift5_fieldmd: 0x36d0
   __TEXT.__swift5_assocty: 0x770
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
   __TEXT.__swift5_mpenum: 0x44
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xd600
-  __TEXT.__eh_frame: 0x9a1c
+  __TEXT.__unwind_info: 0xd678
+  __TEXT.__eh_frame: 0x99fc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6558
+  __DATA_CONST.__const: 0x6580
   __DATA_CONST.__objc_classlist: 0x708
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x350
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6be0
+  __DATA_CONST.__objc_selrefs: 0x6c18
   __DATA_CONST.__objc_protorefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x238
   __DATA_CONST.__objc_arraydata: 0x2c0
-  __DATA_CONST.__got: 0x1bf8
-  __AUTH_CONST.__const: 0xe260
+  __DATA_CONST.__got: 0x1c00
+  __AUTH_CONST.__const: 0xe410
   __AUTH_CONST.__cfstring: 0x13060
-  __AUTH_CONST.__objc_const: 0x146d0
+  __AUTH_CONST.__objc_const: 0x14700
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2920
+  __AUTH_CONST.__auth_got: 0x2938
   __AUTH.__objc_data: 0x11f8
   __AUTH.__data: 0x1b98
   __DATA.__objc_ivar: 0x580
-  __DATA.__data: 0x39b8
+  __DATA.__data: 0x3ab8
   __DATA.__bss: 0x5e48
   __DATA.__common: 0x1f8
   __DATA_DIRTY.__objc_data: 0x2ff0

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
-  Functions: 13809
-  Symbols:   2870
-  CStrings:  7519
+  Functions: 13841
+  Symbols:   2872
+  CStrings:  7523
 
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
