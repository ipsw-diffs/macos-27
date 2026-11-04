## Contacts

> `/System/Library/Frameworks/Contacts.framework/Versions/A/Contacts`

```diff

-3846.200.91.1.2
-  __TEXT.__text: 0x1ead80
-  __TEXT.__objc_methlist: 0x1b858
+3846.300.31.0.0
+  __TEXT.__text: 0x1ec2e8
+  __TEXT.__objc_methlist: 0x1b988
   __TEXT.__const: 0x49f0
-  __TEXT.__gcc_except_tab: 0x328c
-  __TEXT.__cstring: 0xcdb9
-  __TEXT.__dlopen_cstrs: 0xa44
-  __TEXT.__oslogstring: 0xd06a
+  __TEXT.__gcc_except_tab: 0x32f4
+  __TEXT.__cstring: 0xce49
+  __TEXT.__dlopen_cstrs: 0xaee
+  __TEXT.__oslogstring: 0xd14a
   __TEXT.__ustring: 0xe
   __TEXT.__constg_swiftt: 0x12d4
   __TEXT.__swift5_typeref: 0x1867

   __TEXT.__swift_as_entry: 0x70
   __TEXT.__swift_as_ret: 0x60
   __TEXT.__swift_as_cont: 0x98
-  __TEXT.__unwind_info: 0xb298
+  __TEXT.__unwind_info: 0xb2e8
   __TEXT.__eh_frame: 0x30c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2cf0
-  __DATA_CONST.__objc_classlist: 0x1158
+  __DATA_CONST.__const: 0x2d20
+  __DATA_CONST.__objc_classlist: 0x1168
   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0x328
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa390
+  __DATA_CONST.__objc_selrefs: 0xa448
   __DATA_CONST.__objc_protorefs: 0xf0
-  __DATA_CONST.__objc_superrefs: 0x980
+  __DATA_CONST.__objc_superrefs: 0x988
   __DATA_CONST.__objc_arraydata: 0x348
   __DATA_CONST.__got: 0x1b70
   __AUTH_CONST.__const: 0xd121
-  __AUTH_CONST.__cfstring: 0xe220
-  __AUTH_CONST.__objc_const: 0x2c4b0
+  __AUTH_CONST.__cfstring: 0xe2a0
+  __AUTH_CONST.__objc_const: 0x2c6e0
   __AUTH_CONST.__objc_intobj: 0x600
   __AUTH_CONST.__objc_arrayobj: 0x1f8
   __AUTH_CONST.__objc_dictobj: 0x230
   __AUTH_CONST.__auth_got: 0x12d0
-  __AUTH.__objc_data: 0x5560
+  __AUTH.__objc_data: 0x5600
   __AUTH.__data: 0x808
-  __DATA.__objc_ivar: 0x1224
+  __DATA.__objc_ivar: 0x1238
   __DATA.__data: 0x3930
-  __DATA.__bss: 0x6350
+  __DATA.__bss: 0x6370
   __DATA.__common: 0x98
   __DATA_DIRTY.__objc_data: 0x6368
   __DATA_DIRTY.__data: 0x50
-  __DATA_DIRTY.__bss: 0xea0
+  __DATA_DIRTY.__bss: 0xeb0
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/ClassKit.framework/Versions/A/ClassKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13704
-  Symbols:   23629
-  CStrings:  3359
+  Functions: 13730
+  Symbols:   23692
+  CStrings:  3365
 
Symbols:
+ +[CNFakeSensitiveNicknameProvider makeIfEnabled]
+ -[CNCDSaveRequestExecutor cn_persistentStoresForMeCardTracking]
+ -[CNFakeSensitiveIMNicknameProvider .cxx_destruct]
+ -[CNFakeSensitiveIMNicknameProvider allNicknamesForContact:]
+ -[CNFakeSensitiveIMNicknameProvider cn_anyHandleForContact:]
+ -[CNFakeSensitiveIMNicknameProvider contactsByRecordID]
+ -[CNFakeSensitiveIMNicknameProvider forwardingTargetForSelector:]
+ -[CNFakeSensitiveIMNicknameProvider identifiers]
+ -[CNFakeSensitiveIMNicknameProvider realProvider]
+ -[CNFakeSensitiveIMNicknameProvider setContactsByRecordID:]
+ -[CNFakeSensitiveIMNicknameProvider setIdentifiers:]
+ -[CNFakeSensitiveIMNicknameProvider setRealProvider:]
+ -[CNFakeSensitiveNicknameProvider .cxx_destruct]
+ -[CNFakeSensitiveNicknameProvider cn_makeSensitivityAnalysis]
+ -[CNFakeSensitiveNicknameProvider cn_stablePosterArchiveDataForContact:]
+ -[CNFakeSensitiveNicknameProvider fakeIMProvider]
+ -[CNFakeSensitiveNicknameProvider initWithIdentifiers:]
+ -[CNFakeSensitiveNicknameProvider realProvider]
+ -[CNFakeSensitiveNicknameProvider setFakeIMProvider:]
+ -[CNFakeSensitiveNicknameProvider setRealProvider:]
+ -[CNFakeSensitiveNicknameProvider sharedWallpaperForNickname:]
+ -[CNSharedProfileStateOracle cn_isFakeSensitiveDebugContact]
+ _OBJC_CLASS_$_CNFakeSensitiveIMNicknameProvider
+ _OBJC_CLASS_$_CNFakeSensitiveNicknameProvider
+ _OBJC_IVAR_$_CNFakeSensitiveIMNicknameProvider._contactsByRecordID
+ _OBJC_IVAR_$_CNFakeSensitiveIMNicknameProvider._identifiers
+ _OBJC_IVAR_$_CNFakeSensitiveIMNicknameProvider._realProvider
+ _OBJC_IVAR_$_CNFakeSensitiveNicknameProvider._fakeIMProvider
+ _OBJC_IVAR_$_CNFakeSensitiveNicknameProvider._realProvider
+ _OBJC_METACLASS_$_CNFakeSensitiveIMNicknameProvider
+ _OBJC_METACLASS_$_CNFakeSensitiveNicknameProvider
+ __OBJC_$_CLASS_METHODS_CNFakeSensitiveNicknameProvider
+ __OBJC_$_INSTANCE_METHODS_CNFakeSensitiveIMNicknameProvider
+ __OBJC_$_INSTANCE_METHODS_CNFakeSensitiveNicknameProvider
+ __OBJC_$_INSTANCE_VARIABLES_CNFakeSensitiveIMNicknameProvider
+ __OBJC_$_INSTANCE_VARIABLES_CNFakeSensitiveNicknameProvider
+ __OBJC_$_PROP_LIST_CNFakeSensitiveIMNicknameProvider
+ __OBJC_$_PROP_LIST_CNFakeSensitiveNicknameProvider
+ __OBJC_CLASS_RO_$_CNFakeSensitiveIMNicknameProvider
+ __OBJC_CLASS_RO_$_CNFakeSensitiveNicknameProvider
+ __OBJC_METACLASS_RO_$_CNFakeSensitiveIMNicknameProvider
+ __OBJC_METACLASS_RO_$_CNFakeSensitiveNicknameProvider
+ _descriptionForActionType:.cn_once_object_78
+ _descriptionForActionType:.cn_once_token_78
+ _descriptionForUpdateState:.cn_once_object_79
+ _descriptionForUpdateState:.cn_once_token_79
+ _objc_msgSend$cn_anyHandleForContact:
+ _objc_msgSend$cn_isFakeSensitiveDebugContact
+ _objc_msgSend$cn_makeSensitivityAnalysis
+ _objc_msgSend$cn_persistentStoresForMeCardTracking
+ _objc_msgSend$cn_stablePosterArchiveDataForContact:
+ _objc_msgSend$contactsByRecordID
+ _objc_msgSend$dataForKey:
+ _objc_msgSend$fakeIMProvider
+ _objc_msgSend$initWithDataRepresentation:error:
+ _objc_msgSend$initWithNudityDetectionValue:
+ _objc_msgSend$integerForKey:
+ _objc_msgSend$isInternalBuild
+ _objc_msgSend$makeIfEnabled
+ _objc_msgSend$mutableBytes
+ _objc_msgSend$realProvider
+ _objc_msgSend$setContactsByRecordID:
+ _objc_msgSend$setHandle:
+ _objc_msgSend$setIdentifiers:
+ _objc_msgSend$setImNicknameProvider:
+ _objc_msgSend$setRealProvider:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$stringForKey:
- GCC_except_table48
- _descriptionForActionType:.cn_once_object_76
- _descriptionForActionType:.cn_once_token_76
- _descriptionForUpdateState:.cn_once_object_77
- _descriptionForUpdateState:.cn_once_token_77
CStrings:
+ "CNFakeSensitiveNicknameProviderContentType"
+ "CNFakeSensitiveNicknameProviderEnabled"
+ "CNFakeSensitiveNicknameProviderIdentifiers"
+ "CNFakeSensitivePosterArchive."
+ "FakeSensitive debug: ignoring shared-profile action %@ (with nicknames) for %{public}@ to preserve the faked poster"
+ "FakeSensitive debug: ignoring shared-profile action %@ for %{public}@ to preserve the faked poster"
```
