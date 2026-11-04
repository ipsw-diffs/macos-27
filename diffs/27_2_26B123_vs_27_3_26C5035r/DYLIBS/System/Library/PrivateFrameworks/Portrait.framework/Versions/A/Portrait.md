## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Versions/A/Portrait`

```diff

-560.40.5.0.0
-  __TEXT.__text: 0x90774
+560.60.5.0.0
+  __TEXT.__text: 0x90a78
   __TEXT.__delay_helper: 0x264
   __TEXT.__objc_methlist: 0x8d3c
-  __TEXT.__const: 0x20ae8
+  __TEXT.__const: 0x20af8
   __TEXT.__cstring: 0x4ea7
-  __TEXT.__oslogstring: 0x5631
+  __TEXT.__oslogstring: 0x5661
   __TEXT.__gcc_except_tab: 0x1b7c
   __TEXT.__ustring: 0x30
   __TEXT.__unwind_info: 0x2b30

   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0x1790
   __DATA.__data: 0x10
-  __DATA.__bss: 0x210
+  __DATA.__bss: 0x218
   __DATA_DIRTY.__objc_data: 0x3160
   __DATA_DIRTY.__data: 0x788
   __DATA_DIRTY.__bss: 0x68

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3667
-  Symbols:   8221
-  CStrings:  1416
+  Functions: 3668
+  Symbols:   8223
+  CStrings:  1417
 
Symbols:
+ ___62-[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:]_block_invoke
+ _initWithData:minorVersion:.onceToken
Functions:
~ ___69-[PTCinematographyScript loadWithAsset:changesDictionary:completion:]_block_invoke.53 : 1972 -> 2060
+ ___62-[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:]_block_invoke
~ +[PTRaytracingUtils createFocusObject:anamorphicFactor:radialObstructionFactor:colorSize:circleOfConfusionReference:fNumberLimitWeight:enableFocalLengthLimits:] : 740 -> 892
~ -[PTMonocularDisparityProvider disparityForColorBuffer:timedRenderingMetadata:time:outputBuffer:] : 276 -> 372
~ -[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:] : 652 -> 912
CStrings:
+ "Repairing adaptive overscan visCropFactor %f %f"
```
