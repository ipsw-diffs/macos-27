## MailCore

> `/System/Library/PrivateFrameworks/MailCore.framework/Versions/A/MailCore`

```diff

-3901.200.71.1.16
-  __TEXT.__text: 0x82a18
+3901.300.31.0.0
+  __TEXT.__text: 0x827a4
   __TEXT.__objc_methlist: 0x826c
-  __TEXT.__cstring: 0x810c
+  __TEXT.__cstring: 0x7f85
   __TEXT.__gcc_except_tab: 0x1684
   __TEXT.__const: 0x4b8
   __TEXT.__oslogstring: 0x1f0e

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1218
+  __DATA_CONST.__const: 0x11f0
   __DATA_CONST.__objc_classlist: 0x380
   __DATA_CONST.__objc_catlist: 0xb8
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x54b8
+  __DATA_CONST.__objc_selrefs: 0x54c0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x290
   __DATA_CONST.__objc_arraydata: 0x1b0
   __DATA_CONST.__got: 0x1138
   __AUTH_CONST.__const: 0x13c0
-  __AUTH_CONST.__cfstring: 0x92a0
-  __AUTH_CONST.__objc_const: 0xced0
+  __AUTH_CONST.__cfstring: 0x9200
+  __AUTH_CONST.__objc_const: 0xcef8
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x948
   __AUTH.__objc_data: 0xbe0
-  __DATA.__objc_ivar: 0x7bc
+  __DATA.__objc_ivar: 0x7c0
   __DATA.__data: 0xda8
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x20a

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2910
-  Symbols:   7638
-  CStrings:  1487
+  Functions: 2911
+  Symbols:   7636
+  CStrings:  1482
 
Symbols:
+ -[MCConnection authenticatedSASLMechanism]
+ -[MCConnection setAuthenticatedSASLMechanism:]
+ _OBJC_IVAR_$_MCConnection._authenticatedSASLMechanism
+ _objc_msgSend$setAuthenticatedSASLMechanism:
- -[MCMemoryDataSource messageFlagsDidChange:flags:]
- _MCMessageDataSourceMessagesCompactedNotification
- _MCMessageDataSourceMessagesDeletedNotification
- _MCMessageDataSourceMessagesReadNotification
- _MCNotificationKeyMessages
- _MCNotificationKeySecondaryMessages
CStrings:
+ "!appleFileEntryIsInBounds(&thisEntry, length)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32)"
+ "thisEntry.entryLength > MAXPATHLEN"
- "MCMessageDataSourceMessagesCompactedNotification"
- "MCMessageDataSourceMessagesDeletedNotification"
- "MCMessageDataSourceMessagesReadNotification"
- "messages"
- "secondaryMessages"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength || thisEntry.entryLength > MAXPATHLEN"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16))"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32))"
```
