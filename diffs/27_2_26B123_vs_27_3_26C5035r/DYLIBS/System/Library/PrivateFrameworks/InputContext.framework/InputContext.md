## InputContext

> `/System/Library/PrivateFrameworks/InputContext.framework/InputContext`

```diff

-137.0.0.0.0
-  __TEXT.__text: 0x12ae4
-  __TEXT.__objc_methlist: 0x1464
+138.0.0.0.0
+  __TEXT.__text: 0x128f8
+  __TEXT.__objc_methlist: 0x156c
   __TEXT.__const: 0xe8
-  __TEXT.__cstring: 0x8ab
-  __TEXT.__gcc_except_tab: 0x7c4
-  __TEXT.__oslogstring: 0xf39
+  __TEXT.__cstring: 0x879
+  __TEXT.__gcc_except_tab: 0x720
+  __TEXT.__oslogstring: 0xe8e
   __TEXT.__ustring: 0x12
-  __TEXT.__unwind_info: 0x7f0
+  __TEXT.__unwind_info: 0x7c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x60
-  __DATA_CONST.__objc_classlist: 0xa0
+  __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_catlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x50
+  __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc60
-  __DATA_CONST.__objc_superrefs: 0x80
+  __DATA_CONST.__objc_selrefs: 0xcd0
+  __DATA_CONST.__objc_superrefs: 0x88
   __DATA_CONST.__objc_arraydata: 0x78
-  __DATA_CONST.__got: 0x240
-  __AUTH_CONST.__const: 0x680
-  __AUTH_CONST.__cfstring: 0xca0
-  __AUTH_CONST.__objc_const: 0x2200
+  __DATA_CONST.__got: 0x2b0
+  __AUTH_CONST.__const: 0x5f0
+  __AUTH_CONST.__cfstring: 0xc60
+  __AUTH_CONST.__objc_const: 0x23d0
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x19c
-  __DATA.__data: 0x42a
-  __DATA.__bss: 0x18
-  __DATA_DIRTY.__objc_data: 0x5f0
-  __DATA_DIRTY.__bss: 0xa0
+  __AUTH.__objc_data: 0xf0
+  __DATA.__objc_ivar: 0x1ac
+  __DATA.__data: 0x48a
+  __DATA.__bss: 0x28
+  __DATA_DIRTY.__objc_data: 0x5a0
+  __DATA_DIRTY.__bss: 0x90
+  - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/LanguageModeling.framework/Versions/A/LanguageModeling
   - /System/Library/PrivateFrameworks/Lexicon.framework/Versions/A/Lexicon
+  - /System/Library/PrivateFrameworks/PeopleSuggester.framework/Versions/A/PeopleSuggester
   - /System/Library/PrivateFrameworks/PersonalizationPortrait.framework/Versions/A/PersonalizationPortrait
   - /System/Library/PrivateFrameworks/ProactiveInputPredictions.framework/Versions/A/ProactiveInputPredictions
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 544
-  Symbols:   1305
-  CStrings:  210
+  Functions: 538
+  Symbols:   1326
+  CStrings:  204
 
Symbols:
+ +[_ICContactScorer scoreForContactIdentifier:rankMap:]
+ -[_ICContactScorer .cxx_destruct]
+ -[_ICContactScorer fetchRankMap]
+ -[_ICContactScorer init]
+ -[_ICContactsLexiconSource .cxx_destruct]
+ -[_ICContactsLexiconSource _beginPass:manager:]
+ -[_ICContactsLexiconSource _contactFromCNContact:]
+ -[_ICContactsLexiconSource _contactStoreDidChange:]
+ -[_ICContactsLexiconSource _deletedContactPlaceholder]
+ -[_ICContactsLexiconSource _endPassWithManager:isInitialLoad:]
+ -[_ICContactsLexiconSource _handleContact:changeType:]
+ -[_ICContactsLexiconSource _processChangeHistory]
+ -[_ICContactsLexiconSource _rankMapForPass]
+ -[_ICContactsLexiconSource dealloc]
+ -[_ICContactsLexiconSource hibernate]
+ -[_ICContactsLexiconSource init]
+ -[_ICContactsLexiconSource startLoadingWithManager:]
+ -[_ICContactsLexiconSource visitAddContactEvent:]
+ -[_ICContactsLexiconSource visitDeleteContactEvent:]
+ -[_ICContactsLexiconSource visitDropEverythingEvent:]
+ -[_ICContactsLexiconSource visitUpdateContactEvent:]
+ -[_ICContactsLexiconSource warmUp]
+ _CNContactFamilyNameKey
+ _CNContactGivenNameKey
+ _CNContactIdentifierKey
+ _CNContactJobTitleKey
+ _CNContactMiddleNameKey
+ _CNContactNicknameKey
+ _CNContactOrganizationNameKey
+ _CNContactPhoneticFamilyNameKey
+ _CNContactPhoneticGivenNameKey
+ _CNContactPhoneticMiddleNameKey
+ _CNContactPostalAddressesKey
+ _CNContactRelationsKey
+ _CNContactStoreDidChangeNotification
+ _OBJC_CLASS_$_CNChangeHistoryFetchRequest
+ _OBJC_CLASS_$_CNContactStore
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$__ICContactScorer
+ _OBJC_CLASS_$__ICContactsLexiconSource
+ _OBJC_CLASS_$__PSPredictionContext
+ _OBJC_CLASS_$__PSSuggester
+ _OBJC_IVAR_$__ICContactScorer._suggester
+ _OBJC_IVAR_$__ICContactsLexiconSource._historyToken
+ _OBJC_IVAR_$__ICContactsLexiconSource._manager
+ _OBJC_IVAR_$__ICContactsLexiconSource._observingStoreChanges
+ _OBJC_IVAR_$__ICContactsLexiconSource._pass
+ _OBJC_IVAR_$__ICContactsLexiconSource._queue
+ _OBJC_IVAR_$__ICContactsLexiconSource._rankMap
+ _OBJC_IVAR_$__ICContactsLexiconSource._scorer
+ _OBJC_IVAR_$__ICContactsLexiconSource._store
+ _OBJC_METACLASS_$__ICContactScorer
+ _OBJC_METACLASS_$__ICContactsLexiconSource
+ __ICContactKeyDescriptors.keys
+ __ICContactKeyDescriptors.onceToken
+ __OBJC_$_CLASS_METHODS__ICContactScorer
+ __OBJC_$_INSTANCE_METHODS__ICContactScorer
+ __OBJC_$_INSTANCE_METHODS__ICContactsLexiconSource
+ __OBJC_$_INSTANCE_VARIABLES__ICContactScorer
+ __OBJC_$_INSTANCE_VARIABLES__ICContactsLexiconSource
+ __OBJC_$_PROP_LIST__ICContactsLexiconSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CNChangeHistoryEventVisitor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CNChangeHistoryEventVisitor
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CNChangeHistoryEventVisitor
+ __OBJC_$_PROTOCOL_REFS_CNChangeHistoryEventVisitor
+ __OBJC_CLASS_PROTOCOLS_$__ICContactsLexiconSource
+ __OBJC_CLASS_RO_$__ICContactScorer
+ __OBJC_CLASS_RO_$__ICContactsLexiconSource
+ __OBJC_LABEL_PROTOCOL_$_CNChangeHistoryEventVisitor
+ __OBJC_METACLASS_RO_$__ICContactScorer
+ __OBJC_METACLASS_RO_$__ICContactsLexiconSource
+ __OBJC_PROTOCOL_$_CNChangeHistoryEventVisitor
+ ___51-[_ICContactsLexiconSource _contactStoreDidChange:]_block_invoke
+ ___52-[_ICContactsLexiconSource startLoadingWithManager:]_block_invoke
+ ____ICContactKeyDescriptors_block_invoke
+ _objc_msgSend$_beginPass:manager:
+ _objc_msgSend$_contactFromCNContact:
+ _objc_msgSend$_deletedContactPlaceholder
+ _objc_msgSend$_endPassWithManager:isInitialLoad:
+ _objc_msgSend$_handleContact:changeType:
+ _objc_msgSend$_processChangeHistory
+ _objc_msgSend$_rankMapForPass
+ _objc_msgSend$acceptEventVisitor:
+ _objc_msgSend$addObserver:selector:name:object:
+ _objc_msgSend$city
+ _objc_msgSend$contactIdentifier
+ _objc_msgSend$contactRelations
+ _objc_msgSend$conversationIdentifier
+ _objc_msgSend$currentHistoryToken
+ _objc_msgSend$defaultCenter
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$enumeratorForChangeHistoryFetchRequest:error:
+ _objc_msgSend$familyName
+ _objc_msgSend$fetchRankMap
+ _objc_msgSend$givenName
+ _objc_msgSend$phoneticFamilyName
+ _objc_msgSend$phoneticGivenName
+ _objc_msgSend$postalAddresses
+ _objc_msgSend$rankedGlobalSuggestionsFromContext:contactsOnly:
+ _objc_msgSend$removeObserver:
+ _objc_msgSend$scoreForContactIdentifier:rankMap:
+ _objc_msgSend$setAdditionalContactKeyDescriptors:
+ _objc_msgSend$setIncludeGroupChanges:
+ _objc_msgSend$setShouldUnifyResults:
+ _objc_msgSend$setStartingToken:
+ _objc_msgSend$street
+ _objc_msgSend$suggesterWithDaemonUsingMaxSuggestionCount:
- +[_ICPortraitUtilities contactChangeTypeForPortraitChangeType:]
- +[_ICPortraitUtilities contactFromPortraitContact:]
- +[_ICPortraitUtilities contactRecordFromPortraitContactRecord:]
- +[_ICPortraitUtilities contactSourceTypeForPortraitSourceType:]
- +[_ICPortraitUtilities excludedAlgorithms]
- -[_ICPortraitLexiconSource .cxx_destruct]
- -[_ICPortraitLexiconSource _makeContactDelegate]
- -[_ICPortraitLexiconSource _makeNamedEntityDelegate]
- -[_ICPortraitLexiconSource _makePPNamedEntityStore]
- -[_ICPortraitLexiconSource hibernate]
- -[_ICPortraitLexiconSource init]
- -[_ICPortraitLexiconSource provideFeedbackForString:type:style:]
- -[_ICPortraitLexiconSource startLoadingWithManager:]
- -[_ICPortraitLexiconSource warmUp]
- GCC_except_table15
- GCC_except_table6
- _OBJC_CLASS_$_PPContactNameRecordLoadingDelegate
- _OBJC_CLASS_$_PPContactStore
- _OBJC_CLASS_$_PPNamedEntityQuery
- _OBJC_CLASS_$_PPNamedEntityRecordLoadingDelegate
- _OBJC_CLASS_$_PPNamedEntityStore
- _OBJC_CLASS_$__ICPortraitLexiconSource
- _OBJC_IVAR_$__ICPortraitLexiconSource._contactDelegate
- _OBJC_IVAR_$__ICPortraitLexiconSource._contactStore
- _OBJC_IVAR_$__ICPortraitLexiconSource._manager
- _OBJC_IVAR_$__ICPortraitLexiconSource._namedEntityDelegate
- _OBJC_IVAR_$__ICPortraitLexiconSource._namedEntityStore
- _OBJC_METACLASS_$__ICPortraitLexiconSource
- __OBJC_$_INSTANCE_METHODS__ICPortraitLexiconSource
- __OBJC_$_INSTANCE_VARIABLES__ICPortraitLexiconSource
- __OBJC_CLASS_PROTOCOLS_$__ICPortraitLexiconSource
- __OBJC_CLASS_RO_$__ICPortraitLexiconSource
- __OBJC_METACLASS_RO_$__ICPortraitLexiconSource
- ___48-[_ICPortraitLexiconSource _makeContactDelegate]_block_invoke
- ___48-[_ICPortraitLexiconSource _makeContactDelegate]_block_invoke_2
- ___48-[_ICPortraitLexiconSource _makeContactDelegate]_block_invoke_3
- ___51-[_ICPortraitLexiconSource _makePPNamedEntityStore]_block_invoke
- ___52-[_ICPortraitLexiconSource _makeNamedEntityDelegate]_block_invoke
- ___52-[_ICPortraitLexiconSource _makeNamedEntityDelegate]_block_invoke_2
- ___52-[_ICPortraitLexiconSource _makeNamedEntityDelegate]_block_invoke_3
- ___52-[_ICPortraitLexiconSource _makeNamedEntityDelegate]_block_invoke_4
- ___52-[_ICPortraitLexiconSource _makeNamedEntityDelegate]_block_invoke_5
- ___block_descriptor_40_e8_32w_e29_C16?0"PPContactNameRecord"8l
- ___block_descriptor_40_e8_32w_e29_C16?0"PPNamedEntityRecord"8l
- ___block_descriptor_40_e8_32w_e5_C8?0l
- __makePPNamedEntityStore.onceToken
- __makePPNamedEntityStore.store
- _objc_msgSend$_makeContactDelegate
- _objc_msgSend$_makeNamedEntityDelegate
- _objc_msgSend$_makePPNamedEntityStore
- _objc_msgSend$allValues
- _objc_msgSend$cityNames
- _objc_msgSend$completeNamedEntities
- _objc_msgSend$completeRecentNamedEntities
- _objc_msgSend$contactChangeTypeForPortraitChangeType:
- _objc_msgSend$contactFromPortraitContact:
- _objc_msgSend$contactRecordFromPortraitContactRecord:
- _objc_msgSend$contactSourceTypeForPortraitSourceType:
- _objc_msgSend$excludedAlgorithms
- _objc_msgSend$handleNamedEntity:
- _objc_msgSend$handleRecentNamedEntity:
- _objc_msgSend$loadContactNameRecordsAndMonitorChangesWithDelegate:error:
- _objc_msgSend$loadNamedEntityRecordsAndMonitorChangesWithDelegate:query:error:
- _objc_msgSend$numberWithUnsignedLong:
- _objc_msgSend$phoneticFirstName
- _objc_msgSend$phoneticLastName
- _objc_msgSend$relatedNames
- _objc_msgSend$resetNamedEntities
- _objc_msgSend$setContactNameRecordsCompletion:
- _objc_msgSend$setContactNameRecordsHandler:
- _objc_msgSend$setContactNameRecordsSetup:
- _objc_msgSend$setExcludingAlgorithms:
- _objc_msgSend$setMatchingSourceBundleIds:
- _objc_msgSend$setNamedEntityRecordsCompletion:
- _objc_msgSend$setNamedEntityRecordsHandler:
- _objc_msgSend$setNamedEntityRecordsSetup:
- _objc_msgSend$setRecentContactNameRecordsCompletion:
- _objc_msgSend$setRecentContactNameRecordsHandler:
- _objc_msgSend$setRecentContactNameRecordsSetup:
- _objc_msgSend$setRecentNamedEntityRecordsCompletion:
- _objc_msgSend$setRecentNamedEntityRecordsHandler:
- _objc_msgSend$setRecentNamedEntityRecordsSetup:
- _objc_msgSend$setResetNamedEntityRecordData:
- _objc_msgSend$setupNamedEntities
- _objc_msgSend$setupRecentNamedEntities
- _objc_msgSend$streetNames
CStrings:
+ "Failed to read contact change history: %@"
+ "PeopleSuggester ranked %lu of %lu suggested contacts"
+ "_ICContactsLexiconSource loading contacts"
+ "com.apple.inputcontext.contactslexiconsource"
- "C16@?0@\"PPContactNameRecord\"8"
- "C16@?0@\"PPNamedEntityRecord\"8"
- "C8@?0"
- "Error: feedback received by _ICPortraitLexiconSource with unknown type or style: %d / %d"
- "Feedback received by _ICPortraitLexiconSource with type = %d, style = %d"
- "ICLex"
- "ICPortraitLexiconSource"
- "_ICPortraitLexiconSource loading data"
- "failed to load contact name records from Portrait: %@"
- "failed to load named entity records from Portrait: %@"
```
