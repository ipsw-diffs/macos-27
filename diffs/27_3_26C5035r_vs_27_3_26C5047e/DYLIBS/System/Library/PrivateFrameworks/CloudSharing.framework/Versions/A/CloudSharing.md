## CloudSharing

> `/System/Library/PrivateFrameworks/CloudSharing.framework/Versions/A/CloudSharing`

```diff

-240.2.4.0.0
-  __TEXT.__text: 0x3aaa4
-  __TEXT.__objc_methlist: 0x530
+240.2.6.0.0
+  __TEXT.__text: 0x3b0cc
+  __TEXT.__objc_methlist: 0x5a4
   __TEXT.__const: 0x398
   __TEXT.__cstring: 0xf7
   __TEXT.__swift5_typeref: 0x454
   __TEXT.__swift5_capture: 0x137c
   __TEXT.__oslogstring: 0x1054
-  __TEXT.__constg_swiftt: 0x1e8
+  __TEXT.__constg_swiftt: 0x200
   __TEXT.__swift5_fieldmd: 0x3c
   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_reflstr: 0x23
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x18
   __TEXT.__swift5_types: 0x14
-  __TEXT.__unwind_info: 0x550
+  __TEXT.__unwind_info: 0x578
   __TEXT.__eh_frame: 0xe0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x438
+  __DATA_CONST.__objc_selrefs: 0x480
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__got: 0xf8
   __AUTH_CONST.__const: 0x39d8
-  __AUTH_CONST.__objc_const: 0x2d8
+  __AUTH_CONST.__objc_const: 0x2f0
   __AUTH_CONST.__auth_got: 0x380
   __AUTH.__objc_data: 0x48
   __DATA.__data: 0x188
   __DATA.__bss: 0x310
-  __DATA_DIRTY.__objc_data: 0x218
+  __DATA_DIRTY.__objc_data: 0x230
   __DATA_DIRTY.__data: 0x50
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 874
-  Symbols:   334
+  Functions: 890
+  Symbols:   340
   CStrings:  87
 
Symbols:
+ +[CSCloudSharing completeShare:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:]
+ +[CSCloudSharing shareFileOrFolderURL:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:]
+ +[CSCloudSharing shareFolderRemovingSubshares:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:]
+ _objc_msgSend$addToCloudKitSharing:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:
+ _objc_msgSend$callForCloudKitAddToShare:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:
+ _objc_msgSend$callForFileSharing:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:
+ _objc_msgSend$callForForciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:reply:
+ _objc_msgSend$forciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:
+ _objc_msgSend$startFileSharingWithURLWrapper:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:withReply:
- _objc_msgSend$addToCloudKitSharing:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:withReply:
- _objc_msgSend$forciblyShareFolder:emailAddresses:phoneNumbers:optionsGroups:withReply:
- _objc_msgSend$startFileSharingWithURLWrapper:emailAddresses:phoneNumbers:optionsGroups:withReply:
```
