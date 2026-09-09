## VDCAssistant

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/Current/Resources/VDC.plugin/Contents/Resources/VDCAssistant`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 520.21.1.0.0
-  __TEXT.__text: 0x6eb9c
+  __TEXT.__text: 0x6e1d4
   __TEXT.__auth_stubs: 0x19f0
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__init_offsets: 0x4

   __TEXT.__cstring: 0x18ea2
   __TEXT.__oslogstring: 0x1401c
   __TEXT.__objc_methname: 0xd6
-  __TEXT.__unwind_info: 0x1dc0
+  __TEXT.__unwind_info: 0x2698
   __DATA_CONST.__const: 0x20c8
   __DATA_CONST.__cfstring: 0xc60
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __ZN4CMIO3DPA3VDC6Server11RollSupport6DeviceD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server11RollSupport6Device15GetFeatureStateEjRNS1_12ControlStateE : 212 -> 200
~ __ZN4CMIO3DPA3VDC6Server14DeleteTexturesERNS2_11TextureListE : 132 -> 120
~ __ZN4CMIO3DPA3VDC6Server14CreateTexturesERNS2_11TextureListERNSt3__15dequeIPNS2_11NativeFrameENS5_9allocatorIS8_EEEEb : 556 -> 572
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _GLOBAL__sub_I_GL_FrameTextures.cpp : 136 -> 124
~ __ZN4CMIO3PTA23IsochronousThreadForUSB5ResetEPP23IOUSBInterfaceStruct800 : 368 -> 356
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_2 : 36 -> 24
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ __Z11DrawRectYCcPhS_jjjjjjjht : 532 -> 536
~ __Z11DrawRectYCcPjjjjjjjj : 272 -> 276
~ __Z11DrawRectYCcPjjjjjjjjd : 592 -> 580
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ ____ZN7CMIOVDC12SystemStatus10updateDataE13audit_token_tPK10__CFStringb_block_invoke : 120 -> 108
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ __ZN4CMIO3DPA3VDC6Server7TextureD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server7Texture18TextureDataChangedEv : 60 -> 48
~ __ZN4CMIO3DPA3VDC6Server7Texture18TextureDataChangedEPKvmmj : 64 -> 52
~ __ZN4CMIO3DPA3VDC6Server7Texture18TextureDataChangedEPKvmm : 112 -> 100
~ __ZN4CMIO3DPA3VDC6Server10GPUProgram10SetProgramEjPKc : 368 -> 356
~ __ZNK4CMIO3DPA3VDC6Server14GPUProgramList10SetProgramEi : 208 -> 196
~ __ZN4CMIO3DPA3VDC6Server11GPURenderer6RenderEv : 220 -> 208
~ __ZNSt3__16vectorIPN4CMIO3DPA3VDC6Server7TextureENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 196 -> 192
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _OUTLINED_FUNCTION_8 : 24 -> 12
~ __ZNK9CACFArray13GetCACFStringEjR10CACFString : 168 -> 156
~ __ZNK9CACFArray12GetCACFArrayEjRS_ : 188 -> 176
~ __ZNK9CACFArray17GetCACFDictionaryEjR14CACFDictionary : 188 -> 176
~ __ZNK14CACFDictionary13GetCACFStringEPK10__CFStringR10CACFString : 144 -> 132
~ __ZNK14CACFDictionary12GetCACFArrayEPK10__CFStringR9CACFArray : 164 -> 152
~ __ZNK14CACFDictionary17GetCACFDictionaryEPK10__CFStringRS_ : 164 -> 152
~ __ZN27CACFDistributedNotification11AddObserverEPKvPFvP22__CFNotificationCenterPvPK10__CFStringS1_PK14__CFDictionaryES7_32CFNotificationSuspensionBehavior : 92 -> 80
~ __ZN27CACFDistributedNotification14RemoveObserverEPKvPK10__CFString : 68 -> 56
~ __ZN27CACFDistributedNotification16PostNotificationEPK10__CFStringPK14__CFDictionaryb : 92 -> 80
~ __ZN12CACFMachPortD0Ev : 56 -> 44
~ __ZN12CACFMachPort14ReceiveMessageEjP17mach_msg_header_tj : 128 -> 116
~ __ZN20CACFLocalMessagePortD0Ev : 56 -> 44
~ __ZN20CACFLocalMessagePort16SetDispatchQueueEP16dispatch_queue_s : 88 -> 76
~ __ZN21CACFRemoteMessagePortD0Ev : 56 -> 44
~ __ZN21CACFRemoteMessagePort16SetDispatchQueueEP16dispatch_queue_s : 88 -> 76
~ __ZN15CACFPreferences9CopyValueEPK10__CFStringbb : 152 -> 140
~ __ZN15CACFPreferences8SetValueEPK10__CFStringPKvbbb : 168 -> 156
~ __ZN15CACFPreferences11DeleteValueEPK10__CFStringbbb : 176 -> 164
~ __ZN7CAGuardD2Ev : 88 -> 76
~ __ZN7CAGuardD0Ev : 56 -> 44
~ __ZN7CAGuard9WaitUntilEy : 264 -> 252
~ __ZN7CAMutexD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU28Filter_ThresholdedChromaBlur9RunShaderENS5_8EProgramEii : 100 -> 88
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU28Filter_ThresholdedChromaBlur7ProcessEifb : 188 -> 176
~ __ZN4CMIO3DPA3VDC6Server5Wave26DeviceD2Ev : 296 -> 284
~ __ZN4CMIO3DPA3VDC6Server5Wave26DeviceD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server5Wave26Device19InitializeShadowMapEv : 324 -> 312
~ __ZN4CMIO3DPA3VDC6Server5Wave26Device20AllocateGPUResourcesERKNS2_6Device11FrameFormatEll : 240 -> 228
~ __ZN4CMIO3DPA3VDC6Server5Wave26Device18DeleteGPUResourcesEv : 112 -> 100
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeI4RectNS_3mapIjN4CMIO3DPA3VDC20ProbeControlSettingsENS_4lessIjEENS1_INS_4pairIKjS9_EEEEEEEEPvEEEEEclB9nqe220106EPSJ_ : 96 -> 84
~ _OUTLINED_FUNCTION_6 : 28 -> 16
~ _OUTLINED_FUNCTION_7 : 28 -> 16
~ _OUTLINED_FUNCTION_9 : 12 -> 20
~ _OUTLINED_FUNCTION_10 : 20 -> 12
~ _OUTLINED_FUNCTION_11 : 32 -> 20
~ __ZN4CMIO3DPA3VDC6Server11NativeFrameD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server11NativeFrame11AppendBytesEPhm : 1112 -> 1108
~ __ZN4CMIO3DPA3VDC6Server12CaptureFrameD0Ev : 108 -> 96
~ __ZN4CMIO3DPA3VDC6Server16FrameAccumulator12DisposePoolsEv : 156 -> 144
~ __ZN4CMIO3DPA3VDC6Server16FrameAccumulator20ReprimeStillCapturesEPNS2_12CaptureFrameE : 704 -> 692
~ __ZN4CMIO3CVA5Pixel6BufferD0Ev : 56 -> 44
~ __ZN4CMIO3CVA5Image6BufferD0Ev : 56 -> 44
~ __ZN4CMIO3CVA6BufferD0Ev : 56 -> 44
~ __ZN4CMIO3CVA5Image6BufferD2Ev : 120 -> 108
~ __ZN4CMIO3CVA5Pixel6BufferD2Ev : 120 -> 108
~ __ZN4CMIO3CVA5Pixel10BufferPoolD0Ev : 56 -> 44
~ __ZN4CMIO2SA5CacheD0Ev : 56 -> 44
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJRKjEEEPjDpOT_ : 196 -> 192
~ __ZN4CMIO3CMA12SampleBufferD0Ev : 56 -> 44
~ _OUTLINED_FUNCTION_26 : 36 -> 24
~ _OUTLINED_FUNCTION_28 : 32 -> 20
~ __ZN4CMIO3DPA3VDC6Server9Assistant16SetMIGServerPortEj : 188 -> 176
~ __ZN4CMIO3DPA3VDC6Server9Assistant10DisconnectEj : 360 -> 340
~ __ZN4CMIO3DPA3VDC6Server9Assistant10ClientDiedEj : 1468 -> 1448
~ __ZN4CMIO3DPA3VDC6Server9Assistant7GetNameEyPtPj : 296 -> 288
~ __ZN4CMIO3DPA3VDC6Server9Assistant13GetVendorNameEyPtPj : 296 -> 288
~ __ZN4CMIO3DPA3VDC6Server9Assistant19GetNonLocalizedNameEyPtPj : 296 -> 288
~ __ZN4CMIO3DPA3VDC6Server9Assistant12GetClientPIDEj : 256 -> 236
~ __ZN4CMIO3DPA3VDC6Server9Assistant11StartStreamEjyj13audit_token_t : 1604 -> 1584
~ __ZN4CMIO3DPA3VDC6Server9Assistant22UpdateClientAuditTokenEj13audit_token_t : 272 -> 252
~ __ZN4CMIO3DPA3VDC6Server9Assistant19GetClientAuditTokenEj : 300 -> 280
~ __ZN4CMIO3DPA3VDC6Server9Assistant27GeneralInterestNotificationEjjPv : 248 -> 236
~ __ZN4CMIO3DPA3VDC6Server9Assistant33InitializeSystemPowerNotificationEv : 104 -> 92
~ ___main_block_invoke_2 : 60 -> 48
~ __Z17CMIODPAVDCConnectjiPj : 64 -> 52
~ __Z20CMIODPAVDCStopStreamjy : 64 -> 52
~ __Z17CMIODPAVDCGetNamejyPtPj : 80 -> 68
~ __Z23CMIODPAVDCGetVendorNamejyPtPj : 80 -> 68
~ __Z29CMIODPAVDCGetNonLocalizedNamejyPtPj : 80 -> 68
~ __Z25CMIODPAVDCGetFrameFormatsjyPPN4CMIO3DPA3VDC11FrameFormatEPj : 80 -> 68
~ __Z30CMIODPAVDCGetStillImageFormatsjyPPN4CMIO3DPA3VDC16StillImageFormatEPj : 80 -> 68
~ __Z27CMIODPAVDCGetStillImageDatajyjPPhPj : 88 -> 76
~ __Z27CMIODPAVDCGetFrameIntervalsjyjPPjS_ : 88 -> 76
~ __Z22CMIODPAVDCGetFrameTypejyPj : 64 -> 52
~ __Z22CMIODPAVDCSetFrameTypejyj : 80 -> 68
~ __Z26CMIODPAVDCGetFrameIntervaljyPj : 64 -> 52
~ __Z26CMIODPAVDCSetFrameIntervaljyj : 80 -> 68
~ __Z26CMIODPAVDCGetFormatForTypejyjPN4CMIO3DPA3VDC11FrameFormatE : 80 -> 68
~ __Z31CMIODPAVDCSetPreferredFrameTypejyj : 80 -> 68
~ __Z31CMIODPAVDCSetPreferredFrameRatejyd : 80 -> 68
~ __Z26CMIODPAVDCSetControlsStatejyjPN4CMIO3DPA3VDC12ControlStateEj : 108 -> 96
~ __ZN4CMIO3DPA3VDC6Server9Assistant11CameraNamesD2Ev : 76 -> 64
~ __ZNSt3__16vectorIN4CMIO4IOKA6ObjectENS_9allocatorIS3_EEE16__destroy_vectorclB9nqe220106Ev : 132 -> 120
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeIyN4CMIO3DPA3VDC6Server9Assistant11CameraNamesEEEPvEEEEEclB9nqe220106EPSC_ : 116 -> 104
~ __ZNSt3__16vectorIN4CMIO4IOKA6ObjectENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS3_EEEPS3_DpOT_ : 288 -> 284
~ _OUTLINED_FUNCTION_20 : 24 -> 12
~ _OUTLINED_FUNCTION_22 : 32 -> 20
~ __ZN4CMIO3DPA3VDC6Server12ClientStreamD0Ev : 56 -> 44
~ _OUTLINED_FUNCTION_3 -> _OUTLINED_FUNCTION_2 : 32 -> 20
~ __ZN4CMIO3DPA3VDC6Server9USBClient43DoesWaveCameraSupportVendorSpecificControlsEPh : 936 -> 928
~ __ZN4CMIO3AII6BufferD0Ev : 56 -> 44
~ _OUTLINED_FUNCTION_13 : 36 -> 24
~ _OUTLINED_FUNCTION_18 : 32 -> 20
~ _OUTLINED_FUNCTION_24 : 32 -> 20
~ _OUTLINED_FUNCTION_26 : 28 -> 16
~ _OUTLINED_FUNCTION_27 : 32 -> 20
~ _OUTLINED_FUNCTION_29 : 28 -> 16
~ _OUTLINED_FUNCTION_31 : 32 -> 20
~ _OUTLINED_FUNCTION_32 : 28 -> 16
~ _OUTLINED_FUNCTION_33 : 24 -> 12
~ _OUTLINED_FUNCTION_36 : 24 -> 12
~ _OUTLINED_FUNCTION_38 : 24 -> 12
~ __ZN4CMIO2DS4Both5MutexD0Ev : 56 -> 44
~ __ZN4CMIO2DS4Both5GuardD0Ev : 56 -> 44
~ __ZN4CMIO2DS4Both5Guard9WaitUntilEyRb : 340 -> 328
~ _OUTLINED_FUNCTION_4 : 28 -> 16
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ _OUTLINED_FUNCTION_10 : 24 -> 12
~ __ZN4CMIO3DPA3VDC6Server6Device9PostEventENS2_11DeviceEventEm : 268 -> 256
~ __ZN4CMIO3DPA3VDC6Server6DeviceD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server6Device27TrimResolutionsOrFrameRatesEv : 1864 -> 1860
~ __ZN4CMIO3DPA3VDC6Server6Device15GetFeatureStateEjRNS1_12ControlStateE : 1920 -> 1900
~ __ZN4CMIO3DPA3VDC6Server6Device17InsertTestPatternEPvjjbb : 712 -> 732
~ __ZN4CMIO3DPA3VDC6Server6Device12DeviceDetachEv : 148 -> 136
~ __ZN4CMIO3DPA3VDC6Server6Device30SendPropertyChangeNotificationENS_15PropertyAddressE : 228 -> 216
~ __ZN4CMIO3DPA3VDC6Server6Device12DeviceUnplugEv : 156 -> 144
~ __ZN4CMIO3DPA3VDC6ServerL28PreviousStateTransitionGuardENSt3__110shared_ptrINS2_11DeviceStateEEES6_NS2_11DeviceEventEPvm : 180 -> 184
~ __ZN4CMIO3DPA3VDC6ServerL23StreamingStateExitGuardENSt3__110shared_ptrINS2_11DeviceStateEEES6_NS2_11DeviceEventEPvm : 364 -> 368
~ __ZNSt3__16vectorIN4CMIO15PropertyAddressENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 252 -> 244
~ __ZNSt3__16vectorINS_4pairIN4CMIO3DPA3VDC6Server11DeviceEventEmEENS_9allocatorIS7_EEE24__emplace_back_slow_pathIJS7_EEEPS7_DpOT_ : 196 -> 192
~ __ZNSt3__15dequeINS_10shared_ptrIN4CMIO3DPA3VDC6Server11DeviceStateEEENS_9allocatorIS7_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPNS_10shared_ptrIN4CMIO3DPA3VDC6Server11DeviceStateEEENS_9allocatorIS8_EEE12emplace_backIJRS8_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPNS_10shared_ptrIN4CMIO3DPA3VDC6Server11DeviceStateEEERNS_9allocatorIS8_EEE12emplace_backIJS8_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__16vectorINS_10unique_ptrIN4CMIO3DPA3VDC6Server21DeviceStateTransitionENS_14default_deleteIS6_EEEENS_9allocatorIS9_EEE16__destroy_vectorclB9nqe220106Ev : 132 -> 120
~ __ZNSt3__119__shared_weak_count16__release_sharedB9nqe220106Ev : 100 -> 88
~ __ZNSt3__15dequeINS_10shared_ptrIN4CMIO3DPA3VDC6Server11DeviceStateEEENS_9allocatorIS7_EEE8pop_backEv : 112 -> 104
~ __ZNSt3__120__shared_ptr_emplaceIN4CMIO3DPA3VDC6Server11DeviceStateENS_9allocatorIS5_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN4CMIO3DPA3VDC6Server11DeviceStateENS_9allocatorIS5_EEE16__on_zero_sharedEv : 68 -> 56
~ __ZNSt3__16vectorINS_10shared_ptrIN4CMIO3DPA3VDC6Server11DeviceStateEEENS_9allocatorIS7_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ _OUTLINED_FUNCTION_15 : 32 -> 20
~ _OUTLINED_FUNCTION_18 : 28 -> 16
~ _OUTLINED_FUNCTION_19 : 32 -> 20
~ _OUTLINED_FUNCTION_20 : 24 -> 12
~ __ZN4CMIO3DPA3VDC6Server7iBridge6DeviceD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server7iBridge6Device20InitializePropertiesEv : 244 -> 232
~ __ZN4CMIO3DPA3VDC6Server7iBridge6Device22GetFeatureCapabilitiesEjRNS1_12ControlStateE : 268 -> 256
~ __ZN4CMIO3DPA3VDC6Server7iBridge6Device15GetFeatureStateEjRNS1_12ControlStateE : 516 -> 504
~ _OUTLINED_FUNCTION_8 : 32 -> 20
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21EnableFragmentProgramEj : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU27EnableFragmentProgramStringEPKc : 264 -> 240
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU3FBOD0Ev : 56 -> 44
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU3FBO6UnbindEv : 56 -> 44
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU3FBO8ReadBackERNS2_7TextureEb : 304 -> 292
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU3FBO6RenderEv : 220 -> 208
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU16Filter_Bilateral9RunShaderERKNS4_9BLF_ParmsENS4_14BLFShadersEnum8EProgramEii : 192 -> 180
~ _OUTLINED_FUNCTION_4 : 36 -> 24
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ __ZN4CMIO2DS4Both13DispatchQueueD0Ev : 56 -> 44
~ __ZNK4CMIO2DS4Both13DispatchQueue8DispatchEbU13block_pointerFvvE : 184 -> 160
~ __ZNK4CMIO2DS4Both13DispatchQueue8DispatchEyU13block_pointerFvvE : 108 -> 84
~ __ZNK4CMIO2DS4Both13DispatchQueue8DispatchEbPvPFvS3_E : 204 -> 180
~ __ZNK4CMIO2DS4Both13DispatchQueue8DispatchEyPvPFvS3_E : 132 -> 108
~ __ZN4CMIO2DS4Both13DispatchQueue15Dispatch_GlobalElbU13block_pointerFvvE : 208 -> 184
~ __ZN4CMIO2DS4Both13DispatchQueue15Dispatch_GlobalElyU13block_pointerFvvE : 136 -> 112
~ __ZN4CMIO2DS4Both13DispatchQueue15Dispatch_GlobalElbPvPFvS3_E : 212 -> 188
~ __ZN4CMIO2DS4Both13DispatchQueue15Dispatch_GlobalElyPvPFvS3_E : 148 -> 124
~ __ZN4CMIO2DS4Both13DispatchQueue28InitializeGlobalSerialQueuesEPv : 156 -> 144
~ __ZNSt3__16vectorIN4CMIO2DS4Both13DispatchQueue11EventSourceENS_9allocatorIS5_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__16vectorIN4CMIO2DS4Both13DispatchQueue11EventSourceENS_9allocatorIS5_EEE24__emplace_back_slow_pathIJS5_EEEPS5_DpOT_ : 284 -> 280
~ _OUTLINED_FUNCTION_6 : 28 -> 16
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU3BLF11GLSLProgramD0Ev : 56 -> 44
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU3BLF11GLSLProgram10UseProgramEv : 140 -> 128
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU17SetShaderSamplingERKNS4_3BLF11GLSLProgramEffff : 156 -> 144
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU24Filter_Bilateral_Shaders6RenderEiiRKNS4_9BLF_ParmsEi : 752 -> 744
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU24Filter_Bilateral_Shaders6RenderEiii : 160 -> 148
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU12GammaTexture10ResetGammaEv : 100 -> 88
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU12Filter_GammaD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU12Filter_Gamma7ProcessEv : 128 -> 116
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU14FrameProcessor17ProcessImageFrameERNS2_11NativeFrameERKNS1_26Wave2CameraAncillaryDataV3ERKNS5_10ParametersE : 4888 -> 4868
~ _OUTLINED_FUNCTION_12 : 28 -> 16
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU17DeleteGLSLProgramEPvS5_S5_ : 72 -> 60
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReductionD0Ev : 56 -> 44
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReduction16EnableGLSL_pass1Efff : 488 -> 476
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReduction16EnableGLSL_pass2Ev : 264 -> 252
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU18GetMotionThresholdEdi : 324 -> 316
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReduction13ProcessPackedEdiNS5_7EFormatE : 576 -> 564
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReduction13ProcessPlanarEdi : 596 -> 584
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU21Filter_NoiseReduction8ReadBackERNS2_7TextureE : 88 -> 76
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU11GLSLProgramD0Ev : 56 -> 44
~ __ZNK4CMIO3DPA3VDC6Server5Wave23GPU11GLSLProgram10UseProgramEv : 140 -> 128
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU17SetShaderSamplingERKNS4_11GLSLProgramEffff : 156 -> 144
~ __ZN4CMIO3DPA3VDC6Server5Wave23GPU38Render_YCbCr_422_ThresholdedChromaBlurEiiifi : 312 -> 300
~ ___ZN4CMIO3DPA3VDC6Server9Assistant15UpdateTCCAccessEjy13audit_token_t_block_invoke.26.cold.1 : 84 -> 72
~ ___ZN4CMIO3DPA3VDC6Server9Assistant15UpdateTCCAccessEjy13audit_token_t_block_invoke.26.cold.2 : 84 -> 72
```
