## ExchangeAuthenticationPlugin

> `/System/Library/Accounts/Authentication/ExchangeAuthenticationPlugin.bundle/Contents/MacOS/ExchangeAuthenticationPlugin`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_protolist`
- `__DATA.__data`

```diff

-846.200.41.1.1
-  __TEXT.__text: 0xa6c4
-  __TEXT.__auth_stubs: 0x2c0
-  __TEXT.__objc_stubs: 0x16e0
-  __TEXT.__objc_methlist: 0x4fc
-  __TEXT.__const: 0xd8
-  __TEXT.__cstring: 0x510
-  __TEXT.__oslogstring: 0x12f1
-  __TEXT.__objc_classname: 0xfa
-  __TEXT.__objc_methname: 0x18b5
-  __TEXT.__objc_methtype: 0x6df
-  __TEXT.__gcc_except_tab: 0x214
-  __TEXT.__unwind_info: 0x388
-  __DATA_CONST.__const: 0x558
-  __DATA_CONST.__cfstring: 0x320
-  __DATA_CONST.__objc_classlist: 0x28
+846.200.51.0.0
+  __TEXT.__text: 0xd038
+  __TEXT.__auth_stubs: 0x330
+  __TEXT.__objc_stubs: 0x1cc0
+  __TEXT.__objc_methlist: 0x6a4
+  __TEXT.__const: 0xf0
+  __TEXT.__cstring: 0x58b
+  __TEXT.__oslogstring: 0x1516
+  __TEXT.__objc_classname: 0x15c
+  __TEXT.__objc_methname: 0x2247
+  __TEXT.__objc_methtype: 0x7ba
+  __TEXT.__gcc_except_tab: 0x278
+  __TEXT.__unwind_info: 0x460
+  __DATA_CONST.__const: 0x698
+  __DATA_CONST.__cfstring: 0x360
+  __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__objc_intobj: 0x30
-  __DATA_CONST.__auth_got: 0x170
-  __DATA_CONST.__got: 0x2f0
-  __DATA.__objc_const: 0xde8
-  __DATA.__objc_selrefs: 0x6d8
-  __DATA.__objc_ivar: 0x38
-  __DATA.__objc_data: 0x190
+  __DATA_CONST.__objc_superrefs: 0x20
+  __DATA_CONST.__objc_intobj: 0x60
+  __DATA_CONST.__auth_got: 0x1a8
+  __DATA_CONST.__got: 0x348
+  __DATA.__objc_const: 0x1140
+  __DATA.__objc_selrefs: 0x850
+  __DATA.__objc_ivar: 0x64
+  __DATA.__objc_data: 0x280
   __DATA.__data: 0x180
-  __DATA.__bss: 0x10
+  __DATA.__bss: 0x20
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 217
-  Symbols:   161
-  CStrings:  422
+  Functions: 271
+  Symbols:   190
+  CStrings:  508
 
