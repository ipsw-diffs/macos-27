## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/Versions/A/CoreImage`

```diff

-1667.40.3.0.0
-  __TEXT.__text: 0x34b684
-  __TEXT.__objc_methlist: 0x16098
+1667.40.5.0.0
+  __TEXT.__text: 0x34c9a8
+  __TEXT.__objc_methlist: 0x160b0
   __TEXT.__const: 0xe268
-  __TEXT.__gcc_except_tab: 0xaa6c
-  __TEXT.__cstring: 0x105a7a
-  __TEXT.__oslogstring: 0xb94e
-  __TEXT.__dlopen_cstrs: 0x3fd
+  __TEXT.__gcc_except_tab: 0xaaa4
+  __TEXT.__cstring: 0x105c5f
+  __TEXT.__oslogstring: 0xba57
+  __TEXT.__dlopen_cstrs: 0x445
   __TEXT.__runtimeheader: 0x15aa4
   __TEXT.__cikl2metal_pre: 0x54b
   __TEXT.__grain: 0x105040
   __TEXT.__cruft: 0x36d1
-  __TEXT.__unwind_info: 0xcb48
+  __TEXT.__unwind_info: 0xcbb8
   __TEXT.__eh_frame: 0x350
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4690
+  __DATA_CONST.__const: 0x46a8
   __DATA_CONST.__objc_classlist: 0x10c0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x90b0
+  __DATA_CONST.__objc_selrefs: 0x90c0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x3a0
   __DATA_CONST.__objc_arraydata: 0x1478
-  __DATA_CONST.__got: 0xb60
-  __AUTH_CONST.__const: 0x104a0
-  __AUTH_CONST.__cfstring: 0x1de40
+  __DATA_CONST.__got: 0xb68
+  __AUTH_CONST.__const: 0x10500
+  __AUTH_CONST.__cfstring: 0x1df60
   __AUTH_CONST.__objc_const: 0x2be10
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0xde0

   __AUTH_CONST.__objc_floatobj: 0x2e0
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__auth_got: 0x1848
-  __AUTH.__objc_data: 0x9880
+  __AUTH.__objc_data: 0x97e0
   __AUTH.__data: 0x277f0
   __DATA.__objc_ivar: 0x200c
   __DATA.__data: 0x6668
   __DATA.__bss: 0x3628
   __DATA.__common: 0x38
-  __DATA_DIRTY.__objc_data: 0xf00
+  __DATA_DIRTY.__objc_data: 0xfa0
   __DATA_DIRTY.__data: 0x48
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0xb28
+  __DATA_DIRTY.__bss: 0xb38
   __DATA_DIRTY.__common: 0x230
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15324
-  Symbols:   29365
-  CStrings:  9011
+  Functions: 15346
+  Symbols:   29392
+  CStrings:  9029
 
Symbols:
+ -[CIImage isMonochrome]
+ -[CIRAWFilterImpl rawSensorPattern]
+ GCC_except_table157
+ GCC_except_table162
+ GCC_except_table165
+ GCC_except_table170
+ GCC_except_table181
+ GCC_except_table184
+ GCC_except_table195
+ GCC_except_table313
+ GCC_except_table315
+ GCC_except_table339
+ GCC_except_table349
+ RawCameraLibraryCore.frameworkLibrary
+ _CIRAWFilterDownloadNotNeeded
+ _CIRAWFilterStartDownload
+ _OBJC_CLASS_$_NSLock
+ _RawCameraLibraryCore
+ _ZN2CIL25fillBlockFromDataProviderEP14CGDataProvidermP11__IOSurface
+ __CIRAWFilterStartDownload_block_invoke
+ __ZN2CI6CGNode15restore_cgimageENS_10ImageIndexENS_22ImageLeafContentDigestEP7CGImageS4_PU28objcproto17OS_dispatch_queue8NSObject
+ __ZN2CI6CGNodeC1EiNS_10ImageIndexEP7CGImageS3_NS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
+ __ZN2CI6CGNodeC2EiNS_10ImageIndexEP7CGImageS3_NS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
+ __ZN2CI7CGImage18updateDecodedImageEv
+ __ZN2CIL25fillBlockFromDataProviderEP14CGDataProvidermP11__IOSurface
+ __ZZN2CI7CGImage18updateDecodedImageEvEN3$_08__invokeEPvPKvm
+ __ZZN2CI7CGImage18updateDecodedImageEvEN3$_18__invokeEPvPKvm
+ ___CIRAWFilterDownloadNotNeeded_block_invoke
+ ___CIRAWFilterStartDownload_block_invoke
+ ___RawCameraLibraryCore_block_invoke
+ ____ZN2CIL25fillBlockFromDataProviderEP14CGDataProvidermP11__IOSurface_block_invoke
+ ___block_descriptor_48_e8_32o40b_e8_v12?0B8l
+ ___block_descriptor_56_e8_32o40b48r_e17_v16?0"NSError"8l
+ ___block_descriptor_76_e23_v16?0r^{__IOSurface=}8l
+ ___copy_helper_block_e8_32o40b48r
+ ___destroy_helper_block_e8_32o40b48r
+ ___getRCModelDownloadStartSymbolLoc_block_invoke
+ __getRCModelDownloadStartSymbolLoc_block_invoke
+ _audit_stringRawCamera
+ _getRCModelDownloadStartSymbolLoc
+ _objc_msgSend$rawSensorPattern
+ getRCModelDownloadStartSymbolLoc.ptr
- GCC_except_table158
- GCC_except_table167
- GCC_except_table171
- GCC_except_table183
- GCC_except_table216
- GCC_except_table324
- GCC_except_table360
- GCC_except_table90
- __ZL27_cgImageProviderGetPropertyP15CGImageProviderPK10__CFString
- __ZN2CI6CGNode15restore_cgimageENS_10ImageIndexENS_22ImageLeafContentDigestEP7CGImagePU28objcproto17OS_dispatch_queue8NSObject
- __ZN2CI6CGNodeC1EiNS_10ImageIndexEP7CGImageNS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
- __ZN2CI6CGNodeC2EiNS_10ImageIndexEP7CGImageNS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
- ___62-[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]_block_invoke
- ___65+[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]_block_invoke
- ___block_descriptor_60_e23_v16?0r^{__IOSurface=}8l
CStrings:
+ "%{public}s Raw demosaic filter produced no image; the decoder's on-demand resources may be unavailable."
+ "%{public}s RawCamera is not available on this platform."
+ "%{public}s Unable to soft link RCModelDownloadStart from RawCamera."
+ "+[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]"
+ "-[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]"
+ "/System/Library/CoreServices/RawCamera.bundle/Contents/MacOS/RawCamera"
+ "1667.40.5"
+ "CIRAWFilter.m"
+ "CIRAWFilterErrorDomain"
+ "Failed to access data provider bytes."
+ "Failed to download %@."
+ "NSProgress *CI_RCModelDownloadStart(uint32_t, int, void (^)(BOOL))"
+ "RCModelDownloadStart"
+ "Source data provider is nil."
+ "Timed out downloading %@."
+ "inputPattern"
+ "softlink:o:path:/System/Library/CoreServices/RawCamera.bundle/RawCamera"
+ "the RAW decoder resources"
+ "the resources required to decode this image"
+ "v16@?0@\"NSError\"8"
+ "void *RawCameraLibrary(void)"
- "1667.40.3"
- "Source image provider is nil."
- "_inputImage != nil"
```
