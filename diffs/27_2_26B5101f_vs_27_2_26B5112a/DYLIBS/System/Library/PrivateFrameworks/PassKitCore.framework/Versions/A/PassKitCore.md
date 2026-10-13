## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1696.2.8.1.0
-  __TEXT.__text: 0x86b394
-  __TEXT.__objc_methlist: 0x70278
+1696.2.9.0.0
+  __TEXT.__text: 0x86a5e0
+  __TEXT.__objc_methlist: 0x70248
   __TEXT.__const: 0x18fe0
   __TEXT.__swift5_typeref: 0x7ba2
-  __TEXT.__cstring: 0x6fabc
+  __TEXT.__cstring: 0x6fa07
   __TEXT.__constg_swiftt: 0x6de8
   __TEXT.__swift5_reflstr: 0x5d2d
   __TEXT.__swift5_fieldmd: 0x73b0

   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x6638
   __TEXT.__ustring: 0x1e6c
-  __TEXT.__unwind_info: 0x24a08
+  __TEXT.__unwind_info: 0x249e0
   __TEXT.__eh_frame: 0x73d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x12428
+  __DATA_CONST.__const: 0x123e8
   __DATA_CONST.__objc_classlist: 0x3d28
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23c48
+  __DATA_CONST.__objc_selrefs: 0x23c30
   __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x3030
   __DATA_CONST.__objc_arraydata: 0x2850
   __DATA_CONST.__got: 0x4920
   __AUTH_CONST.__const: 0x2f560
-  __AUTH_CONST.__cfstring: 0x783c0
-  __AUTH_CONST.__objc_const: 0xcc360
+  __AUTH_CONST.__cfstring: 0x78280
+  __AUTH_CONST.__objc_const: 0xcc330
   __AUTH_CONST.__objc_arrayobj: 0xd50
   __AUTH_CONST.__objc_intobj: 0x10e0
   __AUTH_CONST.__objc_dictobj: 0x1590

   __AUTH.__data: 0x53f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x707c
+  __DATA.__objc_ivar: 0x7078
   __DATA.__data: 0x8720
   __DATA.__bss: 0x21598
   __DATA.__common: 0x1d9
   __DATA_DIRTY.__objc_ivar: 0x1f20
   __DATA_DIRTY.__objc_data: 0x8a20
   __DATA_DIRTY.__data: 0x88
-  __DATA_DIRTY.__bss: 0x10d0
+  __DATA_DIRTY.__bss: 0x10c0
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 53209
-  Symbols:   88740
-  CStrings:  20923
+  Functions: 53201
+  Symbols:   88714
+  CStrings:  20913
 
Symbols:
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:]
+ +[PKPaymentAuthorizationErrorStateParam paramWithError:requiresExtendedDisplayDuration:]
+ -[PKPaymentAuthorizationErrorStateParam requiresExtendedDisplayDuration]
+ -[PKPaymentAuthorizationErrorStateParam setRequiresExtendedDisplayDuration:]
+ -[PKPaymentProvisioningController allowsUserGeneratedPass]
+ -[PKPaymentProvisioningController includePrecursorPasses]
+ -[PKPaymentProvisioningController setAllowsUserGeneratedPass:]
+ -[PKPaymentProvisioningController setIncludePrecursorPasses:]
+ OBJC_IVAR_$_PKPaymentAuthorizationErrorStateParam._requiresExtendedDisplayDuration
+ OBJC_IVAR_$_PKPaymentProvisioningController._allowsUserGeneratedPass
+ OBJC_IVAR_$_PKPaymentProvisioningController._includePrecursorPasses
+ _objc_msgSend$paramWithError:requiresExtendedDisplayDuration:
+ _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:
+ _objc_msgSend$setRequiresExtendedDisplayDuration:
- +[PKAnalyticsReporter(Attribution) isNewToWalletUser]
- +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:]
- -[PKPaymentProvisioningController allowUserGeneratedPassInUnsupportedRegion]
- -[PKPaymentProvisioningController setAllowUserGeneratedPassInUnsupportedRegion:]
- -[PKProvisioningAnalyticsSession reportNCCCheck]
- -[PKProvisioningAnalyticsSessionCampaignAttributionSubjectHandle reportNCCCheckWithState:]
- -[PKProvisioningAnalyticsState campaignAttributionNewToProductUser]
- -[PKProvisioningAnalyticsState campaignAttributionNewToWalletUser]
- -[PKProvisioningAnalyticsState campaignAttributionReferralSource]
- -[PKProvisioningAnalyticsState setCampaignAttributionNewToProductUser:]
- -[PKProvisioningAnalyticsState setCampaignAttributionNewToWalletUser:]
- OBJC_IVAR_$_PKPaymentProvisioningController._allowUserGeneratedPassInUnsupportedRegion
- OBJC_IVAR_$_PKProvisioningAnalyticsSession._didReportNCCCheck
- OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToProductUser
- OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToWalletUser
- _PKAnalyticsReportNewToCreditUserKey
- _PKAnalyticsReportNewToDebitUserKey
- _PKAnalyticsReportNewToTransitUserKey
- _PKAnalyticsReportNewToWalletUserKey
- _PKCurrentSecureElementPasses
- _PKISO23220_1_PhotoID_FamilyNameUnicode
- _PKISO23220_1_PhotoID_GivenNameUnicode
- _PKISO23220_1_PhotoID_IssuingAuthorityUnicode
- _PKPendingCampaignAttributionCampaignIdentifierKey
- _PKPendingCampaignAttributionForPassUniqueIdentifier
- _PKPendingCampaignAttributionNewToProductUserKey
- _PKPendingCampaignAttributionNewToWalletUserKey
- _PKPendingCampaignAttributionProductTypeKey
- _PKPendingCampaignAttributionReferralSourceKey
- _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
- _PKSetLocalSecureElementPassesProvider
- _PKSetPendingCampaignAttributionForPassUniqueIdentifier
- _objc_msgSend$campaignAttributionNewToProductUser
- _objc_msgSend$campaignAttributionNewToWalletUser
- _objc_msgSend$campaignAttributionReferralSource
- _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:
- _objc_msgSend$reportNCCCheck
- _objc_msgSend$reportNCCCheckWithState:
- _objc_msgSend$setCampaignAttributionNewToProductUser:
- _objc_msgSend$setCampaignAttributionNewToWalletUser:
CStrings:
+ "requiresExtendedDisplayDuration: '%@'; "
- "PKPendingCampaignAttributionKey"
- "appleAccount"
- "campaignAttributionNewToProductUser"
- "campaignAttributionNewToWalletUser"
- "cardReadyToUse"
- "nccCheck"
- "newToCreditUser"
- "newToDebitUser"
- "newToProductUser"
- "newToTransitUser"
- "newToWalletUser"
```
