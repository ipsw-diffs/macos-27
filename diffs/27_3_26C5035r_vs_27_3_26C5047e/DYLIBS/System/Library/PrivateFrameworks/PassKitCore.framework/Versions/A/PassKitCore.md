## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1696.3.3.1.0
-  __TEXT.__text: 0x86fd60
-  __TEXT.__objc_methlist: 0x703b0
+1696.3.5.4.0
+  __TEXT.__text: 0x873928
+  __TEXT.__objc_methlist: 0x70568
   __TEXT.__const: 0x18f80
   __TEXT.__swift5_typeref: 0x7ba2
-  __TEXT.__cstring: 0x6fc7d
+  __TEXT.__cstring: 0x70191
   __TEXT.__constg_swiftt: 0x6de8
   __TEXT.__swift5_reflstr: 0x5d2d
   __TEXT.__swift5_fieldmd: 0x73b0

   __TEXT.__swift5_proto: 0x116c
   __TEXT.__swift5_types: 0x754
   __TEXT.__swift5_capture: 0x4a3c
-  __TEXT.__oslogstring: 0x3727d
+  __TEXT.__oslogstring: 0x37332
   __TEXT.__swift_as_entry: 0x158
   __TEXT.__swift_as_ret: 0x16c
   __TEXT.__swift_as_cont: 0x2e8
   __TEXT.__swift5_mpenum: 0x138
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x6710
+  __TEXT.__gcc_except_tab: 0x6724
   __TEXT.__ustring: 0x1e76
-  __TEXT.__unwind_info: 0x24ad0
+  __TEXT.__unwind_info: 0x24bc0
   __TEXT.__eh_frame: 0x73d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x12490
+  __DATA_CONST.__const: 0x12500
   __DATA_CONST.__objc_classlist: 0x3d28
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23d00
+  __DATA_CONST.__objc_selrefs: 0x23de0
   __DATA_CONST.__objc_protorefs: 0x210
-  __DATA_CONST.__objc_superrefs: 0x3030
-  __DATA_CONST.__objc_arraydata: 0x28b0
-  __DATA_CONST.__got: 0x4920
-  __AUTH_CONST.__const: 0x2f670
-  __AUTH_CONST.__cfstring: 0x78460
-  __AUTH_CONST.__objc_const: 0xcc430
-  __AUTH_CONST.__objc_arrayobj: 0xd50
-  __AUTH_CONST.__objc_intobj: 0x10e0
+  __DATA_CONST.__objc_superrefs: 0x3038
+  __DATA_CONST.__objc_arraydata: 0x2ab8
+  __DATA_CONST.__got: 0x4940
+  __AUTH_CONST.__const: 0x2f710
+  __AUTH_CONST.__cfstring: 0x78d40
+  __AUTH_CONST.__objc_const: 0xcc608
+  __AUTH_CONST.__objc_arrayobj: 0xd68
+  __AUTH_CONST.__objc_intobj: 0x10f8
   __AUTH_CONST.__objc_dictobj: 0x15e0
   __AUTH_CONST.__objc_doubleobj: 0x2b0
   __AUTH_CONST.__auth_got: 0x28d8

   __AUTH.__data: 0x53f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x708c
+  __DATA.__objc_ivar: 0x70b8
   __DATA.__data: 0x8720
   __DATA.__bss: 0x21598
   __DATA.__common: 0x1c9
   __DATA_DIRTY.__objc_ivar: 0x1f20
   __DATA_DIRTY.__objc_data: 0x8a20
   __DATA_DIRTY.__data: 0x88
-  __DATA_DIRTY.__bss: 0x10c0
+  __DATA_DIRTY.__bss: 0x1108
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 53260
-  Symbols:   87881
-  CStrings:  20931
+  Functions: 53325
+  Symbols:   87998
+  CStrings:  21008
 
