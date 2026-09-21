## libusd_ms.dylib

> `/usr/lib/usd/libusd_ms.dylib`

```diff

-24.1.31.0.0
-  __TEXT.__text: 0x29316d0
-  __TEXT.__gcc_except_tab: 0x282764
-  __TEXT.__const: 0x6533b0
-  __TEXT.__cstring: 0x2cff1c
-  __TEXT.__oslogstring: 0x1f0bf
+24.1.32.0.0
+  __TEXT.__text: 0x2932d00
+  __TEXT.__gcc_except_tab: 0x282780
+  __TEXT.__const: 0x6533d0
+  __TEXT.__cstring: 0x2d04cc
+  __TEXT.__oslogstring: 0x1f4fc
   __TEXT.__swift5_typeref: 0x5f12
   __TEXT.__constg_swiftt: 0x7980
   __TEXT.__swift5_reflstr: 0x4af9

   __TEXT.__swift5_protos: 0xb0
   __TEXT.__swift5_types2: 0x1c
   __TEXT.__swift5_capture: 0x18c
-  __TEXT.__unwind_info: 0x13b2a8
-  __TEXT.__eh_frame: 0x424e8
+  __TEXT.__unwind_info: 0x13b2f0
+  __TEXT.__eh_frame: 0x424a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xde00
+  __DATA_CONST.__const: 0xde20
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x1ef0
   __DATA_CONST.__objc_selrefs: 0x8d8
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x918
-  __AUTH_CONST.__const: 0x150538
+  __AUTH_CONST.__const: 0x1504d8
   __AUTH_CONST.__cfstring: 0x640
   __AUTH_CONST.__objc_const: 0x670
-  __AUTH_CONST.__weak_auth_got: 0xb1f8
+  __AUTH_CONST.__weak_auth_got: 0xb218
   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1c28
+  __AUTH_CONST.__auth_got: 0x1c08
   __AUTH.__data: 0x5f40
   __AUTH.__mtlx_registry: 0x2c0
   __AUTH.pxrctor: 0x40
-  __AUTH.__tf_func: 0x39a8
+  __AUTH.__tf_func: 0x39c0
   __AUTH.__thread_vars: 0x2d0
   __AUTH.__thread_data: 0x4
   __AUTH.__thread_bss: 0x44150
-  __DATA.__data: 0x559c8
-  __DATA.__bss: 0x26fdc0
-  __DATA.__common: 0x5ff8
+  __DATA.__data: 0x559e8
+  __DATA.__bss: 0x26fdd0
+  __DATA.__common: 0x6000
   __DATA_DIRTY.__mtlx_registry: 0x0
   __DATA_DIRTY.__tf_func: 0x0
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_errno.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 211253
-  Symbols:   55381
-  CStrings:  34506
+  Functions: 211256
+  Symbols:   55382
+  CStrings:  34533
 
Symbols:
+ __Z57__retain__ZN32pxrInternal__aapl__pxrReserved__9SdfBufferEPN32pxrInternal__aapl__pxrReserved__9SdfBufferE
+ __Z58__release__ZN32pxrInternal__aapl__pxrReserved__9SdfBufferEPN32pxrInternal__aapl__pxrReserved__9SdfBufferE
+ __ZN32pxrInternal__aapl__pxrReserved__22Tf_RetainReleaseHelper6retainINS_9SdfBufferEEEvPT_
+ __ZN32pxrInternal__aapl__pxrReserved__22Tf_RetainReleaseHelper7releaseINS_9SdfBufferEEEvPT_
+ __ZN32pxrInternal__aapl__pxrReserved__38SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTHE
+ __ZN32pxrInternal__aapl__pxrReserved__44SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH_valueE
+ __ZN32pxrInternal__aapl__pxrReserved__8TfRefPtrINS_9SdfBufferEE13_AddRefStaticEPNS_9TfRefBaseE
+ __ZN32pxrInternal__aapl__pxrReserved__8TfRefPtrINS_9SdfBufferEE16_RemoveRefStaticEPKNS_9TfRefBaseE
+ _dispatch_apply
- _$sSb8swiftUsdEySbSo019pxrInternal__aapl__C10Reserved__O0B13APISchemaBaseVcfC
- __ZN32pxrInternal__aapl__pxrReserved__9SdfBuffer88__synthesized_lifetimeAccessor___retain__ZN32pxrInternal__aapl__pxrReserved__9TfRefBaseEEv
- __ZN32pxrInternal__aapl__pxrReserved__9SdfBuffer89__synthesized_lifetimeAccessor___release__ZN32pxrInternal__aapl__pxrReserved__9TfRefBaseEEv
- _dispatch_group_async
- _dispatch_release
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
CStrings:
+ "19:48:22)"
+ "Failed to allocate destination images (%d x %d) for specular-glossiness to metallic-roughness conversion; aborting conversion"
+ "Generate"
+ "GetOrLoadEntryData"
+ "Image::allocate: image dimensions (%d x %d x %d) are invalid or too large; refusing to allocate to avoid integer overflow"
+ "Image::read: decoded image dimensions (%d x %d x %d) are invalid or too large; refusing to allocate to avoid integer overflow"
+ "Maximum nesting depth for container values (lists, tuples, and dictionaries) in the USDA text file format. Input nested more deeply than this is rejected as a parse error to prevent a thread-stack overflow. Values less than 1 are treated as 1."
+ "Ptex face %d has an out-of-range resolution log2 (%d, %d); skipping to avoid an out-of-bounds write."
+ "Ptex face %d tile (%d x %d) does not fit in the texture page (%d x %d); skipping to avoid an out-of-bounds write."
+ "Ptex face resolution log2 (%d x %d) exceeds the maximum packable size (%d); rejecting face by treating it as 1x1."
+ "SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH"
+ "Sep 13 2026"
+ "Unable to open private inspection stage for variant enumeration; skipping cross-layer GeomSubset check for non-default variants."
+ "Value nesting too deep (exceeds maximum depth of %zu). Increase SDF_TEXT_FILE_FORMAT_MAX_NESTING_DEPTH if this input is trusted."
+ "[SdfZipFile] pread fallback read %zu of %u bytes at file offset %u (fd=%d) — returning zero-filled buffer to preserve non-null GetFile() contract"
+ "_markMeshesWithCrossLayerSubsets-session.usda"
+ "allocate"
+ "bool adobe::usd::Image::allocate(int, int, int)"
+ "bool adobe::usd::Image::read(const ImageAsset &, int)"
+ "bool adobe::usd::processAnisotropyPixels(const Image &, const tinygltf::Image *, float, bool, const AnisotropyData &, Image &, Image &)"
+ "bool adobe::usd::processAnisotropyPixelsFromRoughness(const AnisotropyData &, const tinygltf::Image *, bool, Image &)"
+ "const char *pxrInternal__aapl__pxrReserved__::SdfZipFile::_Impl::GetOrLoadEntryData(uint32_t, uint32_t) const"
+ "nanoexr error: invalid or too-large image dimensions\n"
+ "processAnisotropyPixels"
+ "processAnisotropyPixels: failed to allocate %d x %d anisotropy level/angle images; skipping anisotropy conversion"
+ "processAnisotropyPixelsFromRoughness"
+ "processAnisotropyPixelsFromRoughness: failed to allocate %d x %d anisotropy level image; skipping anisotropy conversion"
+ "read"
+ "std::pair<size_t, bool> pxrInternal__aapl__pxrReserved__::_CountTriangles(const SdfPath &, const VtIntArray &, const VtIntArray &)"
+ "v16@?0Q8"
+ "void pxrInternal__aapl__pxrReserved__::HdStPtexMipmapTextureLoader::Block::Generate(HdStPtexMipmapTextureLoader *, PtexTexture *, unsigned char *, int, int, int)"
+ "void pxrInternal__aapl__pxrReserved__::HdStPtexMipmapTextureLoader::Block::SetSize(unsigned char, unsigned char, bool)"
- " path="
- "01:58:47)"
- "Sep  1 2026"
- "[diag] _processTexture skipped: res="
- "std::pair<int, bool> pxrInternal__aapl__pxrReserved__::_CountTriangles(const SdfPath &, const VtIntArray &, const VtIntArray &)"
```
