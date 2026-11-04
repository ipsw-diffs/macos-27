## CoreVideo

> `/System/Library/Frameworks/CoreVideo.framework/Versions/A/CoreVideo`

```diff

-776.2.0.0.0
-  __TEXT.__text: 0x7b424
-  __TEXT.__cstring: 0x17ed0
+780.2.0.0.0
+  __TEXT.__text: 0x7bae8
+  __TEXT.__cstring: 0x185c0
   __TEXT.__objc_databytes: 0x483
   __TEXT.__const: 0x5f1a
   __TEXT.__oslogstring: 0x253

   __TEXT.__swift5_types2: 0x8
   __TEXT.__swift5_mpenum: 0x84
   __TEXT.__dof_CVPixelBu: 0x24a
-  __TEXT.__unwind_info: 0x2890
+  __TEXT.__unwind_info: 0x2898
   __TEXT.__eh_frame: 0x864
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xe0
-  __DATA_CONST.__objc_arraydata: 0x492a0
+  __DATA_CONST.__objc_arraydata: 0x4bb60
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x5ac8
   __AUTH_CONST.__cfstring: 0x30e0

   __AUTH_CONST.__objc_dictobj: 0x14a78
   __AUTH_CONST.__objc_intobj: 0x2430
   __AUTH_CONST.__objc_arrayobj: 0x3828
-  __AUTH_CONST.__auth_got: 0x1240
+  __AUTH_CONST.__auth_got: 0x1248
   __AUTH.__objc_dataobj: 0x990
   __AUTH.__objc_databytes: 0x330
   __AUTH.__data: 0x938

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 3975
-  Symbols:   4393
-  CStrings:  1265
+  Functions: 3978
+  Symbols:   4396
+  CStrings:  1278
 
Symbols:
+ _OUTLINED_FUNCTION_5
+ _OUTLINED_FUNCTION_6
+ _dyld_program_sdk_at_least
CStrings:
+ "CVPixelBufferCreateWithBytes called for a pixel format with block height %d which is greater than 1"
+ "CVPixelBufferCreateWithBytes returning err %d because bytesPerRow %u is too small for width %u (bytesPerElement %u, elementsPerBlock %u)"
+ "CVPixelBufferCreateWithBytes returning err %d because pixel format %c%c%c%c is planar (%ld planes); use CVPixelBufferCreateWithPlanarBytes()"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because kCVPixelFormatPlanes entry is not a CFArray"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because numberOfPlanes is %d whereas kCVPixelFormatPlanes indicates %d planes"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because planeBaseAddress %p + plane size %d overflows the address space for planeIndex %d"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because planeHeight %d * planeBytesPerRow %d overflows for planeIndex %d"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because planeHeight %d is not equal to %d required by image height %d and verticalSubsampling %d for planeIndex %d"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because planeWidth %d is not equal to %d required by image width %d and horizontalSubsampling %d for planeIndex %d"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because the planes %u do not fit inside dataPtr %p .. dataPtr+dataSize (%u bytes)"
+ "CVPixelBufferCreateWithPlanarBytes returning err %d because the planes span %d bytes which does not fit inside dataSize %d"
+ "WARNING: CVPixelBufferCreateWithPlanarBytes planeHeight %d is not equal to %d required by image height %d and verticalSubsampling %d for planeIndex %d."
+ "WARNING: CVPixelBufferCreateWithPlanarBytes planeWidth %d is not equal to %d required by image width %d and horizontalSubsampling %d for planeIndex %d."
```
