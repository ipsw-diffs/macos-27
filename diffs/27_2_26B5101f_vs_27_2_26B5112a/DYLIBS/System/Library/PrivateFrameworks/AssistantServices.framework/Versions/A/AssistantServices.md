## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3605.30.1.4.1
-  __TEXT.__text: 0x19e868
-  __TEXT.__objc_methlist: 0x1eff4
+3605.31.1.14.2
+  __TEXT.__text: 0x19f550
+  __TEXT.__objc_methlist: 0x1f104
   __TEXT.__const: 0x3f0
   __TEXT.__dlopen_cstrs: 0x421
   __TEXT.__gcc_except_tab: 0x1fc0
-  __TEXT.__cstring: 0x3b7d5
-  __TEXT.__oslogstring: 0xeef9
+  __TEXT.__cstring: 0x3ba11
+  __TEXT.__oslogstring: 0xef74
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x98d0
+  __TEXT.__unwind_info: 0x9910
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x42b0
+  __DATA_CONST.__const: 0x42e0
   __DATA_CONST.__objc_classlist: 0xef8
   __DATA_CONST.__objc_catlist: 0x2a0
   __DATA_CONST.__objc_protolist: 0x5f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbd98
+  __DATA_CONST.__objc_selrefs: 0xbe20
   __DATA_CONST.__objc_protorefs: 0x180
   __DATA_CONST.__objc_superrefs: 0xf10
   __DATA_CONST.__objc_arraydata: 0x2450
   __DATA_CONST.__got: 0x1660
-  __AUTH_CONST.__const: 0x8350
-  __AUTH_CONST.__cfstring: 0x27e20
-  __AUTH_CONST.__objc_const: 0x363c8
+  __AUTH_CONST.__const: 0x8370
+  __AUTH_CONST.__cfstring: 0x27fe0
+  __AUTH_CONST.__objc_const: 0x36530
   __AUTH_CONST.__objc_intobj: 0x2730
   __AUTH_CONST.__objc_dictobj: 0xd20
   __AUTH_CONST.__objc_arrayobj: 0x5d0

   __AUTH_CONST.__auth_got: 0x990
   __AUTH.__objc_data: 0x84a8
   __AUTH.__data: 0xd0
-  __DATA.__objc_ivar: 0x2580
+  __DATA.__objc_ivar: 0x259c
   __DATA.__data: 0x48c0
-  __DATA.__bss: 0xf28
+  __DATA.__bss: 0xf30
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12002
-  Symbols:   26427
-  CStrings:  8368
+  Functions: 12026
+  Symbols:   26475
+  CStrings:  8386
 
