## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/Versions/A/CoreWiFi`

```diff

-1042.8.0.0.0
-  __TEXT.__text: 0x45c074
-  __TEXT.__objc_methlist: 0x12660
+1046.2.0.0.0
+  __TEXT.__text: 0x4644bc
+  __TEXT.__objc_methlist: 0x12a98
   __TEXT.__const: 0x9bf8
-  __TEXT.__cstring: 0x2b7ee
+  __TEXT.__cstring: 0x2bebe
   __TEXT.__oslogstring: 0x20d6c
-  __TEXT.__gcc_except_tab: 0x15ec0
+  __TEXT.__gcc_except_tab: 0x160c8
   __TEXT.__dlopen_cstrs: 0x9cc
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x16b1

   __TEXT.__swift5_types: 0x1bc
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_capture: 0x1e0
-  __TEXT.__unwind_info: 0xc1d0
+  __TEXT.__unwind_info: 0xc368
   __TEXT.__eh_frame: 0x1278
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x10c8
-  __DATA_CONST.__objc_classlist: 0x418
+  __DATA_CONST.__const: 0x10d8
+  __DATA_CONST.__objc_classlist: 0x430
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x130
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9228
+  __DATA_CONST.__objc_selrefs: 0x9368
   __DATA_CONST.__objc_protorefs: 0x88
-  __DATA_CONST.__objc_superrefs: 0x3a0
-  __DATA_CONST.__objc_arraydata: 0x1e00
-  __DATA_CONST.__got: 0xa88
-  __AUTH_CONST.__const: 0x93e8
-  __AUTH_CONST.__cfstring: 0x1cba0
-  __AUTH_CONST.__objc_const: 0x18468
-  __AUTH_CONST.__objc_intobj: 0x3e58
+  __DATA_CONST.__objc_superrefs: 0x3b8
+  __DATA_CONST.__objc_arraydata: 0x1e08
+  __DATA_CONST.__got: 0xaa0
+  __AUTH_CONST.__const: 0x9478
+  __AUTH_CONST.__cfstring: 0x1d560
+  __AUTH_CONST.__objc_const: 0x18a10
+  __AUTH_CONST.__objc_intobj: 0x3e70
   __AUTH_CONST.__objc_arrayobj: 0x4c8
   __AUTH_CONST.__objc_dictobj: 0x230
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1080
   __AUTH.__objc_data: 0x50
   __AUTH.__data: 0x10
-  __DATA.__objc_ivar: 0x1594
+  __DATA.__objc_ivar: 0x15c4
   __DATA.__data: 0xe70
   __DATA.__bss: 0xeaf0
   __DATA.__common: 0x38
-  __DATA_DIRTY.__objc_data: 0x27d0
+  __DATA_DIRTY.__objc_data: 0x28c0
   __DATA_DIRTY.__data: 0x1268
   __DATA_DIRTY.__bss: 0x88
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 11129
-  Symbols:   22599
-  CStrings:  6803
+  Functions: 11221
+  Symbols:   22770
+  CStrings:  6880
 
Symbols:
+ +[CWFApple80211 convertSensingParameters:toDriverAPParams:error:]
+ +[CWFApple80211 convertSensingParametersCollection:toDriverStructure:error:]
+ +[CWFApple80211 convertSingleSensingParameter:toDriverStructure:error:]
+ +[CWFSensingParameters supportsSecureCoding]
+ +[CWFSensingParametersCollection supportsSecureCoding]
+ +[CWFSensingResult supportsSecureCoding]
+ -[CWFApple80211 csiConfig:]
+ -[CWFApple80211 csiFWStats:]
+ -[CWFAutoJoinManager meshCandidatePayloadHandler]
+ -[CWFAutoJoinManager setMeshCandidatePayloadHandler:]
+ -[CWFAutoJoinMetric coreAnalyticsUnfilteredEventPayload]
+ -[CWFAutoJoinMetric meshCandidatePayload]
+ -[CWFAutoJoinMetric setMeshCandidatePayload:]
+ -[CWFInterface configureSensing:reply:]
+ -[CWFInterface csiConfig]
+ -[CWFInterface csiFWStats]
+ -[CWFInterface csiStatsIncludingAOP2:]
+ -[CWFInterface requestAOP2CSIStats:]
+ -[CWFInterface setSensingEnabled:error:]
+ -[CWFSensingParameters .cxx_destruct]
+ -[CWFSensingParameters band]
+ -[CWFSensingParameters beaconInterval]
+ -[CWFSensingParameters channelNumber]
+ -[CWFSensingParameters copyWithZone:]
+ -[CWFSensingParameters description]
+ -[CWFSensingParameters encodeWithCoder:]
+ -[CWFSensingParameters hash]
+ -[CWFSensingParameters highPriority]
+ -[CWFSensingParameters initWithCoder:]
+ -[CWFSensingParameters init]
+ -[CWFSensingParameters isEqual:]
+ -[CWFSensingParameters isEqualToSensingParameters:]
+ -[CWFSensingParameters matchFrameType]
+ -[CWFSensingParameters matchMACAddress]
+ -[CWFSensingParameters setBand:]
+ -[CWFSensingParameters setBeaconInterval:]
+ -[CWFSensingParameters setChannelNumber:]
+ -[CWFSensingParameters setHighPriority:]
+ -[CWFSensingParameters setMatchFrameType:]
+ -[CWFSensingParameters setMatchMACAddress:]
+ -[CWFSensingParameters(Dictionary) JSONCompatibleKeyValueMap]
+ -[CWFSensingParameters(DriverConversion) convertToDriverAPParams:error:]
+ -[CWFSensingParameters(DriverConversion) convertToDriverStructure:error:]
+ -[CWFSensingParametersCollection .cxx_destruct]
+ -[CWFSensingParametersCollection copyWithZone:]
+ -[CWFSensingParametersCollection count]
+ -[CWFSensingParametersCollection csiTimeoutMs]
+ -[CWFSensingParametersCollection description]
+ -[CWFSensingParametersCollection encodeWithCoder:]
+ -[CWFSensingParametersCollection forceDualAntenna]
+ -[CWFSensingParametersCollection hash]
+ -[CWFSensingParametersCollection initWithCoder:]
+ -[CWFSensingParametersCollection initWithParameters:]
+ -[CWFSensingParametersCollection init]
+ -[CWFSensingParametersCollection isEqual:]
+ -[CWFSensingParametersCollection parameters]
+ -[CWFSensingParametersCollection setCsiTimeoutMs:]
+ -[CWFSensingParametersCollection setForceDualAntenna:]
+ -[CWFSensingParametersCollection setParameters:]
+ -[CWFSensingParametersCollection(DriverConversion) convertToDriverStructure:error:]
+ -[CWFSensingResult .cxx_destruct]
+ -[CWFSensingResult copyWithZone:]
+ -[CWFSensingResult data]
+ -[CWFSensingResult description]
+ -[CWFSensingResult encodeWithCoder:]
+ -[CWFSensingResult hash]
+ -[CWFSensingResult initWithCoder:]
+ -[CWFSensingResult isEqual:]
+ -[CWFSensingResult isEqualToSensingResult:]
+ -[CWFSensingResult setData:]
+ -[CWFSensingResult(Dictionary) JSONCompatibleKeyValueMap]
+ -[CWFXPCConnection queryCSIConfigWithRequestParams:reply:]
+ -[CWFXPCConnection queryCSIFWStatsWithRequestParams:reply:]
+ -[CWFXPCConnection queryCSIStatsIncludingAOP2:requestParams:reply:]
+ -[CWFXPCConnection requestAOP2CSIStatsWithRequestParams:reply:]
+ GCC_except_table296
+ GCC_except_table300
+ GCC_except_table306
+ GCC_except_table333
+ GCC_except_table368
+ GCC_except_table371
+ GCC_except_table406
+ GCC_except_table409
+ GCC_except_table416
+ GCC_except_table419
+ GCC_except_table422
+ GCC_except_table435
+ GCC_except_table441
+ GCC_except_table447
+ GCC_except_table452
+ GCC_except_table458
+ GCC_except_table467
+ GCC_except_table564
+ GCC_except_table570
+ GCC_except_table655
+ GCC_except_table658
+ GCC_except_table687
+ GCC_except_table691
+ GCC_except_table703
+ GCC_except_table748
+ GCC_except_table751
+ GCC_except_table754
+ GCC_except_table757
+ GCC_except_table760
+ GCC_except_table763
+ GCC_except_table793
+ GCC_except_table796
+ GCC_except_table799
+ GCC_except_table802
+ GCC_except_table805
+ GCC_except_table808
+ GCC_except_table811
+ GCC_except_table906
+ GCC_except_table909
+ GCC_except_table912
+ GCC_except_table918
+ GCC_except_table921
+ GCC_except_table924
+ GCC_except_table936
+ _CWFEventNoCsiDataBSSIDKey
+ _CWFXPCIncludeAOP2StatsKey
+ _OBJC_CLASS_$_CWFSensingParameters
+ _OBJC_CLASS_$_CWFSensingParametersCollection
+ _OBJC_CLASS_$_CWFSensingResult
+ _OBJC_IVAR_$_CWFAutoJoinManager._meshCandidatePayloadHandler
+ _OBJC_IVAR_$_CWFAutoJoinMetric._meshCandidatePayload
+ _OBJC_IVAR_$_CWFSensingParameters._band
+ _OBJC_IVAR_$_CWFSensingParameters._beaconInterval
+ _OBJC_IVAR_$_CWFSensingParameters._channelNumber
+ _OBJC_IVAR_$_CWFSensingParameters._highPriority
+ _OBJC_IVAR_$_CWFSensingParameters._matchFrameType
+ _OBJC_IVAR_$_CWFSensingParameters._matchMACAddress
+ _OBJC_IVAR_$_CWFSensingParametersCollection._csiTimeoutMs
+ _OBJC_IVAR_$_CWFSensingParametersCollection._forceDualAntenna
+ _OBJC_IVAR_$_CWFSensingParametersCollection._parameters
+ _OBJC_IVAR_$_CWFSensingResult._data
+ _OBJC_METACLASS_$_CWFSensingParameters
+ _OBJC_METACLASS_$_CWFSensingParametersCollection
+ _OBJC_METACLASS_$_CWFSensingResult
+ __OBJC_$_CLASS_METHODS_CWFApple80211
+ __OBJC_$_CLASS_METHODS_CWFSensingParameters
+ __OBJC_$_CLASS_METHODS_CWFSensingParametersCollection
+ __OBJC_$_CLASS_METHODS_CWFSensingResult
+ __OBJC_$_CLASS_PROP_LIST_CWFSensingParameters
+ __OBJC_$_CLASS_PROP_LIST_CWFSensingParametersCollection
+ __OBJC_$_CLASS_PROP_LIST_CWFSensingResult
+ __OBJC_$_INSTANCE_METHODS_CWFSensingParameters(Dictionary|DriverConversion)
+ __OBJC_$_INSTANCE_METHODS_CWFSensingParametersCollection(DriverConversion)
+ __OBJC_$_INSTANCE_METHODS_CWFSensingResult(Dictionary)
+ __OBJC_$_INSTANCE_VARIABLES_CWFSensingParameters
+ __OBJC_$_INSTANCE_VARIABLES_CWFSensingParametersCollection
+ __OBJC_$_INSTANCE_VARIABLES_CWFSensingResult
+ __OBJC_$_PROP_LIST_CWFSensingParametersCollection
+ __OBJC_CLASS_PROTOCOLS_$_CWFSensingParameters(Dictionary|DriverConversion)
+ __OBJC_CLASS_PROTOCOLS_$_CWFSensingParametersCollection
+ __OBJC_CLASS_PROTOCOLS_$_CWFSensingResult(Dictionary)
+ __OBJC_CLASS_RO_$_CWFSensingParameters
+ __OBJC_CLASS_RO_$_CWFSensingParametersCollection
+ __OBJC_CLASS_RO_$_CWFSensingResult
+ __OBJC_METACLASS_RO_$_CWFSensingParameters
+ __OBJC_METACLASS_RO_$_CWFSensingParametersCollection
+ __OBJC_METACLASS_RO_$_CWFSensingResult
+ ___25-[CWFInterface csiConfig]_block_invoke
+ ___25-[CWFInterface csiConfig]_block_invoke_2
+ ___26-[CWFInterface csiFWStats]_block_invoke
+ ___26-[CWFInterface csiFWStats]_block_invoke_2
+ ___36-[CWFInterface requestAOP2CSIStats:]_block_invoke
+ ___36-[CWFInterface requestAOP2CSIStats:]_block_invoke_2
+ ___38-[CWFInterface csiStatsIncludingAOP2:]_block_invoke
+ ___38-[CWFInterface csiStatsIncludingAOP2:]_block_invoke_2
+ ___39-[CWFInterface configureSensing:reply:]_block_invoke
+ ___39-[CWFInterface configureSensing:reply:]_block_invoke_2
+ ___39-[CWFInterface configureSensing:reply:]_block_invoke_3
+ ___39-[CWFInterface configureSensing:reply:]_block_invoke_4
+ ___39-[CWFInterface configureSensing:reply:]_block_invoke_5
+ ___40-[CWFInterface setSensingEnabled:error:]_block_invoke
+ ___40-[CWFInterface setSensingEnabled:error:]_block_invoke_2
+ ___63-[CWFXPCConnection requestAOP2CSIStatsWithRequestParams:reply:]_block_invoke
+ ___67-[CWFXPCConnection queryCSIStatsIncludingAOP2:requestParams:reply:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e17_v16?0"NSError"8l
+ _csiFWStats:.zero_addr
+ _objc_msgSend$channelNumber
+ _objc_msgSend$configureSensing:requestParams:reply:
+ _objc_msgSend$convertSensingParameters:toDriverAPParams:error:
+ _objc_msgSend$convertToDriverAPParams:error:
+ _objc_msgSend$coreAnalyticsUnfilteredEventPayload
+ _objc_msgSend$csiConfig:
+ _objc_msgSend$csiFWStats:
+ _objc_msgSend$csiTimeoutMs
+ _objc_msgSend$decodeInt32ForKey:
+ _objc_msgSend$encodeInt32:forKey:
+ _objc_msgSend$forceDualAntenna
+ _objc_msgSend$highPriority
+ _objc_msgSend$isEqualToSensingParameters:
+ _objc_msgSend$isEqualToSensingResult:
+ _objc_msgSend$matchFrameType
+ _objc_msgSend$matchMACAddress
+ _objc_msgSend$meshCandidatePayload
+ _objc_msgSend$meshCandidatePayloadHandler
+ _objc_msgSend$queryCSIConfigWithRequestParams:reply:
+ _objc_msgSend$queryCSIFWStatsWithRequestParams:reply:
+ _objc_msgSend$queryCSIStatsIncludingAOP2:requestParams:reply:
+ _objc_msgSend$requestAOP2CSIStatsWithRequestParams:reply:
+ _objc_msgSend$setBeaconInterval:
+ _objc_msgSend$setChannelNumber:
+ _objc_msgSend$setCsiTimeoutMs:
+ _objc_msgSend$setData:
+ _objc_msgSend$setForceDualAntenna:
+ _objc_msgSend$setHighPriority:
+ _objc_msgSend$setMatchFrameType:
+ _objc_msgSend$setMatchMACAddress:
+ _objc_msgSend$setMeshCandidatePayload:
+ _objc_msgSend$setMeshCandidatePayloadHandler:
+ _objc_msgSend$setSensingEnabled:requestParams:reply:
+ _objc_msgSend$updateServerSideEventRegistration:add:
- GCC_except_table219
- GCC_except_table294
- GCC_except_table305
- GCC_except_table330
- GCC_except_table374
- GCC_except_table377
- GCC_except_table380
- GCC_except_table394
- GCC_except_table397
- GCC_except_table400
- GCC_except_table407
- GCC_except_table413
- GCC_except_table417
- GCC_except_table420
- GCC_except_table423
- GCC_except_table443
- GCC_except_table449
- GCC_except_table453
- GCC_except_table456
- GCC_except_table459
- GCC_except_table461
- GCC_except_table568
- GCC_except_table571
- GCC_except_table574
- GCC_except_table664
- GCC_except_table667
- GCC_except_table681
- GCC_except_table682
- GCC_except_table685
- GCC_except_table712
- GCC_except_table745
- GCC_except_table769
- GCC_except_table772
- GCC_except_table775
- GCC_except_table778
- GCC_except_table781
- GCC_except_table784
- GCC_except_table816
- GCC_except_table819
- GCC_except_table822
- GCC_except_table825
- GCC_except_table828
- GCC_except_table831
- GCC_except_table834
CStrings:
+ "\t\"DATA_BUFFER[%ld]\" ="
+ "\t\"DATA_BUFFER_LEN[%ld]\" = %ld\n"
+ "\t\"DATA_INFO_AGC_GAIN\" = %ld\n"
+ "\t\"DATA_INFO_BSSID\" = %@\n"
+ "\t\"DATA_INFO_BW\" = %ld\n"
+ "\t\"DATA_INFO_CHANNEL\" = %ld\n"
+ "\t\"DATA_INFO_FRAME_TYPE\" = 0x%lx\n"
+ "\t\"DATA_INFO_NSTS_IN_FRAME\" = %ld\n"
+ "\t\"DATA_INFO_NSTS_REPORTED\" = %ld\n"
+ "\t\"DATA_INFO_NUM_RSSI\" = %ld\n"
+ "\t\"DATA_INFO_NUM_RX_CORES\" = %ld\n"
+ "\t\"DATA_INFO_NUM_TONES\" = %ld\n"
+ "\t\"DATA_INFO_RA\" = %@\n"
+ "\t\"DATA_INFO_RSSI[%ld]\" ="
+ "\t\"DATA_INFO_SLICE\" = %ld\n"
+ "\t\"DATA_INFO_TA\" = %@\n"
+ "\t\"DATA_TIMESTAMP[%ld]\" = %@\n"
+ "\n"
+ " %ld"
+ " 0x%08lx"
+ "(null)"
+ "<%@: %p, count=%lu, parameters=%@>"
+ "BSSID_%u"
+ "CONFIGURE SENSING"
+ "CWFApple80211ErrorDomain"
+ "Collection exceeds maximum (%d APs)"
+ "Collection is empty"
+ "IncludeAOP2Stats"
+ "Invalid MAC address format"
+ "Invalid parameters at index %lu"
+ "NULL apParams"
+ "NULL enableStruct"
+ "NUM_CSI_FW_OUT_OF_SYNC_%u"
+ "NUM_CSI_FW_PACKETS_%u"
+ "NoCsiDataBSSID"
+ "SENSING_RESULTS_DATA_BUFFER"
+ "SENSING_RESULTS_DATA_BUFFER_LEN"
+ "SENSING_RESULTS_DATA_INFO_AGC_GAIN"
+ "SENSING_RESULTS_DATA_INFO_BSSID"
+ "SENSING_RESULTS_DATA_INFO_BW"
+ "SENSING_RESULTS_DATA_INFO_CHANNEL"
+ "SENSING_RESULTS_DATA_INFO_FRAME_TYPE"
+ "SENSING_RESULTS_DATA_INFO_NSTS"
+ "SENSING_RESULTS_DATA_INFO_NUM_RSSI"
+ "SENSING_RESULTS_DATA_INFO_NUM_RX_CORES"
+ "SENSING_RESULTS_DATA_INFO_NUM_STREAMS"
+ "SENSING_RESULTS_DATA_INFO_NUM_TONES"
+ "SENSING_RESULTS_DATA_INFO_RA"
+ "SENSING_RESULTS_DATA_INFO_RSSI"
+ "SENSING_RESULTS_DATA_INFO_SLICE"
+ "SENSING_RESULTS_DATA_INFO_TA"
+ "SENSING_RESULTS_DATA_TIMESTAMP"
+ "SET SENSING ENABLED"
+ "WIFI CSI DATA"
+ "WIFI CSI NO CSI DATA"
+ "_beaconInterval"
+ "_channelNumber"
+ "_data"
+ "_highPriority"
+ "_matchFrameType"
+ "_matchMACAddress"
+ "_meshCandidatePayload"
+ "band=%d, "
+ "beaconInterval=%u, "
+ "channelNumber"
+ "channelNumber=%d, "
+ "csiTimeoutMs"
+ "data=%@\n"
+ "data={\n"
+ "forceDualAntenna"
+ "highPriority=%d"
+ "matchFrameType"
+ "matchFrameType=%d, "
+ "matchMACAddress"
+ "matchMACAddress=%@, "
+ "parameters"
+ "}\n"
```