Symbols:
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:]
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:sessionIdentifier:]
+ +[PKAnalyticsReporter(Attribution) reportCashCampaignIdentifier:eventType:]
+ -[PKPassLibrary addPendingCampaignAttribution:forPassUniqueIdentifier:]
+ -[PKPassLibrary campaignAttributionNewToStatusesWithCompletion:]
+ -[PKPaymentService deleteUserNotificationReceiptForNotificationIdentifier:]
+ -[PKPaymentService insertUserNotificationReceiptForAccountIdentifier:deliveredDate:]
+ -[PKProvisioningAnalyticsSession _fetchCampaignAttributionNewToStatusesIfNeeded]
+ -[PKProvisioningAnalyticsSession _resolveCampaignAttributionNewToWalletUser]
+ -[PKProvisioningAnalyticsSession _setCampaignAttributionProvisionedPassUniqueIdentifier:onLocalDevice:]
+ -[PKProvisioningAnalyticsSession reportNCCCheck]
+ -[PKProvisioningAnalyticsSession setProvisionedPass:onLocalDevice:]
+ -[PKProvisioningAnalyticsSessionCampaignAttributionSubjectHandle reportNCCCheckWithState:]
+ -[PKProvisioningAnalyticsSessionStepReporter setProvisionedPass:onLocalDevice:]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToProductUser]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToWalletUser]
+ -[PKProvisioningAnalyticsState campaignAttributionReferralSource]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToProductUser:]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToWalletUser:]
+ -[PKSpotlightBaseDocumentProcessor fieldMapForFieldBuckets:duplicateKeys:]
+ -[PKSpotlightBaseDocumentProcessor isDonatableValue:]
+ -[PKSpotlightBoardingPassDocumentProcessor barcodeLegFromLegs:departureAirportCode:arrivalAirportCode:]
+ -[PKSpotlightBoardingPassDocumentProcessor carrierCodeForPassFlightNumber:barcodeAttributes:]
+ -[PKSpotlightBoardingPassDocumentProcessor departureDateForPass:]
+ -[PKSpotlightBoardingPassDocumentProcessor extractAttributesFromBarcodeOfPass:departureAirportCode:arrivalAirportCode:]
+ -[PKSpotlightBoardingPassDocumentProcessor isWellFormedBarcodeLeg:]
+ -[PKSpotlightBoardingPassDocumentProcessor passengerNameFromBarcodeName:]
+ -[PKSpotlightBoardingPassDocumentProcessor processDocument:]
+ -[PKSpotlightBoardingPassDocumentProcessor seatDesignationFromBarcodeSeat:]
+ -[PKUserNotificationReceipt initWithNotificationIdentifier:notificationType:accountIdentifier:accountBaseURL:requiresReporting:]
+ -[PKUserNotificationReceipt notificationType]
+ -[PKUserNotificationReceipt requiresReporting]
+ -[PKUserNotificationReceipt setNotificationType:]
+ -[PKUserNotificationReceipt setRequiresReporting:]
+ GCC_except_table112
+ GCC_except_table162
+ GCC_except_table205
+ GCC_except_table299
+ GCC_except_table302
+ GCC_except_table313
+ GCC_except_table326
+ GCC_except_table340
+ GCC_except_table352
+ GCC_except_table376
+ GCC_except_table385
+ GCC_except_table389
+ GCC_except_table407
+ GCC_except_table428
+ GCC_except_table485
+ GCC_except_table495
+ GCC_except_table498
+ GCC_except_table540
+ GCC_except_table544
+ GCC_except_table548
+ GCC_except_table558
+ GCC_except_table566
+ GCC_except_table568
+ GCC_except_table583
+ GCC_except_table586
+ GCC_except_table589
+ GCC_except_table592
+ GCC_except_table610
+ GCC_except_table773
+ GCC_except_table893
+ _MDItemEventFlightArrivalTerminal
+ _MDItemEventFlightCarrierCode
+ _MDItemEventFlightDepartureDateTime
+ _MDItemEventFlightDepartureTerminal
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._campaignAttributionNewToStatuses
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._campaignAttributionNewToStatusesGeneration
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._campaignAttributionQueue
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._didReportNCCCheck
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._didRequestCampaignAttributionNewToStatuses
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._didResolveCampaignAttributionNewToWalletUser
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._pendingCardReadyToUsePassUniqueIdentifier
+ _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToProductUser
+ _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToWalletUser
+ _OBJC_IVAR_$_PKUserNotificationReceipt._notificationType
+ _OBJC_IVAR_$_PKUserNotificationReceipt._requiresReporting
+ _PKAddPendingCampaignAttributionForPassUniqueIdentifier
+ _PKAnalyticsReportNewToCreditUserKey
+ _PKAnalyticsReportNewToDebitUserKey
+ _PKAnalyticsReportNewToTransitUserKey
+ _PKAnalyticsReportNewToWalletUserKey
+ _PKAnalyticsReporterAttributionAddLocalPendingCardReadyToUse
+ _PKAnalyticsReporterAttributionFetchNewToStatuses
+ _PKAnalyticsReporterAttributionSetLocalNewToStatusProvider
+ _PKAnalyticsReporterAttributionSetLocalPendingCardReadyToUseAddedHandler
+ _PKAnalyticsReporterAttributionSetPendingCardReadyToUse
+ _PKPassUniqueIdentifiersWithPendingCampaignAttribution
+ _PKPendingCampaignAttributionCampaignIdentifierKey
+ _PKPendingCampaignAttributionForPassUniqueIdentifier
+ _PKPendingCampaignAttributionNewToProductUserKey
+ _PKPendingCampaignAttributionNewToWalletUserKey
+ _PKPendingCampaignAttributionProductTypeKey
+ _PKPendingCampaignAttributionQueue
+ _PKPendingCampaignAttributionReferralSourceKey
+ _PKPendingCampaignAttributionSessionIDKey
+ _PKPendingCampaignAttributions
+ _PKRemoveExpiredPendingCampaignAttributions
+ _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
+ _PKSetPendingCampaignAttributions
+ _PKURLActionRoutePeerPaymentSendOrRequest
+ ___38-[PKProvisioningAnalyticsSession stop]_block_invoke
+ ___42-[PKProvisioningAnalyticsSession setPass:]_block_invoke
+ ___48-[PKProvisioningAnalyticsSession reportNCCCheck]_block_invoke
+ ___57-[PKProvisioningAnalyticsSession resetForNewProductSetup]_block_invoke
+ ___64-[PKPassLibrary campaignAttributionNewToStatusesWithCompletion:]_block_invoke
+ ___67-[PKProvisioningAnalyticsSession setProvisionedPass:onLocalDevice:]_block_invoke
+ ___71-[PKPassLibrary addPendingCampaignAttribution:forPassUniqueIdentifier:]_block_invoke
+ ___75-[PKProvisioningAnalyticsSession setCampaignAttributionReferrerIdentifier:]_block_invoke
+ ___80-[PKProvisioningAnalyticsSession _fetchCampaignAttributionNewToStatusesIfNeeded]_block_invoke
+ ___80-[PKProvisioningAnalyticsSession reportProvisioningCompleteForReporter:success:]_block_invoke
+ ___91-[PKProvisioningAnalyticsSession initWithEnvironment:intent:referralSource:archivedParent:]_block_invoke
+ ___95-[PKProvisioningAnalyticsSession reportProvisioningStepForReporter:step:success:error:context:]_block_invoke
+ ___PKAnalyticsReporterAttributionAddLocalPendingCardReadyToUse_block_invoke
+ ___PKAnalyticsReporterAttributionFetchNewToStatuses_block_invoke
+ ___PKAnalyticsReporterAttributionFetchNewToStatuses_block_invoke_2
+ ___PKAnalyticsReporterAttributionSendEvent_block_invoke
+ ___PKAnalyticsReporterAttributionSendEvent_block_invoke_2
+ ___PKAnalyticsReporterAttributionSendEvent_block_invoke_3
+ ___PKPendingCampaignAttributionQueue_block_invoke
+ ___PKRemoveExpiredPendingCampaignAttributions_block_invoke
+ ___block_descriptor_48_e8_32s_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ ___block_descriptor_48_e8_32w_e22_v16?0"NSDictionary"8l
+ ___swift_closure_destructor.42Tm
+ _objc_msgSend$_fetchCampaignAttributionNewToStatusesIfNeeded
+ _objc_msgSend$_resolveCampaignAttributionNewToWalletUser
+ _objc_msgSend$_setCampaignAttributionProvisionedPassUniqueIdentifier:onLocalDevice:
+ _objc_msgSend$addPendingCampaignAttribution:forPassUniqueIdentifier:
+ _objc_msgSend$barcodeLegFromLegs:departureAirportCode:arrivalAirportCode:
+ _objc_msgSend$campaignAttributionNewToProductUser
+ _objc_msgSend$campaignAttributionNewToStatusesWithCompletion:
+ _objc_msgSend$campaignAttributionNewToStatusesWithHandler:
+ _objc_msgSend$campaignAttributionNewToWalletUser
+ _objc_msgSend$campaignAttributionReferralSource
+ _objc_msgSend$carrierCodeForPassFlightNumber:barcodeAttributes:
+ _objc_msgSend$deleteUserNotificationReceiptForNotificationIdentifier:
+ _objc_msgSend$departureAirportCode
+ _objc_msgSend$departureDateForPass:
+ _objc_msgSend$destinationAirportCode
+ _objc_msgSend$extractAttributesFromBarcodeOfPass:departureAirportCode:arrivalAirportCode:
+ _objc_msgSend$fieldMapForFieldBuckets:duplicateKeys:
+ _objc_msgSend$initWithBarcodeMessage:
+ _objc_msgSend$insertUserNotificationReceiptForAccountIdentifier:deliveredDate:
+ _objc_msgSend$isDonatableValue:
+ _objc_msgSend$isWellFormedBarcodeLeg:
+ _objc_msgSend$passengerName
+ _objc_msgSend$passengerNameFromBarcodeName:
+ _objc_msgSend$passengerNameRecordNumber
+ _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:
+ _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:sessionIdentifier:
+ _objc_msgSend$reportNCCCheck
+ _objc_msgSend$reportNCCCheckWithState:
+ _objc_msgSend$seatDesignationFromBarcodeSeat:
+ _objc_msgSend$setCampaignAttributionNewToProductUser:
+ _objc_msgSend$setCampaignAttributionNewToWalletUser:
+ _objc_msgSend$setProvisionedPass:onLocalDevice:
- +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:]
- -[PKProvisioningAnalyticsSessionStepReporter setProvisionedPass:]
- -[PKUserNotificationReceipt initWithNotificationIdentifier:accountIdentifier:accountBaseURL:]
- GCC_except_table100
- GCC_except_table127
- GCC_except_table163
- GCC_except_table167
- GCC_except_table169
- GCC_except_table258
- GCC_except_table284
- GCC_except_table294
- GCC_except_table297
- GCC_except_table304
- GCC_except_table306
- GCC_except_table308
- GCC_except_table321
- GCC_except_table330
- GCC_except_table332
- GCC_except_table342
- GCC_except_table371
- GCC_except_table380
- GCC_except_table384
- GCC_except_table402
- GCC_except_table480
- GCC_except_table488
- GCC_except_table536
- GCC_except_table542
- GCC_except_table546
- GCC_except_table553
- GCC_except_table561
- GCC_except_table578
- GCC_except_table581
- GCC_except_table584
- GCC_except_table587
- GCC_except_table605
- GCC_except_table771
- GCC_except_table891
- _MDItemEventFlightBoardingDateTime
- ___swift_closure_destructor.43Tm
- _objc_msgSend$reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:
- _objc_msgSend$setProvisionedPass:
CStrings:
+ "-[PKPassLibrary %@]: no extended interface; cardReadyToUse won't be reported for %@"
+ "Failed to write pending campaign attributions"
+ "PKPendingCampaignAttributions"
+ "Pending campaign attribution already exists for %@"
+ "^([A-Z]{2,3}|[A-Z][0-9]|[0-9][A-Z]) ?[0-9]{1,4}[A-Z]?$"
+ "^0*([1-9][0-9]{0,2}[A-Z])$"
+ "^[0-9]{1,4}$"
+ "^[A-Z0-9]{2,3}$"
+ "^[A-Z]{3}$"
+ "addMoneySuccess"
+ "appleAccount"
+ "arrival terminal"
+ "arrival_gate"
+ "arrival_terminal"
+ "arrivalterminal"
+ "boarding gate"
+ "boarding-gate"
+ "boarding_gate"
+ "boardinggate"
+ "booking"
+ "booking_reference"
+ "bookingreference"
+ "campaignAttributionNewToProductUser"
+ "campaignAttributionNewToWalletUser"
+ "cardReadyToUse"
+ "com.apple.passkit.attribution.teardown"
+ "com.apple.passkit.pendingcampaignattribution"
+ "com.apple.passkit.provisioninganalytics.attribution"
+ "conf #"
+ "conf#"
+ "confirmation number"
+ "confirmationcode"
+ "confirmationnumber"
+ "confnum"
+ "customer name"
+ "departingterminal"
+ "departure terminal"
+ "departure_gate"
+ "departure_terminal"
+ "departureterminal"
+ "destination gate"
+ "destination terminal"
+ "destinationgate"
+ "destinationterminal"
+ "flight #"
+ "flight no"
+ "flight no."
+ "flight_number"
+ "flightnb"
+ "flightno"
+ "gate number"
+ "gate_number"
+ "name of passenger"
+ "nccCheck"
+ "newToCreditUser"
+ "newToDebitUser"
+ "newToProductUser"
+ "newToTransitUser"
+ "newToWalletUser"
+ "passenger-name"
+ "passenger_name"
+ "record locator"
+ "record_locator"
+ "recordlocator"
+ "requestMoneySuccess"
+ "requiresReporting"
+ "requiresReporting: %@; "
+ "reservation"
+ "reservation number"
+ "seat no"
+ "seat no."
+ "seat_number"
+ "seatno"
+ "sendMoneySuccess"
+ "startAddMoney"
+ "startRequestMoney"
+ "startSendMoney"
+ "startSendOrRequestMoney"
+ "traveler"
+ "traveler name"
+ "travelername"
- "boarding"
- "boarding time"
- "boardingtime"
- "boards"
```
