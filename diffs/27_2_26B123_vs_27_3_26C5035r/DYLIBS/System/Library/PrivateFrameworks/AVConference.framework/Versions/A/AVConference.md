## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2260.15.1.0.0
-  __TEXT.__text: 0x7c3f28
+2265.2.1.0.0
+  __TEXT.__text: 0x7c4114
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x3a090
+  __TEXT.__objc_methlist: 0x3a098
   __TEXT.__const: 0x184a8
-  __TEXT.__cstring: 0x9bd3c
-  __TEXT.__oslogstring: 0x143de9
+  __TEXT.__cstring: 0x9bd3b
+  __TEXT.__oslogstring: 0x143e5f
   __TEXT.__gcc_except_tab: 0x326c
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3eb8
+  __DATA_CONST.__const: 0x3ec0
   __DATA_CONST.__objc_classlist: 0x14a0
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18630
+  __DATA_CONST.__objc_selrefs: 0x18638
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1240
   __DATA_CONST.__objc_arraydata: 0x2790

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35384
-  Symbols:   52625
-  CStrings:  33447
+  Functions: 35385
+  Symbols:   52630
+  CStrings:  33448
 
Symbols:
+ -[VCVideoStream shouldSkipVideoJitterBuffer:]
+ _kVCRateControlMachineLearningInferenceQueueSpecificKey
+ _objc_msgSend$setupLocalABTestSwitches
+ _objc_msgSend$setupLocalOnOffSwitches
+ _objc_msgSend$shouldSkipVideoJitterBuffer:
Functions:
~ __VCVideoPacketBuffer_AssembleFrame : 14620 -> 14780
~ _VideoDecoder_VTDecompressionCallback : 3668 -> 3884
~ -[VCSwitchManager initializeLocalSwitches] : 668 -> 704
~ _VCVideoCaptureServer_OnCaptureVideoFrame : 2640 -> 2636
~ -[VCRateControlMachineLearningInference initWithModelPath:] : 332 -> 352
~ -[VCRateControlMachineLearningInference dealloc] : 196 -> 232
+ -[VCVideoStream shouldSkipVideoJitterBuffer:]
~ -[VCVideoStream videoReceiverConfigWithVideoStreamConfig:] : 4552 -> 4576
~ _VCVideoCaptureServer_OnCaptureVideoFrame.cold.2 : 124 -> 120
CStrings:
+ " [%s] %s:%d SwitchManager: A/B testing turned off - using master local switch: %08X"
+ " [%s] %s:%d videoDecoder=%p decoded frame CGColorSpace attachment restored for streamID=%d width=%d height=%d"
+ "2265.2.1"
- " [%s] %s:%d SwitchManager: Non-seed build - using master local switch: %08X"
- "2260.15.1"
```
