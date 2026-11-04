## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

-1777.40.37.0.0
-  __TEXT.__text: 0x5da24c
+1777.60.14.0.1
+  __TEXT.__text: 0x5dde84
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x4f9d1
-  __TEXT.__const: 0x120ed4
-  __TEXT.__swift5_typeref: 0x13308
-  __TEXT.__swift5_reflstr: 0x12348
-  __TEXT.__swift5_assocty: 0x7ba8
-  __TEXT.__swift5_fieldmd: 0x1b13c
-  __TEXT.__constg_swiftt: 0x262b4
+  __TEXT.__cstring: 0x50141
+  __TEXT.__const: 0x121564
+  __TEXT.__swift5_typeref: 0x13356
+  __TEXT.__swift5_reflstr: 0x124a8
+  __TEXT.__swift5_assocty: 0x7c20
+  __TEXT.__swift5_fieldmd: 0x1b428
+  __TEXT.__constg_swiftt: 0x26480
   __TEXT.__swift5_protos: 0x8c0
-  __TEXT.__swift5_proto: 0x3ad8
-  __TEXT.__swift5_types: 0x2288
-  __TEXT.__swift5_types2: 0x60
+  __TEXT.__swift5_proto: 0x3b40
+  __TEXT.__swift5_types: 0x22b8
+  __TEXT.__swift5_types2: 0x64
   __TEXT.__swift5_builtin: 0x1590
   __TEXT.__swift5_capture: 0xfec
   __TEXT.__objc_methtype: 0x111
   __TEXT.__swift5_mpenum: 0x3b8
-  __TEXT.__swift_as_entry: 0x9b4
-  __TEXT.__swift_as_ret: 0xb2c
-  __TEXT.__swift_as_cont: 0x1224
+  __TEXT.__swift_as_entry: 0x9bc
+  __TEXT.__swift_as_ret: 0xb34
+  __TEXT.__swift_as_cont: 0x1234
   __TEXT.__oslogstring: 0xf0
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xb0
-  __TEXT.__eh_frame: 0x33a84
+  __TEXT.__eh_frame: 0x33c14
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3ba78
-  __DATA.__data: 0x16dc8
+  __DATA.__const: 0x3c1d0
+  __DATA.__data: 0x16e48
   __DATA.__mod_init_func: 0x40
-  __DATA.__ENDPOINTS: 0x1a84b
-  __DATA.__auth_ptr: 0x2088
+  __DATA.__ENDPOINTS: 0x1aa59
+  __DATA.__auth_ptr: 0x2090
   __DATA.__DEVICETREE: 0x18
   __DATA.__shared_cache: 0x380
   __DATA.__MMIOREGS: 0x795

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xe570
-  __DATA.__common: 0x6da
+  __DATA.__bss: 0xe580
+  __DATA.__common: 0x6aa
   __PDATA.__auth_ptr: 0x280
-  __PDATA.__const: 0x6810
+  __PDATA.__const: 0x6910
   __PDATA.__objc_imageinfo: 0x8
   __PDATA.__mod_init_func: 0x18
   __PDATA.__data: 0x2af0

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22660
+  Functions: 22721
   Symbols:   1
-  CStrings:  7257
+  CStrings:  7299
 
