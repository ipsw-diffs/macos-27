## iCloudQuotaUI

> `/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/Versions/A/iCloudQuotaUI`

```diff

-301.24.2.4.0
-  __TEXT.__text: 0x9f31c
-  __TEXT.__objc_methlist: 0x1fcc
-  __TEXT.__const: 0x7594
-  __TEXT.__gcc_except_tab: 0x6e4
-  __TEXT.__cstring: 0x505a
-  __TEXT.__oslogstring: 0x3bab
+301.24.2.8.0
+  __TEXT.__text: 0xa08cc
+  __TEXT.__objc_methlist: 0x1fec
+  __TEXT.__const: 0x75a4
+  __TEXT.__gcc_except_tab: 0x6f0
+  __TEXT.__cstring: 0x535a
+  __TEXT.__oslogstring: 0x3d2b
   __TEXT.__dlopen_cstrs: 0x218
   __TEXT.__swift5_typeref: 0x760a
   __TEXT.__swift5_reflstr: 0x1532

   __TEXT.__swift_as_ret: 0x78
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift_as_cont: 0x3c
-  __TEXT.__unwind_info: 0x3480
+  __TEXT.__unwind_info: 0x34a0
   __TEXT.__eh_frame: 0x1298
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x550
+  __DATA_CONST.__const: 0x558
   __DATA_CONST.__objc_classlist: 0x120
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d98
+  __DATA_CONST.__objc_selrefs: 0x1dd8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x478
-  __DATA_CONST.__got: 0xae0
-  __AUTH_CONST.__const: 0x4be0
-  __AUTH_CONST.__cfstring: 0x3520
+  __DATA_CONST.__got: 0xae8
+  __AUTH_CONST.__const: 0x4c50
+  __AUTH_CONST.__cfstring: 0x38a0
   __AUTH_CONST.__objc_const: 0x4f98
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x398

   __AUTH.__data: 0x1960
   __DATA.__objc_ivar: 0x1f8
   __DATA.__data: 0x2160
-  __DATA.__bss: 0x8370
+  __DATA.__bss: 0x8390
   __DATA.__common: 0x258
   __DATA_DIRTY.__objc_data: 0x3d8
   __DATA_DIRTY.__data: 0x58

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3815
-  Symbols:   3380
-  CStrings:  952
+  Functions: 3824
+  Symbols:   3402
+  CStrings:  987
 
Symbols:
+ +[ICQInAppAlert alertForReason:bundleId:placement:inOffer:]
+ -[ICQInAppMessaging(U18) _isUnder18]
+ -[ICQInAppMessaging(U18) _under18AIAlertForReason:]
+ -[ICQInAppMessaging(U18) _under18AIMessageForReason:]
+ _ICQUIInAppMessageIdentifierUpgradeSuppressed
+ __ICQU18AlertCopyKeys.onceToken
+ __ICQU18AlertCopyKeys.table
+ __ICQU18CopyKeys.onceToken
+ __ICQU18CopyKeys.table
+ __OBJC_$_INSTANCE_METHODS_ICQInAppMessaging(U18)
+ ____ICQU18AlertCopyKeys_block_invoke
+ ____ICQU18CopyKeys_block_invoke
+ ___block_descriptor_64_e8_32s40r48r56r_e5_v8?0l
+ ___copy_helper_block_e8_32s40r48r56r
+ ___destroy_helper_block_e8_32s40r48r56r
+ ___kCFBooleanTrue
+ _objc_msgSend$_isUnder18
+ _objc_msgSend$_under18AIAlertForReason:
+ _objc_msgSend$_under18AIMessageForReason:
+ _objc_msgSend$aa_altDSID
+ _objc_msgSend$ageRange
+ _objc_msgSend$ageRangeSnapshot
+ _objc_msgSend$alertForReason:bundleId:placement:inOffer:
+ _objc_msgSend$altDSID
+ _objc_msgSend$inAppAlertKeyForReason:bundleId:placement:
+ _objc_msgSend$isAdultForAltDSID:
- +[ICQInAppAlert alertForReason:placement:inOffer:]
- __OBJC_$_INSTANCE_METHODS_ICQInAppMessaging
- _objc_msgSend$alertForReason:placement:inOffer:
- _objc_msgSend$inAppAlertKeyForReason:placement:
CStrings:
+ "Age range %{private}lu; using U18 AI-limit copy"
+ "No U18 %{public}@ alert for bundle %{public}@"
+ "No U18 %{public}@ copy for bundle %{public}@"
+ "No age range from ind for bundle %{public}@; using U18 AI-limit copy"
+ "Returning U18 %{public}@ alert for bundle %{public}@"
+ "Returning U18 %{public}@ message for bundle %{public}@"
+ "The age range from ind is for another account; using U18 AI-limit copy"
+ "U18_AI_ALERT_LEARN_MORE_BUTTON_TITLE"
+ "U18_AI_ALERT_NOT_NOW_BUTTON_TITLE"
+ "U18_AI_ALERT_OK_BUTTON_TITLE"
+ "U18_AI_APPROACHING_IMAGE_PLAYGROUND_BODY"
+ "U18_AI_APPROACHING_PHOTOS_BODY"
+ "U18_AI_APPROACHING_SHORTCUTS_BODY"
+ "U18_AI_APPROACHING_SHORTCUTS_TITLE"
+ "U18_AI_APPROACHING_SIRI_BODY"
+ "U18_AI_APPROACHING_SIRI_TITLE"
+ "U18_AI_LEARN_MORE_BUTTON_TITLE"
+ "U18_AI_PLAN_UPGRADE_SHORTCUTS_ALERT_BODY"
+ "U18_AI_PLAN_UPGRADE_SHORTCUTS_BODY"
+ "U18_AI_REACHED_IMAGE_PLAYGROUND_BODY"
+ "U18_AI_REACHED_PHOTOS_BODY"
+ "U18_AI_REACHED_SHORTCUTS_BODY"
+ "U18_AI_REACHED_SHORTCUTS_TITLE"
+ "U18_AI_REACHED_SIRI_BODY"
+ "U18_AI_REACHED_SIRI_CONCISE_TITLE"
+ "U18_AI_REACHED_SIRI_TITLE"
+ "UpgradeSuppressed"
+ "body"
+ "cancelTitle"
+ "com.apple.GenerativePlaygroundApp"
+ "com.apple.Photos"
+ "com.apple.campo"
+ "com.apple.shortcuts"
+ "learnMoreBtnId"
+ "learnMoreTitle"
```
