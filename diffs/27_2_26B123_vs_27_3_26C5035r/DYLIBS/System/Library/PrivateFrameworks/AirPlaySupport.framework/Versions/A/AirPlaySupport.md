## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/Versions/A/AirPlaySupport`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0xc31e8
+1015.5.1.0.0
+  __TEXT.__text: 0xc3cf0
   __TEXT.__objc_methlist: 0x374
-  __TEXT.__const: 0xf10
+  __TEXT.__const: 0x1cf0
   __TEXT.__dlopen_cstrs: 0x158
   __TEXT.__gcc_except_tab: 0x368
-  __TEXT.__cstring: 0x321f4
+  __TEXT.__cstring: 0x324cc
   __TEXT.__oslogstring: 0x1cc
-  __TEXT.__unwind_info: 0x29a0
+  __TEXT.__unwind_info: 0x29b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2718
+  __DATA_CONST.__const: 0x27a8
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x60
-  __DATA_CONST.__got: 0x650
-  __AUTH_CONST.__const: 0x4508
-  __AUTH_CONST.__cfstring: 0x71c0
+  __DATA_CONST.__got: 0x678
+  __AUTH_CONST.__const: 0x4510
+  __AUTH_CONST.__cfstring: 0x7200
   __AUTH_CONST.__objc_const: 0x7a8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x48

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2626
-  Symbols:   5034
-  CStrings:  4307
+  Functions: 2631
+  Symbols:   5057
+  CStrings:  4318
 
Symbols:
+ GCC_except_table1792
+ GCC_except_table1795
+ GCC_except_table1802
+ GCC_except_table2100
+ GCC_except_table2240
+ GCC_except_table2473
+ GCC_except_table2476
+ GCC_except_table2477
+ GCC_except_table2552
+ _APSAPAPExtensionConvertContentTypeBBufAndMergeIntoLoudnessInfoDict
+ _APSAPAPExtensionConvertLibraryLoudnessBBufAndMergeIntoLoudnessInfoDict
+ _APSAPAPExtensionConvertLoudnessInfoDictContentTypeToBBuf
+ _APSAPAPExtensionConvertLoudnessInfoDictLibraryLoudnessToBBuf
+ _AudioConverterReset
+ _kContentTypeDictionary_ContentTypeFlagsKey
+ _kContentTypeDictionary_ContentTypeKey
+ _kContentTypeDictionary_ContentTypeVersionKey
+ _kLoudnessInfoDictionary_ContentTypeKey
+ _kLoudnessInfoDictionary_LibraryLoudnessKey
+ _kSARPreWarmPackets_AACELD_48k_5_1
+ _kSARPreWarmPackets_AACELD_48k_7_1
+ _kSARPreWarmPackets_AACELD_48k_Stereo
+ _kSARPreWarm_AACELD_48k_5_1_Silence
+ _kSARPreWarm_AACELD_48k_5_1_pkt0
+ _kSARPreWarm_AACELD_48k_5_1_pkt1
+ _kSARPreWarm_AACELD_48k_7_1_Silence
+ _kSARPreWarm_AACELD_48k_7_1_pkt0
+ _kSARPreWarm_AACELD_48k_7_1_pkt1
+ _kSARPreWarm_AACELD_48k_Stereo_Silence
+ _kSARPreWarm_AACELD_48k_Stereo_pkt0
+ _kSARPreWarm_AACELD_48k_Stereo_pkt1
+ _sar_preWarmDecodeCallback
- GCC_except_table1788
- GCC_except_table1791
- GCC_except_table1794
- GCC_except_table2096
- GCC_except_table2235
- GCC_except_table2468
- GCC_except_table2471
- GCC_except_table2472
- GCC_except_table2547
CStrings:
+ "%@ Codec pre-warm done, AudioConverterReset err=%#m\n"
+ "%@ Codec pre-warm packet %u/%u size=%u: err=%#m frameCount=%u\n"
+ "APSAPAPExtensionConvertContentTypeBBufAndMergeIntoLoudnessInfoDict"
+ "APSAPAPExtensionConvertLibraryLoudnessBBufAndMergeIntoLoudnessInfoDict"
+ "APSAPAPExtensionConvertLoudnessInfoDictContentTypeToBBuf"
+ "APSAPAPExtensionConvertLoudnessInfoDictLibraryLoudnessToBBuf"
+ "MeshASQUIC"
+ "OSStatus hoseSBAR_audioHoseSetRateCallbackInternal(APSEndpointStreamAudioHoseSBARRef, uint32_t, APSAudioTransportTime, APSAudioTransportTime *, APSNetworkTime *)"
+ "[%{ptr}] Finished Rate Change (receiver anchor): -> %u. (err=%d) networkTime: %1.6f(id=%llu)\n"
+ "[%{ptr}] Finished Rate Change: %u -> %u. (err=%d) networkTime: %1.6f(id=%llu)\n"
+ "terminus"
+ "void sar_preWarmCodec(APSStreamingAudioRendererRef)"
- "[%{ptr}] Finished Rate Change: %u -> %u. (err=%d)\n"
```
