## CacheDelete

> `/System/Library/PrivateFrameworks/CacheDelete.framework/Versions/A/CacheDelete`

```diff

-904.40.2.0.0
-  __TEXT.__text: 0x38280
-  __TEXT.__objc_methlist: 0x1864
+904.60.1.0.1
+  __TEXT.__text: 0x3909c
+  __TEXT.__objc_methlist: 0x18bc
   __TEXT.__dlopen_cstrs: 0x56
   __TEXT.__const: 0x200
-  __TEXT.__gcc_except_tab: 0xd24
-  __TEXT.__cstring: 0x24ce
-  __TEXT.__oslogstring: 0x5c96
-  __TEXT.__unwind_info: 0xcc8
+  __TEXT.__gcc_except_tab: 0xd54
+  __TEXT.__cstring: 0x251c
+  __TEXT.__oslogstring: 0x5cd2
+  __TEXT.__unwind_info: 0xd00
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1118
+  __DATA_CONST.__objc_selrefs: 0x1140
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_arraydata: 0x200
   __DATA_CONST.__got: 0x1e8
-  __AUTH_CONST.__const: 0x13f0
-  __AUTH_CONST.__cfstring: 0x2020
-  __AUTH_CONST.__objc_const: 0x2360
+  __AUTH_CONST.__const: 0x1480
+  __AUTH_CONST.__cfstring: 0x2040
+  __AUTH_CONST.__objc_const: 0x2390
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_dictobj: 0x370
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x5e0
   __AUTH.__objc_data: 0xf0
-  __DATA.__objc_ivar: 0x170
+  __DATA.__objc_ivar: 0x174
   __DATA.__data: 0x498
   __DATA.__bss: 0x18
   __DATA_DIRTY.__objc_ivar: 0x2c
   __DATA_DIRTY.__objc_data: 0x4b0
   __DATA_DIRTY.__data: 0xc
-  __DATA_DIRTY.__bss: 0x1c0
+  __DATA_DIRTY.__bss: 0x1e8
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /System/Library/PrivateFrameworks/UserManagement.framework/Versions/A/UserManagement
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 851
-  Symbols:   1944
-  CStrings:  864
+  Functions: 866
+  Symbols:   1966
+  CStrings:  867
 
Symbols:
+ +[CDPurgeableResultCache sharedPublicPurgeableResultsCache]
+ -[CDRecentInfo coarsenDiskSpace]
+ -[CDRecentServiceInfo coarsenDiskSpace]
+ -[CDRecentVolumeInfo coarsenDiskSpace]
+ -[CDRecentVolumeInfo reduceToTotals]
+ -[CDRecentVolumeInfo setTotals:]
+ -[CDRecentVolumeInfo totals]
+ GCC_except_table2
+ GCC_except_table20
+ GCC_except_table41
+ GCC_except_table9
+ _OBJC_IVAR_$_CDRecentVolumeInfo._totals
+ ___38-[CDRecentVolumeInfo coarsenDiskSpace]_block_invoke
+ ___59+[CDPurgeableResultCache sharedPublicPurgeableResultsCache]_block_invoke
+ ____clientCachedResults_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"<CacheDeleteClientProtocol>"8l
+ ___block_descriptor_57_e8_32s40r48r_e8_v12?0i8l
+ ___block_descriptor_64_e8_32s40s48r_e5_v8?0l
+ ___publicClientCachedResults_block_invoke
+ __clientCachedResults
+ __registerPurgeableUpdates
+ _coarsenItemizedAmount
+ _objc_msgSend$coarsenDiskSpace
+ _objc_msgSend$setTotals:
+ _objc_msgSend$sharedPublicPurgeableResultsCache
+ _objc_msgSend$totals
+ _publicClientCachedResults
- GCC_except_table18
- GCC_except_table23
- ___block_descriptor_49_e8_32r40r_e8_v12?0i8l
- ___block_descriptor_56_e8_32s40r_e5_v8?0l
- ___clientCachedResults_block_invoke_2
CStrings:
+ "CACHE_DELETE_PRECOMPUTED_TOTALS"
+ "Exception (%@): Could not decode totals dict for volume: %@"
+ "com.apple.cache_delete.public_purgeable_cache"
```
