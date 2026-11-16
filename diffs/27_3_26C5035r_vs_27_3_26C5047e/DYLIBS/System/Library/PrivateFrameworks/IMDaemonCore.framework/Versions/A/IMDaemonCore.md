## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/Versions/A/IMDaemonCore`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x41b0c0
+1491.300.74.0.0
+  __TEXT.__text: 0x41d800
   __TEXT.__objc_methlist: 0x222e4
-  __TEXT.__const: 0x86d8
-  __TEXT.__cstring: 0x13f39
-  __TEXT.__oslogstring: 0x57e00
-  __TEXT.__gcc_except_tab: 0x21b40
+  __TEXT.__const: 0x8708
+  __TEXT.__cstring: 0x13e49
+  __TEXT.__oslogstring: 0x58150
+  __TEXT.__gcc_except_tab: 0x21c8c
   __TEXT.__ustring: 0x32c
   __TEXT.__dlopen_cstrs: 0x190
-  __TEXT.__swift5_typeref: 0x4256
+  __TEXT.__swift5_typeref: 0x427c
   __TEXT.__constg_swiftt: 0x3334
   __TEXT.__swift5_reflstr: 0x1a37
   __TEXT.__swift5_fieldmd: 0x1ebc
   __TEXT.__swift5_builtin: 0x244
   __TEXT.__swift5_assocty: 0x618
-  __TEXT.__swift5_capture: 0x22dc
+  __TEXT.__swift5_capture: 0x22fc
   __TEXT.__swift5_proto: 0x404
   __TEXT.__swift5_types: 0x2b8
   __TEXT.__swift_as_entry: 0x444
-  __TEXT.__swift_as_ret: 0x538
-  __TEXT.__swift_as_cont: 0x9cc
+  __TEXT.__swift_as_ret: 0x53c
+  __TEXT.__swift_as_cont: 0x9d8
   __TEXT.__swift5_protos: 0x74
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x12330
-  __TEXT.__eh_frame: 0xb6d8
+  __TEXT.__unwind_info: 0x123b0
+  __TEXT.__eh_frame: 0xb808
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1438
+  __DATA_CONST.__const: 0x1440
   __DATA_CONST.__objc_classlist: 0xd30
   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0xbc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x110c0
+  __DATA_CONST.__objc_selrefs: 0x110f0
   __DATA_CONST.__objc_protorefs: 0x390
   __DATA_CONST.__objc_superrefs: 0x710
-  __DATA_CONST.__objc_arraydata: 0x188
-  __DATA_CONST.__got: 0x39c0
-  __AUTH_CONST.__const: 0x122a8
-  __AUTH_CONST.__cfstring: 0xde80
-  __AUTH_CONST.__objc_const: 0x31e88
+  __DATA_CONST.__objc_arraydata: 0x170
+  __DATA_CONST.__got: 0x39d0
+  __AUTH_CONST.__const: 0x122e0
+  __AUTH_CONST.__cfstring: 0xde20
+  __AUTH_CONST.__objc_const: 0x31e20
   __AUTH_CONST.__objc_intobj: 0xbe8
-  __AUTH_CONST.__objc_arrayobj: 0x1b0
+  __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2c18
+  __AUTH_CONST.__auth_got: 0x2c30
   __AUTH.__objc_data: 0x5118
   __AUTH.__data: 0x870
   __DATA.__objc_ivar: 0x13f0
-  __DATA.__data: 0x8190
-  __DATA.__bss: 0x4360
+  __DATA.__data: 0x81e0
+  __DATA.__bss: 0x4370
   __DATA.__common: 0x100
   __DATA_DIRTY.__objc_data: 0x4020
-  __DATA_DIRTY.__data: 0x3690
+  __DATA_DIRTY.__data: 0x3670
   __DATA_DIRTY.__bss: 0x2460
   __DATA_DIRTY.__common: 0x1d0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /System/Library/PrivateFrameworks/IDS.framework/Versions/A/IDS
   - /System/Library/PrivateFrameworks/IDSFoundation.framework/Versions/A/IDSFoundation
   - /System/Library/PrivateFrameworks/IDSKVStore.framework/Versions/A/IDSKVStore
-  - /System/Library/PrivateFrameworks/IMCore.framework/Versions/A/IMCore
   - /System/Library/PrivateFrameworks/IMCorePipeline.framework/Versions/A/IMCorePipeline
   - /System/Library/PrivateFrameworks/IMDMessageServices.framework/Versions/A/IMDMessageServices
   - /System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16834
-  Symbols:   3331
-  CStrings:  8626
+  Functions: 16854
+  Symbols:   3334
+  CStrings:  8636
 
Symbols:
+ _IMTransferAgentErrorDomain
+ _IMTransferAgentErrorFZErrorTypeKey
+ _kNumberOfTimesRespondedToThreadKey
CStrings:
+ "  => Could not mark message %@ as sending; not sending it out"
+ "Bailing, the GUID of message %@ is already used by an item of class %@"
+ "Incoming payload file missing or not written at %@, marking transfer %@ as failed"
+ "Not storing message %@: its GUID is already used by an item of class %@"
+ "PersistentTaskSchedulerExpirationGraceSeconds"
+ "Reloaded transfer %@ from the attachment store for accept, it has a CloudKit record"
+ "Storing new plugin message %{public}@ with no payload data (balloonBundleID %{public}@)"
+ "TelephonyServiceSession (%@): Acquisition failure for message %@; failing send."
+ "Translation is not supported, skipping outgoing translation."
+ "Updating autoDonationBehavior: %ld"
+ "[%{public}s] cancelled while loading tasks, leaving them queued to resume"
+ "[%{public}s] run did not unwind after DAS expiry; abandoning it so DAS is answered"
+ "[TEST] Simulating a 0-byte file for %s due to default force-empty-attachment-acquisition"
+ "force-empty-attachment-acquisition"
+ "isMMSWithContentForSMSRelay"
- "*** If this is an internal group, please request logs from all participants! ***\n\nChats were found using the provided identifiers %@ and participants %@ that had no matching participants.\n\nChats Found: %@\n\nIdentifiers: %@"
- "Updating chatInfo with autoDonationBehavior: %ld"
- "[FindChat] Found Chat By Identifier With No Matching Participants"
- "[Internal] Chat Inconsistencies"
- "com.apple.MobileSMS.BestCandidateChatAlert"
```
