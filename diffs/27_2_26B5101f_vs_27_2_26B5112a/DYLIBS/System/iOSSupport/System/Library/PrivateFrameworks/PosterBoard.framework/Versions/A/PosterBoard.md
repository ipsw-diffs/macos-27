## PosterBoard

> `/System/iOSSupport/System/Library/PrivateFrameworks/PosterBoard.framework/Versions/A/PosterBoard`

```diff

-355.2.10.100.0
-  __TEXT.__text: 0x1bd24c
-  __TEXT.__objc_methlist: 0xc87c
+355.2.12.100.0
+  __TEXT.__text: 0x1be83c
+  __TEXT.__objc_methlist: 0xc8ac
   __TEXT.__const: 0x55f4
   __TEXT.__gcc_except_tab: 0x45d0
-  __TEXT.__cstring: 0x1193e
-  __TEXT.__oslogstring: 0x1a222
+  __TEXT.__cstring: 0x1196e
+  __TEXT.__oslogstring: 0x1a532
   __TEXT.__dlopen_cstrs: 0x150
   __TEXT.__ustring: 0xe
   __TEXT.__swift5_typeref: 0x5bbe

   __TEXT.__swift_as_entry: 0x28
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x3c
-  __TEXT.__unwind_info: 0x7158
+  __TEXT.__unwind_info: 0x71b0
   __TEXT.__eh_frame: 0xa18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x48b8
+  __DATA_CONST.__const: 0x48e0
   __DATA_CONST.__objc_classlist: 0x638
   __DATA_CONST.__objc_catlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x510
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x81c0
+  __DATA_CONST.__objc_selrefs: 0x81f0
   __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x398
-  __DATA_CONST.__objc_arraydata: 0x140
-  __DATA_CONST.__got: 0x1900
+  __DATA_CONST.__objc_arraydata: 0x158
+  __DATA_CONST.__got: 0x1910
   __AUTH_CONST.__const: 0x5830
-  __AUTH_CONST.__cfstring: 0xb5c0
-  __AUTH_CONST.__objc_const: 0x2f650
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__cfstring: 0xb5e0
+  __AUTH_CONST.__objc_const: 0x2f660
+  __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH.__objc_data: 0x2920
   __AUTH.__data: 0xa80
   __DATA.__objc_ivar: 0xea4
-  __DATA.__data: 0x4a50
+  __DATA.__data: 0x4b00
   __DATA.__bss: 0x25f8
   __DATA.__common: 0xa0
   __DATA_DIRTY.__objc_data: 0x50b0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8285
-  Symbols:   13165
-  CStrings:  3444
+  Functions: 8307
+  Symbols:   13176
+  CStrings:  3453
 
Symbols:
+ +[NSUserDefaults(PBFUtilities) pbf_ambientRepairHasOccurred]
+ +[NSUserDefaults(PBFUtilities) pbf_setAmbientRepairHasOccurred:]
+ -[PBFAmbientRoleCoordinator _ambientPublishedDescriptorsForLegacyDominoProvider:]
+ -[PBFAmbientRoleCoordinator _restoreMissingLegacyDominoAmbientPostersWithChangeHandler:outEvents:]
+ ___81-[PBFAmbientRoleCoordinator _ambientPublishedDescriptorsForLegacyDominoProvider:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e49_v24?0"PBFPosterDescriptorStoreCoordinator"8^B16ls32l8s40l8
+ _objc_msgSend$_ambientPublishedDescriptorsForLegacyDominoProvider:
+ _objc_msgSend$_restoreMissingLegacyDominoAmbientPostersWithChangeHandler:outEvents:
+ _objc_msgSend$initWithOrderedSet:
+ _objc_msgSend$isEqualToOrderedSet:
+ _objc_msgSend$pbf_ambientRepairHasOccurred
+ _objc_msgSend$pbf_setAmbientRepairHasOccurred:
- GCC_except_table106
CStrings:
+ "AmbientStandByDowngradeRepairHasOccurred"
+ "[%{public}@] All legacy Domino posters confirmed present;"
+ "[%{public}@] Corrected editingBehavior on existing Clock poster against live descriptor"
+ "[%{public}@] Failed to build restored legacy Domino poster for provider %{public}@ (descriptor %{public}@): %{public}@"
+ "[%{public}@] Failed to correct editingBehavior on existing Clock poster: %{public}@"
+ "[%{public}@] Failed to reorder ambient posters after restoring legacy Domino posters: %{public}@"
+ "[%{public}@] Failed to restore missing legacy Domino poster for provider %{public}@ (descriptor %{public}@): %{public}@"
+ "[%{public}@] No extension store coordinator yet for legacy Domino provider %{public}@; will retry on a later finalize: %{public}@"
+ "[%{public}@] Restored missing legacy Domino poster for provider %{public}@ (descriptor %{public}@)"
```
