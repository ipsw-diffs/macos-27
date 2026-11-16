## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/Versions/A/CoreCDPInternal`

```diff

-448.250.2.0.0
-  __TEXT.__text: 0x957f0
-  __TEXT.__objc_methlist: 0x5744
+448.250.5.0.0
+  __TEXT.__text: 0x9646c
+  __TEXT.__objc_methlist: 0x5774
   __TEXT.__const: 0x890
-  __TEXT.__oslogstring: 0x1502a
-  __TEXT.__cstring: 0xe9e6
+  __TEXT.__oslogstring: 0x150aa
+  __TEXT.__cstring: 0xeac6
   __TEXT.__gcc_except_tab: 0xb4c
   __TEXT.__dlopen_cstrs: 0xbc
   __TEXT.__constg_swiftt: 0x1e4

   __TEXT.__swift_as_ret: 0x58
   __TEXT.__swift_as_cont: 0x68
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2f80
+  __TEXT.__unwind_info: 0x2f98
   __TEXT.__eh_frame: 0x930
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4d8
+  __DATA_CONST.__const: 0x4f8
   __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x39f0
+  __DATA_CONST.__objc_selrefs: 0x3a10
   __DATA_CONST.__objc_protorefs: 0x50
-  __DATA_CONST.__objc_superrefs: 0x150
-  __DATA_CONST.__objc_arraydata: 0x230
-  __DATA_CONST.__got: 0x1158
-  __AUTH_CONST.__const: 0x2f40
-  __AUTH_CONST.__cfstring: 0x9a40
-  __AUTH_CONST.__objc_const: 0xfce8
+  __DATA_CONST.__objc_superrefs: 0x158
+  __DATA_CONST.__objc_arraydata: 0x150
+  __DATA_CONST.__got: 0x1170
+  __AUTH_CONST.__const: 0x2f60
+  __AUTH_CONST.__cfstring: 0x9a80
+  __AUTH_CONST.__objc_const: 0xfd08
   __AUTH_CONST.__objc_intobj: 0x168
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x800
   __AUTH.__objc_data: 0x170
-  __DATA.__objc_ivar: 0x3c8
+  __DATA.__objc_ivar: 0x3cc
   __DATA.__data: 0x1190
   __DATA.__bss: 0x498
   __DATA_DIRTY.__objc_data: 0x1910

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3253
-  Symbols:   5826
-  CStrings:  2863
+  Functions: 3260
+  Symbols:   5839
+  CStrings:  2868
 
Symbols:
+ -[CDPDXPCEventObserver initWithEventStreamRegistrar:]
+ -[CDPDXPCEventObserver init]
+ -[CDPDXPCListener _buildRawEntitlementsBitMaskForConnection:]
+ -[CDPDXPCListener _connection:hasRawEntitlement:]
+ -[CDPWalrusDaemonService _shouldDenyPCSKeysAccess]
+ _OBJC_IVAR_$_CDPDXPCEventObserver._registrar
+ ___28-[CDPDXPCEventObserver init]_block_invoke
+ ___block_descriptor_32_e76_v32?0r*8"NSObject<OS_dispatch_queue>"16?<v?"NSObject<OS_xpc_object>">24l
+ _kAAAnalyticsEventDeviceListCacheHit
+ _kAAAnalyticsEventDeviceListCacheMiss
+ _kAAAnalyticsEventDeviceListCacheValidation
+ _objc_msgSend$_buildRawEntitlementsBitMaskForConnection:
+ _objc_msgSend$_connection:hasRawEntitlement:
+ _objc_msgSend$_shouldDenyPCSKeysAccess
+ _objc_msgSend$initWithEventStreamRegistrar:
+ _objc_msgSend$shouldDenyAccessGivenIsEntitled:context:error:alwaysEnforced:
- -[CDPDXPCListener _shouldAcceptNewConnectionWithEntitlements:]
- ___72-[CDPDClientHandler deleteRecoveryKeyWithContext:uiProvider:completion:]_block_invoke_2
- _objc_msgSend$_shouldAcceptNewConnectionWithEntitlements:
CStrings:
+ "Accepting new connection %@ with raw entitlements mask %i"
+ "Denying walrus operation. Missing walrus entitlement."
+ "Denying walrus operation. Missing walrus.pcskeys entitlement."
+ "com.apple.appleaccount.custodian.healthcheck.owner.cleanupPhantomCustodian"
+ "com.apple.appleaccount.recoveryContact.custodian.nto.landing"
+ "com.apple.distnoted.matching.trusted"
+ "v32@?0r*8@\"NSObject<OS_dispatch_queue>\"16@?<v@?@\"NSObject<OS_xpc_object>\">24"
- "Accepting new connection %@ with entitlements mask %i"
- "com.apple.distnoted.matching"
```
