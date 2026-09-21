## ExchangeWebServices

> `/System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices`

```diff

-846.200.41.1.1
-  __TEXT.__text: 0x40ca4
-  __TEXT.__objc_methlist: 0xb110
-  __TEXT.__const: 0x188
-  __TEXT.__cstring: 0xaa34
-  __TEXT.__oslogstring: 0xf6c
+846.200.51.0.0
+  __TEXT.__text: 0x41efc
+  __TEXT.__objc_methlist: 0xb258
+  __TEXT.__const: 0x1a8
+  __TEXT.__cstring: 0xaa9a
+  __TEXT.__oslogstring: 0x122f
   __TEXT.__gcc_except_tab: 0x5f0
-  __TEXT.__unwind_info: 0x1788
+  __TEXT.__unwind_info: 0x17f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x25d0
+  __DATA_CONST.__const: 0x2620
   __DATA_CONST.__objc_classlist: 0xfa0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f38
+  __DATA_CONST.__objc_selrefs: 0x4018
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x458
-  __DATA_CONST.__objc_arraydata: 0xf0
-  __DATA_CONST.__got: 0x10f0
-  __AUTH_CONST.__const: 0x720
-  __AUTH_CONST.__cfstring: 0x107c0
-  __AUTH_CONST.__objc_const: 0x49e28
+  __DATA_CONST.__objc_arraydata: 0x110
+  __DATA_CONST.__got: 0x10f8
+  __AUTH_CONST.__const: 0x740
+  __AUTH_CONST.__cfstring: 0x10a20
+  __AUTH_CONST.__objc_const: 0x49e88
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__auth_got: 0x338
   __AUTH.__objc_data: 0x9c40
-  __DATA.__objc_ivar: 0x1010
+  __DATA.__objc_ivar: 0x1018
   __DATA.__data: 0x550
-  __DATA.__bss: 0x260
+  __DATA.__bss: 0x270
   __DATA.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3263
-  Symbols:   9106
-  CStrings:  2236
+  Functions: 3295
+  Symbols:   9168
+  CStrings:  2262
 
Symbols:
+ +[EWSMailboxDenialPolicy denialReasonForHTTPResponse:]
+ +[EWSMailboxDenialPolicy denialReasonForStatusCode:policyReason:]
+ +[EWSMailboxDenialPolicy denialTallyContinuesFromReason:toReason:]
+ +[EWSMailboxDenialPolicy shouldClearRecordedDenialsWhenPublishingReporting:reportingEnabled:]
+ +[EWSMailboxDenialPolicy shouldPublishReportingEnabled:currentValue:valueWhenAbsent:accountInStore:retrying:]
+ +[EWSMailboxDenialPolicy shouldReportRefusalWithStatusCode:reason:endpointGoneAllowed:]
+ +[EWSMailboxDenialPolicy statusCodeIsClassifiableRefusal:]
+ +[EWSMailboxDenialPolicy statusCodeIsEndpointGoneRefusal:]
+ +[EWSMailboxDenialPolicy tokenForDenialReason:]
+ +[EWSRetirementAlertPolicy locationRetryIntervalForLocation:configuration:]
+ +[EWSRetirementAlertPolicy retryIsDueAfterInterval:retryInterval:]
+ +[EWSRetirementAlertPresenter _keyForKind:suffix:single:]
+ +[EWSRetirementAlertPresenter _keyPrefixForKind:suffix:]
+ +[EWSRetirementAlertPresenter _localizedStringForKey:]
+ +[EWSRetirementAlertPresenter _quotedAccountName:]
+ +[EWSRetirementAlertPresenter _stringForKey:substitution:]
+ +[EWSRetirementAlertPresenter _stringsBundle]
+ +[EWSRetirementAlertPresenter accountIconURL]
+ +[EWSRetirementAlertPresenter log]
+ +[EWSRetirementAlertPresenter messageForKind:accountNames:]
+ +[EWSRetirementAlertPresenter titleForKind:accountNames:]
+ -[EWSExchangeServiceBinding _endpointGoneReportingAllowedForAccount:]
+ -[EWSMailboxLocationStore _accountIdentifierForKey:]
+ -[EWSMailboxLocationStore _attemptDateForKey:]
+ -[EWSMailboxLocationStore _consumerAttemptKeyForAccountIdentifier:consumer:]
+ -[EWSMailboxLocationStore _recordLocation:attemptDate:attemptKey:forAccountIdentifier:]
+ -[EWSMailboxLocationStore lastAttemptDateForAccountIdentifier:consumer:]
+ -[EWSMailboxLocationStore recordLocation:attemptDate:forAccountIdentifier:consumer:]
+ -[EWSRetirementAlertConfiguration confirmedLocationRetryInterval]
+ -[EWSRetirementAlertConfiguration initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:]
+ -[EWSRetirementAlertConfiguration isEndpointGoneEnabled]
+ -[EWSRetirementAlertCoordinator _probeServerLocationForEmailAddress:completion:]
+ -[EWSRetirementAlertCoordinator _restoreAlertEligibilityForAccountIdentifier:]
+ -[EWSRetirementAlertCoordinator locationProbeForTests]
+ -[EWSRetirementAlertCoordinator mailboxReportingFlagsForAccountIdentifier:managed:]
+ -[EWSRetirementAlertCoordinator setLocationProbeForTests:]
+ GCC_except_table38
+ GCC_except_table43
+ GCC_except_table53
+ GCC_except_table55
+ GCC_except_table63
+ OBJC_IVAR_$_EWSRetirementAlertConfiguration._confirmedLocationRetryInterval
+ OBJC_IVAR_$_EWSRetirementAlertConfiguration._endpointGoneEnabled
+ OBJC_IVAR_$_EWSRetirementAlertCoordinator._locationProbeForTests
+ _EWSMailboxDenialPolicyReasonMatches
+ ___34+[EWSRetirementAlertPresenter log]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s_e23_v32?0q8q16"NSError"24l
+ _kCFUserNotificationIconURLKey
+ _kEWSMailboxDenialTokenEndpointGone
+ _kEWSMailboxEndpointGoneReportingEnabledKey
+ _kEWSMailboxPolicyReasonHeaderField
+ _kExchangeGraphCapabilityKey
+ _kExchangeGraphMigrationContactsKey
+ _kExchangeGraphMigrationExchangeSyncKey
+ _kExchangeGraphMigrationMailKey
+ _objc_msgSend$URLForResource:withExtension:
+ _objc_msgSend$_attemptDateForKey:
+ _objc_msgSend$_consumerAttemptKeyForAccountIdentifier:consumer:
+ _objc_msgSend$_endpointGoneReportingAllowedForAccount:
+ _objc_msgSend$_keyForKind:suffix:single:
+ _objc_msgSend$_keyPrefixForKind:suffix:
+ _objc_msgSend$_localizedStringForKey:
+ _objc_msgSend$_probeServerLocationForEmailAddress:completion:
+ _objc_msgSend$_quotedAccountName:
+ _objc_msgSend$_recordLocation:attemptDate:attemptKey:forAccountIdentifier:
+ _objc_msgSend$_restoreAlertEligibilityForAccountIdentifier:
+ _objc_msgSend$_stringForKey:substitution:
+ _objc_msgSend$_stringsBundle
+ _objc_msgSend$accountIconURL
+ _objc_msgSend$arrayWithCapacity:
+ _objc_msgSend$confirmedLocationRetryInterval
+ _objc_msgSend$denialReasonForHTTPResponse:
+ _objc_msgSend$denialReasonForStatusCode:policyReason:
+ _objc_msgSend$denialTallyContinuesFromReason:toReason:
+ _objc_msgSend$initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:
+ _objc_msgSend$isEndpointGoneEnabled
+ _objc_msgSend$localizedStringForKey:value:table:
+ _objc_msgSend$localizedStringWithFormat:
+ _objc_msgSend$locationProbeForTests
+ _objc_msgSend$locationRetryIntervalForLocation:configuration:
+ _objc_msgSend$messageForKind:accountNames:
+ _objc_msgSend$retryIsDueAfterInterval:retryInterval:
+ _objc_msgSend$shouldReportRefusalWithStatusCode:reason:endpointGoneAllowed:
+ _objc_msgSend$statusCodeIsClassifiableRefusal:
+ _objc_msgSend$statusCodeIsEndpointGoneRefusal:
+ _objc_msgSend$titleForKind:accountNames:
+ _objc_msgSend$tokenForDenialReason:
+ _objc_msgSend$valueForHTTPHeaderField:
- +[EWSMailboxDenialPolicy denialReasonForStatusCode:isAccessDeniedFault:faultMessage:]
- +[EWSMailboxDenialPolicy shouldPublishReportingEnabled:currentValue:accountInStore:retrying:]
- +[EWSMailboxDenialPolicy statusCodeIsAccessDeniedRefusal:isAccessDeniedFault:]
- +[EWSRetirementAlertPolicy shouldClassifyMailboxLocation:intervalSinceLastAttempt:retryInterval:]
- -[EWSExchangeServiceBindingTask faultIsAccessDenied]
- -[EWSExchangeServiceBindingTask setFaultIsAccessDenied:]
- -[EWSRetirementAlertConfiguration initWithEnabled:classificationRetryInterval:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:]
- -[EWSRetirementAlertCoordinator denialReportingEnabledForAccountIdentifier:managed:]
- -[EWSRetirementAlertCoordinator denialReportingEnabled]
- GCC_except_table35
- GCC_except_table42
- GCC_except_table48
- GCC_except_table54
- GCC_except_table60
- OBJC_IVAR_$_EWSExchangeServiceBindingTask._faultIsAccessDenied
- _EWSMailboxDenialFaultMessageContains
- ___block_descriptor_56_e8_32s40s48s_e23_v32?0q8q16"NSError"24l
- _objc_msgSend$arrayByAddingObject:
- _objc_msgSend$denialReasonForStatusCode:isAccessDeniedFault:faultMessage:
- _objc_msgSend$denialReportingEnabled
- _objc_msgSend$faultIsAccessDenied
- _objc_msgSend$initWithEnabled:classificationRetryInterval:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:
- _objc_msgSend$setFaultIsAccessDenied:
- _objc_msgSend$shouldClassifyMailboxLocation:intervalSinceLastAttempt:retryInterval:
- _objc_msgSend$statusCodeIsAccessDeniedRefusal:isAccessDeniedFault:
- _objc_msgSend$subarrayWithRange:
CStrings:
+ "\"("
+ "%@%@%@"
+ "%{public}@ mailbox answered %ld for every address, which is not being reported yet. Header %{private}@, url %{private}@."
+ "%{public}@ mailbox refused with status %ld and carried no reason header at all. Url %{private}@, fault %{private}@."
+ "%{public}@ mailbox refused with status %ld and no known shutoff reason. Header %{private}@, url %{private}@, fault %{private}@."
+ ".Attempt."
+ "Account %{public}@ is hosted in the cloud again; discarded stale refusals %{public}s, alert history %{public}s."
+ "Account %{public}@ was refused for reason %{public}@; report %{public}s."
+ "Account %{public}@ was refused with a missing endpoint, which is not being acted on yet."
+ "ConfirmedLocationRetryInterval"
+ "EWS retirement alert not shown: CFUserNotificationCreate failed with %d."
+ "EWS retirement alert not shown: a button title is missing from the bundle."
+ "EWS retirement alert not shown: its title or body is missing from the bundle."
+ "EWSMailboxEndpointGoneReportingEnabled"
+ "EWS_ALERT_ACCOUNT_LIST_OTHERS"
+ "EWS_ALERT_ACCOUNT_NAME"
+ "EWS_ALERT_DISMISS_BUTTON"
+ "EWS_ALERT_LEARN_MORE_BUTTON"
+ "EWS_LOCALIZED_STRING_MISSING"
+ "EWS_PROACTIVE_ALERT_"
+ "EWS_REACTIVE_ALERT_"
+ "EndpointGoneEnabled"
+ "ExchangeAccountIcon"
+ "ExchangeGraphCapability"
+ "ExchangeGraphMigrationContacts"
+ "ExchangeGraphMigrationExchangeSync"
+ "ExchangeGraphMigrationMail"
+ "Group.Read.All"
+ "MESSAGE"
+ "R"
+ "TITLE"
+ "User.Read.All"
+ "X-EWS-Policy-Reason"
+ "_MANY"
+ "_ONE"
+ "endpointGone"
+ "tiff"
- "\"'"
- "%lu others"
- "%{public}@ mailbox refused with access denied but no known shutoff wording, status %ld, fault %{private}@."
- "1 other"
- "Account %{public}@ was refused; report %{public}s."
- "B"
- "Learn More"
- "Microsoft is ending support for the protocol these accounts use: %@. Update macOS to keep them syncing."
- "The server is refusing to sync these accounts: %@. This can happen when support for the protocol they use ends, or when an administrator turns it off. Contact the administrator of your account."
- "Your Exchange account has stopped syncing"
- "Your Exchange account will stop syncing"
```
