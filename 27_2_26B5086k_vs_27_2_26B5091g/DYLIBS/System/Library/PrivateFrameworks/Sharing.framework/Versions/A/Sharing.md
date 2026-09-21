## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2131.20.65.1.1
-  __TEXT.__text: 0x3340d4
-  __TEXT.__objc_methlist: 0x12ca4
-  __TEXT.__cstring: 0x2cd58
+2131.20.71.0.0
+  __TEXT.__text: 0x33491c
+  __TEXT.__objc_methlist: 0x12d0c
+  __TEXT.__cstring: 0x2cd68
   __TEXT.__const: 0x21ddc
-  __TEXT.__gcc_except_tab: 0x353c
-  __TEXT.__oslogstring: 0xcbd3
+  __TEXT.__gcc_except_tab: 0x3544
+  __TEXT.__oslogstring: 0xcd83
   __TEXT.__dlopen_cstrs: 0x5f2
   __TEXT.__ustring: 0x18
   __TEXT.__swift5_typeref: 0x8939

   __TEXT.__swift_as_ret: 0x40c
   __TEXT.__swift_as_cont: 0xa88
   __TEXT.__swift5_mpenum: 0xb8
-  __TEXT.__unwind_info: 0x11828
+  __TEXT.__unwind_info: 0x11850
   __TEXT.__eh_frame: 0xeb0c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x360
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x86b8
+  __DATA_CONST.__objc_selrefs: 0x8710
   __DATA_CONST.__objc_protorefs: 0x1d8
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x2f0
   __DATA_CONST.__got: 0x1290
   __AUTH_CONST.__const: 0x1c3d0
-  __AUTH_CONST.__cfstring: 0x11800
-  __AUTH_CONST.__objc_const: 0x352d8
+  __AUTH_CONST.__cfstring: 0x11840
+  __AUTH_CONST.__objc_const: 0x356a8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__auth_got: 0x2960
-  __AUTH.__objc_data: 0x5fc0
-  __AUTH.__data: 0x3da0
-  __DATA.__objc_ivar: 0x1fc0
-  __DATA.__data: 0xbad0
+  __AUTH.__objc_data: 0x2b58
+  __AUTH.__data: 0x3090
+  __DATA.__objc_ivar: 0x1fc8
+  __DATA.__data: 0xb980
   __DATA.__bss: 0x397c0
   __DATA.__common: 0x160
-  __DATA_DIRTY.__objc_data: 0x1120
-  __DATA_DIRTY.__data: 0x520
+  __DATA_DIRTY.__objc_data: 0x4588
+  __DATA_DIRTY.__data: 0x1398
   __DATA_DIRTY.__bss: 0x428
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21815
-  Symbols:   21213
-  CStrings:  7458
+  Functions: 21820
+  Symbols:   21239
+  CStrings:  7466
 
Symbols:
+ -[SFAutoUnlockNotificationModel authToken]
+ -[SFAutoUnlockNotificationModel setAuthToken:]
+ -[SFCollaborationPerformer _failIfMetadataLoadFailed]
+ -[SFCollaborationPerformer _isOptionsLoadInFlightForItem:]
+ -[SFCollaborationPerformer _performAfterOptionsCheck]
+ -[SFCollaborationPerformer _stopWaitingForOptionsLoad]
+ -[SFCollaborationPerformer isWaitingForOptionsLoad]
+ -[SFCollaborationPerformer observable:didChange:]
+ -[SFCollaborationPerformer setIsWaitingForOptionsLoad:]
+ GCC_except_table70
+ GCC_except_table75
+ OBJC_IVAR_$_SFAutoUnlockNotificationModel._authToken
+ OBJC_IVAR_$_SFCollaborationPerformer._isWaitingForOptionsLoad
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationPerformer
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke_2
+ ___54-[SFCollaborationPerformer _stopWaitingForOptionsLoad]_block_invoke
+ _objc_msgSend$_failIfMetadataLoadFailed
+ _objc_msgSend$_isOptionsLoadInFlightForItem:
+ _objc_msgSend$_performAfterOptionsCheck
+ _objc_msgSend$_stopWaitingForOptionsLoad
+ _objc_msgSend$authToken
+ _objc_msgSend$inheritedParticipants
+ _objc_msgSend$isCurrentUser
+ _objc_msgSend$isReadOnly
+ _objc_msgSend$isWaitingForOptionsLoad
+ _objc_msgSend$setAuthToken:
+ _objc_msgSend$setIsWaitingForOptionsLoad:
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke_2
CStrings:
+ "%@: cannot set allowsAccessRequests:%s, share options have not loaded"
+ "%@: cannot set isPublicCollaboration:%s, share options have not loaded"
+ "Collaboration Performer for item %@ resuming after options loaded"
+ "Collaboration Performer for item %@ resuming without options after loading finished"
+ "Collaboration Performer for item %@ waiting for options to load before performing"
+ "Mac17,5"
+ "MacBookNeo"
+ "canShowShareOptions:no, the share options are read-only"
```
