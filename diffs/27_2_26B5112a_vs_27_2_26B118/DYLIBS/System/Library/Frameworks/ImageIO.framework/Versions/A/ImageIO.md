## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

 2851.1.8.0.0
-  __TEXT.__text: 0x3cd29c
+  __TEXT.__text: 0x3cd524
   __TEXT.__objc_methlist: 0xd68
   __TEXT.__const: 0x2b620
-  __TEXT.__gcc_except_tab: 0x1d848
-  __TEXT.__cstring: 0x780f5
+  __TEXT.__gcc_except_tab: 0x1d860
+  __TEXT.__cstring: 0x78385
   __TEXT.__oslogstring: 0x17
   __TEXT.__constg_swiftt: 0x26a4
   __TEXT.__swift5_typeref: 0x3d88

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0x14848
+  __TEXT.__unwind_info: 0x14858
   __TEXT.__eh_frame: 0x90dc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 19859
+  Functions: 19862
   Symbols:   23084
-  CStrings:  15243
+  CStrings:  15253
 
CStrings:
+ "*** ERROR: CGImagePluginInitThumbJPEGAtOffsetWithOptions offset (%ld) + size (%ld) out of range (%zu)\n"
+ "*** ERROR: decodeStripPlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: decodeTilePlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: extractImageInfo: thumbnail offset (%llu) + length (%llu) out of range (%zu)\n"
+ "*** ERROR: initThumbnail: thumbnail offset (%zu) + length (%zu) out of range (%zu)\n"
+ "*** ERROR: marker 0x%04X is out of bounds (offset %llu, length %u, size %zd) - skipping\n"
+ "*** ERROR: markerLength too big: %u  max: %zd\n"
+ "*** ERROR: short read for tag %d, count: %d\n"
+ "*** TIFFReadEncodedStrip(%d) failed - strip %d is zero-filled\n"
+ "decodeStripChunky"
+ "decodeStripPlanar"
- "*** WARNING: check markerLength: %d - expected max: %zd\n"
```
