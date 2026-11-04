## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Versions/A/CloudKitDaemon`

```diff

-2720.17.5.0.0
-  __TEXT.__text: 0x40b558
-  __TEXT.__objc_methlist: 0x317bc
+2730.18.0.0.0
+  __TEXT.__text: 0x410f28
+  __TEXT.__objc_methlist: 0x31b04
   __TEXT.__const: 0x4e20
   __TEXT.__swift5_typeref: 0x21a1
-  __TEXT.__oslogstring: 0x32e1a
+  __TEXT.__oslogstring: 0x3362c
   __TEXT.__swift5_capture: 0x918
   __TEXT.__constg_swiftt: 0x1ac0
   __TEXT.__swift5_reflstr: 0x1136

   __TEXT.__swift_as_ret: 0x16c
   __TEXT.__swift_as_cont: 0x23c
   __TEXT.__swift5_protos: 0x38
-  __TEXT.__cstring: 0x2b591
+  __TEXT.__cstring: 0x2bd40
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__gcc_except_tab: 0xcad4
+  __TEXT.__gcc_except_tab: 0xcc14
   __TEXT.__ustring: 0x2c
-  __TEXT.__unwind_info: 0xeb88
+  __TEXT.__unwind_info: 0xecb8
   __TEXT.__eh_frame: 0x3ba8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x2068
-  __DATA_CONST.__objc_classlist: 0x14e8
+  __DATA_CONST.__objc_classlist: 0x1510
   __DATA_CONST.__objc_catlist: 0x148
   __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13170
+  __DATA_CONST.__objc_selrefs: 0x13288
   __DATA_CONST.__objc_protorefs: 0xa0
-  __DATA_CONST.__objc_superrefs: 0x13c0
+  __DATA_CONST.__objc_superrefs: 0x13d8
   __DATA_CONST.__objc_arraydata: 0x1558
-  __DATA_CONST.__got: 0x2088
-  __AUTH_CONST.__const: 0xdc08
-  __AUTH_CONST.__cfstring: 0x23920
-  __AUTH_CONST.__objc_const: 0x4ad88
-  __AUTH_CONST.__objc_intobj: 0xcd8
+  __DATA_CONST.__got: 0x20b8
+  __AUTH_CONST.__const: 0xdc38
+  __AUTH_CONST.__cfstring: 0x23e00
+  __AUTH_CONST.__objc_const: 0x4b2d8
+  __AUTH_CONST.__objc_intobj: 0xcf0
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_dictobj: 0xbe0
-  __AUTH_CONST.__auth_got: 0x2110
-  __AUTH.__objc_data: 0x5258
+  __AUTH_CONST.__auth_got: 0x2128
+  __AUTH.__objc_data: 0x53e8
   __AUTH.__data: 0x5b0
-  __DATA.__objc_ivar: 0x1a8c
+  __DATA.__objc_ivar: 0x1a94
   __DATA.__data: 0x1ee0
   __DATA.__bss: 0x31a0
   __DATA.__common: 0xa0
-  __DATA_DIRTY.__objc_ivar: 0x1980
+  __DATA_DIRTY.__objc_ivar: 0x19a8
   __DATA_DIRTY.__objc_data: 0x8530
   __DATA_DIRTY.__data: 0x2278
   __DATA_DIRTY.__bss: 0x3900

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 21187
-  Symbols:   2964
-  CStrings:  8505
+  Functions: 21267
+  Symbols:   2977
+  CStrings:  8579
 
Symbols:
+ _CKTestDeviceOptionSelfAddedPCSV2Upgrade
+ _OBJC_CLASS_$_CKDFetchScreeningKeyOperation
+ _OBJC_CLASS_$_CKDFetchScreeningKeyOperationInfo
+ _OBJC_CLASS_$_CKDScreeningEligibilityEvaluator
+ _OBJC_CLASS_$_CKDSelfAddedPCSUpgrader
+ _OBJC_METACLASS_$_CKDFetchScreeningKeyOperation
+ _OBJC_METACLASS_$_CKDFetchScreeningKeyOperationInfo
+ _OBJC_METACLASS_$_CKDScreeningEligibilityEvaluator
+ _OBJC_METACLASS_$_CKDSelfAddedPCSUpgrader
+ _SecKeyCopyExternalRepresentation
+ _SecKeyCopyPublicKey
+ _SecKeyCreateRandomKey
+ _kSecAttrKeySizeInBits
CStrings:
+ "Adding screening identity to selfAddedPCS for share %@"
+ "CKDFetchScreeningKeyURLRequest.m"
+ "Can't upgrade a share PCS that is not read-write"
+ "Cannot verify screening key: containerScopedUserID unavailable for share %@"
+ "Couldn't copy a private key into the v2 share PCS"
+ "Couldn't copy a sharee into the v2 share PCS"
+ "Couldn't create a v2 share PCS"
+ "Couldn't set the current private key of the v2 share PCS"
+ "Couldn't strip screening identity from public PCS for share at URL %@: %@"
+ "Couldn't upgrade selfAddedPCS to v2 for share %@; saving with the existing selfAddedPCS: %@"
+ "Couldn't upgrade share PCS to v2: %@"
+ "Error fetching screening key for share %@"
+ "Error fetching signing certificates for screening key: %@"
+ "Error upgrading selfAddedPCS %@ to v2: %@"
+ "Failed to add screening identity to selfAddedPCS for share %@"
+ "Failed to create screening PCS identity for share %@"
+ "Failed to create test screening PCS identity for share %@"
+ "Failed to generate test screening key for share %@: %@"
+ "Failed to parse screening key signature envelope for share %@"
+ "Failed to remove stale screening identity from selfAddedPCS for share %@: %@"
+ "Failed to resolve server environment for screening key certificate fetch: %@"
+ "Failed to serialize publicProtectionData for share %@ under test hook: %@"
+ "Fetch screening key request failed: %@"
+ "Fetching Screening Key"
+ "Fetching Signing Certificates"
+ "Forced screening key fetch error for share %@"
+ "Forced selfAddedPCS upgrade failure for testing"
+ "Missing shareRecordID for screening key fetch"
+ "New share %@ is eligible for screening"
+ "No share PCS to upgrade to v2"
+ "No valid signing certificates available to verify screening key for share %@"
+ "No valid signing certificates found for screening key verification"
+ "Public PCS doesn't contain screening key after add attempt for share %@"
+ "Removed stale screening identity from selfAddedPCS for share %@; share is no longer eligible for screening"
+ "ReportSharePCSPrepFailure"
+ "Saving participant is not the share owner for share %@"
+ "Saving participant may not modify the PCS chain for share %@"
+ "Screening identity already present in selfAddedPCS for share %@; skipping fetch and add"
+ "Screening key response is missing required publicKey or signature for share %@"
+ "Screening key signature is not trusted: no pinned certificate verified the signature for share %@"
+ "Screening public key length %lu does not match reported key type %ld (expected %lu bytes) for share %@"
+ "Server rejected the screening key request for share %@; saving without adding screening key to the share: %@"
+ "Share %@ is being made public and is eligible for screening"
+ "Share %@ is not eligible for screening"
+ "Share %@ was last saved with public permission %ld; keeping its existing screening state"
+ "Share PCS version %ld %{public}@ an upgrade to v2"
+ "Share screening feature not enabled"
+ "Stripped screening identity from PPPCS during participant vetting for URL %@"
+ "Stripped screening identity from PPPCS during public share acceptance for URL %@"
+ "TestForceDuplicateScreeningIdentity"
+ "TestForceScreeningKeyFetchErrorCode"
+ "TestForceSelfAddedPCSUpgradeFailure"
+ "TestForceSerializePublicProtectionData"
+ "TestSkipAddScreeningKeyToSelfAddedPCS"
+ "TestSkipRemoveStaleScreeningKeyFromSelfAddedPCS"
+ "The upgraded share PCS has a different current private key"
+ "The upgraded share PCS has different private keys"
+ "The upgraded share PCS has different sharees or sharee flags"
+ "The upgraded share PCS is not v2"
+ "Upgraded selfAddedPCS %@ to v2 PCS %@"
+ "Upgraded selfAddedPCS to v2 for share %@"
+ "Upgraded share PCS to v2 with %lu private keys and %lu sharees"
+ "Upgrading selfAddedPCS %@ to v2"
+ "Upgrading share PCS from version %ld to v2"
+ "daemon/fetch-screening-key"
+ "does not need"
+ "https://gateway.icloud.com/config-qa/server-signature-verification.plist"
+ "missingScreeningKeyInSelfAddedPcs"
+ "needs"
+ "screening"
+ "selfAddedPCS for share %@ contains %lu screening keys; expected at most one"
+ "selfAddedPCS v2 upgrade %{public}@ by behavior option for share %@"
+ "selfAddedPCS v2 upgrade %{public}@ by test device option for share %@"
+ "v44@?0@\"NSData\"8q16i24@\"NSData\"28@\"CKDPResponseOperationResult\"36"
```
