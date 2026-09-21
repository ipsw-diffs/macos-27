## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1696.2.5.0.0
-  __TEXT.__text: 0x861df4
-  __TEXT.__objc_methlist: 0x70148
-  __TEXT.__const: 0x18f60
-  __TEXT.__swift5_typeref: 0x7a7e
-  __TEXT.__cstring: 0x6f54f
-  __TEXT.__constg_swiftt: 0x6db4
+1696.2.6.1.0
+  __TEXT.__text: 0x868d50
+  __TEXT.__objc_methlist: 0x701d8
+  __TEXT.__const: 0x18f30
+  __TEXT.__swift5_typeref: 0x7b9a
+  __TEXT.__cstring: 0x6f739
+  __TEXT.__constg_swiftt: 0x6dcc
   __TEXT.__swift5_reflstr: 0x5cfd
   __TEXT.__swift5_fieldmd: 0x7370
   __TEXT.__swift5_builtin: 0x4b0
   __TEXT.__swift5_assocty: 0xba0
   __TEXT.__swift5_proto: 0x1164
   __TEXT.__swift5_types: 0x750
-  __TEXT.__swift5_capture: 0x4714
-  __TEXT.__oslogstring: 0x36e10
-  __TEXT.__swift_as_entry: 0x160
-  __TEXT.__swift_as_ret: 0x174
-  __TEXT.__swift_as_cont: 0x2f4
+  __TEXT.__swift5_capture: 0x4904
+  __TEXT.__oslogstring: 0x371ad
+  __TEXT.__swift_as_entry: 0x158
+  __TEXT.__swift_as_ret: 0x16c
+  __TEXT.__swift_as_cont: 0x2e8
   __TEXT.__swift5_mpenum: 0x138
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x6638
   __TEXT.__ustring: 0x1e6c
-  __TEXT.__unwind_info: 0x248b8
-  __TEXT.__eh_frame: 0x73e8
+  __TEXT.__unwind_info: 0x24988
+  __TEXT.__eh_frame: 0x73d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x12310
+  __DATA_CONST.__const: 0x12358
   __DATA_CONST.__objc_classlist: 0x3d28
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23b40
+  __DATA_CONST.__objc_selrefs: 0x23bf8
   __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x3030
   __DATA_CONST.__objc_arraydata: 0x2850
   __DATA_CONST.__got: 0x4920
-  __AUTH_CONST.__const: 0x2ece0
-  __AUTH_CONST.__cfstring: 0x77ee0
-  __AUTH_CONST.__objc_const: 0xcc140
+  __AUTH_CONST.__const: 0x2f2b8
+  __AUTH_CONST.__cfstring: 0x780a0
+  __AUTH_CONST.__objc_const: 0xcc1b0
   __AUTH_CONST.__objc_arrayobj: 0xd50
   __AUTH_CONST.__objc_intobj: 0x10e0
   __AUTH_CONST.__objc_dictobj: 0x1590
   __AUTH_CONST.__objc_doubleobj: 0x2b0
-  __AUTH_CONST.__auth_got: 0x28a0
-  __AUTH.__objc_data: 0x201a8
-  __AUTH.__data: 0x52b8
+  __AUTH_CONST.__auth_got: 0x28d0
+  __AUTH.__objc_data: 0x1ee48
+  __AUTH.__data: 0x53e0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x7058
+  __DATA.__objc_ivar: 0x7060
   __DATA.__data: 0x8720
   __DATA.__bss: 0x21498
   __DATA.__common: 0x1d9
   __DATA_DIRTY.__objc_ivar: 0x1f1c
-  __DATA_DIRTY.__objc_data: 0x76c0
+  __DATA_DIRTY.__objc_data: 0x8a20
   __DATA_DIRTY.__data: 0x88
-  __DATA_DIRTY.__bss: 0x10c0
+  __DATA_DIRTY.__bss: 0x10d0
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 53056
-  Symbols:   88613
-  CStrings:  20866
+  Functions: 53166
+  Symbols:   88685
+  CStrings:  20895
 
