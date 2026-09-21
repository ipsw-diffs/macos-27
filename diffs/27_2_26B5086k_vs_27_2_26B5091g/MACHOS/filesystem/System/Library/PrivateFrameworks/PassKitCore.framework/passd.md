## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1696.2.5.0.0
-  __TEXT.__text: 0x590e9c
-  __TEXT.__auth_stubs: 0x5f60
-  __TEXT.__objc_stubs: 0x72200
-  __TEXT.__objc_methlist: 0x35da4
+1696.2.6.1.0
+  __TEXT.__text: 0x592178
+  __TEXT.__auth_stubs: 0x5f90
+  __TEXT.__objc_stubs: 0x722c0
+  __TEXT.__objc_methlist: 0x35de4
   __TEXT.__const: 0x4448
-  __TEXT.__cstring: 0x65c94
+  __TEXT.__cstring: 0x65d04
   __TEXT.__objc_classname: 0x7d38
   __TEXT.__objc_methtype: 0x13e62
-  __TEXT.__gcc_except_tab: 0x7e04
-  __TEXT.__objc_methname: 0xa211c
-  __TEXT.__oslogstring: 0x51c4b
+  __TEXT.__gcc_except_tab: 0x81dc
+  __TEXT.__objc_methname: 0xa220c
+  __TEXT.__oslogstring: 0x51cdb
   __TEXT.__ustring: 0x10
   __TEXT.__swift5_typeref: 0x244e
   __TEXT.__constg_swiftt: 0x1b8c

   __TEXT.__swift_as_cont: 0x7c
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x18700
+  __TEXT.__unwind_info: 0x18728
   __TEXT.__eh_frame: 0x1510
-  __DATA_CONST.__const: 0x2ebb0
+  __DATA_CONST.__const: 0x2ec10
   __DATA_CONST.__cfstring: 0x32d40
   __DATA_CONST.__objc_classlist: 0x1a08
   __DATA_CONST.__objc_catlist: 0x40

   __DATA_CONST.__objc_protorefs: 0x100
   __DATA_CONST.__objc_superrefs: 0xf60
   __DATA_CONST.__objc_intobj: 0x13f8
-  __DATA_CONST.__objc_arraydata: 0x540
+  __DATA_CONST.__objc_arraydata: 0x548
   __DATA_CONST.__objc_dictobj: 0x2a8
-  __DATA_CONST.__objc_arrayobj: 0x540
+  __DATA_CONST.__objc_arrayobj: 0x558
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA_CONST.__auth_got: 0x2fc0
-  __DATA_CONST.__got: 0x3b60
+  __DATA_CONST.__auth_got: 0x2fd8
+  __DATA_CONST.__got: 0x3b90
   __DATA_CONST.__auth_ptr: 0x770
-  __DATA.__objc_const: 0x42788
-  __DATA.__objc_selrefs: 0x1f9a8
-  __DATA.__objc_ivar: 0x28e4
+  __DATA.__objc_const: 0x427a8
+  __DATA.__objc_selrefs: 0x1f9d8
+  __DATA.__objc_ivar: 0x28e8
   __DATA.__objc_data: 0x119c0
   __DATA.__data: 0x6270
   __DATA.__bss: 0x3cb0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 27499
-  Symbols:   3471
-  CStrings:  34411
+  Functions: 27509
+  Symbols:   3480
+  CStrings:  34422
 
Symbols:
+ _PKPassSharingCarKeyBundleGroupIdentifierKey
+ _PKPendingCampaignAttributionCampaignIdentifierKey
+ _PKPendingCampaignAttributionForPassUniqueIdentifier
+ _PKPendingCampaignAttributionNewToProductUserKey
+ _PKPendingCampaignAttributionNewToWalletUserKey
+ _PKPendingCampaignAttributionProductTypeKey
+ _PKPendingCampaignAttributionReferralSourceKey
+ _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
+ _PKSetLocalSecureElementPassesProvider
CStrings:
+ "@\"NSArray\"8@?0"
+ "@\"PKPassShare\"20@?0@\"PKPassShare\"8B16"
+ "PDPaymentWebServiceCoordinator.deferred_pass_fetch_resume"
+ "Provisioning finished, resuming deferred pass fetch for push topic %@."
+ "Provisioning is in progress, deferring pass fetch for push topic %@."
+ "_localTargetDevices"
+ "_predicateForLocalCredentialShare"
+ "_sharePIDsWithLocalCredentialSharesForPassPID:inDatabase:"
+ "isLocal"
+ "isNewToWalletUser"
+ "isSameUnderlyingShareAs:ignoringRecipientHandle:"
+ "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:"
- "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:"
```
