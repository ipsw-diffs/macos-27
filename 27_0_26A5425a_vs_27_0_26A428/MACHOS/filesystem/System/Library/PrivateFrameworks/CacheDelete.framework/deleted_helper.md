## deleted_helper

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 904.0.7.0.0
-  __TEXT.__text: 0x87ec
-  __TEXT.__auth_stubs: 0x5d0
+  __TEXT.__text: 0x88dc
+  __TEXT.__auth_stubs: 0x5e0
   __TEXT.__objc_stubs: 0x6a0
   __TEXT.__objc_methlist: 0x1cc
   __TEXT.__const: 0x174

   __TEXT.__objc_classname: 0x40
   __TEXT.__objc_methname: 0x6c6
   __TEXT.__objc_methtype: 0xc5
-  __TEXT.__cstring: 0x5b5
-  __TEXT.__oslogstring: 0x19be
-  __TEXT.__unwind_info: 0x170
-  __DATA_CONST.__const: 0x460
-  __DATA_CONST.__cfstring: 0x460
+  __TEXT.__cstring: 0x603
+  __TEXT.__oslogstring: 0x1a30
+  __TEXT.__unwind_info: 0x1b8
+  __DATA_CONST.__const: 0x4a0
+  __DATA_CONST.__cfstring: 0x4a0
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_intobj: 0x30
-  __DATA_CONST.__objc_arraydata: 0x30
+  __DATA_CONST.__objc_arraydata: 0x40
   __DATA_CONST.__objc_dictobj: 0x78
-  __DATA_CONST.__auth_got: 0x2f8
+  __DATA_CONST.__objc_arrayobj: 0x18
+  __DATA_CONST.__auth_got: 0x300
   __DATA_CONST.__got: 0x70
   __DATA.__objc_const: 0x488
   __DATA.__objc_selrefs: 0x238

   - /System/Library/PrivateFrameworks/CacheDelete.framework/Versions/A/CacheDelete
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 88
-  Symbols:   319
-  CStrings:  279
+  Functions: 89
+  Symbols:   323
+  CStrings:  285
 
Symbols:
+ _OBJC_CLASS_$_NSConstantArray
+ ___block_descriptor_32_e51_B24?0r*8^{?=BBqiIQQQ{timespec=qq}{timespec=qq}B}16l
+ ___periodic_block_invoke
+ _os_variant_has_internal_diagnostics
Functions:
~ -[CDCloneAnalyzer .cxx_destruct] : 68 -> 56
~ _fsPurgeable : 1568 -> 1556
~ _fsPurge : 3760 -> 3748
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ __main_block_invoke.83 : 2480 -> 2484
~ __main_block_invoke.97 : 548 -> 536
~ ___main_block_invoke_2 : 212 -> 712
~ ___RegisterCacheDeleteOrphanDirHandlerService_block_invoke : 104 -> 92
~ ___RegisterPurgeSpecificAppsService_block_invoke : 104 -> 92
~ __RegisterPurgeSpecificAppsService_block_invoke.147 : 104 -> 92
~ _analyzePurgeableRecordsForApps : 5716 -> 5704
~ ___copy_helper_block_e8_32s40s48s56s64r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64r : 88 -> 76
~ __RegisterPurgeSpecificAppsService_block_invoke.160 : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64s72r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56s64s72r : 96 -> 84
~ _buildPurgeResult : 1124 -> 1112
~ _adjustBundleSizesForClones : 836 -> 824
~ __purge_orphans_block_invoke.196 : 100 -> 88
~ ___fsPurgeable_block_invoke : 236 -> 224
~ _fsPurgeableSingleVolume : 1148 -> 1136
~ ___copy_helper_block_e8_32s40s48s56s64s72s80r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r : 104 -> 92
~ ___copy_helper_block_e8_32s40s48s56s64s72s80r88r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r88r : 116 -> 104
+ ___periodic_block_invoke
~ +[CacheDeletePruner prunerWithFileAge:dirAge:] : 76 -> 64
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
CStrings:
+ "/Library/AutoBugCapture/"
+ "/Library/Logs/AutoBugCapture/"
+ "Customer build, clearing %@"
+ "com.apple.cache_delete"
+ "customerReleaseBuild IS INTERNAL BUILD"
+ "customerReleaseBuild IS NOT INTERNAL BUILD"
+ "customerReleaseBuild IS NOT SEED BUILD"
- "customerReleaseBuild IS SEED BUILD"
```
