## Email

> `/System/Library/PrivateFrameworks/Email.framework/Versions/A/Email`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

```diff

-3901.200.34.0.0
-  __TEXT.__text: 0xeb1c0
-  __TEXT.__objc_methlist: 0xd68c
+3901.200.41.0.0
+  __TEXT.__text: 0xeba78
+  __TEXT.__objc_methlist: 0xd744
   __TEXT.__const: 0x18d2
-  __TEXT.__gcc_except_tab: 0x1bd54
+  __TEXT.__gcc_except_tab: 0x1be50
   __TEXT.__cstring: 0xca59
   __TEXT.__ustring: 0x170
   __TEXT.__oslogstring: 0x6c03

   __TEXT.__swift5_capture: 0x48
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x87d8
+  __TEXT.__unwind_info: 0x8880
   __TEXT.__eh_frame: 0x328
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x19e8
-  __DATA_CONST.__objc_classlist: 0x598
+  __DATA_CONST.__objc_classlist: 0x5a0
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6770
+  __DATA_CONST.__objc_selrefs: 0x67c0
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0x478
+  __DATA_CONST.__objc_superrefs: 0x480
   __DATA_CONST.__objc_arraydata: 0x1e8
-  __DATA_CONST.__got: 0xd20
+  __DATA_CONST.__got: 0xd28
   __AUTH_CONST.__const: 0x55d0
   __AUTH_CONST.__cfstring: 0xaa80
-  __AUTH_CONST.__objc_const: 0x178e0
+  __AUTH_CONST.__objc_const: 0x17a88
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0xaa0
+  __AUTH_CONST.__auth_got: 0xaa8
   __AUTH.__objc_data: 0x2f0
-  __AUTH.__data: 0x158
-  __DATA.__objc_ivar: 0xcfc
+  __AUTH.__data: 0x28
+  __DATA.__objc_ivar: 0xd0c
   __DATA.__data: 0x2880
-  __DATA.__bss: 0x21e0
-  __DATA_DIRTY.__objc_data: 0x3768
-  __DATA_DIRTY.__data: 0x268
-  __DATA_DIRTY.__bss: 0xcd0
+  __DATA.__bss: 0x21d0
+  __DATA_DIRTY.__objc_data: 0x37b8
+  __DATA_DIRTY.__data: 0x388
+  __DATA_DIRTY.__bss: 0xce0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5399
-  Symbols:   11858
+  Functions: 5416
+  Symbols:   11894
   CStrings:  2230
 
Symbols:
+ +[EMMessageBodyParsingUtils strippedQuoteBlockFromHTMLBody:]
+ -[EMAccountRepository accountIfAvailableForIdentifier:]
+ -[EMMailboxRepository _cachedAllMailboxObjectIDs]
+ -[EMMailboxRepository _cachedMailboxObjectIDsForMailboxType:]
+ -[EMMailboxRepository _cachedMailboxTypeForMailboxObjectID:cacheValid:]
+ -[EMMailboxRepository _failMailboxesPromiseAsTemporarilyUnavailable]
+ -[EMMailboxRepository availableMailboxTypeResolver]
+ -[EMMailboxRepository isMailboxCacheWarm]
+ -[EMMailboxRepository mailboxesFuture]
+ -[_EMAvailableMailboxTypeResolver .cxx_destruct]
+ -[_EMAvailableMailboxTypeResolver allMailboxObjectIDs]
+ -[_EMAvailableMailboxTypeResolver initWithRepository:]
+ -[_EMAvailableMailboxTypeResolver mailboxObjectIDsForMailboxType:]
+ -[_EMAvailableMailboxTypeResolver mailboxTypeForMailboxObjectID:]
+ OBJC_IVAR_$_EMAccountRepository._accountsRequestInFlight
+ OBJC_IVAR_$_EMMailbox._repository
+ OBJC_IVAR_$_EMMailboxRepository._availableMailboxTypeResolver
+ OBJC_IVAR_$__EMAvailableMailboxTypeResolver._repository
+ _OBJC_CLASS_$__EMAvailableMailboxTypeResolver
+ _OBJC_METACLASS_$__EMAvailableMailboxTypeResolver
+ __OBJC_$_INSTANCE_METHODS__EMAvailableMailboxTypeResolver
+ __OBJC_$_INSTANCE_VARIABLES__EMAvailableMailboxTypeResolver
+ __OBJC_$_PROP_LIST__EMAvailableMailboxTypeResolver
+ __OBJC_CLASS_PROTOCOLS_$__EMAvailableMailboxTypeResolver
+ __OBJC_CLASS_RO_$__EMAvailableMailboxTypeResolver
+ __OBJC_METACLASS_RO_$__EMAvailableMailboxTypeResolver
+ ___55-[EMAccountRepository accountIfAvailableForIdentifier:]_block_invoke
+ ___61-[EMMailboxRepository _cachedMailboxObjectIDsForMailboxType:]_block_invoke
+ ___remoteInterfaceForConnection_block_invoke
+ __remoteInterfaceForConnection_block_invoke
+ _objc_msgSend$_cachedAllMailboxObjectIDs
+ _objc_msgSend$_cachedMailboxObjectIDsForMailboxType:
+ _objc_msgSend$_cachedMailboxTypeForMailboxObjectID:cacheValid:
+ _objc_msgSend$_failMailboxesPromiseAsTemporarilyUnavailable
+ _objc_msgSend$accountIfAvailableForIdentifier:
+ _objc_msgSend$initWithRepository:
+ _objc_msgSend$strippedQuoteBlockFromHTMLBody:
+ _os_unfair_lock_trylock
+ _remoteInterfaceForConnection
- __52-[EMVIPManager _startObservingVIPChangesIfNecessary]_block_invoke
- __70-[EMOutgoingMessageRepository _startObservingUnsentChangesIfNecessary]_block_invoke
- ___54-[EMMailboxRepository mailboxObjectIDsForMailboxType:]_block_invoke
CStrings:
+ "A1"
+ "Error establishing xpc connection: %{public}@"
- "A"
- "Error establishing xpc connection : %@"
```
