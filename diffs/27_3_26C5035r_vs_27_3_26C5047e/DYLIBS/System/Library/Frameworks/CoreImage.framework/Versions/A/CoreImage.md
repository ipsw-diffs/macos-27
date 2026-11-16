## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/Versions/A/CoreImage`

```diff

-1667.60.2.0.0
-  __TEXT.__text: 0x34d324
-  __TEXT.__objc_methlist: 0x160b0
+1667.60.3.0.0
+  __TEXT.__text: 0x34f4a0
+  __TEXT.__objc_methlist: 0x160d0
   __TEXT.__const: 0xe268
-  __TEXT.__gcc_except_tab: 0xaac4
-  __TEXT.__cstring: 0x105c24
-  __TEXT.__oslogstring: 0xba57
+  __TEXT.__gcc_except_tab: 0xab24
+  __TEXT.__cstring: 0x105d2f
+  __TEXT.__oslogstring: 0xbbf8
   __TEXT.__dlopen_cstrs: 0x445
   __TEXT.__runtimeheader: 0x15aa4
   __TEXT.__cikl2metal_pre: 0x54b
   __TEXT.__grain: 0x105040
   __TEXT.__cruft: 0x36d1
-  __TEXT.__unwind_info: 0xcbb8
+  __TEXT.__unwind_info: 0xcc10
   __TEXT.__eh_frame: 0x350
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x90c0
+  __DATA_CONST.__objc_selrefs: 0x90e8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x3a0
   __DATA_CONST.__objc_arraydata: 0x1478
   __DATA_CONST.__got: 0xb68
   __AUTH_CONST.__const: 0x10500
-  __AUTH_CONST.__cfstring: 0x1df60
-  __AUTH_CONST.__objc_const: 0x2be10
+  __AUTH_CONST.__cfstring: 0x1dfa0
+  __AUTH_CONST.__objc_const: 0x2be30
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0xde0
   __AUTH_CONST.__objc_dictobj: 0x3e8

   __AUTH_CONST.__auth_got: 0x1848
   __AUTH.__objc_data: 0x97e0
   __AUTH.__data: 0x277f0
-  __DATA.__objc_ivar: 0x200c
+  __DATA.__objc_ivar: 0x2010
   __DATA.__data: 0x6668
-  __DATA.__bss: 0x3628
+  __DATA.__bss: 0x3638
   __DATA.__common: 0x38
   __DATA_DIRTY.__objc_data: 0xfa0
   __DATA_DIRTY.__data: 0x48

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15347
-  Symbols:   28820
-  CStrings:  9027
+  Functions: 15361
+  Symbols:   28841
+  CStrings:  9033
 
Symbols:
+ -[CIKernelLibrary fallbackLibraryForFunctionName:]
+ -[CIKernelLibrary sliceLibraries]
+ -[CIKernelLibrary stitchableLibraryForFunctionName:]
+ GCC_except_table156
+ GCC_except_table211
+ GCC_except_table229
+ GCC_except_table236
+ GCC_except_table408
+ GCC_except_table417
+ GCC_except_table494
+ _CIMetalDeviceSupportsDynamicLibraries
+ _CIMetalFunctionImportsCoreImageDylib
+ _CI_SIMULATE_NO_METAL_DYLIB_SUPPORT
+ _OBJC_IVAR_$_CIKernelLibrary._slice_libraries
+ __ZGVZ34CI_SIMULATE_NO_METAL_DYLIB_SUPPORTE1v
+ __ZL25applyMetalUserAnnotationsP15CIKernelLibraryPKcRjRN2CI11PixelFormatE
+ __ZN18CIKernelReflection38reflectLegacyWithStitchableAnnotationsEP15CIKernelLibraryS1_PKcPP7NSError
+ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZL21fatMetalLibrarySlicesP6NSDataE3$_0P20FatMetalLibrarySliceLb0EEEvT1_S8_T0_NS_15iterator_traitsIS8_E15difference_typeEb
+ __ZNSt3__119__allocate_at_leastB9nqn220106INS_9allocatorI20FatMetalLibrarySliceEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__127__insertion_sort_incompleteB9nqn220106INS_17_ClassicAlgPolicyERZL21fatMetalLibrarySlicesP6NSDataE3$_0P20FatMetalLibrarySliceEEbT1_S8_T0_
+ __ZNSt3__16vectorI20FatMetalLibrarySliceNS_9allocatorIS1_EEE20__throw_length_errorB9nqn220106Ev
+ __ZNSt3__16vectorI20FatMetalLibrarySliceNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_
+ __ZNSt3__17__sort5B9nqn220106INS_17_ClassicAlgPolicyERZL21fatMetalLibrarySlicesP6NSDataE3$_0P20FatMetalLibrarySliceLi0EEEvT1_S8_S8_S8_S8_T0_
+ __ZZ34CI_SIMULATE_NO_METAL_DYLIB_SUPPORTE1v
+ _objc_msgSend$fallbackLibraryForFunctionName:
+ _objc_msgSend$initWithContentsOfURL:options:error:
+ _objc_msgSend$sliceLibraries
+ _objc_msgSend$stitchableLibraryForFunctionName:
+ _objc_msgSend$subdataWithRange:
- GCC_except_table129
- GCC_except_table146
- GCC_except_table227
- GCC_except_table231
- GCC_except_table234
- GCC_except_table406
- GCC_except_table415
- GCC_except_table492
CStrings:
+ "1667.60.3"
+ "CI_SIMULATE_NO_METAL_DYLIB_SUPPORT"
+ "Kernel '%{public}s' links CoreImage.metallib but this device does not support dynamic libraries."
+ "Kernel '%{public}s' links CoreImage.metallib which this device does not support. Using the non-stitchable version of the function from another slice of the library."
+ "Kernel '%{public}s': the non-stitchable version in another slice of the library does not have the same signature as the stitchable one, so it is not used."
+ "Kernel links the Core Image Metal dynamic library, which is not supported on this GPU, and its non-stitchable version has a different signature."
+ "Kernel links the Core Image Metal dynamic library, which is not supported on this GPU."
- "1667.60.2"
```
