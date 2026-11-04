## RemoteTextInput

> `/System/Library/PrivateFrameworks/RemoteTextInput.framework/Versions/A/RemoteTextInput`

```diff

-180.0.0.0.0
-  __TEXT.__text: 0x21d6c
-  __TEXT.__objc_methlist: 0x2a6c
+180.2.1.0.0
+  __TEXT.__text: 0x22338
+  __TEXT.__objc_methlist: 0x2aec
   __TEXT.__const: 0x108
-  __TEXT.__cstring: 0x2fed
+  __TEXT.__cstring: 0x300d
   __TEXT.__oslogstring: 0xcb5
   __TEXT.__gcc_except_tab: 0x284
   __TEXT.__dlopen_cstrs: 0x9b
-  __TEXT.__unwind_info: 0xb98
+  __TEXT.__unwind_info: 0xbc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x100
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18e8
+  __DATA_CONST.__objc_selrefs: 0x1938
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0xc0
+  __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x248
-  __AUTH_CONST.__const: 0xe20
-  __AUTH_CONST.__cfstring: 0x2da0
-  __AUTH_CONST.__objc_const: 0x64e0
+  __AUTH_CONST.__const: 0xe40
+  __AUTH_CONST.__cfstring: 0x2de0
+  __AUTH_CONST.__objc_const: 0x65c0
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x320
+  __DATA.__objc_ivar: 0x338
   __DATA.__data: 0x420
-  __DATA.__bss: 0x18
+  __DATA.__bss: 0x30
   __DATA_DIRTY.__objc_data: 0xa00
   __DATA_DIRTY.__bss: 0xb0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1032
-  Symbols:   2347
-  CStrings:  517
+  Functions: 1049
+  Symbols:   2382
+  CStrings:  520
 
Symbols:
+ -[RTIDocumentState acknowledgedSourceRevision]
+ -[RTIDocumentState documentStateByStrippingTextContent]
+ -[RTIDocumentState setAcknowledgedSourceRevision:]
+ -[RTIInputSystemClient _acknowledgeSourceRevisionOnDocumentState:]
+ -[RTIInputSystemClient _recordSeenSourceRevision:]
+ -[RTIInputSystemSession init]
+ -[RTIInputSystemSession shouldAcceptTextFromClientDocumentState:]
+ -[RTIInputSystemSession stampOutgoingTextOperations:]
+ -[RTITextOperations setSourceRevision:]
+ -[RTITextOperations sourceRevision]
+ GCC_except_table114
+ GCC_except_table126
+ GCC_except_table130
+ GCC_except_table26
+ GCC_except_table44
+ GCC_except_table48
+ GCC_except_table56
+ _OBJC_IVAR_$_RTIDocumentState._acknowledgedSourceRevision
+ _OBJC_IVAR_$_RTIInputSystemClient._lastSeenSourceRevision
+ _OBJC_IVAR_$_RTIInputSystemClient._lastSeenSourceRevisionLock
+ _OBJC_IVAR_$_RTIInputSystemSession._lastSentSourceRevision
+ _OBJC_IVAR_$_RTIInputSystemSession._lastSentSourceRevisionLock
+ _OBJC_IVAR_$_RTITextOperations._sourceRevision
+ _RTIClientHasSeenSourceRevision
+ _RTINextSourceRevision
+ _RTISourceRevisionEpoch
+ _RTISourceRevisionEpoch.epoch
+ _RTISourceRevisionEpoch.onceToken
+ ___RTISourceRevisionEpoch_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e41_v16?0"<RTIInputSystemSessionProtocol>"8l
+ ___copy_helper_block_e8_32s40s48s56s
+ __rtiSourceRevisionCounter
+ __rtiSourceRevisionLock
+ _arc4random
+ _objc_msgSend$_acknowledgeSourceRevisionOnDocumentState:
+ _objc_msgSend$_recordSeenSourceRevision:
+ _objc_msgSend$acknowledgedSourceRevision
+ _objc_msgSend$documentStateByStrippingTextContent
+ _objc_msgSend$setAcknowledgedSourceRevision:
+ _objc_msgSend$setSourceRevision:
+ _objc_msgSend$shouldAcceptTextFromClientDocumentState:
+ _objc_msgSend$sourceRevision
+ _objc_msgSend$stampOutgoingTextOperations:
- GCC_except_table113
- GCC_except_table123
- GCC_except_table127
- GCC_except_table25
- GCC_except_table43
- GCC_except_table47
- GCC_except_table55
- ___block_descriptor_56_e8_32s40s48s_e41_v16?0"<RTIInputSystemSessionProtocol>"8l
CStrings:
+ "&"
+ "ackSourceRev"
+ "sourceRevision"
+ "{"
+ "\x81"
- ")"
- "["
```
