## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/Versions/A/FileProvider`

```diff

-4838.41.1.0.0
-  __TEXT.__text: 0x13b6b8
-  __TEXT.__objc_methlist: 0xe9c4
+4838.60.42.0.0
+  __TEXT.__text: 0x13b760
+  __TEXT.__objc_methlist: 0xe9dc
   __TEXT.__const: 0x8aa
-  __TEXT.__cstring: 0x15146
+  __TEXT.__cstring: 0x151b3
   __TEXT.__gcc_except_tab: 0x8998
   __TEXT.__oslogstring: 0xe0ea
   __TEXT.__dlopen_cstrs: 0x6ba
-  __TEXT.__ustring: 0x25a
+  __TEXT.__ustring: 0x288
   __TEXT.__swift5_typeref: 0xb4
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_reflstr: 0x45

   __TEXT.__swift_as_entry: 0x4
   __TEXT.__swift_as_ret: 0x4
   __TEXT.__swift_as_cont: 0xc
-  __TEXT.__unwind_info: 0x6ed8
+  __TEXT.__unwind_info: 0x6ee0
   __TEXT.__eh_frame: 0xa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1698
+  __DATA_CONST.__const: 0x16a0
   __DATA_CONST.__objc_classlist: 0x690
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x2a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7090
+  __DATA_CONST.__objc_selrefs: 0x70a0
   __DATA_CONST.__objc_protorefs: 0x158
   __DATA_CONST.__objc_superrefs: 0x548
   __DATA_CONST.__objc_arraydata: 0xab0
   __DATA_CONST.__got: 0xb58
   __AUTH_CONST.__const: 0x7008
-  __AUTH_CONST.__cfstring: 0x11a40
-  __AUTH_CONST.__objc_const: 0x250c0
+  __AUTH_CONST.__cfstring: 0x11aa0
+  __AUTH_CONST.__objc_const: 0x250f0
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__auth_got: 0xf18
   __AUTH.__objc_data: 0x1a40
   __AUTH.__data: 0x10
-  __DATA.__objc_ivar: 0x10c8
+  __DATA.__objc_ivar: 0x10cc
   __DATA.__data: 0x23f0
-  __DATA.__bss: 0xbd0
+  __DATA.__bss: 0xbe0
   __DATA.__common: 0x2b
   __DATA_DIRTY.__objc_data: 0x2760
   __DATA_DIRTY.__data: 0x1

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
-  Functions: 7549
-  Symbols:   13846
-  CStrings:  4094
+  Functions: 7552
+  Symbols:   13851
+  CStrings:  4099
 
Symbols:
+ -[FPProviderDomain owningApplicationIsInstallationHeld]
+ -[FPProviderDomain setOwningApplicationIsInstallationHeld:]
+ _OBJC_IVAR_$_FPProviderDomain._owningApplicationIsInstallationHeld
+ _fpfs_is_seed_build.is_seed_build
+ _objc_msgSend$owningApplicationIsInstallationHeld
Functions:
+ sub_195f28f8c
~ _fpfs_is_seed_build : 52 -> 56
~ ___fpfs_is_seed_build_block_invoke : 4 -> 16
~ ___fpfs_supports_tap_to_feedback_block_invoke : 96 -> 104
~ -[FPProviderDomain description] : 1552 -> 1588
~ -[FPProviderDomain initWithCoder:] : 1516 -> 1536
~ -[FPProviderDomain encodeWithCoder:] : 940 -> 960
~ -[FPProviderDomain localizedDisconnectionBannerText] : 436 -> 420
~ -[FPProviderDomain isHidden] : 76 -> 88
- -[FPProviderDomain setSupportedSearchFilters:]
+ -[FPProviderDomain setSupportedSearchFilters:]
- -[FPProviderDomain setDomainUserInfo:]
+ -[FPProviderDomain setDomainUserInfo:]
- -[FPProviderDomain setProgress:]
+ -[FPProviderDomain setDomain:]
- -[FPProviderDomain setPurposeIdentifier:]
+ -[FPProviderDomain purposeIdentifier]
+ -[FPProviderDomain setVersion:]
+ -[FPProviderDomain setShouldHideDomainDisplayName:]
~ _FPConnectionStateToPrettyString : 280 -> 292
CStrings:
+ "(⏹  installation held)"
+ ",appHeld"
+ ",installationHeld"
+ "4838.60.42"
+ "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
+ "DISCONNECTION_REASON_INSTALLATION_HELD_%@"
+ "_owningApplicationIsInstallationHeld"
- "4838.41.1"
- "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
```
