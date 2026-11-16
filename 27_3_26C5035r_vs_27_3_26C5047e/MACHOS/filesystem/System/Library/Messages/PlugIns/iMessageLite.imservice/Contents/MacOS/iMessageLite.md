## iMessageLite

> `/System/Library/Messages/PlugIns/iMessageLite.imservice/Contents/MacOS/iMessageLite`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__auth_ptr`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x4bd30
-  __TEXT.__auth_stubs: 0x15a0
-  __TEXT.__objc_stubs: 0x24c0
-  __TEXT.__objc_methlist: 0x3bc
+1491.300.74.0.0
+  __TEXT.__text: 0x4c040
+  __TEXT.__auth_stubs: 0x15b0
+  __TEXT.__objc_stubs: 0x2580
+  __TEXT.__objc_methlist: 0x424
   __TEXT.__const: 0x28d8
-  __TEXT.__gcc_except_tab: 0x1d0
-  __TEXT.__cstring: 0x10e7
+  __TEXT.__gcc_except_tab: 0x1e4
+  __TEXT.__cstring: 0x1137
   __TEXT.__oslogstring: 0x2314
-  __TEXT.__objc_classname: 0x1d1
-  __TEXT.__objc_methtype: 0x77e
-  __TEXT.__objc_methname: 0x26b3
+  __TEXT.__objc_classname: 0x1e1
+  __TEXT.__objc_methtype: 0x78e
+  __TEXT.__objc_methname: 0x27d3
   __TEXT.__dlopen_cstrs: 0x44
   __TEXT.__swift5_typeref: 0xba2
   __TEXT.__constg_swiftt: 0x7d8

   __TEXT.__swift_as_cont: 0x1f4
   __TEXT.__swift5_assocty: 0x130
   __TEXT.__swift5_protos: 0xc
-  __TEXT.__unwind_info: 0x1458
+  __TEXT.__unwind_info: 0x1480
   __TEXT.__eh_frame: 0x2de0
-  __DATA_CONST.__const: 0x2718
-  __DATA_CONST.__cfstring: 0x80
-  __DATA_CONST.__objc_classlist: 0x18
+  __DATA_CONST.__const: 0x2748
+  __DATA_CONST.__cfstring: 0xa0
+  __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__auth_got: 0xae0
-  __DATA_CONST.__got: 0x648
+  __DATA_CONST.__objc_superrefs: 0x8
+  __DATA_CONST.__auth_got: 0xae8
+  __DATA_CONST.__got: 0x658
   __DATA_CONST.__auth_ptr: 0x4f8
-  __DATA.__objc_const: 0x808
-  __DATA.__objc_selrefs: 0xa60
-  __DATA.__objc_data: 0xc0
-  __DATA.__data: 0xb88
+  __DATA.__objc_const: 0x950
+  __DATA.__objc_selrefs: 0xa90
+  __DATA.__objc_ivar: 0xc
+  __DATA.__objc_data: 0x110
+  __DATA.__data: 0xb80
   __DATA.__bss: 0x20f0
   __DATA.__common: 0xc0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/FamilyCircle.framework/Versions/A/FamilyCircle
   - /System/Library/PrivateFrameworks/IDS.framework/Versions/A/IDS
   - /System/Library/PrivateFrameworks/IDSFoundation.framework/Versions/A/IDSFoundation
-  - /System/Library/PrivateFrameworks/IMCore.framework/Versions/A/IMCore
   - /System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence
   - /System/Library/PrivateFrameworks/IMDaemonCore.framework/Versions/A/IMDaemonCore
   - /System/Library/PrivateFrameworks/IMFoundation.framework/Versions/A/IMFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1234
-  Symbols:   3868
-  CStrings:  689
+  Functions: 1246
+  Symbols:   3901
+  CStrings:  707
 
Symbols:
+ +[IMLitePluginPayload imCoreBundle]
+ +[IMLitePluginPayload pluginBundleIDForBalloonBundleID:]
+ -[IMLitePluginPayload .cxx_destruct]
+ -[IMLitePluginPayload data]
+ -[IMLitePluginPayload initWithMessageItem:]
+ -[IMLitePluginPayload pluginBundleID]
+ -[IMLitePluginPayload url]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/MessagesCore/install/TempContent/Objects/iMessageLite.build/iMessageLite.build/Objects-normal/arm64e/IMLitePluginPayload.o
+ IMLitePluginPayload.m
+ _$sSo12NSDictionaryCMa
+ _$sSo13IMMessageItemC12iMessageLiteE12imCoreString33_1BC1E26FF7EAE316FD1B216EFFD0ADEELL6forKeySSSgSS_tFTf4nd_n
+ _$sSo13IMMessageItemC12iMessageLiteE7summary33_1BC1E26FF7EAE316FD1B216EFFD0ADEELL4fromSSSgSo19IMLitePluginPayloadC_tFTf4nd_n
+ _IMBalloonBundleIdentifierAskTo
+ _IMBalloonBundleIdentifierLegacyAskToBuy
+ _IMBalloonBundleIdentifierLegacyScreenTime
+ _IMLinkAttributeName
+ _OBJC_CLASS_$_IMLitePluginPayload
+ _OBJC_CLASS_$_NSObject
+ _OBJC_IVAR_$_IMLitePluginPayload._data
+ _OBJC_IVAR_$_IMLitePluginPayload._pluginBundleID
+ _OBJC_IVAR_$_IMLitePluginPayload._url
+ _OBJC_METACLASS_$_IMLitePluginPayload
+ __OBJC_$_CLASS_METHODS_IMLitePluginPayload
+ __OBJC_$_CLASS_PROP_LIST_IMLitePluginPayload
+ __OBJC_$_INSTANCE_METHODS_IMLitePluginPayload
+ __OBJC_$_INSTANCE_VARIABLES_IMLitePluginPayload
+ __OBJC_$_PROP_LIST_IMLitePluginPayload
+ __OBJC_CLASS_RO_$_IMLitePluginPayload
+ __OBJC_METACLASS_RO_$_IMLitePluginPayload
+ ___43-[IMLitePluginPayload initWithMessageItem:]_block_invoke
+ ___block_descriptor_40_e8_32r_e34_v40?0"NSURL"8{_NSRange=QQ}16^B32l
+ _objc_msgSend$_FTOptionallyDecompressData
+ _objc_msgSend$bundleWithPath:
+ _objc_msgSend$enumerateAttribute:inRange:options:usingBlock:
+ _objc_msgSend$imCoreBundle
+ _objc_msgSend$isEqualToString:
+ _objc_msgSend$isUpgradedAskToBuyEnabled
+ _objc_msgSend$pluginBundleIDForBalloonBundleID:
+ _objc_storeStrong
- _$sSo12NSDictionaryCMaTm
- _$sSo13IMMessageItemC12iMessageLiteE7summary33_1BC1E26FF7EAE316FD1B216EFFD0ADEELL4fromSSSgSo15IMPluginPayloadC_tFTf4nd_n
- _$sSo6IMChatCML
- _OBJC_CLASS_$_IMChat
- _OBJC_CLASS_$_IMPluginPayload
- _objc_msgSend$bundleForClass:
CStrings:
+ "/System/Library/PrivateFrameworks/IMCore.framework"
+ "@\"NSData\""
+ "@\"NSString\""
+ "@\"NSURL\""
+ "IMLitePluginPayload"
+ "T@\"NSBundle\",R,N"
+ "T@\"NSData\",R,N,V_data"
+ "T@\"NSString\",R,N,V_pluginBundleID"
+ "T@\"NSURL\",R,N,V_url"
+ "_FTOptionallyDecompressData"
+ "_pluginBundleID"
+ "_url"
+ "bundleWithPath:"
+ "enumerateAttribute:inRange:options:usingBlock:"
+ "imCoreBundle"
+ "isEqualToString:"
+ "isUpgradedAskToBuyEnabled"
+ "pluginBundleIDForBalloonBundleID:"
+ "v40@?0@\"NSURL\"8{_NSRange=QQ}16^B32"
- "bundleForClass:"
```
