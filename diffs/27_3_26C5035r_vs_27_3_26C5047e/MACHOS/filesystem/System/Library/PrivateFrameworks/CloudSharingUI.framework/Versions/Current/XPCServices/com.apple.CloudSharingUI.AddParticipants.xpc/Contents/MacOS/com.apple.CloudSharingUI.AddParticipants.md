## com.apple.CloudSharingUI.AddParticipants

> `/System/Library/PrivateFrameworks/CloudSharingUI.framework/Versions/Current/XPCServices/com.apple.CloudSharingUI.AddParticipants.xpc/Contents/MacOS/com.apple.CloudSharingUI.AddParticipants`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-240.2.4.0.0
-  __TEXT.__text: 0xa3058
+240.2.6.0.0
+  __TEXT.__text: 0xa3b30
   __TEXT.__auth_stubs: 0x1760
   __TEXT.__objc_stubs: 0x1920
-  __TEXT.__objc_methlist: 0x620
+  __TEXT.__objc_methlist: 0x66c
   __TEXT.__const: 0x4490
   __TEXT.__cstring: 0x2873
-  __TEXT.__objc_methname: 0x30a9
+  __TEXT.__objc_methname: 0x3309
   __TEXT.__objc_classname: 0x3cd
-  __TEXT.__objc_methtype: 0x122b
+  __TEXT.__objc_methtype: 0x13bb
   __TEXT.__gcc_except_tab: 0x34
-  __TEXT.__oslogstring: 0x3d39
-  __TEXT.__constg_swiftt: 0xea4
+  __TEXT.__oslogstring: 0x3e29
+  __TEXT.__constg_swiftt: 0xebc
   __TEXT.__swift5_typeref: 0x2601
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_reflstr: 0x1283

   __TEXT.__swift_as_cont: 0x470
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x1d80
-  __TEXT.__eh_frame: 0x3ef0
+  __TEXT.__unwind_info: 0x1da8
+  __TEXT.__eh_frame: 0x3f40
   __DATA_CONST.__const: 0x5e88
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x58

   __DATA_CONST.__auth_got: 0xbc0
   __DATA_CONST.__got: 0x5a0
   __DATA_CONST.__auth_ptr: 0x6d0
-  __DATA.__objc_const: 0x1538
-  __DATA.__objc_selrefs: 0x898
+  __DATA.__objc_const: 0x1550
+  __DATA.__objc_selrefs: 0x8c8
   __DATA.__objc_ivar: 0x8
-  __DATA.__objc_data: 0x6e0
+  __DATA.__objc_data: 0x6f8
   __DATA.__data: 0x1e40
   __DATA.__bss: 0x2e40
   __DATA.__common: 0xa8

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2439
+  Functions: 2449
   Symbols:   262
-  CStrings:  952
+  CStrings:  966
 
CStrings:
+ "Sending SharePrivacyChange, transition %ld, source %ld"
+ "addToCloudKitSharing:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "callForCloudKitAddToShare:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:"
+ "callForFileSharing:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:"
+ "callForForciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:"
+ "changeAccessSetting: new %s, current %s, source %ld, hasCKShare %{bool}d, isOwner %{bool}d"
+ "changeAccessSetting: no owned CKShare yet, not sending SharePrivacyChange"
+ "forciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "startFileSharingWithURLWrapper:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "v64@0:8@\"FPSandboxingURLWrapper\"16@\"NSArray\"24@\"NSArray\"32@\"NSArray\"40q48@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">56"
+ "v64@0:8@\"NSURL\"16@\"NSArray\"24@\"NSArray\"32@\"NSArray\"40q48@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">56"
+ "v64@0:8@16@24@32@40q48@?56"
+ "v72@0:8@\"CKShare\"16@\"CKContainerSetupInfo\"24@\"NSArray\"32@\"NSArray\"40@\"NSArray\"48q56@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">64"
+ "v72@0:8@16@24@32@40@48q56@?64"
```
