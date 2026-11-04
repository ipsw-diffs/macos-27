## IMAP

> `/System/Library/PrivateFrameworks/IMAP.framework/Versions/A/IMAP`

```diff

-3901.200.71.1.16
-  __TEXT.__text: 0x54958
-  __TEXT.__objc_methlist: 0x6874
-  __TEXT.__cstring: 0x416e
+3901.300.31.0.0
+  __TEXT.__text: 0x55300
+  __TEXT.__objc_methlist: 0x692c
+  __TEXT.__cstring: 0x420e
   __TEXT.__const: 0x250
-  __TEXT.__gcc_except_tab: 0x1c0c
+  __TEXT.__gcc_except_tab: 0x1c10
   __TEXT.__oslogstring: 0x1b63
-  __TEXT.__unwind_info: 0x1f20
+  __TEXT.__unwind_info: 0x1f48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x8e8
-  __DATA_CONST.__objc_classlist: 0x490
+  __DATA_CONST.__const: 0x8f0
+  __DATA_CONST.__objc_classlist: 0x498
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2f50
+  __DATA_CONST.__objc_selrefs: 0x2fa0
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x2c0
+  __DATA_CONST.__objc_superrefs: 0x2c8
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x798
-  __AUTH_CONST.__const: 0x1420
-  __AUTH_CONST.__cfstring: 0x4ba0
-  __AUTH_CONST.__objc_const: 0xbe20
+  __DATA_CONST.__got: 0x7a0
+  __AUTH_CONST.__const: 0x1450
+  __AUTH_CONST.__cfstring: 0x4c80
+  __AUTH_CONST.__objc_const: 0xbf58
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x690
-  __DATA.__objc_ivar: 0x62c
+  __AUTH.__objc_data: 0x6e0
+  __DATA.__objc_ivar: 0x638
   __DATA.__data: 0x1098
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x19

   - /System/Library/PrivateFrameworks/MailCore.framework/Versions/A/MailCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2090
-  Symbols:   5383
-  CStrings:  818
+  Functions: 2104
+  Symbols:   5420
+  CStrings:  827
 
Symbols:
+ +[IMAPJMAPAccessResponse handlesResponseWithName:ofLength:]
+ -[IMAPAccountSyncTask fetchMailboxStatusOperation:fetchedMailboxIDsForMailboxNames:]
+ -[IMAPJMAPAccessResponse .cxx_destruct]
+ -[IMAPJMAPAccessResponse description]
+ -[IMAPJMAPAccessResponse initWithURL:]
+ -[IMAPJMAPAccessResponse url]
+ -[IMAPParseContext _newParenthesizedObjectID]
+ -[IMAPParseContext _parseJMAPAccessResponse]
+ -[IMAPStatusCommand mailboxID]
+ -[IMAPStatusCommand setMailboxID:]
+ -[IMAPStatusResponse mailboxID]
+ -[IMAPStatusResponse setMailboxID:]
+ -[IMAPTaskManager supportsRenameActions]
+ GCC_except_table184
+ GCC_except_table188
+ GCC_except_table193
+ GCC_except_table198
+ GCC_except_table207
+ GCC_except_table211
+ GCC_except_table214
+ GCC_except_table219
+ GCC_except_table223
+ GCC_except_table229
+ GCC_except_table238
+ _OBJC_CLASS_$_IMAPJMAPAccessResponse
+ _OBJC_IVAR_$_IMAPJMAPAccessResponse._url
+ _OBJC_IVAR_$_IMAPStatusCommand._mailboxID
+ _OBJC_IVAR_$_IMAPStatusResponse._mailboxID
+ _OBJC_METACLASS_$_IMAPJMAPAccessResponse
+ __OBJC_$_CLASS_METHODS_IMAPJMAPAccessResponse
+ __OBJC_$_INSTANCE_METHODS_IMAPJMAPAccessResponse
+ __OBJC_$_INSTANCE_VARIABLES_IMAPJMAPAccessResponse
+ __OBJC_$_PROP_LIST_IMAPJMAPAccessResponse
+ __OBJC_CLASS_RO_$_IMAPJMAPAccessResponse
+ __OBJC_METACLASS_RO_$_IMAPJMAPAccessResponse
+ ___84-[IMAPAccountSyncTask fetchMailboxStatusOperation:fetchedMailboxIDsForMailboxNames:]_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24l
+ _objc_msgSend$URLWithString:encodingInvalidCharacters:
+ _objc_msgSend$_newParenthesizedObjectID
+ _objc_msgSend$_parseJMAPAccessResponse
+ _objc_msgSend$fetchMailboxStatusOperation:fetchedMailboxIDsForMailboxNames:
+ _objc_msgSend$host
+ _objc_msgSend$initWithURL:
+ _objc_msgSend$mailboxID
+ _objc_msgSend$scheme
+ _objc_msgSend$setMailboxID:
+ _objc_msgSend$setRemoteID:
+ _objc_msgSend$url
- GCC_except_table183
- GCC_except_table187
- GCC_except_table192
- GCC_except_table197
- GCC_except_table206
- GCC_except_table210
- GCC_except_table213
- GCC_except_table218
- GCC_except_table222
- GCC_except_table228
- GCC_except_table237
CStrings:
+ "%@JMAPACCESS %@"
+ "Expected an https URL"
+ "JMAPACCESS"
+ "MAILBOXID"
+ "MAILBOXID (%@) "
+ "Malformed MAILBOXID response code"
+ "OBJECTID"
+ "https"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
```
