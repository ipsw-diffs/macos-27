## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1696.2.9.0.0
-  __TEXT.__text: 0x86a5e0
-  __TEXT.__objc_methlist: 0x70248
-  __TEXT.__const: 0x18fe0
+1696.3.3.1.0
+  __TEXT.__text: 0x86fd60
+  __TEXT.__objc_methlist: 0x703b0
+  __TEXT.__const: 0x18f80
   __TEXT.__swift5_typeref: 0x7ba2
-  __TEXT.__cstring: 0x6fa07
+  __TEXT.__cstring: 0x6fc7d
   __TEXT.__constg_swiftt: 0x6de8
   __TEXT.__swift5_reflstr: 0x5d2d
   __TEXT.__swift5_fieldmd: 0x73b0

   __TEXT.__swift5_assocty: 0xba0
   __TEXT.__swift5_proto: 0x116c
   __TEXT.__swift5_types: 0x754
-  __TEXT.__swift5_capture: 0x4a24
-  __TEXT.__oslogstring: 0x3720c
+  __TEXT.__swift5_capture: 0x4a3c
+  __TEXT.__oslogstring: 0x3727d
   __TEXT.__swift_as_entry: 0x158
   __TEXT.__swift_as_ret: 0x16c
   __TEXT.__swift_as_cont: 0x2e8
   __TEXT.__swift5_mpenum: 0x138
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x6638
-  __TEXT.__ustring: 0x1e6c
-  __TEXT.__unwind_info: 0x249e0
+  __TEXT.__gcc_except_tab: 0x6710
+  __TEXT.__ustring: 0x1e76
+  __TEXT.__unwind_info: 0x24ad0
   __TEXT.__eh_frame: 0x73d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x123e8
+  __DATA_CONST.__const: 0x12490
   __DATA_CONST.__objc_classlist: 0x3d28
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23c30
+  __DATA_CONST.__objc_selrefs: 0x23d00
   __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x3030
-  __DATA_CONST.__objc_arraydata: 0x2850
+  __DATA_CONST.__objc_arraydata: 0x28b0
   __DATA_CONST.__got: 0x4920
-  __AUTH_CONST.__const: 0x2f560
-  __AUTH_CONST.__cfstring: 0x78280
-  __AUTH_CONST.__objc_const: 0xcc330
+  __AUTH_CONST.__const: 0x2f670
+  __AUTH_CONST.__cfstring: 0x78460
+  __AUTH_CONST.__objc_const: 0xcc430
   __AUTH_CONST.__objc_arrayobj: 0xd50
   __AUTH_CONST.__objc_intobj: 0x10e0
-  __AUTH_CONST.__objc_dictobj: 0x1590
+  __AUTH_CONST.__objc_dictobj: 0x15e0
   __AUTH_CONST.__objc_doubleobj: 0x2b0
-  __AUTH_CONST.__auth_got: 0x28d0
+  __AUTH_CONST.__auth_got: 0x28d8
   __AUTH.__objc_data: 0x1ee48
   __AUTH.__data: 0x53f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x7078
+  __DATA.__objc_ivar: 0x708c
   __DATA.__data: 0x8720
   __DATA.__bss: 0x21598
-  __DATA.__common: 0x1d9
+  __DATA.__common: 0x1c9
   __DATA_DIRTY.__objc_ivar: 0x1f20
   __DATA_DIRTY.__objc_data: 0x8a20
   __DATA_DIRTY.__data: 0x88

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 53201
-  Symbols:   87782
-  CStrings:  20913
+  Functions: 53260
+  Symbols:   87881
+  CStrings:  20931
 