CStrings:
+ " LCD conversion type not supported right now"
+ " type for nits -> DBV conversion"
+ "!ctx->used"
+ "(addr - base) % slot_size == 0"
+ "(map[idx / FREE_MAP_WORD_BITS] & bit) == 0"
+ "*** error for object %p: %s\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.3.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.3.Internal.sdk/System/ExclaveCore/usr/local/standalone/RTKit/usr/include/protocols/mbi_tightbeam_protocol.h"
+ "Could not find or convert field nits-to-dbv-conversion-type in EDT"
+ "Direct nits -> DBV (log) conversion"
+ "Direct nits -> DBV (quad) conversion"
+ "Formula based conversion"
+ "Found nits-to-dbv-conversion-type field value in EDT: "
+ "I14@?0{easm_space_destroyxnucontentregion__result_s=C(?={easm_failure_s=CS})}8"
+ "I14@?0{easm_space_remapxnucontentregion__result_s=C(?={easm_failure_s=CS})}8"
+ "I24@?0Q8@?<I@?{easm_space_remapxnucontentregion__result_s=C(?={easm_failure_s=CS})}>16"
+ "I28@?0Q8I16@?<I@?{easm_space_destroyxnucontentregion__result_s=C(?={easm_failure_s=CS})}>20"
+ "Invalid backlight calibration data size or format"
+ "MFM double free"
+ "Missing required configuration for DirectNitsQuad in exbright EDT node"
+ "Nits -> DBV conversion loaded from EDT: "
+ "No EDT to read configuration from for DirectNitsQuad"
+ "No EXBright node to read configuration from for DirectNitsQuad"
+ "No backlight-exbright/backlight node to read configuration from for DirectNitsQuad"
+ "Parsed DirectNitsQuad LCD configuration: "
+ "Power assertion held: "
+ "TB_FATAL: invalid result returned from destroyXnuContentRegion (%s:%d)\n"
+ "TB_FATAL: invalid result returned from remapXnuContentRegion (%s:%d)\n"
+ "Table based conversion"
+ "Unknown nits-to-dbv-conversion-type field value: "
+ "addr - base < populated_bytes"
+ "addr >= base"
+ "carveout_permanent_kib"
+ "carveout_reclaimable_kib"
+ "carveout_total_kib"
+ "cl4_allocations_kib"
+ "destroyXnuContentRegion"
+ "free to already-freed small chunk (likely double-free)"
+ "free to empty or invalid freelist chunk (likely double-free)"
+ "free_map_acquire"
+ "free_map_release"
+ "idx < populated_slots"
+ "initialize_thread_context"
+ "invalid MFM address"
+ "invalid rawValue for EXDisplayPipeSwapAnimationKind: "
+ "ipc_buffer_free_map != NULL"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8886)"
+ "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8314)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7858)"
+ "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2217)"
+ "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5346)"
+ "nits-to-dbv-conversion-type"
+ "not an allocated MFM block"
+ "release_thread_context"
+ "remapXnuContentRegion"
+ "slot_index"
+ "thread_context_free_map != NULL"
+ "v14@?0{easm_space_destroyxnucontentregion__result_s=C(?={easm_failure_s=CS})}8"
+ "v14@?0{easm_space_remapxnucontentregion__result_s=C(?={easm_failure_s=CS})}8"
+ "vas__easm_destroy_xnu_content_region"
+ "vas__easm_remap_xnu_content_region"
- "*** error for object %p: pointer being freed was not allocated\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.2.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.2.Internal.sdk/System/ExclaveCore/usr/local/standalone/RTKit/usr/include/protocols/mbi_tightbeam_protocol.h"
- "BUG IN CLIENT OF LIBMALLOC (%llu): MTE tag mismatch"
- "BUG IN CLIENT OF LIBMALLOC (%llu): double free detected"
- "BUG IN CLIENT OF LIBMALLOC (%llu): invalid address"
- "BUG IN CLIENT OF LIBMALLOC (%llu): not an allocated block"
- "[StrictMode] .rampUp -> .steady"
- "[StrictMode] Can't use pre-wake MIB. Reporting failure."
- "[StrictMode] Disabling (enabledTs="
- "[StrictMode] Enabling (ts="
- "[StrictMode] Healthy. Disabling. MIB="
- "free to empty or invalid chunk detected (likely double-free)"
- "malloc assertion \"!memtag_config.tag_data\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8903)"
- "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8331)"
- "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7872)"
- "malloc assertion \"old_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6854)"
- "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2216)"
- "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5356)"
```
