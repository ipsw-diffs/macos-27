## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2131.30.43.1.1
-  __TEXT.__text: 0x338b74
-  __TEXT.__objc_methlist: 0x12efc
-  __TEXT.__cstring: 0x2d068
-  __TEXT.__const: 0x21f7c
+2131.30.65.0.0
+  __TEXT.__text: 0x3392c0
+  __TEXT.__objc_methlist: 0x12f34
+  __TEXT.__cstring: 0x2d0d8
+  __TEXT.__const: 0x21f8c
   __TEXT.__gcc_except_tab: 0x35c0
-  __TEXT.__oslogstring: 0xd2e3
+  __TEXT.__oslogstring: 0xd3d3
   __TEXT.__dlopen_cstrs: 0x5f2
   __TEXT.__ustring: 0x18
   __TEXT.__swift5_typeref: 0x8a1f

   __TEXT.__swift_as_ret: 0x40c
   __TEXT.__swift_as_cont: 0xa88
   __TEXT.__swift5_mpenum: 0xb8
-  __TEXT.__unwind_info: 0x119b8
+  __TEXT.__unwind_info: 0x119c0
   __TEXT.__eh_frame: 0xeb8c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x360
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8830
+  __DATA_CONST.__objc_selrefs: 0x8868
   __DATA_CONST.__objc_protorefs: 0x1d8
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x2f0
   __DATA_CONST.__got: 0x12b8
   __AUTH_CONST.__const: 0x1c698
-  __AUTH_CONST.__cfstring: 0x11b00
-  __AUTH_CONST.__objc_const: 0x35a10
+  __AUTH_CONST.__cfstring: 0x11b60
+  __AUTH_CONST.__objc_const: 0x35ae8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x398

   __AUTH_CONST.__auth_got: 0x2978
   __AUTH.__objc_data: 0x2ba8
   __AUTH.__data: 0x3098
-  __DATA.__objc_ivar: 0x1ff0
+  __DATA.__objc_ivar: 0x1ff8
   __DATA.__data: 0xba20
   __DATA.__bss: 0x39ad0
   __DATA.__common: 0x160

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21958
-  Symbols:   20697
-  CStrings:  7520
+  Functions: 21965
+  Symbols:   20712
+  CStrings:  7526
 
Symbols:
+ -[SFCollaborationCloudSharingRequest privacyChangeSource]
+ -[SFCollaborationCloudSharingRequest setPrivacyChangeSource:]
+ -[SFCollaborationItem optionsChangedFromPopup]
+ -[SFCollaborationItem setOptionsChangedFromPopup:]
+ GCC_except_table127
+ GCC_except_table212
+ GCC_except_table220
+ GCC_except_table96
+ _OBJC_IVAR_$_SFCollaborationCloudSharingRequest._privacyChangeSource
+ _OBJC_IVAR_$_SFCollaborationItem._optionsChangedFromPopup
+ _SFCloudSharingPrivacyChangeSourceClass
+ _SFCompleteShare
+ _objc_msgSend$completeShare:containerSetupInfo:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:
+ _objc_msgSend$optionsChangedFromPopup
+ _objc_msgSend$privacyChangeSource
+ _objc_msgSend$setPrivacyChangeSource:
+ _objc_msgSend$shareFileOrFolderURL:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:
+ _objc_msgSend$shareFolderRemovingSubshares:emailAddresses:phoneNumbers:optionsGroups:privacyChangeSource:completionHandler:
- GCC_except_table125
- GCC_except_table210
- GCC_except_table218
CStrings:
+ "Collaboration: privacyChangeSource:%ld selectorSupported:%d selector:%@"
+ "Collaboration: transport warning gate shouldShowAlert:%d transportSupportsAddingParticipants:%d addParticipantsAllowed:%d canShowShareOptions:%d sharingExp:%d activityType:%@"
+ "FindMyProxyOptedIn"
+ "footerVisibleOptionIdentifiers"
+ "privacyChangeSource"
+ "setFooterVisibleOptionIdentifiers:"
```