Symbols:
+ +[PKPaymentCommutePlanDetail nextBoundaryDateForPlans:]
+ +[PKTransitCommutePlan(Utilities) activationPromptForCommutePlan:pass:balanceModel:]
+ +[PKTransitCommutePlan(Utilities) dateStringForDate:field:]
+ +[PKTransitCommutePlan(Utilities) localizableStringsFromTickets:]
+ +[PKTransitCommutePlan(Utilities) routeStringFromDeparture:destination:bidirectional:]
+ +[PKTransitCommutePlan(Utilities) routeStringFromTicket:isReloadableTicketsPass:localizedStrings:]
+ +[PKTransitCommutePlan(Utilities) stationCodeFromTicket:stationType:localizedStrings:]
+ -[PKDataAccessor passLocalizedStringsForKeys:completion:]
+ -[PKFileDataAccessor passLocalizedStringsForKeys:completion:]
+ -[PKIssuerMessagingFlag expirationDate]
+ -[PKIssuerMessagingFlag setExpirationDate:]
+ -[PKObject localizedStrings:completion:]
+ -[PKPassLibrary passLocalizedStringsForKeys:uniqueID:completion:]
+ -[PKPaymentCommutePlanDetail isActivatedValue]
+ -[PKPaymentCommutePlanDetail retirementDate]
+ -[PKPaymentCommutePlanDetail setIsActivatedValue:]
+ -[PKPaymentCommutePlanDetail setRetirementDate:]
+ -[PKPaymentCommutePlanDetail setTicketState:]
+ -[PKPaymentCommutePlanDetail ticketState]
+ -[PKPaymentCredential(PKPaymentCredentialSubclassAdditions) compare:withBackedUpDefaultPaymentPassSerialNumber:demoteNonStandardFlowCredentials:]
+ -[PKPaymentDefaultDataProvider _schedulePlanRedelivery:forPassUniqueIdentifier:]
+ -[PKPaymentService(Identity) generateIdentityPrearmTrustKeyMaterialForDeviceID:completion:]
+ -[PKRemoteDataAccessor passLocalizedStringsForKeys:completion:]
+ -[PKTicketDetails transitStatus]
+ -[PKTransitBalanceModel _canStillUseHybridPlan:]
+ -[PKTransitBalanceModel _hasActiveTicketWindowForCommutePlan:]
+ -[PKTransitBalanceModel _summaryForCommutePlans:isExpired:]
+ -[PKTransitBalanceModel _ticketForCommutePlan:]
+ -[PKTransitBalanceModel commutePlanDetailForTicket:]
+ -[PKTransitBalanceModel getDisplayableCommutePlanDetailsForPlans:title:value:subtitle:isExpired:]
+ -[PKTransitBalanceModel getDisplayableTicketDetailsForTitle:value:subtitle:isExpired:]
+ -[PKTransitBalanceModel hasRemainingCommutePlanContent]
+ -[PKTransitBalanceModel hasTicketContent]
+ -[PKTransitBalanceModel isRetiredTicket:]
+ -[PKTransitBalanceModel localizedStatusForTicket:]
+ -[PKTransitBalanceModel localizedTicketStrings]
+ -[PKTransitBalanceModel localizedTransitStatusForTicket:]
+ -[PKTransitBalanceModel pulledOutCommutePlanWithRemainingPlans:]
+ -[PKTransitBalanceModel remainingCommutePlans]
+ -[PKTransitBalanceModel setLocalizedTicketStrings:]
+ -[PKTransitBalanceModel shouldCollectPlan:withAction:]
+ -[PKTransitBalanceModel transitStatusForTicket:]
+ GCC_except_table149
+ GCC_except_table150
+ GCC_except_table258
+ GCC_except_table284
+ GCC_except_table297
+ GCC_except_table304
+ GCC_except_table306
+ GCC_except_table308
+ GCC_except_table321
+ GCC_except_table330
+ GCC_except_table335
+ GCC_except_table342
+ GCC_except_table347
+ GCC_except_table371
+ GCC_except_table380
+ GCC_except_table384
+ GCC_except_table402
+ GCC_except_table423
+ GCC_except_table460
+ GCC_except_table480
+ GCC_except_table488
+ GCC_except_table493
+ GCC_except_table553
+ GCC_except_table563
+ GCC_except_table587
+ GCC_except_table605
+ GCC_except_table677
+ GCC_except_table721
+ GCC_except_table729
+ _OBJC_IVAR_$_PKIssuerMessagingFlag._expirationDate
+ _OBJC_IVAR_$_PKPaymentCommutePlanDetail._isActivatedValue
+ _OBJC_IVAR_$_PKPaymentCommutePlanDetail._retirementDate
+ _OBJC_IVAR_$_PKPaymentCommutePlanDetail._ticketState
+ _OBJC_IVAR_$_PKPaymentDefaultDataProvider._planBoundaryTimers
+ _OBJC_IVAR_$_PKTicketDetails._transitStatus
+ _OBJC_IVAR_$_PKTransitBalanceModel._localizedTicketStrings
+ _OBJC_IVAR_$_PKTransitBalanceModel._pulledOutCommutePlan
+ _OBJC_IVAR_$_PKTransitBalanceModel._remainingCommutePlans
+ _PKHowToUseWalletCapabilityStringHomeButton
+ _PKHowToUseWalletCapabilityStringSideButton
+ _PKISO23220_1_PhotoID_FamilyNameUnicode
+ _PKISO23220_1_PhotoID_GivenNameUnicode
+ _PKISO23220_1_PhotoID_IssuingAuthorityUnicode
+ _PKIssuerMessagingFlagExpirationDateFromRecord
+ _PKLocalizedTicketString
+ _PKRouteArrowBidirectional
+ _PKRouteArrowUnidirectional
+ _PKUnsetDisplayProperties
+ __PKCommutePlanExpiryString
+ __PKDictionaryByDeepMergingPrivateOverRoot
+ __PKFormatDateWithPassField
+ __PKOptionalJSONDictionaryAtURL
+ __Z19_PKGetPassWidthType6CGSizeS_
+ ___145-[PKPaymentCredential(PKPaymentCredentialSubclassAdditions) compare:withBackedUpDefaultPaymentPassSerialNumber:demoteNonStandardFlowCredentials:]_block_invoke
+ ___40-[PKObject localizedStrings:completion:]_block_invoke
+ ___40-[PKObject localizedStrings:completion:]_block_invoke_2
+ ___48-[PKFileDataAccessor passLocalizedStringForKey:]_block_invoke
+ ___52-[PKTransitCommutePlan updateWithCommutePlanDetail:]_block_invoke
+ ___61-[PKFileDataAccessor passLocalizedStringsForKeys:completion:]_block_invoke
+ ___62-[PKTransitBalanceModel _hasActiveTicketWindowForCommutePlan:]_block_invoke
+ ___65-[PKPassLibrary passLocalizedStringsForKeys:uniqueID:completion:]_block_invoke
+ ___73-[PKPaymentPassContent initWithDictionary:bundle:privateBundle:passType:]_block_invoke
+ ___80-[PKPaymentDefaultDataProvider _schedulePlanRedelivery:forPassUniqueIdentifier:]_block_invoke
+ ___80-[PKPaymentDefaultDataProvider _schedulePlanRedelivery:forPassUniqueIdentifier:]_block_invoke_2
+ ___80-[PKPaymentDefaultDataProvider _schedulePlanRedelivery:forPassUniqueIdentifier:]_block_invoke_3
+ ___83-[PKPaymentDefaultDataProvider plansForPaymentPassWithUniqueIdentifier:completion:]_block_invoke
+ ___91-[PKPaymentService(Identity) generateIdentityPrearmTrustKeyMaterialForDeviceID:completion:]_block_invoke
+ ___PKSetDisplayProperties_block_invoke
+ ___PKSetDisplayProperties_block_invoke_2
+ ____PKDictionaryByDeepMergingPrivateOverRoot_block_invoke
+ ___block_descriptor_40_e8_32s_e21_16?0"PKPassField"8l
+ ___block_descriptor_40_e8_32s_e36_B16?0"PKPaymentCommutePlanDetail"8l
+ ___block_descriptor_48_e8_32s40bs_e65_v24?0"PKAuxiliaryCapabilityRequirementKeyMaterial"8"NSError"16l
+ ___block_descriptor_48_e8_32s40w_e17_v16?0"NSArray"8l
+ ___swift_closure_destructor.60Tm
+ _malloc_type_calloc
+ _objc_msgSend$_canStillUseHybridPlan:
+ _objc_msgSend$_hasActiveTicketWindowForCommutePlan:
+ _objc_msgSend$_schedulePlanRedelivery:forPassUniqueIdentifier:
+ _objc_msgSend$_summaryForCommutePlans:isExpired:
+ _objc_msgSend$_ticketForCommutePlan:
+ _objc_msgSend$activationPromptForCommutePlan:pass:balanceModel:
+ _objc_msgSend$commutePlan
+ _objc_msgSend$commutePlanDetailForTicket:
+ _objc_msgSend$compare:withBackedUpDefaultPaymentPassSerialNumber:demoteNonStandardFlowCredentials:
+ _objc_msgSend$concessionScheme
+ _objc_msgSend$contactInfo
+ _objc_msgSend$discountType
+ _objc_msgSend$displayDateStringForCommutePlan:pass:balanceModel:
+ _objc_msgSend$fareClass
+ _objc_msgSend$formattedBalanceForCountOrHybridCommutePlan:
+ _objc_msgSend$generateIdentityPrearmTrustKeyMaterialForDeviceID:completion:
+ _objc_msgSend$getPassLocalizedStringsForKeys:uniqueID:handler:
+ _objc_msgSend$hasExpiredDateForCommutePlan:balanceModel:
+ _objc_msgSend$initWithIdentifier:forValue:roundingToExponent:
+ _objc_msgSend$isActivatedValue
+ _objc_msgSend$isRetiredTicket:
+ _objc_msgSend$nextBoundaryDateForPlans:
+ _objc_msgSend$passLocalizedStringsForKeys:completion:
+ _objc_msgSend$passLocalizedStringsForKeys:uniqueID:completion:
+ _objc_msgSend$passValidityDurationField
+ _objc_msgSend$passengerType
+ _objc_msgSend$pulledOutCommutePlanWithRemainingPlans:
+ _objc_msgSend$requiredIssuerAppAction
+ _objc_msgSend$retirementDate
+ _objc_msgSend$routeName
+ _objc_msgSend$routeStringFromDeparture:destination:bidirectional:
+ _objc_msgSend$routeStringFromTicket:isReloadableTicketsPass:localizedStrings:
+ _objc_msgSend$routeType
+ _objc_msgSend$setPreformattedString:
+ _objc_msgSend$stationCodeFromTicket:stationType:localizedStrings:
+ _objc_msgSend$ticketState
+ _objc_msgSend$transitStatus
+ _objc_msgSend$transitStatusForTicket:
- +[PKPaymentHeroImageController cardArtSizeForWatchViewSize:]
- +[PKTransitBalanceModel shouldCollectPlan:withAction:]
- +[PKTransitCommutePlan(Utilities) routeStringFromTicket:isReloadableTicketsPass:]
- +[PKTransitCommutePlan(Utilities) stationCodeFromTicket:stationType:]
- -[PKFileDataAccessor _passLocalizedStringForKey:preferredLanguages:]
- -[PKObject localizedString:]
- -[PKPaymentHeroImageController cardArtSizeForSize:]
- -[PKPaymentHeroImageController setWatchSize:]
- -[PKPaymentHeroImageController watchSize]
- -[PKTicketStationDetails boardingZone]
- -[PKTicketStationDetails platformBoardingPosition]
- -[PKTicketStationDetails platform]
- -[PKTransitBalanceModel getDisplayableCommutePlanDetailsForTitle:value:subtitle:isExpired:]
- GCC_except_table197
- GCC_except_table218
- GCC_except_table281
- GCC_except_table301
- GCC_except_table303
- GCC_except_table305
- GCC_except_table318
- GCC_except_table327
- GCC_except_table329
- GCC_except_table339
- GCC_except_table344
- GCC_except_table368
- GCC_except_table377
- GCC_except_table381
- GCC_except_table399
- GCC_except_table455
- GCC_except_table477
- GCC_except_table485
- GCC_except_table487
- GCC_except_table550
- GCC_except_table558
- GCC_except_table560
- GCC_except_table575
- GCC_except_table602
- GCC_except_table672
- GCC_except_table716
- GCC_except_table724
- GCC_except_table93
- _OBJC_IVAR_$_PKPaymentHeroImageController._watchSize
- _OBJC_IVAR_$_PKTicketStationDetails._boardingZone
- _OBJC_IVAR_$_PKTicketStationDetails._platform
- _OBJC_IVAR_$_PKTicketStationDetails._platformBoardingPosition
- __OBJC_$_CLASS_METHODS_PKTransitBalanceModel
- __PKFormatCommutePlanDate
- __PKNormalizedLanguageIdentifier
- __Z19_PKGetPassWidthType6CGSize
- ___112-[PKPaymentCredential(PKPaymentCredentialSubclassAdditions) compare:withBackedUpDefaultPaymentPassSerialNumber:]_block_invoke
- ___displayPropertiesSet
- ___swift_closure_destructor.54Tm
- _objc_msgSend$_passLocalizedStringForKey:preferredLanguages:
- _objc_msgSend$cardArtSizeForWatchViewSize:
- _objc_msgSend$displayableCommutePlanCount
- _objc_msgSend$routeStringFromTicket:isReloadableTicketsPass:
- _objc_msgSend$stationCodeFromTicket:stationType:
CStrings:
+ "B16@?0@\"PKPaymentCommutePlanDetail\"8"
+ "COMMUTE_PLAN_COUNT_BASED_NUMBER_OF_RIDES_CROSSINGS"
+ "COMMUTE_PLAN_COUNT_BASED_NUMBER_OF_RIDES_EXCURSIONS"
+ "COMMUTE_PLAN_COUNT_BASED_NUMBER_OF_RIDES_JOURNEYS"
+ "Delegated payment request must not specify a merchant identifier"
+ "HomeButton"
+ "IsVirtualDevice"
+ "PKFieldUnitTypeNone, PKFieldUnitTypeDefault, PKFieldUnitTypeRides, PKFieldUnitTypeTickets, PKFieldUnitTypeLoyaltyPoints, PKFieldUnitTypeCrossings, PKFieldUnitTypeJourneys, PKFieldUnitTypeExcursions"
+ "PKPaymentRequest merchantIdentifier must not be set when isDelegatedRequest is true"
+ "SideButton"
+ "TICKET_STATUS_ACTIVE"
+ "TICKET_STATUS_PENDING"
+ "TICKET_STATUS_SUSPENDED"
+ "TICKET_TRANSIT_STATUS_CANCELLED"
+ "TICKET_TRANSIT_STATUS_DELAYED"
+ "TICKET_TRANSIT_STATUS_ON_TIME"
+ "[%s] Failed to remove pass %s locally: %@"
+ "cardHomeButtonTouchID"
+ "cardSideButtonTouchID"
+ "companionPreArmTrust"
+ "countRemaining"
+ "dot.list.bullet.page"
+ "isActivatedValue"
+ "retirementDate"
+ "ticketState"
+ "v24@?0@\"PKAuxiliaryCapabilityRequirementKeyMaterial\"8@\"NSError\"16"
+ "\u2068%@\u2069"
- "\r"
- "PKFieldUnitTypeNone, PKFieldUnitTypeDefault, PKFieldUnitTypeRides, PKFieldUnitTypeTickets, PKFieldUnitTypeLoyaltyPoints"
- "boardingZone: %@; "
- "cardTouchID"
- "platform"
- "platform: %@; "
- "platformBoardingPosition"
- "platformBoardingPosition: %@; "
- "text.rectangle.page"
```