Symbols:
+ +[PKAnalyticsReporter(Attribution) isNewToWalletUser]
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:]
+ +[PKCoreSpotlightUtilities _addNormalizedPhoneNumberForPhoneNumber:toAttributeSet:]
+ +[PKCoreSpotlightUtilities _normalizedPhoneNumberDigitsFromPhoneNumber:]
+ -[PKPassCredentialShare isLocal]
+ -[PKPassShare isSameUnderlyingShareAs:ignoringRecipientHandle:]
+ -[PKProvisioningAnalyticsSession reportNCCCheck]
+ -[PKProvisioningAnalyticsSessionCampaignAttributionSubjectHandle reportNCCCheckWithState:]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToProductUser]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToWalletUser]
+ -[PKProvisioningAnalyticsState campaignAttributionReferralSource]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToProductUser:]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToWalletUser:]
+ -[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]
+ OBJC_IVAR_$_PKProvisioningAnalyticsSession._didReportNCCCheck
+ OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToProductUser
+ OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToWalletUser
+ _OBJC_CLASS_$_CSCustomAttributeKey
+ _PKAnalyticsReportNewToCreditUserKey
+ _PKAnalyticsReportNewToDebitUserKey
+ _PKAnalyticsReportNewToTransitUserKey
+ _PKAnalyticsReportNewToWalletUserKey
+ _PKCoreSpotlightCustomKeyNormalizedPhoneNumbers
+ _PKCurrentSecureElementPasses
+ _PKHomeAppSharingHost
+ _PKHomeAppURLScheme
+ _PKHomeAppUserLockSettingsHost
+ _PKPassCredentialShareTargetDeviceIsLocal
+ _PKPendingCampaignAttributionCampaignIdentifierKey
+ _PKPendingCampaignAttributionForPassUniqueIdentifier
+ _PKPendingCampaignAttributionNewToProductUserKey
+ _PKPendingCampaignAttributionNewToWalletUserKey
+ _PKPendingCampaignAttributionProductTypeKey
+ _PKPendingCampaignAttributionReferralSourceKey
+ _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
+ _PKSetLocalSecureElementPassesProvider
+ _PKSetPendingCampaignAttributionForPassUniqueIdentifier
+ _PKSharingInvitationFlowIsDeviceTransfer
+ _PKSharingSanitizedRelayURL
+ __60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke
+ ___60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke
+ ___block_descriptor_40_e8_32s_e30_B16?0"PKTransitCommutePlan"8l
+ ___block_descriptor_40_e8_32s_e37_B32?0"PKTransitCommutePlan"8Q16^B24l
+ __swift__destructor.219Tm
+ __swift_closure_destructor.115Tm
+ __swift_closure_destructor.144Tm
+ __swift_closure_destructor.150Tm
+ __swift_closure_destructor.159Tm
+ __swift_closure_destructor.252Tm
+ __swift_closure_destructor.54Tm
+ __swift_closure_destructor.68Tm
+ __swift_closure_destructor.80Tm
+ __swift_closure_destructor.9Tm
+ _generic environment 11PassKitCore25ProvisioningOperationStepRzl
+ _objc_msgSend$_normalizedPhoneNumberDigitsFromPhoneNumber:
+ _objc_msgSend$campaignAttributionNewToProductUser
+ _objc_msgSend$campaignAttributionNewToWalletUser
+ _objc_msgSend$campaignAttributionReferralSource
+ _objc_msgSend$initWithKeyName:searchable:searchableByDefault:unique:multiValued:
+ _objc_msgSend$isLocal
+ _objc_msgSend$isSameUnderlyingShareAs:ignoringRecipientHandle:
+ _objc_msgSend$password
+ _objc_msgSend$percentEncodedFragment
+ _objc_msgSend$percentEncodedPath
+ _objc_msgSend$percentEncodedQuery
+ _objc_msgSend$port
+ _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:
+ _objc_msgSend$reportNCCCheck
+ _objc_msgSend$reportNCCCheckWithState:
+ _objc_msgSend$setCampaignAttributionNewToProductUser:
+ _objc_msgSend$setCampaignAttributionNewToWalletUser:
+ _objc_msgSend$setIsForCurrentUser:
+ _objc_msgSend$setPercentEncodedFragment:
+ _objc_msgSend$setPercentEncodedPath:
+ _objc_msgSend$setPercentEncodedQuery:
+ _objc_msgSend$setValue:forCustomKey:
+ _objc_msgSend$user
+ _symbolic SDySSSo19PKPaymentCredentialCGz_Xx
+ _symbolic SS_So19PKPaymentCredentialCt
+ _symbolic Say______pG 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic SiIegd_
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____GIegn_ s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySS_So19PKPaymentCredentialCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic x4step_______p6runnert 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic y_____ySDySSSo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:]
- -[PKStatefulTransferCredential serialNumber]
- -[PKStatefulTransferCredential setSerialNumber:]
- OBJC_IVAR_$_PKStatefulTransferCredential._serialNumber
- __swift__destructor.176Tm
- __swift_closure_destructor.113Tm
- __swift_closure_destructor.156Tm
- __swift_closure_destructor.209Tm
- __swift_closure_destructor.23Tm
- __swift_closure_destructor.29Tm
- _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:
- _symbolic ScTy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic Scgy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic _____Sg 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV
- _symbolic _____ySaySo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- _symbolic y_____ySaySo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
CStrings:
+ "ADT source UI provider: self deallocated in _generateCryptograms"
+ "B16@?0@\"PKTransitCommutePlan\"8"
+ "B32@?0@\"PKTransitCommutePlan\"8Q16^B24"
+ "PKPendingCampaignAttributionKey"
+ "Passbook_normalizedPhoneNumbers"
+ "SHAREABLE_CREDENTIAL_ERROR_MISMATCHED_ROLE_MESSAGE"
+ "SHAREABLE_CREDENTIAL_ERROR_MISMATCHED_ROLE_TITLE"
+ "[%@] PKPaymentProvisioningController: skipping NCCE for FPAN credential, missing a field required by this card's issuer (expiration required: %d missing: %d, name required: %d missing: %d)"
+ "[%s] Car key destination provider: Missing pass identifiers on credential"
+ "[%s] Dropping credential %s: failed to create PKExistingCardAuthorizationCredential"
+ "[%s] Dropping credential %s: no redemption token in response"
+ "[%s] Dropping credential with no remote credential"
+ "[%s] Failed to deprovision removed pass, result %lu: %@"
+ "[%s] Failed to deprovision rolled back pass, result %lu: %@"
+ "[%s] Failed to deprovision tracked pass during teardown, result %lu: %@"
+ "[%s] ProvisioningOperationComposer: Timed out tearing down %ld step(s); continuing"
+ "[%s] Timed out deprovisioning removed passes"
+ "[%s] Timed out deprovisioning rolled back passes."
+ "appleAccount"
+ "campaignAttributionNewToProductUser"
+ "campaignAttributionNewToWalletUser"
+ "cardReadyToUse"
+ "com.apple.Home-private"
+ "nccCheck"
+ "newToCreditUser"
+ "newToDebitUser"
+ "newToProductUser"
+ "newToTransitUser"
+ "newToWalletUser"
+ "userLockSettings"
- "ADT source UI provider: self deallocated in _generateCrytogram"
```