Symbols:
+ -[AFCompanionDeviceInfo ifpCapableDevice]
+ -[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:]
+ -[AFCompanionDeviceInfo linwoodCapableDevice]
+ -[AFCompanionDeviceInfo siriAvailability]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:]
+ -[AFCompanionDeviceInfo(SiriAvailability) createSiriAvailability]
+ -[AFSiriAvailability createDictionaryExcludingBootSession]
+ -[AFSiriAvailability isLinwoodAccessRestricted]
+ -[AFSiriAvailability isLinwoodGMSAvailable]
+ -[AFSiriAvailability isLinwoodGMSEnabled]
+ -[AFSpeechRequestOptions isReplyToSiriPrompt]
+ -[AFSpeechRequestOptions setIsReplyToSiriPrompt:]
+ -[_AFCompanionDeviceInfoMutation getIfpCapableDevice]
+ -[_AFCompanionDeviceInfoMutation getLinwoodCapableDevice]
+ -[_AFCompanionDeviceInfoMutation getSiriAvailability]
+ -[_AFCompanionDeviceInfoMutation setIfpCapableDevice:]
+ -[_AFCompanionDeviceInfoMutation setLinwoodCapableDevice:]
+ -[_AFCompanionDeviceInfoMutation setSiriAvailability:]
+ AFIsJ265.isJ265
+ AFIsJ265.onceToken
+ GCC_except_table10112
+ GCC_except_table10117
+ GCC_except_table10118
+ GCC_except_table10122
+ GCC_except_table10312
+ GCC_except_table10485
+ GCC_except_table10610
+ GCC_except_table10614
+ GCC_except_table10618
+ GCC_except_table10647
+ GCC_except_table10995
+ GCC_except_table10997
+ GCC_except_table11000
+ GCC_except_table11009
+ GCC_except_table11075
+ GCC_except_table11090
+ GCC_except_table11115
+ GCC_except_table11121
+ GCC_except_table11280
+ GCC_except_table11284
+ GCC_except_table11286
+ GCC_except_table11289
+ GCC_except_table11295
+ GCC_except_table11302
+ GCC_except_table11509
+ GCC_except_table11833
+ GCC_except_table11974
+ GCC_except_table11977
+ GCC_except_table11979
+ GCC_except_table2756
+ GCC_except_table2769
+ GCC_except_table2773
+ GCC_except_table2785
+ GCC_except_table2789
+ GCC_except_table2902
+ GCC_except_table2904
+ GCC_except_table2961
+ GCC_except_table3005
+ GCC_except_table3352
+ GCC_except_table3359
+ GCC_except_table3365
+ GCC_except_table3367
+ GCC_except_table3369
+ GCC_except_table3404
+ GCC_except_table3406
+ GCC_except_table3412
+ GCC_except_table3418
+ GCC_except_table3422
+ GCC_except_table3428
+ GCC_except_table3435
+ GCC_except_table3437
+ GCC_except_table3444
+ GCC_except_table3446
+ GCC_except_table3451
+ GCC_except_table3463
+ GCC_except_table3466
+ GCC_except_table3480
+ GCC_except_table3482
+ GCC_except_table3484
+ GCC_except_table3486
+ GCC_except_table3488
+ GCC_except_table3490
+ GCC_except_table3536
+ GCC_except_table3562
+ GCC_except_table3619
+ GCC_except_table3655
+ GCC_except_table4038
+ GCC_except_table4326
+ GCC_except_table4529
+ GCC_except_table4537
+ GCC_except_table4963
+ GCC_except_table4967
+ GCC_except_table5012
+ GCC_except_table5018
+ GCC_except_table5045
+ GCC_except_table5052
+ GCC_except_table5264
+ GCC_except_table5338
+ GCC_except_table5349
+ GCC_except_table5382
+ GCC_except_table5385
+ GCC_except_table5462
+ GCC_except_table5466
+ GCC_except_table5476
+ GCC_except_table5487
+ GCC_except_table5502
+ GCC_except_table5587
+ GCC_except_table5589
+ GCC_except_table5613
+ GCC_except_table5729
+ GCC_except_table5792
+ GCC_except_table5795
+ GCC_except_table5799
+ GCC_except_table5818
+ GCC_except_table5833
+ GCC_except_table5907
+ GCC_except_table5965
+ GCC_except_table5991
+ GCC_except_table6259
+ GCC_except_table6388
+ GCC_except_table6438
+ GCC_except_table6532
+ GCC_except_table6717
+ GCC_except_table6805
+ GCC_except_table6859
+ GCC_except_table7085
+ GCC_except_table7086
+ GCC_except_table7283
+ GCC_except_table7343
+ GCC_except_table7557
+ GCC_except_table7560
+ GCC_except_table7565
+ GCC_except_table7569
+ GCC_except_table7583
+ GCC_except_table7630
+ GCC_except_table7642
+ GCC_except_table7735
+ GCC_except_table7739
+ GCC_except_table7849
+ GCC_except_table7912
+ GCC_except_table7914
+ GCC_except_table7916
+ GCC_except_table7918
+ GCC_except_table7932
+ GCC_except_table7938
+ GCC_except_table8063
+ GCC_except_table8067
+ GCC_except_table8072
+ GCC_except_table8444
+ GCC_except_table8459
+ GCC_except_table8466
+ GCC_except_table8482
+ GCC_except_table8553
+ GCC_except_table8582
+ GCC_except_table8620
+ GCC_except_table8621
+ GCC_except_table8622
+ GCC_except_table8647
+ GCC_except_table8671
+ GCC_except_table9031
+ GCC_except_table9036
+ GCC_except_table9039
+ GCC_except_table9042
+ GCC_except_table9045
+ GCC_except_table9048
+ GCC_except_table9051
+ GCC_except_table9054
+ GCC_except_table9057
+ GCC_except_table9060
+ GCC_except_table9233
+ GCC_except_table9236
+ GCC_except_table9309
+ GCC_except_table9469
+ GCC_except_table9571
+ GCC_except_table9762
+ GCC_except_table9767
+ GCC_except_table9895
+ OBJC_IVAR_$_AFCompanionDeviceInfo._ifpCapableDevice
+ OBJC_IVAR_$_AFCompanionDeviceInfo._linwoodCapableDevice
+ OBJC_IVAR_$_AFCompanionDeviceInfo._siriAvailability
+ OBJC_IVAR_$_AFSpeechRequestOptions._isReplyToSiriPrompt
+ OBJC_IVAR_$__AFCompanionDeviceInfoMutation._ifpCapableDevice
+ OBJC_IVAR_$__AFCompanionDeviceInfoMutation._linwoodCapableDevice
+ OBJC_IVAR_$__AFCompanionDeviceInfoMutation._siriAvailability
+ _AFIsJ265
+ _AFIsWaffleiron
+ _AFMeDeviceLinwoodEnablementDidChangeNotification
+ __AFPreferencesSetSiriPersonalContentSetting
+ __AFPreferencesSiriPersonalContentSetting
+ __OBJC_$_CATEGORY_SAUIAssistantUtteranceView_$_AssistantAdditions
+ __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_INSTANCE_METHODS_AFClockAlarmSnapshot(Utility|AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_AFClockTimerSnapshot(Utility|AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(BackwardCompatibility|SiriAvailability|AFCompanionDeviceInfoMutability)
+ __OBJC_$_INSTANCE_METHODS_AFLocationSnapshot(Ace|AFLocationSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_AFPeerInfo(BackwardCompatibility|ShortDescription|AFPeerInfoMutability)
+ __OBJC_$_INSTANCE_METHODS_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_INSTANCE_METHODS_SAUIAssistantUtteranceView(AssistantAdditions|ClientFeedbackPresented|AnalyticsContextVending)
+ __OBJC_CLASS_PROTOCOLS_$_AFClockAlarmSnapshot(Utility|AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_AFClockTimerSnapshot(Utility|AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_AFLocationSnapshot(Ace|AFLocationSnapshotMutability|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ ___294-[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:]_block_invoke
+ ___AFIsJ265_block_invoke
+ ___block_descriptor_119_e8_32s40s48s56s64s72s80s88s96s104s_e41_v16?0"<AFCompanionDeviceInfoMutating>"8l
+ _kAFPersonalContentSettingChangedDarwinNotification
+ _kAFSiriTVPersonalContentSettingKey
+ _objc_msgSend$getIfpCapableDevice
+ _objc_msgSend$getLinwoodCapableDevice
+ _objc_msgSend$getSiriAvailability
+ _objc_msgSend$ifpCapableDevice
+ _objc_msgSend$initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:
+ _objc_msgSend$initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:
+ _objc_msgSend$initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:
+ _objc_msgSend$linwoodCapableDevice
+ _objc_msgSend$setIfpCapableDevice:
+ _objc_msgSend$setIsReplyToSiriPrompt:
+ _objc_msgSend$setLinwoodCapableDevice:
+ _objc_msgSend$toDictionary
- -[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:]
- GCC_except_table10057
- GCC_except_table10068
- GCC_except_table10101
- GCC_except_table10104
- GCC_except_table10180
- GCC_except_table10184
- GCC_except_table10194
- GCC_except_table10205
- GCC_except_table10220
- GCC_except_table10305
- GCC_except_table10307
- GCC_except_table10331
- GCC_except_table10447
- GCC_except_table10510
- GCC_except_table10517
- GCC_except_table10536
- GCC_except_table10550
- GCC_except_table10624
- GCC_except_table10682
- GCC_except_table10708
- GCC_except_table10973
- GCC_except_table11102
- GCC_except_table11152
- GCC_except_table11246
- GCC_except_table11485
- GCC_except_table11809
- GCC_except_table11950
- GCC_except_table11953
- GCC_except_table11955
- GCC_except_table2659
- GCC_except_table2749
- GCC_except_table2803
- GCC_except_table3029
- GCC_except_table3030
- GCC_except_table3227
- GCC_except_table3288
- GCC_except_table3504
- GCC_except_table3507
- GCC_except_table3512
- GCC_except_table3516
- GCC_except_table3530
- GCC_except_table3577
- GCC_except_table3583
- GCC_except_table3589
- GCC_except_table3682
- GCC_except_table3686
- GCC_except_table3796
- GCC_except_table3859
- GCC_except_table3861
- GCC_except_table3863
- GCC_except_table3865
- GCC_except_table3879
- GCC_except_table3885
- GCC_except_table4010
- GCC_except_table4014
- GCC_except_table4019
- GCC_except_table4391
- GCC_except_table4406
- GCC_except_table4413
- GCC_except_table4429
- GCC_except_table4501
- GCC_except_table4530
- GCC_except_table4568
- GCC_except_table4569
- GCC_except_table4570
- GCC_except_table4619
- GCC_except_table4979
- GCC_except_table4984
- GCC_except_table4987
- GCC_except_table4990
- GCC_except_table4993
- GCC_except_table4996
- GCC_except_table4999
- GCC_except_table5002
- GCC_except_table5005
- GCC_except_table5008
- GCC_except_table5181
- GCC_except_table5184
- GCC_except_table5257
- GCC_except_table5417
- GCC_except_table5519
- GCC_except_table5710
- GCC_except_table5715
- GCC_except_table5843
- GCC_except_table6060
- GCC_except_table6066
- GCC_except_table6067
- GCC_except_table6071
- GCC_except_table6261
- GCC_except_table6434
- GCC_except_table6462
- GCC_except_table6559
- GCC_except_table6563
- GCC_except_table6567
- GCC_except_table6596
- GCC_except_table6944
- GCC_except_table6946
- GCC_except_table6949
- GCC_except_table6958
- GCC_except_table7020
- GCC_except_table7035
- GCC_except_table7060
- GCC_except_table7066
- GCC_except_table7216
- GCC_except_table7220
- GCC_except_table7222
- GCC_except_table7225
- GCC_except_table7231
- GCC_except_table7238
- GCC_except_table7488
- GCC_except_table7501
- GCC_except_table7505
- GCC_except_table7517
- GCC_except_table7521
- GCC_except_table7634
- GCC_except_table7688
- GCC_except_table7732
- GCC_except_table8079
- GCC_except_table8086
- GCC_except_table8092
- GCC_except_table8094
- GCC_except_table8096
- GCC_except_table8131
- GCC_except_table8133
- GCC_except_table8139
- GCC_except_table8145
- GCC_except_table8149
- GCC_except_table8155
- GCC_except_table8162
- GCC_except_table8164
- GCC_except_table8169
- GCC_except_table8171
- GCC_except_table8176
- GCC_except_table8188
- GCC_except_table8191
- GCC_except_table8205
- GCC_except_table8207
- GCC_except_table8209
- GCC_except_table8211
- GCC_except_table8213
- GCC_except_table8215
- GCC_except_table8261
- GCC_except_table8287
- GCC_except_table8344
- GCC_except_table8380
- GCC_except_table8761
- GCC_except_table9049
- GCC_except_table9248
- GCC_except_table9256
- GCC_except_table9314
- GCC_except_table9682
- GCC_except_table9686
- GCC_except_table9731
- GCC_except_table9737
- GCC_except_table9764
- GCC_except_table9771
- GCC_except_table9983
- __OBJC_$_CATEGORY_SAUIAssistantUtteranceView_$_ClientFeedbackPresented
- __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription|AFPreferences|AssistantServices)
- __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
- __OBJC_$_INSTANCE_METHODS_AFClockAlarmSnapshot(AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot|Utility)
- __OBJC_$_INSTANCE_METHODS_AFClockTimerSnapshot(AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot|Utility)
- __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(AFCompanionDeviceInfoMutability|BackwardCompatibility)
- __OBJC_$_INSTANCE_METHODS_AFLocationSnapshot(AFLocationSnapshotMutability|ShortDescription|ContextSnapshot|Ace)
- __OBJC_$_INSTANCE_METHODS_AFPeerInfo(ShortDescription|BackwardCompatibility|AFPeerInfoMutability)
- __OBJC_$_INSTANCE_METHODS_AceObject(AFSecurityDigestibleChunksProvider|AnalyticsContextVending|AssistantAdditions)
- __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription|AFPreferences|AssistantServices)
- __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
- __OBJC_$_INSTANCE_METHODS_SAUIAssistantUtteranceView(ClientFeedbackPresented|AnalyticsContextVending|AssistantAdditions)
- __OBJC_CLASS_PROTOCOLS_$_AFClockAlarmSnapshot(AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot|Utility)
- __OBJC_CLASS_PROTOCOLS_$_AFClockTimerSnapshot(AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot|Utility)
- __OBJC_CLASS_PROTOCOLS_$_AFLocationSnapshot(AFLocationSnapshotMutability|ShortDescription|ContextSnapshot|Ace)
- __OBJC_CLASS_PROTOCOLS_$_AceObject(AFSecurityDigestibleChunksProvider|AnalyticsContextVending|AssistantAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
- ___239-[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:]_block_invoke
- ___block_descriptor_109_e8_32s40s48s56s64s72s80s88s96s_e41_v16?0"<AFCompanionDeviceInfoMutating>"8l
CStrings:
+ "%@ {assistantID = %@, speechID = %@, idsIdentifier = %@, productPrefix = %@, aceHost = %@, syncMetadata = %@, syncMetadataCapability = %@, peerToPeerHandoffCapability = %@, muxSupportCapability = %@, meDevice = %@, siriLanguage = %@, companionName = %@, buildVersion = %@, linwoodEnabled = %@, linwoodCapableDevice = %@, ifpCapableDevice = %@, siriAvailability = %@}"
+ "%s Asked to set nil iCloudAltDSID for personal content setting"
+ "%s Requested nil iCloudAltDSID for personal content setting"
+ ", isReplyToSiriPrompt = %d"
+ "AFCompanionDeviceInfo::ifpCapableDevice"
+ "AFCompanionDeviceInfo::linwoodCapableDevice"
+ "AFCompanionDeviceInfo::siriAvailability"
+ "AFMeDeviceLinwoodEnablementDidChangeNotification"
+ "AppleTV18,1"
+ "RISESSION_CLIENT_EVENT"
+ "RI_CLIENT_EVENT"
+ "Siri Apple TV Personal content setting"
+ "_AFPreferencesSetSiriPersonalContentSetting"
+ "_AFPreferencesSiriPersonalContentSetting"
+ "_isReplyToSiriPrompt"
+ "com.apple.siri.personalcontent.setting.changed"
+ "ifpCapableDevice"
+ "linwoodCapableDevice"
+ "siriAvailability"
- "%@ {assistantID = %@, speechID = %@, idsIdentifier = %@, productPrefix = %@, aceHost = %@, syncMetadata = %@, syncMetadataCapability = %@, peerToPeerHandoffCapability = %@, muxSupportCapability = %@, meDevice = %@, siriLanguage = %@, companionName = %@, buildVersion = %@, linwoodEnabled = %@}"
```
