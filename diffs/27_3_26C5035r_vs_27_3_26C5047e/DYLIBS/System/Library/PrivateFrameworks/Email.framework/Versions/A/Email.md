## Email

> `/System/Library/PrivateFrameworks/Email.framework/Versions/A/Email`

```diff

-3901.300.31.0.0
-  __TEXT.__text: 0xed234
-  __TEXT.__objc_methlist: 0xd9d4
-  __TEXT.__const: 0x18d2
-  __TEXT.__gcc_except_tab: 0x1c168
-  __TEXT.__cstring: 0xcc59
+3901.300.60.0.0
+  __TEXT.__text: 0xef3ec
+  __TEXT.__objc_methlist: 0xdacc
+  __TEXT.__const: 0x18f8
+  __TEXT.__gcc_except_tab: 0x1c488
+  __TEXT.__cstring: 0xcca9
   __TEXT.__ustring: 0x170
-  __TEXT.__oslogstring: 0x6cf3
+  __TEXT.__oslogstring: 0x6db3
   __TEXT.__dlopen_cstrs: 0x160
-  __TEXT.__swift5_typeref: 0x4aa
-  __TEXT.__constg_swiftt: 0x538
+  __TEXT.__swift5_typeref: 0x4c0
+  __TEXT.__constg_swiftt: 0x540
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_reflstr: 0x41f
   __TEXT.__swift5_fieldmd: 0x610

   __TEXT.__swift5_capture: 0x48
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x89c8
+  __TEXT.__unwind_info: 0x8aa0
   __TEXT.__eh_frame: 0x328
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1a20
-  __DATA_CONST.__objc_classlist: 0x5b8
+  __DATA_CONST.__objc_classlist: 0x5c0
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6878
+  __DATA_CONST.__objc_selrefs: 0x6960
   __DATA_CONST.__objc_protorefs: 0x110
   __DATA_CONST.__objc_superrefs: 0x498
   __DATA_CONST.__objc_arraydata: 0x1e8
-  __DATA_CONST.__got: 0xd40
-  __AUTH_CONST.__const: 0x5630
-  __AUTH_CONST.__cfstring: 0xad00
-  __AUTH_CONST.__objc_const: 0x17f20
+  __DATA_CONST.__got: 0xd80
+  __AUTH_CONST.__const: 0x5680
+  __AUTH_CONST.__cfstring: 0xad60
+  __AUTH_CONST.__objc_const: 0x180d0
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0xaa8
-  __AUTH.__objc_data: 0x3e0
+  __AUTH_CONST.__auth_got: 0xac0
+  __AUTH.__objc_data: 0x430
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0xd30
-  __DATA.__data: 0x2880
+  __DATA.__objc_ivar: 0xd44
+  __DATA.__data: 0x28a8
   __DATA.__bss: 0x21d0
-  __DATA_DIRTY.__objc_data: 0x37b8
+  __DATA_DIRTY.__objc_data: 0x37c0
   __DATA_DIRTY.__data: 0x388
   __DATA_DIRTY.__bss: 0xce0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5460
-  Symbols:   11844
-  CStrings:  2254
+  Functions: 5492
+  Symbols:   11909
+  CStrings:  2261
 
Symbols:
+ +[EMMailSearchQueryBiomeLogger _normalizedKeyForQueryString:]
+ +[EMXiCloudHMEHeaderVerifier _hasVerifiedTrustedSignatureCoveringXiCloudHMEHeader:verifier:]
+ +[EMXiCloudHMEHeaderVerifier dkimSignatureCoversXiCloudHMEHeader:]
+ +[EMXiCloudHMEHeaderVerifier hasExactlyOneXiCloudHMEHeader:]
+ +[EMXiCloudHMEHeaderVerifier signingDomainsFromServerConfigurationValue:]
+ +[EMXiCloudHMEHeaderVerifier tagValueListForHeaderBody:isVerified:]
+ +[EMXiCloudHMEHeaderVerifier trustedSigningDomains]
+ +[EMXiCloudHMEHeaderVerifier trustedTagValueListForHeaders:deliveredByICloud:]
+ +[EMXiCloudHMEHeaderVerifier trustedTagValueListForHeaders:deliveredByICloud:verifier:]
+ -[EMLocalSearchInfo initWithQueryStatus:hasQueryEmbedding:hasKeywordResults:hasEmbeddingResults:querySafety:rankingSignalsByObjectID:]
+ -[EMLocalSearchInfo querySafety]
+ -[EMMailSearchQueryBiomeLogger _canLogCurrentState]
+ -[EMMailSearchQueryBiomeLogger _logEngagedStateIfSafe]
+ -[EMMailSearchQueryBiomeLogger querySafetyByQueryString]
+ -[EMMailSearchQueryBiomeLogger querySafetyKeysInInsertionOrder]
+ -[EMMailSearchQueryBiomeLogger setQuerySafetyByQueryString:]
+ -[EMMailSearchQueryBiomeLogger setQuerySafetyKeysInInsertionOrder:]
+ -[EMMailSearchQueryBiomeLogger trackQuerySafety:forQueryString:]
+ -[EMOutgoingMessageRepository outboxPresenceOfUnsentMessageWithMessageIDHeaderHash:completion:]
+ -[EMSearchQueryState querySafety]
+ -[EMSearchQueryState setQuerySafety:]
+ -[EMSearchableIndexQuery querySafetyBlock]
+ -[EMSearchableIndexQuery setQuerySafetyBlock:]
+ -[EMSearchableIndexTopHitsQuery querySafetyHandler]
+ -[EMSearchableIndexTopHitsQuery setQuerySafetyHandler:]
+ _ECMessageHeaderKeyHMEAddress
+ _EMQuerySafetyByCombining
+ _EMQuerySafetyForIsUnsafeQuery
+ _OBJC_CLASS_$_ECAngleBracketIDHash
+ _OBJC_CLASS_$_ECDKIMVerifier
+ _OBJC_CLASS_$_ECTagValueList
+ _OBJC_CLASS_$_EMXiCloudHMEHeaderVerifier
+ _OBJC_IVAR_$_EMLocalSearchInfo._querySafety
+ _OBJC_IVAR_$_EMMailSearchQueryBiomeLogger._querySafetyByQueryString
+ _OBJC_IVAR_$_EMMailSearchQueryBiomeLogger._querySafetyKeysInInsertionOrder
+ _OBJC_IVAR_$_EMSearchQueryState._querySafety
+ _OBJC_IVAR_$_EMSearchableIndexQuery._querySafetyBlock
+ _OBJC_IVAR_$_EMSearchableIndexTopHitsQuery._querySafetyHandler
+ _OBJC_METACLASS_$_EMXiCloudHMEHeaderVerifier
+ __OBJC_$_CLASS_METHODS_EMXiCloudHMEHeaderVerifier
+ __OBJC_$_CLASS_PROP_LIST_EMXiCloudHMEHeaderVerifier
+ __OBJC_CLASS_RO_$_EMXiCloudHMEHeaderVerifier
+ __OBJC_METACLASS_RO_$_EMXiCloudHMEHeaderVerifier
+ ___64-[EMMailSearchQueryBiomeLogger trackQuerySafety:forQueryString:]_block_invoke
+ ___66+[EMXiCloudHMEHeaderVerifier dkimSignatureCoversXiCloudHMEHeader:]_block_invoke
+ ___95-[EMOutgoingMessageRepository outboxPresenceOfUnsentMessageWithMessageIDHeaderHash:completion:]_block_invoke
+ ___block_descriptor_48_ea8_32bs_e5_v8?0l
+ ___block_descriptor_56_ea8_32bs40bs48w_e27_v16?0"CSAttributedQuery"8l
+ ___copy_helper_block_ea8_32b40b48w
+ _objc_msgSend$_canLogCurrentState
+ _objc_msgSend$_hasVerifiedTrustedSignatureCoveringXiCloudHMEHeader:verifier:
+ _objc_msgSend$_logEngagedStateIfSafe
+ _objc_msgSend$_normalizedKeyForQueryString:
+ _objc_msgSend$dkimSignatureCoversXiCloudHMEHeader:
+ _objc_msgSend$ef_stringByTrimmingWhitespaceAndNewlineCharacters
+ _objc_msgSend$encodedHeaders
+ _objc_msgSend$firstHeaderForKey:
+ _objc_msgSend$hasExactlyOneXiCloudHMEHeader:
+ _objc_msgSend$outboxPresenceOfUnsentMessageWithMessageIDHeaderHash:completion:
+ _objc_msgSend$querySafety
+ _objc_msgSend$querySafetyBlock
+ _objc_msgSend$querySafetyByQueryString
+ _objc_msgSend$querySafetyHandler
+ _objc_msgSend$querySafetyKeysInInsertionOrder
+ _objc_msgSend$removeObjectAtIndex:
+ _objc_msgSend$setQuerySafety:
+ _objc_msgSend$setQuerySafetyBlock:
+ _objc_msgSend$setWithObject:
+ _objc_msgSend$signedHeaderFields
+ _objc_msgSend$signingDomainIdentifier
+ _objc_msgSend$signingDomainsFromServerConfigurationValue:
+ _objc_msgSend$tagValueListFromString:error:
+ _objc_msgSend$trustedSigningDomains
+ _objc_msgSend$trustedTagValueListForHeaders:deliveredByICloud:verifier:
+ _objc_msgSend$verifiableMessageForMessageData:dkimSignatureHeaders:error:
+ _objc_msgSend$verifyMessage:withDKIMSignatureHeaders:options:error:
+ _swift_arrayInitWithCopy
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV6PolicyV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 5Email21ActivityStateObserverC08ObservedE0V
- -[EMContentRepresentation setSkipMessageReformatting:]
- -[EMContentRepresentation skipMessageReformatting]
- -[EMLocalSearchInfo initWithQueryStatus:hasQueryEmbedding:hasKeywordResults:hasEmbeddingResults:rankingSignalsByObjectID:]
- -[EMMessageContentCachedMetadata setSkipMessageReformatting:]
- -[EMMessageContentCachedMetadata skipMessageReformatting]
- -[EMSearchQueryState canBeLogged]
- -[EMSearchQueryState isUnsafeQuery]
- -[EMSearchQueryState setIsUnsafeQuery:]
- _OBJC_IVAR_$_EMSearchQueryState._isUnsafeQuery
- ___block_descriptor_48_ea8_32bs40w_e27_v16?0"CSAttributedQuery"8l
- _objc_msgSend$canBeLogged
- _objc_msgSend$setIsUnsafeQuery:
- _objc_msgSend$setSkipMessageReformatting:
- _objc_msgSend$skipMessageReformatting
CStrings:
+ "<%@ %p queryStatus: %d, hasQueryEmbedding: %@, hasKeywordResults: %@, hasEmbeddingResults: %@ querySafety: %ld rankingSignalsByObjectID.count: %lu>"
+ "Device isChinaRegion=%{bool}d"
+ "EFPropertyKey_querySafety"
+ "Not logging query because querySafety=%ld"
+ "TemporaryItems"
+ "Tracking querySafety=%ld for a query"
+ "encountered error while looking for an unsent outbox message: %{public}@"
+ "x-icloud-hme"
+ "x-icloud-hme-signing-domains"
- "<%@ %p queryStatus: %d, hasQueryEmbedding: %@, hasKeywordResults: %@, hasEmbeddingResults: %@ rankingSignalsByObjectID.count: %lu>"
- "SkipMessageReformat"
```
