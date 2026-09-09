## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Versions/A/XPCServices/ACCHWComponentAuthService.xpc/Contents/MacOS/ACCHWComponentAuthService`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x49338
+  __TEXT.__text: 0x4934c
   __TEXT.__auth_stubs: 0xf40
-  __TEXT.__objc_stubs: 0x1120
-  __TEXT.__objc_methlist: 0x63c
-  __TEXT.__const: 0x1f3c3
-  __TEXT.__cstring: 0x3501
+  __TEXT.__objc_stubs: 0x1140
+  __TEXT.__objc_methlist: 0x684
+  __TEXT.__const: 0x1f3d3
+  __TEXT.__cstring: 0x35f8
   __TEXT.__objc_classname: 0x9b
-  __TEXT.__objc_methname: 0x1820
+  __TEXT.__objc_methname: 0x192d
   __TEXT.__objc_methtype: 0x873
-  __TEXT.__oslogstring: 0x6a3e
-  __TEXT.__gcc_except_tab: 0x2c8
-  __TEXT.__unwind_info: 0xb08
-  __DATA_CONST.__const: 0x8148
-  __DATA_CONST.__cfstring: 0x1620
+  __TEXT.__oslogstring: 0x6aaf
+  __TEXT.__gcc_except_tab: 0x2d4
+  __TEXT.__unwind_info: 0x1428
+  __DATA_CONST.__const: 0x8228
+  __DATA_CONST.__cfstring: 0x1720
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x7b0
   __DATA_CONST.__got: 0x158
   __DATA_CONST.__auth_ptr: 0x50
-  __DATA.__objc_const: 0xa70
-  __DATA.__objc_selrefs: 0x5e0
+  __DATA.__objc_const: 0xb10
+  __DATA.__objc_selrefs: 0x608
   __DATA.__objc_ivar: 0x60
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x940
-  __DATA.__bss: 0x110
+  __DATA.__bss: 0x118
   __DATA.__common: 0x38
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1603
-  Symbols:   3575
-  CStrings:  1495
+  Functions: 1612
+  Symbols:   3593
+  CStrings:  1512
 
Symbols:
+ -[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]
+ -[ACCHWComponentAuthService signRCAMChallenge:completionHandler:componentIndex:]
+ GCC_except_table83
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke_2
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _objc_msgSend$createVillanovaNonce:IDSN:challenge:
+ authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.RCAMQueue
+ authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.onceToken
- GCC_except_table80
- systemInfo_isDeveloperBuild.developerBuild
CStrings:
+ "(moduleType=%d) %s: cpGetDeviceIDSN failed: ret=%x len=%zu"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "ComponentBusyError"
+ "Flags indicate rcam...do not call cpCopyCertificate()"
+ "PlatformIDOverride"
+ "RCAM"
+ "TestCreateBLEPairingOnInductive"
+ "authenticateRCAMWithChallenge:completionHandler:updateRegistry:"
+ "authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:"
+ "com.apple.ACCHWComponentAuthService.rcam"
+ "createVillanovaNonce:IDSN:challenge:"
+ "prpc"
+ "signRCAMChallenge:completionHandler:"
+ "signRCAMChallenge:completionHandler:componentIndex:"
```
