## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1219.40.5.0.0
-  __TEXT.__text: 0x18b94c
+1219.40.7.0.0
+  __TEXT.__text: 0x18bb48
   __TEXT.__auth_stubs: 0x1860
-  __TEXT.__objc_stubs: 0x9060
-  __TEXT.__objc_methlist: 0x6dbc
+  __TEXT.__objc_stubs: 0x90a0
+  __TEXT.__objc_methlist: 0x6de4
   __TEXT.__const: 0x1b31
   __TEXT.__gcc_except_tab: 0x1ec4
   __TEXT.__objc_classname: 0xff5
-  __TEXT.__objc_methname: 0xfaae
+  __TEXT.__objc_methname: 0xfadb
   __TEXT.__objc_methtype: 0x3399
-  __TEXT.__cstring: 0xe802
-  __TEXT.__oslogstring: 0x38500
+  __TEXT.__cstring: 0xe831
+  __TEXT.__oslogstring: 0x385b3
   __TEXT.__ustring: 0x232
-  __TEXT.__unwind_info: 0x6408
-  __DATA_CONST.__const: 0x9f48
-  __DATA_CONST.__cfstring: 0x7580
+  __TEXT.__unwind_info: 0x6420
+  __DATA_CONST.__const: 0x9f88
+  __DATA_CONST.__cfstring: 0x75a0
   __DATA_CONST.__objc_classlist: 0x308
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x188

   __DATA_CONST.__got: 0xc50
   __DATA_CONST.__auth_ptr: 0x90
   __DATA.__objc_const: 0xae60
-  __DATA.__objc_selrefs: 0x3338
+  __DATA.__objc_selrefs: 0x3348
   __DATA.__objc_ivar: 0x778
   __DATA.__objc_data: 0x1e50
   __DATA.__data: 0x1910
-  __DATA.__bss: 0xb68
+  __DATA.__bss: 0xb78
   __DATA.__common: 0x28
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 8239
-  Symbols:   10794
-  CStrings:  8630
+  Functions: 8247
+  Symbols:   10806
+  CStrings:  8635
 
Symbols:
+ -[ACCTransportServer isConnectionEntitled:]
+ -[ACCTransportServer shouldAcceptConnection:]
+ -[NSXPCConnection(Entitlements) hasBooleanEntitlement:]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(acc_internal_settings.o)
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ _acc_internalSettings_boolForKey
+ _kCFACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
+ _kCFACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
+ _kCFACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
+ _kCFACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
+ _objc_msgSend$hasBooleanEntitlement:
+ _objc_msgSend$isConnectionEntitled:
+ acc_internalSettings_boolForKey
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
- _ACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
- _ACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
- _ACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
- _ACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
CStrings:
+ "Unentitled XPC connection from pid %d! (Missing entitlement: '%@')! (API: ACCTransportClient / acc_transport_client)"
+ "acc_internalSettings: internal-only setting %{public}@ active"
+ "com.apple.private.accessories.transport-client"
+ "hasBooleanEntitlement:"
+ "isConnectionEntitled:"
```
