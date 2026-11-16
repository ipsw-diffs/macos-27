## AXAssetLoader

> `/System/Library/PrivateFrameworks/AXAssetLoader.framework/Versions/A/AXAssetLoader`

```diff

-3245.8.14.0.0
-  __TEXT.__text: 0x11858
+3245.8.23.0.0
+  __TEXT.__text: 0x11a58
   __TEXT.__objc_methlist: 0xfec
-  __TEXT.__const: 0x98
+  __TEXT.__const: 0xa0
   __TEXT.__gcc_except_tab: 0x5cc
   __TEXT.__cstring: 0xbb1
-  __TEXT.__oslogstring: 0xda9
+  __TEXT.__oslogstring: 0xe89
   __TEXT.__dlopen_cstrs: 0xa8
   __TEXT.__unwind_info: 0x6f8
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/libobjc.A.dylib
   Functions: 444
   Symbols:   1111
-  CStrings:  197
+  CStrings:  199
 
Functions:
~ -[AXAssetMetadataStore requestAssertion:] : 208 -> 508
~ -[AXImageCaptionModelAssetPolicy assetsToDownloadFromRefreshedAssets:] : 1736 -> 1948
CStrings:
+ "ImageCaptionModel download evaluation. Refreshed: %lu, installed: %lu, downloadable: %lu. Assertions held: %lu version-locked, %lu upgradable"
+ "Requested assertion for %@ from %@. Store available: %d. Assertions now held: %lu"
```
