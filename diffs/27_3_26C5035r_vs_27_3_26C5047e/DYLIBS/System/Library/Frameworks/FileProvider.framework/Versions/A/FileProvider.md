## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/Versions/A/FileProvider`

```diff

-4838.60.42.0.0
-  __TEXT.__text: 0x13b760
-  __TEXT.__objc_methlist: 0xe9dc
+4838.60.55.0.0
+  __TEXT.__text: 0x13bd44
+  __TEXT.__objc_methlist: 0xe9f4
   __TEXT.__const: 0x8aa
-  __TEXT.__cstring: 0x151b3
+  __TEXT.__cstring: 0x1535a
   __TEXT.__gcc_except_tab: 0x8998
   __TEXT.__oslogstring: 0xe0ea
   __TEXT.__dlopen_cstrs: 0x6ba
-  __TEXT.__ustring: 0x288
+  __TEXT.__ustring: 0x2be
   __TEXT.__swift5_typeref: 0xb4
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_reflstr: 0x45

   __TEXT.__swift_as_entry: 0x4
   __TEXT.__swift_as_ret: 0x4
   __TEXT.__swift_as_cont: 0xc
-  __TEXT.__unwind_info: 0x6ee0
+  __TEXT.__unwind_info: 0x6f08
   __TEXT.__eh_frame: 0xa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x16a0
+  __DATA_CONST.__const: 0x16a8
   __DATA_CONST.__objc_classlist: 0x690
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x2a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x70a0
+  __DATA_CONST.__objc_selrefs: 0x70b0
   __DATA_CONST.__objc_protorefs: 0x158
   __DATA_CONST.__objc_superrefs: 0x548
   __DATA_CONST.__objc_arraydata: 0xab0
   __DATA_CONST.__got: 0xb58
-  __AUTH_CONST.__const: 0x7008
-  __AUTH_CONST.__cfstring: 0x11aa0
-  __AUTH_CONST.__objc_const: 0x250f0
+  __AUTH_CONST.__const: 0x7028
+  __AUTH_CONST.__cfstring: 0x11ba0
+  __AUTH_CONST.__objc_const: 0x25120
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__auth_got: 0xf18
   __AUTH.__objc_data: 0x1a40
   __AUTH.__data: 0x10
-  __DATA.__objc_ivar: 0x10cc
+  __DATA.__objc_ivar: 0x10d0
   __DATA.__data: 0x23f0
-  __DATA.__bss: 0xbe0
+  __DATA.__bss: 0xbf0
   __DATA.__common: 0x2b
   __DATA_DIRTY.__objc_data: 0x2760
   __DATA_DIRTY.__data: 0x1

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
-  Functions: 7552
-  Symbols:   13851
-  CStrings:  4099
+  Functions: 7562
+  Symbols:   13866
+  CStrings:  4111
 
Symbols:
+ -[FPProviderDomain owningApplicationIsOffloaded]
+ -[FPProviderDomain setOwningApplicationIsOffloaded:]
+ GCC_except_table103
+ GCC_except_table111
+ _FPExcludedCloudDocsContainerQueryStringFragment
+ _FPExcludedRootContainersQueryStringFragment
+ _FPFeatureFlagIndexDomainRootLocationsIsEnabled
+ _FPIsFileProviderExtensionRecordIncludingOffloaded
+ _FPShouldOmitFileProviderIDFilter
+ _OBJC_IVAR_$_FPProviderDomain._owningApplicationIsOffloaded
+ ___fpfs_supports_offloadedDomainsAreVisible_block_invoke
+ _fpfs_supports_offloadedDomainsAreVisible
+ _fpfs_supports_offloadedDomainsAreVisible.feature_enabled
+ _fpfs_supports_offloadedDomainsAreVisible.once_token
+ _objc_msgSend$owningApplicationIsOffloaded
CStrings:
+ "%@ && %@ && %@ && (%@)"
+ "(%@) && %@"
+ "(%@) && (%@) && (%@) && (%@)"
+ "(%@) && (%@) && (%@) && (%@) && (%@) && (%@)"
+ "(%@) && (%@) && ((%@) || ((%@) && (%@)))"
+ "((%@) && %@ && %@ && %@)"
+ "((kMDItemFileProviderID != \"%s\" && kMDItemFileProviderID != \"%s\") || kMDItemFileItemID != \"*/%@\")"
+ "(FPEvictable == \"1\") && (%@)"
+ "(kMDItemFavoriteRank == \"*\" && kMDItemContentTypeTree == \"public.folder\") && (%@) && (%@) && (%@)"
+ "(kMDItemFileItemID != \"*/%@\")"
+ "(kMDItemIsShared = \"1\") && (%@) && (%@) && (%@) && (FPIsTopLevelSharedItem = \"1\") && (%@) && (%@) && (%@)"
+ "(true) && (%@)"
+ "(⏹  application offloaded)"
+ ",appOffloaded"
+ ",offloaded"
+ "4838.60.55"
+ "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
+ "BOOL FPIsAnyDocumentRecentlyUsed(NSArray<NSString *> *__strong _Nonnull, NSArray<NSString *> *__strong _Nonnull, NSArray<NSString *> *__strong _Nonnull)"
+ "DISCONNECTION_REASON_APPLICATION_OFFLOADED_%@"
+ "IndexDomainRootLocations"
+ "NSExtensionPointIdentifier"
+ "OffloadedDomainsAreVisible"
+ "_owningApplicationIsOffloaded"
- "%@ && %@ && (%@)"
- "(%@) && (%@) && (%@)"
- "(%@) && (%@) && (%@) && (%@) && (%@)"
- "(%@) && ((%@) || ((%@) && (%@)))"
- "((%@) && %@ && %@)"
- "(FPEvictable == \"1\")"
- "(kMDItemFavoriteRank == \"*\" && kMDItemContentTypeTree == \"public.folder\") && (%@) && (%@)"
- "(kMDItemIsShared = \"1\") && (%@) && (%@) && (%@) && (FPIsTopLevelSharedItem = \"1\") && (%@) && (%@)"
- "4838.60.42"
- "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
- "BOOL FPIsAnyDocumentRecentlyUsed(NSArray<NSString *> *__strong, NSArray<NSString *> *__strong, NSArray<NSString *> *__strong)"
```
