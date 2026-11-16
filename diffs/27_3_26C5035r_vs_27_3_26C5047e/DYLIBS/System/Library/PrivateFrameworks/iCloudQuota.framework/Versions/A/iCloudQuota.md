## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/Versions/A/iCloudQuota`

```diff

-301.24.2.4.0
-  __TEXT.__text: 0x772a8
-  __TEXT.__objc_methlist: 0x53ec
-  __TEXT.__const: 0x1370
-  __TEXT.__cstring: 0x4dd1
+301.24.2.8.0
+  __TEXT.__text: 0x77cb4
+  __TEXT.__objc_methlist: 0x5484
+  __TEXT.__const: 0x1380
+  __TEXT.__cstring: 0x4e11
   __TEXT.__gcc_except_tab: 0x578
-  __TEXT.__oslogstring: 0x79ae
+  __TEXT.__oslogstring: 0x7b4e
   __TEXT.__dlopen_cstrs: 0x35b
   __TEXT.__ustring: 0xe
   __TEXT.__swift5_typeref: 0x7f8

   __TEXT.__swift_as_cont: 0xe0
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_protos: 0x1c
-  __TEXT.__unwind_info: 0x24e8
+  __TEXT.__unwind_info: 0x2510
   __TEXT.__eh_frame: 0x1500
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xa48
-  __DATA_CONST.__objc_classlist: 0x358
+  __DATA_CONST.__objc_classlist: 0x360
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2cb8
+  __DATA_CONST.__objc_selrefs: 0x2d10
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x268
+  __DATA_CONST.__objc_superrefs: 0x270
   __DATA_CONST.__objc_arraydata: 0x728
-  __DATA_CONST.__got: 0x718
-  __AUTH_CONST.__const: 0x2680
-  __AUTH_CONST.__cfstring: 0x61c0
-  __AUTH_CONST.__objc_const: 0xa790
+  __DATA_CONST.__got: 0x728
+  __AUTH_CONST.__const: 0x26b0
+  __AUTH_CONST.__cfstring: 0x6260
+  __AUTH_CONST.__objc_const: 0xa8c0
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x948
   __AUTH_CONST.__auth_got: 0xa90
-  __AUTH.__objc_data: 0x1448
+  __AUTH.__objc_data: 0x1498
   __AUTH.__data: 0x5f0
-  __DATA.__objc_ivar: 0x638
+  __DATA.__objc_ivar: 0x644
   __DATA.__data: 0x598
   __DATA.__bss: 0x1150
   __DATA.__common: 0x10

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2932
-  Symbols:   5092
-  CStrings:  1521
+  Functions: 2947
+  Symbols:   5126
+  CStrings:  1533
 
Symbols:
+ +[ICQAgeRangeSnapshot _snapshotForAccount:]
+ +[ICQAgeRangeSnapshot completionAddingSnapshotForAccount:completion:]
+ +[ICQAgeRangeSnapshot snapshotFromReply:]
+ -[ICQAgeRangeSnapshot .cxx_destruct]
+ -[ICQAgeRangeSnapshot ageRange]
+ -[ICQAgeRangeSnapshot altDSID]
+ -[ICQAgeRangeSnapshot description]
+ -[ICQAgeRangeSnapshot initWithAgeRange:altDSID:]
+ -[ICQAgeRangeSnapshot isAdultForAltDSID:]
+ -[ICQOffer inAppAlertKeyForReason:bundleId:placement:]
+ -[ICQOfferManager ageRangeSnapshot]
+ -[ICQOfferManager setAgeRangeSnapshot:]
+ _OBJC_CLASS_$_AKAccountManager
+ _OBJC_CLASS_$_ICQAgeRangeSnapshot
+ _OBJC_IVAR_$_ICQAgeRangeSnapshot._ageRange
+ _OBJC_IVAR_$_ICQAgeRangeSnapshot._altDSID
+ _OBJC_IVAR_$_ICQOfferManager._ageRangeSnapshot
+ _OBJC_METACLASS_$_ICQAgeRangeSnapshot
+ __OBJC_$_CLASS_METHODS_ICQAgeRangeSnapshot
+ __OBJC_$_INSTANCE_METHODS_ICQAgeRangeSnapshot
+ __OBJC_$_INSTANCE_VARIABLES_ICQAgeRangeSnapshot
+ __OBJC_$_PROP_LIST_ICQAgeRangeSnapshot
+ __OBJC_CLASS_RO_$_ICQAgeRangeSnapshot
+ __OBJC_METACLASS_RO_$_ICQAgeRangeSnapshot
+ ___69+[ICQAgeRangeSnapshot completionAddingSnapshotForAccount:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16l
+ _objc_msgSend$_snapshotForAccount:
+ _objc_msgSend$ageRange
+ _objc_msgSend$altDSID
+ _objc_msgSend$completionAddingSnapshotForAccount:completion:
+ _objc_msgSend$fetchAuthKitAccountWithAltDSID:error:
+ _objc_msgSend$initWithAgeRange:altDSID:
+ _objc_msgSend$setAgeRangeSnapshot:
+ _objc_msgSend$snapshotFromReply:
+ _objc_msgSend$userAgeRangeForAccount:
- -[ICQOffer inAppAlertKeyForReason:placement:]
CStrings:
+ "<%@: ageRange %lu>"
+ "Added age range %{private}lu to the default-offer reply"
+ "Default-offer reply has no age range"
+ "Default-offer reply sent without an age range (reply: %{public}@, error: %@)"
+ "Malformed age range in the default-offer reply: %@"
+ "No IdMS account for the age range (error: %@); sending Unknown"
+ "No altDSID on account %@; the default-offer reply has no age range"
+ "Read age range %{private}lu from the default-offer reply"
+ "_ICQAgeRangeSnapshot"
+ "ageRange"
+ "nil"
+ "present"
```
