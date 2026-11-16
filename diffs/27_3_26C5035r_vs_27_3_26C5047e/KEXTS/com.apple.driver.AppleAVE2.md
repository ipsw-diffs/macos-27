## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

```diff

-913.63.1.0.0
+913.71.1.0.0
   __TEXT.__const: 0x4b6c0
-  __TEXT.__cstring: 0x48caf
-  __TEXT.__os_log: 0x5db03
-  __TEXT_EXEC.__text: 0x1d1d48
+  __TEXT.__cstring: 0x49173
+  __TEXT.__os_log: 0x5df09
+  __TEXT_EXEC.__text: 0x1d28c8
   __TEXT_EXEC.__auth_stubs: 0x7b0
   __DATA.__data: 0x2c8
   __DATA.__common: 0x130

   __DATA_CONST.__got: 0xe0
   __DATA_CONST.__auth_ptr: 0x8
   Functions: 2998
-  Symbols:   11826
-  CStrings:  9911
+  Symbols:   11841
+  CStrings:  9936
 
Symbols:
+ __Z25AVE_CalcBufNumOfLFSOutput15_E_AVE_WorkType14_E_AVE_DevTypeibb
+ __Z26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkType16_E_AVE_MCTF_Modebiib
+ __ZZ16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutjiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKcE11_os_log_fmt__28_
+ __ZZ18AVE_Client_PrepareP13_S_AVE_ClientP14_S_AVE_TimeOutP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKcE11_os_log_fmt__11_
+ __ZZ22AVE_Prop_Cfg_AV1_PrintP19_S_AVE_Prop_Cfg_AV1jiPKciE11_os_log_fmt__280_
+ __ZZ22AVE_Prop_Cfg_AV1_PrintP19_S_AVE_Prop_Cfg_AV1jiPKciE11_os_log_fmt__281_
+ __ZZ22AVE_Prop_Cfg_AVC_PrintP19_S_AVE_Prop_Cfg_AVCjiPKciE11_os_log_fmt__276_
+ __ZZ22AVE_Prop_Cfg_AVC_PrintP19_S_AVE_Prop_Cfg_AVCjiPKciE11_os_log_fmt__277_
+ __ZZ23AVE_Prop_Cfg_HEVC_PrintP20_S_AVE_Prop_Cfg_HEVCjiPKciE11_os_log_fmt__364_
+ __ZZ23AVE_Prop_Cfg_HEVC_PrintP20_S_AVE_Prop_Cfg_HEVCjiPKciE11_os_log_fmt__365_
+ __ZZ25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMSE11_os_log_fmt_1
+ __ZZ26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkType16_E_AVE_MCTF_ModebiibE11_os_log_fmt
+ __ZZ26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_StartE11_os_log_fmt_3
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_5
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_6
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_7
+ __ZZ28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_PrepareE11_os_log_fmt_1
+ __ZZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiiP25_S_AVE_DistributedRCStatsE11_os_log_fmt_3
- __Z25AVE_CalcBufNumOfLFSOutput15_E_AVE_WorkTypeibb
- __Z26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkTypebiib
- __ZZ26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkTypebiibE11_os_log_fmt
Functions:
~ __Z28AVE_Work_GGM_CalcSurfaceInfoP13_S_AVE_ClientP15_S_AVE_DLB_UnitP21_S_AVE_SurfaceInfoSet : 620 -> 628
~ __ZN9AVE_FwLog10PrintEntryExx : 1792 -> 1812
~ __Z21AVE_Prop_Cfg_AV1_InitP19_S_AVE_Prop_Cfg_AV1y : 600 -> 608
~ __Z22AVE_Prop_Cfg_AV1_PrintP19_S_AVE_Prop_Cfg_AV1jiPKci : 37548 -> 37808
~ __Z20AVE_CalcBufSizeOfDPB14_E_AVE_DevType14_E_AVE_EncTypeiiii12_E_ChromaFmtbPi : 1964 -> 2088
~ __Z25AVE_CalcBufNumOfLFSOutput15_E_AVE_WorkTypeibb -> __Z25AVE_CalcBufNumOfLFSOutput15_E_AVE_WorkType14_E_AVE_DevTypeibb : 56 -> 92
~ __Z26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkTypebiib -> __Z26AVE_CalcBufSizeOfLRSOutput14_E_AVE_DevType15_E_AVE_WorkType16_E_AVE_MCTF_Modebiib : 468 -> 560
~ __Z27AVE_CalcBufSizeOfMCTFOutput14_E_AVE_DevTypebiii12_E_ChromaFmtbPi : 1056 -> 1148
~ __Z25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMS : 624 -> 844
~ __Z28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 1408 -> 2140
~ __Z17AVE_Client_VerifyP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 752 -> 756
~ __Z18AVE_Client_PrepareP13_S_AVE_ClientP14_S_AVE_TimeOutP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 2644 -> 2888
~ __Z16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutjiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 7796 -> 8052
~ __Z18AVE_Client_ProcessP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1988 -> 2004
~ __Z16AVE_Client_ResetP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1664 -> 1668
~ __Z28AVE_Work_MSC_CalcSurfaceInfoP13_S_AVE_ClientP15_S_AVE_DLB_UnitP21_S_AVE_SurfaceInfoSet : 968 -> 992
~ __Z21AVE_Prop_Cfg_AVC_InitP19_S_AVE_Prop_Cfg_AVCy : 588 -> 584
~ __Z22AVE_Prop_Cfg_AVC_PrintP19_S_AVE_Prop_Cfg_AVCjiPKci : 36344 -> 36592
~ __Z29AVE_Work_MCTF_CalcSurfaceInfoP13_S_AVE_ClientP15_S_AVE_DLB_UnitP21_S_AVE_SurfaceInfoSet : 2316 -> 1968
~ __ZN7AVE_HwC15ProcessIntr_CmdEmij : 6580 -> 6520
~ __Z22AVE_Prop_Cfg_HEVC_InitP20_S_AVE_Prop_Cfg_HEVCy : 676 -> 668
~ __Z23AVE_Prop_Cfg_HEVC_PrintP20_S_AVE_Prop_Cfg_HEVCjiPKci : 48784 -> 49044
~ __ZN12AVE_Pipeline6FindMDEy : 68 -> 60
~ __ZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiiP25_S_AVE_DistributedRCStats : 1368 -> 1612
~ __Z28AVE_Work_Enc_CalcSurfaceInfoP13_S_AVE_ClientP15_S_AVE_DLB_UnitP21_S_AVE_SurfaceInfoSet : 2956 -> 2984
~ __Z29AVE_Work_LRME_CalcSurfaceInfoP13_S_AVE_ClientP15_S_AVE_DLB_UnitP21_S_AVE_SurfaceInfoSet : 720 -> 732
~ __Z28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_Prepare : 492 -> 716
~ __Z26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_Start : 936 -> 1152
CStrings:
+ "%lld %d AVE %s: %p %lld MachThreadPriorityForThreadEmittingFrames %d"
+ "%lld %d AVE %s: %p %lld MachThreadPriorityForThreadEmittingFrames %d\n"
+ "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld\n"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %lld %lld (range: [0,%d])"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %lld %lld (range: [0,%d])\n"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %lld %d (%d %d %d %d %d)"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %lld %d (%d %d %d %d %d)\n"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %lld %u %d"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %lld %u %d\n"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %lld %p %u %lld"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %lld %p %u %lld\n"
+ "%lld %d AVE %s: %s:%d %s | prior stop not drained %p %lld %p %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | prior stop not drained %p %lld %p %p %p %p\n"
+ "%lld %d AVE %s: %s:%d UCInfo epoch still live, prior stop not drained %p %lld %p %p %p %p %d"
+ "%lld %d AVE %s: %s:%d UCInfo epoch still live, prior stop not drained %p %lld %p %p %p %p %d\n"
+ "%lld %d AVE %s: %s::%s CBP0 flag size out of range %p %lld | %u %u"
+ "%lld %d AVE %s: %s::%s CBP0 flag size out of range %p %lld | %u %u\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d\n"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d | %p %d"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d | %p %d\n"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d | %d %d %lld %d | %p %d %d"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d | %d %d %lld %d | %p %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d %lld"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d %lld\n"
+ "%p %lld MachThreadPriorityForThreadEmittingFrames %d"
+ "%p %lld MachThreadPriorityForThreadEmittingFrames %d\n"
+ "01:02:27"
+ "913.71.1"
+ "Nov 10 2026"
+ "pClient->pcUCInfoPool == NULL && pClient->pcExUCInfoPool == NULL && pClient->sClientSurfaceSet.pcUCInfo == NULL && pClient->sClientSurfaceSet.pcExUCInfo == NULL"
+ "pEntry->iBase > 0 && pEntry->sRect.iX >= 0 && pEntry->sRect.iY >= 0 && pEntry->sRect.iWidth >= 0 && pEntry->sRect.iHeight >= 0"
+ "pFrameData->sGOPInfo.iFrameNum >= 0 && pFrameData->sGOPInfo.iFrameNum <= 2147483647"
+ "pIn->frameNumber == (uint32_t)(pClient->iLastFrameNumber + 1)"
+ "pIn->iLayerID < (uint32_t)pClient->sSessionCfg.sEnc.iLayerNum"
- "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %d %d %d %d %lld"
- "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %d %d %d %d %lld\n"
- "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %d %d %d %d %lld"
- "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %d %d %d %d %lld\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d %d\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d %d\n"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d 0x%x | %p %d"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d 0x%x | %p %d\n"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d 0x%x | %d %d %lld %d | %p %d %d"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d 0x%x | %d %d %lld %d | %p %d %d\n"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d %lld"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d %lld\n"
- "01:23:25"
- "913.63.1"
- "Oct 30 2026"
```
