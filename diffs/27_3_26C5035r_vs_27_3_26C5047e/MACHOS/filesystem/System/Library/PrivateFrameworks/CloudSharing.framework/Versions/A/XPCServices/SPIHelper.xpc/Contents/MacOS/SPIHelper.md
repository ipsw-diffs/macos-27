## SPIHelper

> `/System/Library/PrivateFrameworks/CloudSharing.framework/Versions/A/XPCServices/SPIHelper.xpc/Contents/MacOS/SPIHelper`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-240.2.4.0.0
-  __TEXT.__text: 0xb85d0
+240.2.6.0.0
+  __TEXT.__text: 0xbafec
   __TEXT.__auth_stubs: 0x1840
   __TEXT.__objc_stubs: 0x1660
-  __TEXT.__objc_methlist: 0x628
-  __TEXT.__const: 0x51d8
-  __TEXT.__cstring: 0x4119
-  __TEXT.__objc_methname: 0x2ae9
+  __TEXT.__objc_methlist: 0x674
+  __TEXT.__const: 0x5308
+  __TEXT.__cstring: 0x4149
+  __TEXT.__objc_methname: 0x2c59
   __TEXT.__objc_classname: 0x34d
-  __TEXT.__objc_methtype: 0x111c
+  __TEXT.__objc_methtype: 0x12ac
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__constg_swiftt: 0xed0
-  __TEXT.__swift5_typeref: 0x2681
-  __TEXT.__swift5_fieldmd: 0x1280
+  __TEXT.__constg_swiftt: 0xf24
+  __TEXT.__swift5_typeref: 0x26a7
+  __TEXT.__swift5_fieldmd: 0x1340
   __TEXT.__swift5_builtin: 0xf0
-  __TEXT.__swift5_reflstr: 0x1635
+  __TEXT.__swift5_reflstr: 0x16f5
   __TEXT.__swift5_assocty: 0x3f0
-  __TEXT.__oslogstring: 0x3f69
-  __TEXT.__swift5_proto: 0x1e0
-  __TEXT.__swift5_types: 0x100
+  __TEXT.__oslogstring: 0x4089
+  __TEXT.__swift5_proto: 0x1e8
+  __TEXT.__swift5_types: 0x108
   __TEXT.__swift5_protos: 0x18
-  __TEXT.__swift5_capture: 0x145c
+  __TEXT.__swift5_capture: 0x1540
   __TEXT.__swift_as_entry: 0x194
   __TEXT.__swift_as_ret: 0x270
   __TEXT.__swift_as_cont: 0x8d4
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x2cc0
-  __TEXT.__eh_frame: 0x7cc8
-  __DATA_CONST.__const: 0x3c38
+  __TEXT.__unwind_info: 0x2cf0
+  __TEXT.__eh_frame: 0x7d48
+  __DATA_CONST.__const: 0x3e38
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_protolist: 0x40

   __DATA_CONST.__auth_got: 0xc28
   __DATA_CONST.__got: 0x5f0
   __DATA_CONST.__auth_ptr: 0x720
-  __DATA.__objc_const: 0x1938
-  __DATA.__objc_selrefs: 0x7e0
+  __DATA.__objc_const: 0x1970
+  __DATA.__objc_selrefs: 0x7f8
   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x4f8
-  __DATA.__data: 0x22b8
+  __DATA.__data: 0x22d8
   __DATA.__common: 0xb0
-  __DATA.__bss: 0x40f0
+  __DATA.__bss: 0x41f0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2530
+  Functions: 2553
   Symbols:   276
-  CStrings:  1050
+  CStrings:  1063
 
CStrings:
+ "Sending SharePrivacyChange, transition %ld, source %ld"
+ "_stagedSharingOptions"
+ "addToCloudKitSharing(_:containerSetupInfo:emailAddresses:phoneNumbers:oneTimeParticipantCount:optionsGroups:privacyChangeSource:withReply:)"
+ "addToCloudKitSharing:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "applyOptions: source %ld, accessType %ld"
+ "changeAccessSetting: new %s, current %s, source %ld, hasCKShare %{bool}d, isOwner %{bool}d"
+ "changeAccessSetting: no owned CKShare yet, not sending SharePrivacyChange"
+ "forciblyShareFolder(_:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:)"
+ "forciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "startFileSharingWithURLWrapper(_:shareAddresses:optionsGroups:privacyChangeSource:withReply:)"
+ "startFileSharingWithURLWrapper:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:"
+ "v64@0:8@\"FPSandboxingURLWrapper\"16@\"NSArray\"24@\"NSArray\"32@\"NSArray\"40q48@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">56"
+ "v64@0:8@\"NSURL\"16@\"NSArray\"24@\"NSArray\"32@\"NSArray\"40q48@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">56"
+ "v64@0:8@16@24@32@40q48@?56"
+ "v72@0:8@\"CKShare\"16@\"CKContainerSetupInfo\"24@\"NSArray\"32@\"NSArray\"40@\"NSArray\"48q56@?<v@?@\"NSURL\"@\"CKShare\"@\"NSError\">64"
+ "v72@0:8@16@24@32@40@48q56@?64"
- "addToCloudKitSharing(_:containerSetupInfo:emailAddresses:phoneNumbers:oneTimeParticipantCount:optionsGroups:withReply:)"
- "forciblyShareFolder(_:emailAddresses:phoneNumbers:optionsGroups:withReply:)"
- "startFileSharingWithURLWrapper(_:shareAddresses:optionsGroups:withReply:)"
```
