## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/Versions/A/IconFoundation`

```diff

-793.2.2.0.0
-  __TEXT.__text: 0x3982c
+793.2.5.0.0
+  __TEXT.__text: 0x398c8
   __TEXT.__objc_methlist: 0x31ec
   __TEXT.__cstring: 0x12403
   __TEXT.__const: 0x9a8
-  __TEXT.__oslogstring: 0xc2c
+  __TEXT.__oslogstring: 0xcb9
   __TEXT.__constg_swiftt: 0x174
   __TEXT.__swift5_typeref: 0x48
   __TEXT.__swift5_fieldmd: 0xb0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1566
+  Functions: 1565
   Symbols:   3193
   CStrings:  2839
 
Functions:
~ +[IFImage createCGImageWithIFImageData:] : 656 -> 856
+ +[IFImage _layerDataFromIFImageData:].cold.2
- +[IFImage _layerDataFromIFImageData:].cold.2
- +[IFImage _layerDataFromIFImageData:].cold.4
CStrings:
+ "Failed to create cgImage from bitmap data. Data size: %lu, header size: %zu, expected bitmap size: %u, expected layer size: %u, store version: %u (expected %u), pixel size: %.0fx%.0f"
- "Failed to create cgImage from bitmap data"
```
