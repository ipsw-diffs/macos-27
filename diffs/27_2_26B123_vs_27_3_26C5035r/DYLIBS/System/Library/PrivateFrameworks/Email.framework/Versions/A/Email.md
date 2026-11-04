## Email

> `/System/Library/PrivateFrameworks/Email.framework/Versions/A/Email`

```diff

-3901.200.71.1.16
-  __TEXT.__text: 0xebb50
-  __TEXT.__objc_methlist: 0xd7a4
+3901.300.31.0.0
+  __TEXT.__text: 0xed234
+  __TEXT.__objc_methlist: 0xd9d4
   __TEXT.__const: 0x18d2
-  __TEXT.__gcc_except_tab: 0x1be80
-  __TEXT.__cstring: 0xca69
+  __TEXT.__gcc_except_tab: 0x1c168
+  __TEXT.__cstring: 0xcc59
   __TEXT.__ustring: 0x170
-  __TEXT.__oslogstring: 0x6bb3
+  __TEXT.__oslogstring: 0x6cf3
   __TEXT.__dlopen_cstrs: 0x160
   __TEXT.__swift5_typeref: 0x4aa
   __TEXT.__constg_swiftt: 0x538

   __TEXT.__swift5_capture: 0x48
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x8880
+  __TEXT.__unwind_info: 0x89c8
   __TEXT.__eh_frame: 0x328
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x19d8
-  __DATA_CONST.__objc_classlist: 0x5a0
+  __DATA_CONST.__const: 0x1a20
+  __DATA_CONST.__objc_classlist: 0x5b8
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x67e0
+  __DATA_CONST.__objc_selrefs: 0x6878
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0x480
+  __DATA_CONST.__objc_superrefs: 0x498
   __DATA_CONST.__objc_arraydata: 0x1e8
-  __DATA_CONST.__got: 0xd28
-  __AUTH_CONST.__const: 0x55d0
-  __AUTH_CONST.__cfstring: 0xaa80
-  __AUTH_CONST.__objc_const: 0x17b28
+  __DATA_CONST.__got: 0xd40
+  __AUTH_CONST.__const: 0x5630
+  __AUTH_CONST.__cfstring: 0xad00
+  __AUTH_CONST.__objc_const: 0x17f20
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0xaa8
-  __AUTH.__objc_data: 0x2f0
+  __AUTH.__objc_data: 0x3e0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0xd14
+  __DATA.__objc_ivar: 0xd30
   __DATA.__data: 0x2880
   __DATA.__bss: 0x21d0
   __DATA_DIRTY.__objc_data: 0x37b8

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5420
-  Symbols:   11751
-  CStrings:  2229
+  Functions: 5460
+  Symbols:   11844
+  CStrings:  2254
 
Symbols:
+ +[EMAccountMatchResult supportsSecureCoding]
+ +[EMEnterOneTimeCodeFieldResponse supportsSecureCoding]
+ +[EMOneTimeCodeAccelerator maskCharacter]
+ +[EMOneTimeCodeFieldContext supportsSecureCoding]
+ -[EMAccountMatchResult accountIsActive]
+ -[EMAccountMatchResult description]
+ -[EMAccountMatchResult encodeWithCoder:]
+ -[EMAccountMatchResult initWithCoder:]
+ -[EMAccountMatchResult initWithMatch:accountIsActive:]
+ -[EMAccountMatchResult match]
+ -[EMAccountRepository bestAccountMatchForMaskedEmailAddress:]
+ -[EMEnterOneTimeCodeFieldResponse accountIsActive]
+ -[EMEnterOneTimeCodeFieldResponse accountMatchResult]
+ -[EMEnterOneTimeCodeFieldResponse description]
+ -[EMEnterOneTimeCodeFieldResponse encodeWithCoder:]
+ -[EMEnterOneTimeCodeFieldResponse initWithAccountMatch:]
+ -[EMEnterOneTimeCodeFieldResponse initWithAccountMatchResult:accountIsActive:]
+ -[EMEnterOneTimeCodeFieldResponse initWithCoder:]
+ -[EMFetchController expectingOneTimeCodeUntilDateWithReply:]
+ -[EMFetchController startExpectingOneTimeCode]
+ -[EMFetchController stopExpectingOneTimeCode]
+ -[EMMessageTransferAction initWithQuery:origin:actor:destinationMailbox:flagChange:copyMessages:]
+ -[EMOneTimeCodeAccelerator didEnterOneTimeCodeFieldWithContext:completion:]
+ -[EMOneTimeCodeFieldContext .cxx_destruct]
+ -[EMOneTimeCodeFieldContext canReportUnfocus]
+ -[EMOneTimeCodeFieldContext copyWithZone:]
+ -[EMOneTimeCodeFieldContext description]
+ -[EMOneTimeCodeFieldContext emailAddress]
+ -[EMOneTimeCodeFieldContext encodeWithCoder:]
+ -[EMOneTimeCodeFieldContext initWithCoder:]
+ -[EMOneTimeCodeFieldContext initWithEmailAddress:canReportUnfocus:provenance:]
+ -[EMOneTimeCodeFieldContext provenance]
+ -[EMOutgoingMessageRepository canCancelLastDelayedMessage:]
+ -[EMOutgoingMessageRepository invalidateLastDelayedMessageTimer:]
+ -[EMOutgoingMessageRepository restartLastDelayedMessageTimer:]
+ _EMStringForAccountMatch
+ _EMUserDefaultHideDebugMenuInViewOptions
+ _OBJC_CLASS_$_EMAccountMatchResult
+ _OBJC_CLASS_$_EMEnterOneTimeCodeFieldResponse
+ _OBJC_CLASS_$_EMOneTimeCodeFieldContext
+ _OBJC_IVAR_$_EMAccountMatchResult._accountIsActive
+ _OBJC_IVAR_$_EMAccountMatchResult._match
+ _OBJC_IVAR_$_EMEnterOneTimeCodeFieldResponse._accountIsActive
+ _OBJC_IVAR_$_EMEnterOneTimeCodeFieldResponse._accountMatchResult
+ _OBJC_IVAR_$_EMOneTimeCodeFieldContext._canReportUnfocus
+ _OBJC_IVAR_$_EMOneTimeCodeFieldContext._emailAddress
+ _OBJC_IVAR_$_EMOneTimeCodeFieldContext._provenance
+ _OBJC_METACLASS_$_EMAccountMatchResult
+ _OBJC_METACLASS_$_EMEnterOneTimeCodeFieldResponse
+ _OBJC_METACLASS_$_EMOneTimeCodeFieldContext
+ __OBJC_$_CLASS_METHODS_EMAccountMatchResult
+ __OBJC_$_CLASS_METHODS_EMEnterOneTimeCodeFieldResponse
+ __OBJC_$_CLASS_METHODS_EMOneTimeCodeFieldContext
+ __OBJC_$_CLASS_PROP_LIST_EMAccountMatchResult
+ __OBJC_$_CLASS_PROP_LIST_EMEnterOneTimeCodeFieldResponse
+ __OBJC_$_CLASS_PROP_LIST_EMOneTimeCodeFieldContext
+ __OBJC_$_INSTANCE_METHODS_EMAccountMatchResult
+ __OBJC_$_INSTANCE_METHODS_EMEnterOneTimeCodeFieldResponse
+ __OBJC_$_INSTANCE_METHODS_EMOneTimeCodeFieldContext
+ __OBJC_$_INSTANCE_VARIABLES_EMAccountMatchResult
+ __OBJC_$_INSTANCE_VARIABLES_EMEnterOneTimeCodeFieldResponse
+ __OBJC_$_INSTANCE_VARIABLES_EMOneTimeCodeFieldContext
+ __OBJC_$_PROP_LIST_EMAccountMatchResult
+ __OBJC_$_PROP_LIST_EMEnterOneTimeCodeFieldResponse
+ __OBJC_$_PROP_LIST_EMOneTimeCodeFieldContext
+ __OBJC_CLASS_PROTOCOLS_$_EMAccountMatchResult
+ __OBJC_CLASS_PROTOCOLS_$_EMEnterOneTimeCodeFieldResponse
+ __OBJC_CLASS_PROTOCOLS_$_EMOneTimeCodeFieldContext
+ __OBJC_CLASS_RO_$_EMAccountMatchResult
+ __OBJC_CLASS_RO_$_EMEnterOneTimeCodeFieldResponse
+ __OBJC_CLASS_RO_$_EMOneTimeCodeFieldContext
+ __OBJC_METACLASS_RO_$_EMAccountMatchResult
+ __OBJC_METACLASS_RO_$_EMEnterOneTimeCodeFieldResponse
+ __OBJC_METACLASS_RO_$_EMOneTimeCodeFieldContext
+ ___61-[EMAccountRepository bestAccountMatchForMaskedEmailAddress:]_block_invoke
+ ___75-[EMOneTimeCodeAccelerator didEnterOneTimeCodeFieldWithContext:completion:]_block_invoke
+ ___block_descriptor_40_ea8_32bs_e30_v16?0"EMAccountMatchResult"8l
+ ___block_descriptor_40_ea8_32s_e30_v16?0"EMAccountMatchResult"8l
+ _objc_msgSend$accountIsActive
+ _objc_msgSend$accountMatchResult
+ _objc_msgSend$bestAccountMatchForMaskedEmailAddress:
+ _objc_msgSend$bestAccountMatchForMaskedEmailAddress:completionHandler:
+ _objc_msgSend$canCancelLastDelayedMessage:
+ _objc_msgSend$canReportUnfocus
+ _objc_msgSend$didEnterOneTimeCodeFieldWithContext:completion:
+ _objc_msgSend$expectingOneTimeCodeUntilDateWithReply:
+ _objc_msgSend$initWithAccountMatch:
+ _objc_msgSend$initWithAccountMatchResult:accountIsActive:
+ _objc_msgSend$initWithEmailAddress:canReportUnfocus:provenance:
+ _objc_msgSend$invalidateLastDelayedMessageTimer:
+ _objc_msgSend$match
+ _objc_msgSend$provenance
+ _objc_msgSend$restartLastDelayedMessageTimer:
+ _objc_msgSend$startExpectingOneTimeCode
+ _objc_msgSend$stopExpectingOneTimeCode
- -[EMFetchController performFetchForOTC]
- _objc_msgSend$performFetchForOTC
CStrings:
+ "(none)"
+ "<%@: %p> accountMatchResult: %@, accountIsActive: %d"
+ "<%@: %p> emailAddress: %@, canReportUnfocus: %d, provenance: %@"
+ "<%@: %p> match: %@, accountIsActive: %d"
+ "AuthenticatorApp"
+ "EFPropertyKey_accountIsActive"
+ "EFPropertyKey_accountMatchResult"
+ "EFPropertyKey_canReportUnfocus"
+ "EFPropertyKey_emailAddress"
+ "EFPropertyKey_match"
+ "EFPropertyKey_provenance"
+ "Email"
+ "Exact"
+ "Failed to match the masked email address to an account, due to error: %{public}@"
+ "HideDebugMenuInViewOptions"
+ "No email address to match; reporting Unknown without checking accounts"
+ "NoAccountsConfigured"
+ "One Time Code field has been entered with context %{public}@"
+ "Partial"
+ "Received one-time code response: %{public}@"
+ "Skipped looking for best account match for email address since no completion handler was provided"
+ "TextMessage"
+ "Unavailable"
+ "Unknown (%ld)"
+ "Unmatched"
+ "v16@?0@\"EMAccountMatchResult\"8"
- "One Time Code field has been entered."
```
