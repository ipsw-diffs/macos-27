## Mail

> `/System/Library/PrivateFrameworks/Mail.framework/Versions/A/Mail`

```diff

-3901.200.34.0.0
-  __TEXT.__text: 0xa0fd64
-  __TEXT.__objc_methlist: 0x198a4
-  __TEXT.__const: 0x617a9
-  __TEXT.__cstring: 0x31f19
-  __TEXT.__gcc_except_tab: 0x4c3e8
-  __TEXT.__oslogstring: 0x222f9
+3901.200.41.0.0
+  __TEXT.__text: 0xa130a8
+  __TEXT.__objc_methlist: 0x198fc
+  __TEXT.__const: 0x61819
+  __TEXT.__cstring: 0x32039
+  __TEXT.__gcc_except_tab: 0x4c41c
+  __TEXT.__oslogstring: 0x22359
   __TEXT.__ustring: 0x44
-  __TEXT.__swift5_typeref: 0xe744
+  __TEXT.__swift5_typeref: 0xe780
   __TEXT.__constg_swiftt: 0xbc64
-  __TEXT.__swift5_reflstr: 0xe760
+  __TEXT.__swift5_reflstr: 0xe770
   __TEXT.__swift5_fieldmd: 0x131fc
   __TEXT.__swift5_builtin: 0xc44
   __TEXT.__swift5_assocty: 0x1b70
-  __TEXT.__swift5_proto: 0x2244
+  __TEXT.__swift5_proto: 0x224c
   __TEXT.__swift5_types: 0x1518
-  __TEXT.__swift5_capture: 0x25fd0
+  __TEXT.__swift5_capture: 0x26020
   __TEXT.__swift5_mpenum: 0x768
   __TEXT.__swift5_protos: 0x60
-  __TEXT.__unwind_info: 0x2d9b8
-  __TEXT.__eh_frame: 0x15e90
+  __TEXT.__unwind_info: 0x2da60
+  __TEXT.__eh_frame: 0x15fb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x5a0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xe090
+  __DATA_CONST.__objc_selrefs: 0xe0a8
   __DATA_CONST.__objc_protorefs: 0x1d0
   __DATA_CONST.__objc_superrefs: 0x840
   __DATA_CONST.__objc_arraydata: 0x270
   __DATA_CONST.__got: 0x3790
-  __AUTH_CONST.__const: 0x8a5c8
+  __AUTH_CONST.__const: 0x8a6b8
   __AUTH_CONST.__cfstring: 0x1a660
-  __AUTH_CONST.__objc_const: 0x2b210
+  __AUTH_CONST.__objc_const: 0x2b248
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0xd08
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0x3488
+  __AUTH_CONST.__auth_got: 0x3490
   __AUTH.__objc_data: 0x6298
   __AUTH.__data: 0xa130
   __DATA.__objc_ivar: 0x162c
-  __DATA.__data: 0xc724
+  __DATA.__data: 0xc7bc
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x43aa8
+  __DATA.__bss: 0x43ba8
   __DATA.__common: 0xdbc
   __DATA_DIRTY.__objc_data: 0x25d0
   __DATA_DIRTY.__data: 0x10

   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 42831
-  Symbols:   28646
-  CStrings:  7742
+  Functions: 42871
+  Symbols:   28661
+  CStrings:  7750
 
Symbols:
+ +[MFEWSConnection sendSavesToSentItems]
+ +[MFExchangeConnection sendSavesToSentItems]
+ -[MFExchangeAccount connectionClass]
+ -[MFExchangeAccount shouldAppendSentMessageAfterSending]
+ -[MFRemoteStoreAccount shouldAppendSentMessageAfterSending]
+ __CLASS_METHODS_MFGraphSyncConnection
+ __CLASS_PROPERTIES_MFGraphSyncConnection
+ __OBJC_$_CLASS_METHODS_MFEWSConnection
+ _associated conformance 15IMAP2Connection6EnableVSHAASQ
+ _objc_msgSend$connectionClass
+ _objc_msgSend$sendSavesToSentItems
+ _objc_msgSend$shouldAppendSentMessageAfterSending
+ _symbolic _____ 9GraphSync0aB15MessageResourceV
+ _symbolic _____7mailbox______7messaget 16IMAP2Persistence15OpaqueMailboxIDV AA0C26PersistedMessageIdentifierV
+ _symbolic ______Say_____G_____t 15IMAP2Connection6EnableV 12NIOIMAPCore210CapabilityV 0A8Protocol8ServerIDV
CStrings:
+ "#microsoft.graph.eventMessage"
+ "#microsoft.graph.eventMessageRequest"
+ "#microsoft.graph.eventMessageResponse"
+ "#microsoft.graph.message"
+ "#microsoft.graph.post"
+ "+[MFExchangeConnection sendSavesToSentItems]"
+ "GraphSyncMessageResource contains unexpected @odata.type %s"
+ "[%.*hhx-%{public}s] Did enable capabilities: %{public}s"
+ "[%.*hhx-%{public}s] Received post-auth capabilities from server: %{public}s"
+ "enablingCapabilities"
+ "unauthenticated(enablingCapabilities)"
- "[%.*hhx-%{public}s] Did enable UIDONLY"
- "[%.*hhx-%{public}s] Received capabilities from server"
- "unauthenticated(enablingUIDOnly)"
```
