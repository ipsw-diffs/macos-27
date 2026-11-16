## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities`

```diff

-1626.300.42.0.0
-  __TEXT.__text: 0x1b97e0
-  __TEXT.__objc_methlist: 0x1bca8
-  __TEXT.__cstring: 0x12c96
+1626.300.62.0.0
+  __TEXT.__text: 0x1ba344
+  __TEXT.__objc_methlist: 0x1bcf8
+  __TEXT.__cstring: 0x12cd6
   __TEXT.__const: 0x4b8c
-  __TEXT.__oslogstring: 0x13be4
-  __TEXT.__gcc_except_tab: 0x14b4
+  __TEXT.__oslogstring: 0x13c24
+  __TEXT.__gcc_except_tab: 0x14fc
   __TEXT.__ustring: 0xde
   __TEXT.__dlopen_cstrs: 0x4fb
   __TEXT.__constg_swiftt: 0xebc

   __TEXT.__swift_as_cont: 0x1cc
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x91d8
+  __TEXT.__unwind_info: 0x91f8
   __TEXT.__eh_frame: 0x2f90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x428
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb800
+  __DATA_CONST.__objc_selrefs: 0xb818
   __DATA_CONST.__objc_protorefs: 0x110
   __DATA_CONST.__objc_superrefs: 0x708
   __DATA_CONST.__objc_arraydata: 0xaf8
   __DATA_CONST.__got: 0x1060
-  __AUTH_CONST.__const: 0x68f8
-  __AUTH_CONST.__cfstring: 0x12860
-  __AUTH_CONST.__objc_const: 0x2b9a0
+  __AUTH_CONST.__const: 0x6948
+  __AUTH_CONST.__cfstring: 0x128a0
+  __AUTH_CONST.__objc_const: 0x2ba10
   __AUTH_CONST.__objc_intobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0x318
   __AUTH_CONST.__auth_got: 0x1378
   __AUTH.__objc_data: 0x2600
   __AUTH.__data: 0xd08
-  __DATA.__objc_ivar: 0x1958
+  __DATA.__objc_ivar: 0x1960
   __DATA.__data: 0x3fc0
   __DATA.__bss: 0x7ab0
   __DATA.__common: 0xb0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11886
-  Symbols:   20389
-  CStrings:  4490
+  Functions: 11894
+  Symbols:   20400
+  CStrings:  4495
 
Symbols:
+ -[TUContinuitySessionInfo initWithDevice:calls:activeConversations:recentCalls:recentCallsContacts:meContact:meHandle:isDedicatedSession:favorites:conversationLinks:recentCallsInfos:callBlockedStates:]
+ -[TUContinuitySessionInfo meContact]
+ -[TUContinuitySessionInfo meHandle]
+ -[TUConversationManager getLocalCallerIDWithCompletionHandler:]
+ -[TUConversationManagerXPCClient getLocalCallerIDWithCompletionHandler:]
+ GCC_except_table104
+ GCC_except_table177
+ GCC_except_table184
+ GCC_except_table218
+ _OBJC_IVAR_$_TUContinuitySessionInfo._meContact
+ _OBJC_IVAR_$_TUContinuitySessionInfo._meHandle
+ _TUHandleIsNormalized
+ ___72-[TUConversationManagerXPCClient getLocalCallerIDWithCompletionHandler:]_block_invoke
+ ___TUUniqueContactIdentifiersByHandle_block_invoke
+ ___TUUniqueContactIdentifiersByHandle_block_invoke_2
+ ___block_descriptor_56_e8_32s40s48r_e35_v32?0"NSString"8"NSString"16^B24l
+ _objc_msgSend$getLocalCallerIDWithCompletionHandler:
+ _objc_msgSend$initWithDevice:calls:activeConversations:recentCalls:recentCallsContacts:meContact:meHandle:isDedicatedSession:favorites:conversationLinks:recentCallsInfos:callBlockedStates:
+ _os_unfair_recursive_lock_lock
- -[TUContinuitySessionInfo initWithDevice:calls:activeConversations:recentCalls:recentCallsContacts:isDedicatedSession:favorites:conversationLinks:recentCallsInfos:callBlockedStates:]
- GCC_except_table103
- GCC_except_table107
- GCC_except_table167
- GCC_except_table175
- GCC_except_table216
- _objc_msgSend$initWithDevice:calls:activeConversations:recentCalls:recentCallsContacts:isDedicatedSession:favorites:conversationLinks:recentCallsInfos:callBlockedStates:
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ " hasMeContact=%d"
+ " meHandle=%@"
+ "Asked for the local caller ID"
+ "Error in retrieving local caller ID: %@"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
```
