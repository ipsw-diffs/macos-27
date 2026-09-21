## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/Versions/A/IMDaemonCore`

```diff

-1491.200.63.0.0
-  __TEXT.__text: 0x3ae6e8
-  __TEXT.__objc_methlist: 0x1ca74
+1491.200.73.0.0
+  __TEXT.__text: 0x3af640
+  __TEXT.__objc_methlist: 0x1cc04
   __TEXT.__const: 0x76a8
-  __TEXT.__cstring: 0x126d0
-  __TEXT.__oslogstring: 0x51770
-  __TEXT.__gcc_except_tab: 0x1e68c
+  __TEXT.__cstring: 0x12840
+  __TEXT.__oslogstring: 0x51980
+  __TEXT.__gcc_except_tab: 0x1e6ec
   __TEXT.__ustring: 0x32c
   __TEXT.__dlopen_cstrs: 0x190
   __TEXT.__swift5_typeref: 0x39b8
   __TEXT.__constg_swiftt: 0x2ae0
-  __TEXT.__swift5_reflstr: 0x17cf
+  __TEXT.__swift5_reflstr: 0x17bf
   __TEXT.__swift5_fieldmd: 0x1b24
   __TEXT.__swift5_builtin: 0x230
   __TEXT.__swift5_assocty: 0x618

   __TEXT.__swift_as_cont: 0x910
   __TEXT.__swift5_protos: 0x54
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0xfdb8
+  __TEXT.__unwind_info: 0xfe38
   __TEXT.__eh_frame: 0xa00c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1420
-  __DATA_CONST.__objc_classlist: 0xaa8
+  __DATA_CONST.__objc_classlist: 0xac8
   __DATA_CONST.__objc_catlist: 0xf0
-  __DATA_CONST.__objc_protolist: 0x998
+  __DATA_CONST.__objc_protolist: 0x9b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x10960
-  __DATA_CONST.__objc_protorefs: 0x350
-  __DATA_CONST.__objc_superrefs: 0x620
+  __DATA_CONST.__objc_selrefs: 0x109a0
+  __DATA_CONST.__objc_protorefs: 0x360
+  __DATA_CONST.__objc_superrefs: 0x610
   __DATA_CONST.__objc_arraydata: 0x178
-  __DATA_CONST.__got: 0x35a8
+  __DATA_CONST.__got: 0x35d8
   __AUTH_CONST.__const: 0xfd08
   __AUTH_CONST.__cfstring: 0xd900
-  __AUTH_CONST.__objc_const: 0x26b00
-  __AUTH_CONST.__objc_intobj: 0xb58
+  __AUTH_CONST.__objc_const: 0x26f00
+  __AUTH_CONST.__objc_intobj: 0xb70
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2a90
-  __AUTH.__objc_data: 0x35f8
-  __AUTH.__data: 0x578
-  __DATA.__objc_ivar: 0x12fc
-  __DATA.__data: 0x66e0
-  __DATA.__bss: 0x43c0
+  __AUTH_CONST.__auth_got: 0x2a98
+  __AUTH.__objc_data: 0x32a8
+  __AUTH.__data: 0x550
+  __DATA.__objc_ivar: 0x12f4
+  __DATA.__data: 0x6700
+  __DATA.__bss: 0x4140
   __DATA.__common: 0x100
-  __DATA_DIRTY.__objc_data: 0x3a90
-  __DATA_DIRTY.__data: 0x3540
-  __DATA_DIRTY.__bss: 0x22f0
+  __DATA_DIRTY.__objc_data: 0x3fe0
+  __DATA_DIRTY.__data: 0x3760
+  __DATA_DIRTY.__bss: 0x2570
   __DATA_DIRTY.__common: 0x1f8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14621
-  Symbols:   3101
-  CStrings:  8028
+  Functions: 14669
+  Symbols:   3112
+  CStrings:  8039
 
Symbols:
+ _IDSCopyIDForTokenWithID
+ _IMServiceCapabilityOneTimeCodesFromUnknownSenders
+ _IMServiceCapabilityTimeSensitiveOneTimeCodes
+ _OBJC_CLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_CLASS_$_ChatRemoteDebuggingDestination
+ _OBJC_CLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_CLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_CLASS_$_HandleRemoteDebuggingDestination
+ _OBJC_CLASS_$_IDSEndpoint
+ _OBJC_CLASS_$_NewRadarRemoteDebuggingRequest
+ _OBJC_METACLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_METACLASS_$_ChatRemoteDebuggingDestination
+ _OBJC_METACLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_METACLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_METACLASS_$_HandleRemoteDebuggingDestination
+ _OBJC_METACLASS_$_NewRadarRemoteDebuggingRequest
- _OBJC_CLASS_$_IMCTChatBotUtilities
- _OBJC_CLASS_$_IMDNoEligibleDestinationsCache
- _OBJC_CLASS_$_IMDRetryReasonCache
- _OBJC_METACLASS_$_IMDNoEligibleDestinationsCache
- _OBJC_METACLASS_$_IMDRetryReasonCache
CStrings:
+ "/*-------calling into sendRemoteDebuggingRequest: from service that doesn't support it. File a radar-------*/"
+ "IMDaemonCore_Private.ABCRemoteDebuggingRequest"
+ "IMDaemonCore_Private.ChatRemoteDebuggingDestination"
+ "IMDaemonCore_Private.EndpointRemoteDebuggingDestination"
+ "IMDaemonCore_Private.ExistingRadarRemoteDebuggingRequest"
+ "IMDaemonCore_Private.HandleRemoteDebuggingDestination"
+ "IMDaemonCore_Private.NewRadarRemoteDebuggingRequest"
+ "Not applying filter category escalation to one time code in message.guid: %@"
+ "Not inserting group title change item: messageID %@ already stored"
+ "Not tracking one time code in message.guid: %@, service %@ does not track one time codes from unknown senders (known sender: %{BOOL}d)"
+ "Not treating one time code in message.guid: %@ as time sensitive, service %@ does not support time sensitive one time codes"
+ "Queried %lu attachments in the download window, returning %lu with a usable record ID"
+ "Relay status: haveService %{BOOL}d capable %{BOOL}d approved %{BOOL}d"
+ "SMS Relay is remotely approved but no relay IDS service is registered"
- "Does this device have SMS Relay capable devices on its account? %{BOOL}d"
- "Queried %lu attachments, returning %lu after filtering (%lu filtered by date)"
- "Status Of Remote Approval for Relay is %{BOOL}d"
```
