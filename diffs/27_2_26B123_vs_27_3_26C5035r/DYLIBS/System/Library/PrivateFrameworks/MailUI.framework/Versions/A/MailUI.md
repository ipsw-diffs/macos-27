## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/Versions/A/MailUI`

```diff

-3901.200.71.1.16
-  __TEXT.__text: 0x30d598
-  __TEXT.__objc_methlist: 0xfb5c
-  __TEXT.__cstring: 0x10b89
-  __TEXT.__const: 0x19a04
+3901.300.31.0.0
+  __TEXT.__text: 0x320b40
+  __TEXT.__objc_methlist: 0xfc54
+  __TEXT.__cstring: 0x11099
+  __TEXT.__const: 0x19b04
   __TEXT.__gcc_except_tab: 0x1298
-  __TEXT.__oslogstring: 0x81a6
+  __TEXT.__oslogstring: 0x82f6
   __TEXT.__dlopen_cstrs: 0xba
   __TEXT.__ustring: 0x30c
-  __TEXT.__swift5_typeref: 0x1692c
-  __TEXT.__swift5_capture: 0x4774
-  __TEXT.__constg_swiftt: 0x3c0c
-  __TEXT.__swift5_builtin: 0x410
-  __TEXT.__swift5_reflstr: 0x2e71
-  __TEXT.__swift5_fieldmd: 0x2b10
-  __TEXT.__swift5_assocty: 0xf70
-  __TEXT.__swift5_proto: 0x598
-  __TEXT.__swift5_types: 0x468
-  __TEXT.__swift_as_entry: 0x194
-  __TEXT.__swift_as_ret: 0x16c
-  __TEXT.__swift_as_cont: 0x278
+  __TEXT.__swift5_typeref: 0x16af8
+  __TEXT.__swift5_capture: 0x4ab0
+  __TEXT.__constg_swiftt: 0x3c5c
+  __TEXT.__swift5_builtin: 0x424
+  __TEXT.__swift5_reflstr: 0x2ec1
+  __TEXT.__swift5_fieldmd: 0x2b74
+  __TEXT.__swift5_assocty: 0xf88
+  __TEXT.__swift5_proto: 0x5a0
+  __TEXT.__swift5_types: 0x470
+  __TEXT.__swift_as_entry: 0x198
+  __TEXT.__swift_as_ret: 0x17c
+  __TEXT.__swift_as_cont: 0x2ac
   __TEXT.__swift5_protos: 0x24
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0xdb08
-  __TEXT.__eh_frame: 0x30c4
+  __TEXT.__unwind_info: 0xde80
+  __TEXT.__eh_frame: 0x334c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xb8
   __DATA_CONST.__objc_protolist: 0x490
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa8f0
+  __DATA_CONST.__objc_selrefs: 0xa9c8
   __DATA_CONST.__objc_protorefs: 0x148
   __DATA_CONST.__objc_superrefs: 0x378
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x2500
-  __AUTH_CONST.__const: 0x12210
-  __AUTH_CONST.__cfstring: 0x7c60
-  __AUTH_CONST.__objc_const: 0x1b250
+  __DATA_CONST.__got: 0x2510
+  __AUTH_CONST.__const: 0x12a28
+  __AUTH_CONST.__cfstring: 0x7ea0
+  __AUTH_CONST.__objc_const: 0x1b280
   __AUTH_CONST.__objc_intobj: 0x1e0
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2b78
+  __AUTH_CONST.__auth_got: 0x2c10
   __AUTH.__objc_data: 0x1928
-  __AUTH.__data: 0x11f8
+  __AUTH.__data: 0x1298
   __DATA.__objc_ivar: 0xe5c
-  __DATA.__data: 0x7730
+  __DATA.__data: 0x7830
   __DATA.__objc_stublist: 0x8
-  __DATA.__bss: 0x7520
+  __DATA.__bss: 0x7650
   __DATA.__common: 0x3d8
   __DATA_DIRTY.__objc_data: 0x2c78
-  __DATA_DIRTY.__data: 0x2920
+  __DATA_DIRTY.__data: 0x2930
   __DATA_DIRTY.__bss: 0x43e0
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 15041
-  Symbols:   14812
-  CStrings:  2532
+  Functions: 15259
+  Symbols:   14891
+  CStrings:  2570
 
Symbols:
+ +[CSSuggestion(MailUI) mui_dateRangeSuggestionForUserTypedText:currentSuggestion:fromDate:toDate:displayText:]
+ +[MUILocalizedMessageListStrings snippetHighlightCcAddressFormat]
+ +[MUILocalizedMessageListStrings snippetHighlightFromAddressFormat]
+ +[MUILocalizedMessageListStrings snippetHighlightToAddressFormat]
+ -[MUIMessageListObjectProxy _bestMatchingHalfOfAddress:tokens:]
+ -[MUIMessageListObjectProxy _countOfTokens:matchingString:]
+ -[MUIMessageListObjectProxy _createHighlightedStringWithAddress:format:tokens:originalString:]
+ -[MUIMessageListObjectProxy _extractHighlightTokensFromHints:zones:]
+ -[MUIMessageListObjectProxy _firstMatchingRecipientForRecipientType:tokens:]
+ -[MUIMessageListObjectProxy _highlightAddressesIfMatchingWithHints:snippet:]
+ -[MUIMessageListObjectProxy _highlightSender:hints:]
+ -[MUIMessageListObjectProxy _matchingSenderWithTokens:]
+ -[MUIMessageListObjectProxy _recipientHighlightTokensWithHints:]
+ -[MUIMessageListObjectProxy _senderHighlightTokensWithHints:]
+ -[MUIMessageListObjectProxy _senderIsAlreadyHighlightedWithHints:]
+ -[MUIMessageListObjectProxy _shouldHighlightAddressesInSummaryWithHints:]
+ -[MUIMessageListObjectProxy _snippetMessage]
+ -[MUIMessageListObjectProxy _string:matchesAnyToken:]
+ -[MUIRichMessageCellBase layout]
+ -[ThreadDisclosureControl gestureRecognizer:shouldAttemptToRecognizeWithEvent:]
+ -[ThreadDisclosureControl gestureRecognizerShouldBegin:]
+ GCC_except_table144
+ _EMMessageSnippetHintZoneEmailAddresses
+ _EMMessageSnippetHintZoneRecipientEmailAddresses
+ _EMMessageSnippetHintZoneRecipients
+ ___110+[CSSuggestion(MailUI) mui_dateRangeSuggestionForUserTypedText:currentSuggestion:fromDate:toDate:displayText:]_block_invoke
+ ___59-[MUIMessageListObjectProxy _countOfTokens:matchingString:]_block_invoke
+ ___block_descriptor_40_e8_32s_e18_B16?0"NSString"8l
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyAA5GroupVyAA012_ConditionalD0Vy04MailB0021DonationVisualizationD4View33_5E5E9DA319EBC5204010E8DA17B46F05LLVAA012SubscriptionJ0Vy7Combine10PublishersO11AutoconnectCy_So7NSTimerC10FoundationE14TimerPublisherCGACyAA6VStackVyAA05TupleD0VyAA08ProgressJ0VyAA05EmptyJ0VA4_G_AA4TextVQPGGAA16_FlexFrameLayoutVGGGGAA25_AppearanceActionModifierVGA17_GAA0J0HPA18_AAA20_HPA15_AAA20_HPA14_AAA20_HPAkAA20_HPyHC_A13_AAA20_HPyHCHC_HC_A17_AA0J8ModifierHPyHCHC_A17_AAA21_HPyHCHC
+ _mui_dateRangeSuggestionForUserTypedText:currentSuggestion:fromDate:toDate:displayText:.fmt
+ _mui_dateRangeSuggestionForUserTypedText:currentSuggestion:fromDate:toDate:displayText:.onceToken
+ _mui_dateScopeDict
+ _objc_msgSend$_bestMatchingHalfOfAddress:tokens:
+ _objc_msgSend$_countOfTokens:matchingString:
+ _objc_msgSend$_createHighlightedStringWithAddress:format:tokens:originalString:
+ _objc_msgSend$_extractHighlightTokensFromHints:zones:
+ _objc_msgSend$_firstMatchingRecipientForRecipientType:tokens:
+ _objc_msgSend$_highlightAddressesIfMatchingWithHints:snippet:
+ _objc_msgSend$_highlightSender:hints:
+ _objc_msgSend$_matchingSenderWithTokens:
+ _objc_msgSend$_recipientHighlightTokensWithHints:
+ _objc_msgSend$_senderHighlightTokensWithHints:
+ _objc_msgSend$_senderIsAlreadyHighlightedWithHints:
+ _objc_msgSend$_shouldHighlightAddressesInSummaryWithHints:
+ _objc_msgSend$_snippetMessage
+ _objc_msgSend$_string:matchesAnyToken:
+ _objc_msgSend$cc
+ _objc_msgSend$dataTransferByteCount
+ _objc_msgSend$ef_countObjectsPassingTest:
+ _objc_msgSend$ef_posixLocale
+ _objc_msgSend$em_stringForQuotingWithCharacter:
+ _objc_msgSend$initWithUserString:currentSuggestion:suggestionTokenResult:
+ _objc_msgSend$isEqualToAttributedString:
+ _objc_msgSend$rangeOfString:options:
+ _objc_msgSend$readableBodyFromHTMLBody:options:maxLength:
+ _objc_msgSend$replaceCharactersInRange:withAttributedString:
+ _objc_msgSend$senderContainsMailSuggestionWithUserString:currentSuggestion:
+ _objc_msgSend$setDateFormat:
+ _objc_msgSend$setLocale:
+ _objc_msgSend$snippetHighlightCcAddressFormat
+ _objc_msgSend$snippetHighlightFromAddressFormat
+ _objc_msgSend$snippetHighlightToAddressFormat
+ _objc_msgSend$storageByteCount
+ _symbolic SDySSSo16CSSearchableItemCG
+ _symbolic SS_So16CSSearchableItemCt
+ _symbolic Say_____G 6MailUI14CSQueryBuilderC
+ _symbolic ScCyxSg_____G s5NeverO
+ _symbolic Shy_____GIegg_ s5Int64V
+ _symbolic Shy_____GSg s5Int64V
+ _symbolic So11NSPredicateCSg
+ _symbolic So23EMContentRepresentationCSgSbIeggd_
+ _symbolic So23EMContentRepresentationCSgSbIegnd_
+ _symbolic _____ 6MailUI20MessageContentLoaderC15SiriBudgetState33_3D154AA94633874686D627706095E8D1LLV
+ _symbolic _____ 6MailUI36MUIOneTimeCodeTTRRadarContentBuilderV
+ _symbolic _____ So14EMNetworkUsageV
+ _symbolic _____ s15ContinuousClockV7InstantV
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic _____SgSbIegnd_ 10AppIntents10IntentFileV
+ _symbolic _____yAAy_____y_____y__________y_____y______GAAy_____y_____y_____y_____ALG______QPGG_____GGGG_____GAVG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 04MailB0021DonationVisualizationD4View33_5E5E9DA319EBC5204010E8DA17B46F05LLV AA012SubscriptionJ0V 7Combine10PublishersO11AutoconnectC So7NSTimerC10FoundationE14TimerPublisherC AA6VStackV AA05TupleD0V AA08ProgressJ0V AA05EmptyJ0V AA4TextV AA16_FlexFrameLayoutV AA25_AppearanceActionModifierV
+ _symbolic _____ySay_____GG s16IndexingIteratorV 12HybridSearch10ScanResultV
+ _symbolic _____yScTyyt_____GSgG 7SwiftUI5StateV s5NeverO
+ _symbolic _____yScTyyt_____GSgG 7SwiftUI9LazyStateV s5NeverO
+ _symbolic _____yScTyyt_____GSg_G 7SwiftUI9LazyStateV7StorageO s5NeverO
+ _symbolic _____yShy_____GSgG 7SwiftUI5StateV s5Int64V
+ _symbolic _____yShy_____GSgG 7SwiftUI9LazyStateV s5Int64V
+ _symbolic _____yShy_____GSg_G 7SwiftUI9LazyStateV7StorageO s5Int64V
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 6MailUI20MessageContentLoaderC15SiriBudgetState33_3D154AA94633874686D627706095E8D1LLV
+ _symbolic _____y_____G s10ArraySliceV s5Int64V
+ _symbolic _____y_____GSg 12HybridSearch15ComposableQueryV AA11MailContentV
+ _type_layout_string 6MailUI20MessageContentLoaderC15SiriBudgetState33_3D154AA94633874686D627706095E8D1LLV
- -[MUIMessageListObjectProxy _highlightSender:]
- GCC_except_table130
- _get_witness_table 7SwiftUI15ModifiedContentVyAA5GroupVyAA012_ConditionalD0Vy04MailB0021DonationVisualizationD4View33_5E5E9DA319EBC5204010E8DA17B46F05LLVAA012SubscriptionJ0Vy7Combine10PublishersO11AutoconnectCy_So7NSTimerC10FoundationE14TimerPublisherCGACyAA6VStackVyAA05TupleD0VyAA08ProgressJ0VyAA05EmptyJ0VA4_G_AA4TextVQPGGAA16_FlexFrameLayoutVGGGGAA25_AppearanceActionModifierVGAA0J0HPA15_AAA19_HPA14_AAA19_HPAkAA19_HPyHC_A13_AAA19_HPyHCHC_HC_A17_AA0J8ModifierHPyHCHC
- _objc_msgSend$_highlightSender:
- _objc_msgSend$senderContainsSuggestionWithUserString:currentSuggestion:
- _symbolic ScCySo23EMContentRepresentationCSg_____G s5NeverO
- _symbolic ScCy_____Sg_____G 10AppIntents10IntentFileV s5NeverO
- _symbolic SdIegd_
- _symbolic _____ 6MailUI20MessageContentLoaderC18loadRepresentationySo09EMContentG0CSgSo9EMMessageCYaFZyScCyAGs5NeverOGXEfU_5StateL_V
- _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 6MailUI20MessageContentLoaderC18loadRepresentationySo09EMContentK0CSgSo9EMMessageCYaFZyScCyAJs5NeverOGXEfU_5StateL_V
- _type_layout_string 6MailUI20MessageContentLoaderC18loadRepresentationySo09EMContentG0CSgSo9EMMessageCYaFZyScCyAGs5NeverOGXEfU_5StateL_V
CStrings:
+ "\nGlobal Message ID: "
+ " && "
+ " = "
+ " AND "
+ " CONTAINS "
+ " OR "
+ " · AI Generated"
+ "#SiriMail %s exceeded the Siri turn budget; cancelling"
+ "#SiriMail %s skipping attachment — expected size %lld exceeds %llu byte limit"
+ "'*"
+ "*'cd"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/System/Library/PrivateFrameworks/Email.framework/Headers/EMContentRequestOptions.h"
+ "<%{public}@: %p> Address format is missing its placeholder"
+ "AI Generated"
+ "Additional Notes:\n\n1. Which website/app were you autofilling into?\n\n2. What email provider does the account that received the code use (Gmail, Outlook, iCloud, etc.)?\n\n=== Problem Report ===\n\nMail was checking for a one-time code when the user copied something from a message. There may have been a one-time code detection issue.\n\n=== Visible Message ===\nDate: "
+ "After"
+ "Before"
+ "CSSuggestion does not respond to initWithUserString:currentSuggestion:suggestionTokenResult:"
+ "DATE_FROM"
+ "DATE_TO"
+ "Date"
+ "DonationVisualization"
+ "Label below an email summary telling the reader that it was generated by a model"
+ "Label below an email summary written by a third-party model. The argument is the provider name."
+ "Localizable-AIChina"
+ "Mail DB shows this as donated, but GLP has no record of it."
+ "Missing from GLP"
+ "Negative value is not representable"
+ "QUERY"
+ "SnippetHighlightCcAddress%1$@"
+ "SnippetHighlightFromAddress%1$@"
+ "SnippetHighlightToAddress%1$@"
+ "TEXT"
+ "TOKEN"
+ "[%{public}s] GLP batch scan failed, excluding %ld ids from the mismatch check: %{public}s"
+ "[%{public}s] GLP/Mail DB mismatch: %ld of %ld checked Mail-DB-donated messages have no matching GLP record"
+ "[OTC TTR] One-time code was not displayed for autofill"
+ "\\"
+ "attachment load"
+ "content load"
+ "en_US_POSIX"
+ "extractAttachments(networkUsage:deadline:)"
+ "kQPTokenDate"
+ "loadAttachmentsConcurrently(from:networkUsage:deadline:)"
+ "requestAttachmentRepresentation(for:networkUsage:deadline:)"
+ "suggestionDescriptionKey"
+ "suggestionTextKey"
+ "suggestionTokensKey"
+ "suggestionTypeKey"
+ "withSiriTurnBudget(label:deadline:_:)"
+ "yyyy-MM-dd'T'HH:mm:ss"
- "#SiriMail content load exceeded %fs (Siri turn budget); cancelling"
- "&&"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/System/Library/PrivateFrameworks/Email.framework/Headers/EMContentRequestOptions.h"
- "="
- "AND"
- "CONTAINS"
- "CSSuggestion does not respond to senderContainsSuggestionWithUserString:currentSuggestion:"
- "OR"
- "extractAttachments()"
- "loadAttachmentsConcurrently(from:)"
- "loadRepresentation(_:)"
- "requestAttachmentRepresentation(for:)"
- "||"
```
