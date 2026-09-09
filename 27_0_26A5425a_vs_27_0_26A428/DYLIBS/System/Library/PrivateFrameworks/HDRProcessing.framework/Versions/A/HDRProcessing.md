## HDRProcessing

> `/System/Library/PrivateFrameworks/HDRProcessing.framework/Versions/A/HDRProcessing`

```diff

 1.517.51.0.0
-  __TEXT.__text: 0xab8ac
+  __TEXT.__text: 0xab6ec
   __TEXT.__objc_methlist: 0x2588
   __TEXT.__const: 0x4c88
-  __TEXT.__gcc_except_tab: 0x29cc
+  __TEXT.__gcc_except_tab: 0x29bc
   __TEXT.__oslogstring: 0x10e92
   __TEXT.__cstring: 0x837f
-  __TEXT.__unwind_info: 0x1608
+  __TEXT.__unwind_info: 0x1600
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
Functions:
~ -[MSRHDRProcessing updatePolynomialTables:TableSize:] : 112 -> 116
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_01:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 1512 -> 1508
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_02:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 3220 -> 3208
~ -[DISPHDRProcessing setDisplayManagementParametricConfig:HDRControl:] : 612 -> 624
~ -[HDRProcessor initProcessingEngine:config:] : 1604 -> 1616
~ -[HDRBackwardDisplayManagement createMetadataTexture] : 532 -> 524
~ -[HDRBackwardDisplayManagement encodeToCommandBuffer:video:videoSrcRegion:videoDstRegion:ui:uiSrcRegion:uiDstRegion:backgroundColor:output:frameProperties:] : 6564 -> 6544
~ -[MSRHDRProcessingT2 updatePolynomialTablesForComponent:Component:TableSize:] : 112 -> 116
~ __ZN16EDRMetaData_RBSP16rpu_data_mappingEjj : 1992 -> 2024
~ __ZN16EDRMetaData_RBSP12rpu_data_nlqEjj : 1368 -> 1340
~ __ZN16EDRMetaData_RBSP29rpu_data_el_chroma_resamplingEjj : 280 -> 276
~ __ZN16EDRMetaData_RBSP22rpu_data_mapping_paramEjjjj : 2404 -> 2432
~ __ZN16EDRMetaData_RBSP40rpu_data_chroma_resampling_filter_2D_expEjjj : 572 -> 592
~ __ZN16EDRMetaData_RBSP45rpu_data_chroma_resampling_filter_2D_exp_coefEjjjj : 272 -> 288
~ __ZN16EDRMetaData_RBSP45rpu_data_chroma_resampling_filter_1D_exp_coefEjjjj : 236 -> 244
~ __ZN16EDRMetaData_RBSP38rpu_data_spatial_resampling_filter_expEjjj : 284 -> 276
~ -[DolbyVisionComposer embeddedSetupEncoderForCommandBuffer:DMData:dmConfig:isInput422:hasThreeOutputPlane:isSdrOnDolbyOrHDR10:isHDR10OnHDR10TV:isDolbyOnHDR10TV:isHDR10OnDolby:isHDR10OnPad:isHLGOnPad:isDoviOnPad:isDoviOnLLDovi:isHDR10OnLLDovi:isHLGOnHDR10TV:isHLGOnDolbyTV:isHLGOnLLDovi:isPtvMode:orientation:isDolby84:dovi50toHDR10TVMode:isDM4:isGpuTmRefMode:] : 7372 -> 6820
~ -[DolbyVisionComposer embeddedSetupEncoderForGpuMatchMsrCommandBuffer:DMData:dmConfig:isInput422:orientation:isDolby84:dovi50toHDR10TVMode:isDM4:dpcParam:tcControl:hdrControl:isHDR10Content:isHLGContent:isDOVIContent:] : 3216 -> 3220
~ -[DolbyVisionDM4 applyL9:] : 576 -> 572
~ -[DolbyVisionDM4 DmProcess:Height:bufI:bufU:bufV:] : 296 -> 308
~ _SMPTE_ST_2094_50_EncodeSyntaxElementsToBinaryData : 916 -> 912
~ __ZL14packHCUInPlaceP13NSMutableDataPK29hcuApiHdrConfigurationUnitsV3 : 424 -> 428
~ __ZN9HDRConfig15ReadConfigEntryE11HDRConfigID : 1460 -> 1468
~ -[DolbyVisionDisplayManagement setDisplayManagementToneMappingConfigFromMetaData:config:tcCtrl:hdrCtrl:auxData:dpcParam:] : 14132 -> 14136
~ _applyAmveB2DAdaptationS_C : 136 -> 140
~ -[HistBasedToneMapping computeFrameAvgFromHistData] : 72 -> 76
~ -[HistBasedToneMapping computeFrameStdFromHistData] : 84 -> 88
~ -[MSRHDRProcessingByCapabilities updatePolynomialTablesForComponent:Component:TableSize:] : 124 -> 128
~ -[HDRMetadataManager multiviewAddDoViHDMIMetadata:width:height:priority:] : 2232 -> 2224
~ _hdrpMetadataReconstruction : 5752 -> 5796
~ -[DolbyVisionMR metadataReconstruction:dmData:maxDisplayBrightnessNits:targetMaxNits:targetMinNits:displayPrimaries:baseMax:baseMin:videoFullRangeFlag:colourPrimaries:matrixCoeffs:numFrames:] : 6628 -> 6616
~ _Dm4Tc : 3848 -> 3836
```
