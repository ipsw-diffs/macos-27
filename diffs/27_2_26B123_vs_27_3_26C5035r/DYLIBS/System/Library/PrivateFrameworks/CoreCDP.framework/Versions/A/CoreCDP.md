## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/Versions/A/CoreCDP`

```diff

-448.125.10.0.0
-  __TEXT.__text: 0x5208c
-  __TEXT.__objc_methlist: 0x3ac4
-  __TEXT.__const: 0x14dc
+448.250.2.0.0
+  __TEXT.__text: 0x520d8
+  __TEXT.__objc_methlist: 0x3ad4
+  __TEXT.__const: 0x14ec
   __TEXT.__gcc_except_tab: 0x1114
   __TEXT.__oslogstring: 0x91f1
-  __TEXT.__cstring: 0x6655
+  __TEXT.__cstring: 0x67cd
   __TEXT.__dlopen_cstrs: 0x12e
   __TEXT.__ustring: 0x28
   __TEXT.__unwind_info: 0x20b8

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ec8
+  __DATA_CONST.__const: 0x1ef0
   __DATA_CONST.__objc_classlist: 0x1a8
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x21f0
+  __DATA_CONST.__objc_selrefs: 0x21f8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xe8
-  __DATA_CONST.__objc_arraydata: 0x168
+  __DATA_CONST.__objc_arraydata: 0x1d0
   __DATA_CONST.__got: 0x500
-  __AUTH_CONST.__const: 0x1950
-  __AUTH_CONST.__cfstring: 0x4040
-  __AUTH_CONST.__objc_const: 0x8868
+  __AUTH_CONST.__const: 0x1970
+  __AUTH_CONST.__cfstring: 0x41a0
+  __AUTH_CONST.__objc_const: 0x8878
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__objc_arrayobj: 0xf0
+  __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__auth_got: 0x778
   __DATA.__objc_ivar: 0x300
-  __DATA.__data: 0x11a0
-  __DATA.__bss: 0x131
+  __DATA.__data: 0x11a8
+  __DATA.__bss: 0x141
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x1090
   __DATA_DIRTY.__data: 0x8

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2440
-  Symbols:   4538
-  CStrings:  1647
+  Functions: 2444
+  Symbols:   4551
+  CStrings:  1659
 
Symbols:
+ +[CDPUtilities isDBRServerRecreationEnabled]
+ _OUTLINED_FUNCTION_100
+ ___40+[CDPUtilities sanitizedInfoDictionary:]_block_invoke
+ ___der_key_expert_tbm_support
+ _der_key_expert_tbm_support
+ _kCDPAnalyticsPDPServerRecreationFinishEvent
+ _kCDPAnalyticsPDPServerRecreationSetupAfterRecreateEvent
+ _kCDPAnalyticsPDPServerRecreationSkippedEvent
+ _kCDPAnalyticsPDPServerRecreationStartEvent
+ _kCDPAnalyticsPDPSetupHealedOnRevalidateEvent
+ _objc_msgSend$isDBRInlineSignInHealEnabled
+ _sanitizedInfoDictionary:.onceToken
+ _sanitizedInfoDictionary:.sensitiveKeys
Functions:
+ +[CDPUtilities isDBRServerRecreationEnabled]
~ +[CDPUtilities sanitizedInfoDictionary:] : 456 -> 392
+ ___40+[CDPUtilities sanitizedInfoDictionary:]_block_invoke
~ _OUTLINED_FUNCTION_93 : 28 -> 12
~ _OUTLINED_FUNCTION_95 : 20 -> 28
~ _OUTLINED_FUNCTION_99 : 12 -> 20
+ _get_akslog_context
+ _CDPLocalizedStringInTable.cold.1
~ _aks_create_signing_key : 264 -> 260
~ _aks_create_signing_key_with_params : 276 -> 272
~ _aks_drain_backup_keys : 260 -> 256
~ _aks_drain_backup_keys_info : 296 -> 280
CStrings:
+ "DBRServerRecreation"
+ "DBRServerRecreationEnabled"
+ "com.apple.corecdp.pdpServerRecreationFinish"
+ "com.apple.corecdp.pdpServerRecreationSetupAfterRecreate"
+ "com.apple.corecdp.pdpServerRecreationSkipped"
+ "com.apple.corecdp.pdpServerRecreationStart"
+ "com.apple.corecdp.pdpSetupHealedOnRevalidate"
+ "kPCSAuthenticateAppleID"
+ "kPCSSetupAltDSID"
+ "kPCSSetupAuthToken"
+ "kPCSSetupPassword"
+ "kPCSSetupUsername"
```
