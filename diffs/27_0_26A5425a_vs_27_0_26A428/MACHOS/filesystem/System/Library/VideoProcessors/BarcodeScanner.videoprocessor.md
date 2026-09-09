## BarcodeScanner.videoprocessor

> `/System/Library/VideoProcessors/BarcodeScanner.videoprocessor`

### Sections with Same Size but Changed Content

- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`

```diff

 764.21.3.0.0
-  __TEXT.__text: 0x56c4
+  __TEXT.__text: 0x5634
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x358
-  __TEXT.__unwind_info: 0xe8
+  __TEXT.__unwind_info: 0x120
   __TEXT.__auth_stubs: 0x7a0
   __DATA_CONST.__got: 0x258
   __AUTH_CONST.__const: 0xa0
Functions:
~ _FigSampleBufferProcessorCreateForBarcodeScanner : 2248 -> 2236
~ _sbp_bcs_setProperty : 1368 -> 1356
~ _sbp_bcs_copyProperty : 780 -> 768
~ _sbp_bcs_setOutputCallback : 156 -> 144
~ _sbp_bcs_processSampleBuffer : 7024 -> 7012
~ _sbp_bcs_finishPendingProcessing : 144 -> 132
~ _sbp_bcs_purgeResources : 144 -> 132
~ _ensurePyramidArray : 740 -> 736
~ _clearBarcodes : 108 -> 96
~ _OUTLINED_FUNCTION_5 : 36 -> 24
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _OUTLINED_FUNCTION_8 : 44 -> 32
~ _FigDrawLumaRectangle : 428 -> 420
```