Symbols:
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilityFullyStampedAccountIDs
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilityFullyStampedLock
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilityInFlightTracker
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilityRecentlyCheckedEntries
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilityRecentlyCheckedLock
+ OBJC_IVAR_$_ExchangeAuthenticationPlugin._graphCapabilitySession
+ _OBJC_CLASS_$_EWSGraphCapabilityInFlightTracker
+ _OBJC_CLASS_$_EWSGraphCapabilityPolicy
+ _OBJC_CLASS_$_EWSGraphCapabilityRecentlyCheckedEntry
+ _OBJC_CLASS_$_EWSMailboxLocationPolicy
+ _OBJC_CLASS_$_EWSMailboxLocationProbe
+ _OBJC_CLASS_$_EWSRetirementAlertPolicy
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_METACLASS_$_EWSGraphCapabilityInFlightTracker
+ _OBJC_METACLASS_$_EWSGraphCapabilityPolicy
+ _OBJC_METACLASS_$_EWSGraphCapabilityRecentlyCheckedEntry
+ ___NSArray0__struct
+ _arc4random_uniform
+ _dispatch_block_cancel
+ _dispatch_block_create
+ _kEWSMailboxEndpointGoneReportingEnabledKey
+ _kExchangeGraphCapabilityKey
+ _kExchangeGraphMigrationContactsKey
+ _kExchangeGraphMigrationExchangeSyncKey
+ _kExchangeGraphMigrationMailKey
+ _objc_alloc_init
+ _objc_autorelease
+ _objc_retainAutoreleaseReturnValue
+ _os_transaction_create
CStrings:
+ "@\"EWSGraphCapabilityInFlightTracker\""
+ "@\"NSDate\""
+ "@\"NSURLSession\""
+ "@40@0:8@16d24d32"
+ "B32@0:8@16@24"
+ "EWSGraphCapabilityInFlightTracker"
+ "EWSGraphCapabilityPolicy"
+ "EWSGraphCapabilityRecentlyCheckedEntry"
+ "Failed to save Graph migration properties for account %{public}@: %{private}@"
+ "Graph capability check deferred for account %{public}@: no email or username to probe with"
+ "Graph capability check running for account %{public}@ (usingGraph=%{public}d)"
+ "Graph capability verdict for account %{public}@: location=%{public}ld capable=%{public}d fullyResolved=%{public}d locationValueChanged=%{public}d missingMigrationKeys=%{public}lu probeFailedDueToConnectivity=%{public}d"
+ "Graph migration capability"
+ "GraphCapability"
+ "Saved Graph migration properties for account %{public}@ (fullyResolved=%{public}d)"
+ "T@\"NSDate\",R,N,V_checkedAt"
+ "Td,R,N,V_connectivityFailureBase"
+ "Td,R,N,V_retryInterval"
+ "UUID"
+ "_actOnGraphMigrationCapabilityLocation:probeFailedDueToConnectivity:accountIdentifier:accountStore:invocationToken:releaseClaim:"
+ "_allGraphMigrationKeys"
+ "_checkGraphMigrationCapabilityForAccountIdentifier:emailAddress:usingGraph:hasEverBeenEWSAccount:accountStore:"
+ "_checkedAt"
+ "_connectivityFailureBase"
+ "_currentExchangeAccountIdentifiersInStore:"
+ "_freshExchangeAccountWithIdentifier:accountStore:"
+ "_graphCapabilityFullyStampedAccountIDs"
+ "_graphCapabilityFullyStampedLock"
+ "_graphCapabilityInFlightTracker"
+ "_graphCapabilityRecentlyCheckedEntries"
+ "_graphCapabilityRecentlyCheckedLock"
+ "_graphCapabilitySession"
+ "_hasAllGraphMigrationKeysOnAccount:"
+ "_hasEverBeenEWSAccount:"
+ "_isGraphCapabilityFullyStampedForAccountIdentifier:"
+ "_isGraphCapabilityRecentlyCheckedForAccountIdentifier:"
+ "_lock"
+ "_presentGraphMigrationKeysForAccount:allKeys:"
+ "_previousGraphCapabilityConnectivityFailureBaseForAccountIdentifier:"
+ "_pruneGraphCapabilityFullyStampedAccountIDsNotIn:"
+ "_pruneGraphCapabilityRecentlyCheckedEntriesNotIn:"
+ "_recordGraphCapabilityOutcomeForAccountIdentifier:permanentlyResolved:retryInterval:connectivityFailureBase:"
+ "_rememberGraphCapabilityFullyStampedForAccountIdentifier:"
+ "_rememberGraphCapabilityRecentlyCheckedForAccountIdentifier:retryInterval:connectivityFailureBase:"
+ "_retryInterval"
+ "_shouldDispatchGraphCapabilityCheckForAccount:accountIdentifier:"
+ "_tokensByAccountID"
+ "checkedAt"
+ "claimAccountIdentifier:"
+ "com.apple.exchangewebservices.graphcapabilitycheck"
+ "connectivityFailureBase"
+ "d"
+ "d16@0:8"
+ "d24@0:8@16"
+ "d40@0:8d16d24d32"
+ "dictionary"
+ "durableLocationForProbedLocation:statusCode:"
+ "hasEverBeenEWSAccountWithExternalURLPresent:internalURLPresent:"
+ "initWithCheckedAt:retryInterval:connectivityFailureBase:"
+ "intersectSet:"
+ "intervalSinceDate:"
+ "invalidateCachedValues"
+ "isAccountIdentifierClaimed:"
+ "isGraphCapableForDurableMailboxLocation:"
+ "isToken:stillOwnerOfAccountIdentifier:"
+ "lastAttemptDateForAccountIdentifier:consumer:"
+ "locationForAccountIdentifier:"
+ "locationStore"
+ "mailboxReportingFlagsForAccountIdentifier:managed:"
+ "missingKeysFromKeys:presentKeys:"
+ "nextConnectivityFailureBaseInterval:capInterval:baseInterval:"
+ "pruneAccountsNotIn:"
+ "recordLocation:attemptDate:forAccountIdentifier:consumer:"
+ "releaseAccountIdentifier:ifStillOwnedByToken:"
+ "removeObjectForKey:"
+ "removeObjectsForKeys:"
+ "retryInterval"
+ "retryIsDueAfterInterval:retryInterval:"
+ "sendServerLocationRequestForEmailAddress:session:completion:"
+ "setByAddingObject:"
+ "shouldClearRecordedDenialsWhenPublishingReporting:reportingEnabled:"
+ "shouldPublishReportingEnabled:currentValue:valueWhenAbsent:accountInStore:retrying:"
+ "shouldRecordClassificationAttemptForStatusCode:"
+ "v32@?0q8q16@\"NSError\"24"
+ "v40@0:8@16d24d32"
+ "v44@0:8@16B24d28d36"
+ "v48@0:8@16@24B32B36@40"
+ "v60@0:8q16B24@28@36@44@?52"
- "denialReportingEnabledForAccountIdentifier:managed:"
- "shouldPublishReportingEnabled:currentValue:accountInStore:retrying:"
```
