## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/Versions/A/MFAAuthentication`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x27888
-  __TEXT.__objc_methlist: 0x494
-  __TEXT.__const: 0x68b13
-  __TEXT.__cstring: 0x154a
+  __TEXT.__text: 0x27a34
+  __TEXT.__objc_methlist: 0x4a4
+  __TEXT.__const: 0x68b23
+  __TEXT.__cstring: 0x1607
   __TEXT.__gcc_except_tab: 0x90
-  __TEXT.__oslogstring: 0x4a66
+  __TEXT.__oslogstring: 0x4aaa
   __TEXT.__ustring: 0xa
-  __TEXT.__unwind_info: 0x670
+  __TEXT.__unwind_info: 0x678
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x53b0
+  __DATA_CONST.__const: 0x5410
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a8
+  __DATA_CONST.__objc_selrefs: 0x4c0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__got: 0x1f0
   __AUTH_CONST.__const: 0x790
-  __AUTH_CONST.__cfstring: 0x1840
+  __AUTH_CONST.__cfstring: 0x1900
   __AUTH_CONST.__objc_const: 0x648
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x28

   __AUTH.__objc_data: 0x50
   __DATA.__objc_ivar: 0x10
   __DATA.__data: 0x60
-  __DATA.__bss: 0x88
+  __DATA.__bss: 0x80
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__data: 0xc8
   __DATA_DIRTY.__bss: 0x1a8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 747
-  Symbols:   1955
-  CStrings:  638
+  Functions: 748
+  Symbols:   1970
+  CStrings:  646
 
Symbols:
+ -[MFAACertificateManager createVillanovaNonce:IDSN:challenge:]
+ GCC_except_table45
+ GCC_except_table54
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _objc_msgSend$appendBytes:length:
+ _objc_msgSend$dataWithCapacity:
+ createVillanovaNonce:IDSN:challenge:.kAuthPrefix
- GCC_except_table44
- GCC_except_table53
- systemInfo_isDeveloperBuild.developerBuild
Functions:
~ -[MFAACertificateManager verifyModuleCertificate:forModule:forAuthFlags:] : 1148 -> 1188
+ -[MFAACertificateManager createVillanovaNonce:IDSN:challenge:]
~ _OUTLINED_FUNCTION_10 : 16 -> 20
~ _OUTLINED_FUNCTION_11 : 20 -> 24
~ _OUTLINED_FUNCTION_12 : 24 -> 16
~ _systemInfo_isDeveloperBuild : 56 -> 52
~ ___systemInfo_isDeveloperBuild_block_invoke : 16 -> 4
~ _validateSignatureRSA : 632 -> 636
CStrings:
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "PlatformIDOverride"
+ "TestCreateBLEPairingOnInductive"
+ "createVillanovaNonce: nonce=%@ idsn=%@ challenge=%@ -> msg=%@ -> %@"
+ "iPhone RCAM"
```
