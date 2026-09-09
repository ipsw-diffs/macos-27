## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__AUTH_CONST.__const`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

 27062.0.0.0.0
-  __TEXT.__text: 0x5c6f0
+  __TEXT.__text: 0x5c654
   __TEXT.__const: 0x1c0a8
-  __TEXT.__cstring: 0xec26
-  __TEXT.__unwind_info: 0x1ec0
-  __TEXT.__eh_frame: 0x48
-  __DATA_CONST.__const: 0xb30
+  __TEXT.__cstring: 0xec46
+  __TEXT.__unwind_info: 0x2368
+  __TEXT.__eh_frame: 0x50
+  __DATA_CONST.__const: 0xb50
   __AUTH_CONST.__const: 0x3f18
   __AUTH.__data: 0x470
   __DATA.__data: 0x1448

   __DATA.__bss: 0xba408
   __DATA_DIRTY.__all_image_info: 0x170
   Functions: 2758
-  Symbols:   2432
-  CStrings:  1470
+  Symbols:   2433
+  CStrings:  1472
 
Symbols:
+ __ZN5dyld3L14archCacheMagicE
Functions:
~ __ZNK12PatchTableV232forEachPatchableCacheUseOfExportEjjyU13block_pointerFyjEU13block_pointerFvyN6mach_o15PointerMetaDataEybE : 484 -> 480
~ __ZNK12PatchTableV432forEachPatchableCacheUseOfExportEjjyU13block_pointerFyjEU13block_pointerFvyN6mach_o15PointerMetaDataEybE : 464 -> 460
~ ____ZNK15DyldSharedCache34forEachPatchableUseOfExportInImageEjjjU13block_pointerFvjN6mach_o15PointerMetaDataEybE_block_invoke_2 : 200 -> 196
~ __ZNK15DyldSharedCache14fixupDataPagesElb : 992 -> 988
~ __ZN5dyld317OverflowSafeArrayIjLy4294967295EE9push_backEOj : 168 -> 164
~ __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE7compareB9fqn220106EmmS3_ : 104 -> 96
~ __ZN5dyld44APIs17findImageMappedAtEPKvPPKN6mach_o12UnsafeHeaderEPbPPKcPS2_PyPhPPKNS_6LoaderE : 924 -> 936
~ __ZZN5dyld44APIs11dlopen_fromEPKciPvENK3$_0clEv : 1852 -> 1848
~ __ZN3lsl6VectorIPKN5dyld46LoaderEE12reserveExactEy : 360 -> 356
~ __ZZZN5dyld44APIs11dlopen_fromEPKciPvENK3$_0clEvENKUlvE_clEv : 3228 -> 3248
~ __ZN3lsl6VectorINSt3__14pairIPKN5dyld46LoaderEPKcEEE12reserveExactEy : 376 -> 372
~ __ZN3lsl6VectorI18AuthenticatedValueIPN5dyld411PseudoDylibEEE5eraseENS6_15CheckedIteratorIS5_EE : 164 -> 172
~ __ZN3lsl6VectorI18AuthenticatedValueIPN5dyld411PseudoDylibEEE5eraseENS6_15CheckedIteratorIS5_EES8_ : 264 -> 260
~ ____ZN5dyld412RuntimeState19addDynamicReferenceEPKNS_6LoaderES3__block_invoke : 180 -> 192
~ __ZN3lsl6VectorIN5dyld412RuntimeState17MissingFlatSymbolEE5eraseENS4_15CheckedIteratorIS3_EES6_ : 284 -> 280
~ __ZN5dyld317OverflowSafeArrayIN5dyld412RuntimeState15PermanentRanges5RangeELy4294967295EE9push_backERKS4_ : 172 -> 168
~ __ZN5dyld412RuntimeState18notifyDebuggerLoadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 620 -> 624
~ __ZN3lsl6VectorIN5dyld423ExternallyViewableState9ImageInfoEE12reserveExactEy : 396 -> 392
~ __ZN5dyld412RuntimeState10notifyLoadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 940 -> 932
~ __ZN3lsl6VectorIN5dyld412RuntimeState16DynamicReferenceEE5eraseENS4_15CheckedIteratorIS3_EES6_ : 256 -> 252
~ __ZZN5dyld412RuntimeState28rebindMissingFlatLazySymbolsERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEEENK3$_0clERKNS0_17MissingFlatSymbolE : 300 -> 296
~ __ZN3lsl6VectorI18AuthenticatedValueIPKN5dyld46LoaderEEE12reserveExactEy : 396 -> 392
~ __ZN5dyld317OverflowSafeArrayIN5dyld412RuntimeState15PermanentRanges5RangeELy4294967295EE6resizeEy : 160 -> 156
~ ____ZZN5dyld412RuntimeState16setObjCNotifiersENS_16ReadOnlyCallbackIPFvPKcPK11mach_headerEEENS1_IPFvS6_PvS6_PKvEEENS1_IPFvPK29_dyld_objc_notify_mapped_infoEEENS1_IPFvjSI_U13block_pointerFvjEEEEENK3$_0clEv_block_invoke : 1384 -> 1380
~ __ZN5dyld423ExternallyViewableState9addImagesERN3lsl9AllocatorES3_RKNSt3__14spanINS0_9ImageInfoELm18446744073709551615EEE : 1156 -> 1152
~ __ZN3lsl6VectorI15dyld_image_infoE12reserveExactEy : 396 -> 392
~ __ZNK5dyld416JustInTimeLoader11matchesPathERKNS_12RuntimeStateEPKc : 228 -> 232
~ __ZN5dyld317OverflowSafeArrayIPKcLy4294967295EE9push_backERKS2_ : 168 -> 164
~ ____ZN5dyld416JustInTimeLoader14loadDependentsER11DiagnosticsRNS_12RuntimeStateERKNS_6Loader11LoadOptionsE_block_invoke : 948 -> 952
~ __ZN5dyld317OverflowSafeArrayIN5dyld46Loader21MissingFlatLazySymbolELy4294967295EE9push_backEOS3_ : 168 -> 164
~ __ZN5dyld317OverflowSafeArrayIjLy4294967295EE7reserveEy : 152 -> 148
~ __ZN5dyld317OverflowSafeArrayINS_7MapBaseIPKvbN5dyld411HashPointerENS4_12EqualPointerEE9NodeImplTILb0EEELy4294967295EE7reserveEy : 152 -> 148
~ __ZN5dyld317OverflowSafeArrayIPKvLy4294967295EE11verifySpaceEy : 156 -> 152
~ __ZN5dyld317OverflowSafeArrayIPKcLy4294967295EE6resizeEy : 160 -> 156
~ __ZN3lsl6VectorIN5dyld420ObjCClassReplacementEE12reserveExactEy : 380 -> 376
~ __ZN5dyld46Loader16addWeakDefsToMapERNS_12RuntimeStateERKNSt3__14spanIPKS0_Lm18446744073709551615EEE : 260 -> 256
~ __ZN5dyld46Loader9interposeERNS_12RuntimeStateEmPKS0_ : 504 -> 516
~ ____ZNK5dyld46Loader27applyCachePatchesToOverrideERNS_12RuntimeStateEPKS0_tPKNS0_10DylibPatchERNS_34DyldCacheDataConstLazyScopedWriterE_block_invoke_2 : 680 -> 692
~ __ZN5dyld317OverflowSafeArrayINS_7MapBaseIPKcN5dyld415WeakDefMapValueENS_11HashCStringENS_12EqualCStringEE9NodeImplTILb0EEELy4294967295EE9push_backEOSA_ : 204 -> 200
~ __ZN5dyld317OverflowSafeArrayINS_7MapBaseIPKcN5dyld415WeakDefMapValueENS_11HashCStringENS_12EqualCStringEE9NodeImplTILb0EEELy4294967295EE7reserveEy : 172 -> 168
~ __ZN3lsl9Allocator7reallocEPvy : 156 -> 148
~ __ZN5dyld415PremappedLoader4makeERNS_12RuntimeStateEPKN6mach_o12UnsafeHeaderEPKcbbt : 1012 -> 1020
~ __ZN5dyld3L18preflightCacheFileERKNS_18SharedCacheOptionsEPNS_19SharedCacheLoadInfoEPNS_9CacheInfoEiPNSt3__15arrayIA32_cLm128EEEPKS3_ : 1176 -> 1200
~ ____ZN5dyld3L26verboseSharedCacheMappingsEPK15DyldSharedCache_block_invoke : 76 -> 80
~ ___liblibc_memset : 224 -> 240
~ ___liblibc_format_string : 1292 -> 1288
~ _parse_floating_point : 1104 -> 1092
~ _write_field : 248 -> 216
~ _write_char_n : 232 -> 236
~ _write_string : 260 -> 268
~ _OUTLINED_FUNCTION_0 : 12 -> 16
~ _OUTLINED_FUNCTION_4 : 16 -> 20
~ _OUTLINED_FUNCTION_7 : 20 -> 16
~ _OUTLINED_FUNCTION_8 : 20 -> 16
~ _OUTLINED_FUNCTION_11 : 16 -> 20
~ _OUTLINED_FUNCTION_12 : 16 -> 20
~ __insecure_random_buf : 232 -> 216
~ ___strlcpy_chk : 280 -> 272
~ ___liblibc_fwrite_locked : 540 -> 536
~ _dbgserial_message_decode : 300 -> 292
~ _macho_get_vm_base : 132 -> 128
~ _macho_get_vm_limit : 76 -> 72
~ _vas_perthread_fill : 1472 -> 1468
~ ___thread_local_ipc_buffer : 120 -> 116
~ __trace_fill : 244 -> 236
~ __thread_info_backtrace : 544 -> 536
~ __ZNK6mach_o11BindOpcodes11forEachBindEU13block_pointerFv7CStringibhybiS1_bxbRbE : 1900 -> 1876
~ __ZNK6mach_o11ExportsTrie23terminalPayloadToSymbolE7CStringNSt3__14spanIKhLm18446744073709551615EEERNS_6SymbolE : 928 -> 912
~ __ZNK6mach_o13PathToIntTrie7hasPathE7CStringRj : 188 -> 180
~ __ZNK6mach_o21FunctionVariantFixups12forEachFixupEU13block_pointerFvNS0_13InternalFixupEE : 88 -> 80
~ __ZNK6mach_o5Image13linkeditBytesENS_6Header13LinkEditRangeE : 172 -> 180
~ __ZNK6mach_o13RebaseOpcodes13forEachRebaseEU13block_pointerFv7CStringibhyRbE : 1344 -> 1336
~ ___ZNK6mach_o12UnsafeHeader8fileSizeEv_block_invoke.426 : 60 -> 56
CStrings:
+ "dyld_v1  arm64e"
+ "dyld_v1arm64ex1"
```
