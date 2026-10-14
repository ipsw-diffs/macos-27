## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport`

```diff

-751.200.73.0.0
-  __TEXT.__text: 0xe25e4
-  __TEXT.__objc_methlist: 0xa148
-  __TEXT.__cstring: 0x145ec
+751.200.83.0.0
+  __TEXT.__text: 0xe4498
+  __TEXT.__objc_methlist: 0xa1a0
+  __TEXT.__cstring: 0x146cc
   __TEXT.__const: 0x41a8
-  __TEXT.__gcc_except_tab: 0x14f0
+  __TEXT.__gcc_except_tab: 0x1508
   __TEXT.__oslogstring: 0x26bd
   __TEXT.__swift5_typeref: 0xc4f
-  __TEXT.__swift5_capture: 0x950
+  __TEXT.__swift5_capture: 0x958
   __TEXT.__swift5_fieldmd: 0xb34
   __TEXT.__constg_swiftt: 0xdbc
   __TEXT.__swift5_reflstr: 0x93c

   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x3c18
+  __TEXT.__unwind_info: 0x3c48
   __TEXT.__eh_frame: 0x960
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x12f8
+  __DATA_CONST.__const: 0x1300
   __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4590
+  __DATA_CONST.__objc_selrefs: 0x45d8
   __DATA_CONST.__objc_protorefs: 0x100
   __DATA_CONST.__objc_superrefs: 0x1f8
   __DATA_CONST.__objc_arraydata: 0xb0
   __DATA_CONST.__got: 0x4e8
-  __AUTH_CONST.__const: 0x3f30
-  __AUTH_CONST.__cfstring: 0x5f20
-  __AUTH_CONST.__objc_const: 0x115f8
+  __AUTH_CONST.__const: 0x3f90
+  __AUTH_CONST.__cfstring: 0x5fa0
+  __AUTH_CONST.__objc_const: 0x11658
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0xfc8
   __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x1114
+  __DATA.__objc_ivar: 0x111c
   __DATA.__data: 0x738
-  __DATA.__bss: 0x2e20
+  __DATA.__bss: 0x2e30
   __DATA.__common: 0x68
   __DATA_DIRTY.__objc_data: 0x2618
   __DATA_DIRTY.__data: 0x2650

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5871
-  Symbols:   8435
-  CStrings:  3039
+  Functions: 5887
+  Symbols:   8456
+  CStrings:  3046
 
Symbols:
+ -[RPCompanionLinkDevice updateMultiUserDeviceWithPeer:]
+ -[RPConnection _multiUserDeviceWithIdentifier:]
+ -[RPConnection multiUserDevices]
+ -[RPConnection setMultiUserDevices:]
+ -[RPConnection verifyIdentityProof:accountAltDSID:]
+ -[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]
+ -[RPSiriSession setTriggeredPhrase:]
+ -[RPSiriSession triggeredPhrase]
+ GCC_except_table281
+ GCC_except_table300
+ OBJC_IVAR_$_RPConnection._multiUserDevices
+ OBJC_IVAR_$_RPSiriSession._triggeredPhrase
+ _RPOptionMultiUserDeviceID
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke_2
+ ___block_descriptor_65_e8_32s40s48bs56r_e25_v20?0B8"CUPairedPeer"12l
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80r_e23_v20?0B8"RPIdentity"12l
+ ___copy_helper_block_e8_32s40s48s56s64s72b80r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80r
+ _objc_msgSend$_multiUserDeviceWithIdentifier:
+ _objc_msgSend$resolveIdentityforSignature:data:flags:accountaltDSID:
+ _sepBackedIdentityEnabled.enabled
- GCC_except_table292
CStrings:
+ "### Failed to obtain local account for multi-user HK verify\n"
+ "-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]"
+ "SEPBackedIdentity"
+ "_vtPhrase"
+ "iCrowd"
+ "missingFlag.MultiUser"
+ "multiUserDevID"
```
