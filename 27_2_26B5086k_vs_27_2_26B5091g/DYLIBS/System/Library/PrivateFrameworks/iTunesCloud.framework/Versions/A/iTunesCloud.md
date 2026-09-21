## iTunesCloud

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Versions/A/iTunesCloud`

```diff

-4026.200.13.0.0
-  __TEXT.__text: 0x31cc4c
-  __TEXT.__objc_methlist: 0x187dc
-  __TEXT.__const: 0x272d8
+4026.200.17.0.0
+  __TEXT.__text: 0x31fa90
+  __TEXT.__objc_methlist: 0x188dc
+  __TEXT.__const: 0x272e8
   __TEXT.__dlopen_cstrs: 0x2ff
-  __TEXT.__gcc_except_tab: 0x2a3c
-  __TEXT.__cstring: 0x17640
-  __TEXT.__oslogstring: 0x21ed1
+  __TEXT.__gcc_except_tab: 0x2a40
+  __TEXT.__cstring: 0x1777d
+  __TEXT.__oslogstring: 0x2211f
   __TEXT.__ustring: 0x8e
-  __TEXT.__unwind_info: 0x8218
+  __TEXT.__unwind_info: 0x8260
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2bf8
+  __DATA_CONST.__const: 0x2c00
   __DATA_CONST.__objc_classlist: 0xdd8
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa4b0
+  __DATA_CONST.__objc_selrefs: 0xa538
   __DATA_CONST.__objc_protorefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0xc00
   __DATA_CONST.__objc_arraydata: 0x498
   __DATA_CONST.__got: 0x1060
-  __AUTH_CONST.__const: 0x17a90
-  __AUTH_CONST.__cfstring: 0x18960
-  __AUTH_CONST.__objc_const: 0x31768
+  __AUTH_CONST.__const: 0x17ae0
+  __AUTH_CONST.__cfstring: 0x189e0
+  __AUTH_CONST.__objc_const: 0x31928
   __AUTH_CONST.__objc_intobj: 0x468
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x258
   __AUTH_CONST.__auth_got: 0x990
-  __AUTH.__objc_data: 0x5230
-  __DATA.__objc_ivar: 0x24a4
-  __DATA.__data: 0x2b78
-  __DATA.__bss: 0x428
+  __AUTH.__objc_data: 0x280
+  __DATA.__objc_ivar: 0x24c8
+  __DATA.__data: 0x2aa8
+  __DATA.__bss: 0x438
   __DATA.__common: 0xa58
-  __DATA_DIRTY.__objc_data: 0x3840
-  __DATA_DIRTY.__data: 0x108
+  __DATA_DIRTY.__objc_data: 0x87f0
+  __DATA_DIRTY.__data: 0x1d0
   __DATA_DIRTY.__bss: 0x420
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 10149
-  Symbols:   21680
-  CStrings:  5435
+  Functions: 10173
+  Symbols:   21728
+  CStrings:  5449
 
Symbols:
+ +[ICCloudAPNSChannelPushMessage dateFromISO8601Timestamp:defaultFetchStartSeconds:]
+ +[ICCloudAPNSChannelPushMessage messageWithAPSIncomingMessage:defaultFetchStartSeconds:]
+ +[ICCloudEntityUpdate allUpdatesPaused]
+ +[ICCloudEntityUpdate pushReceivedUpdateWithMessages:]
+ +[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]
+ -[ICCloudAPNSChannelPushMessage hash]
+ -[ICCloudAPNSChannelPushMessage isEqual:]
+ -[ICCloudAPNSChannelRegistrationConfiguration initWithChannelID:entityType:storeID:reason:expectedReleaseDate:lastProcessedGoLiveTimestamp:registrationToken:]
+ -[ICCloudAPNSChannelRegistrationConfiguration lastProcessedGoLiveTimestamp]
+ -[ICCloudAPNSChannelRegistrationConfiguration registrationToken]
+ -[ICCloudClientAPNSChannelManager _computeChannelStatesForResync]
+ -[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]
+ -[ICCloudClientAPNSChannelManager _dispatchUpdate:toRegistrationsForChannelIDs:]
+ -[ICCloudClientAPNSChannelManager _resumeUpdates]
+ -[ICCloudClientAPNSChannelManager _serverSetupDidComplete]
+ -[ICCloudClientAPNSChannelManager _xpcRegisterChannelState:completion:]
+ -[ICCloudClientAPNSChannelManager _xpcUnregisterToken:completion:]
+ -[ICCloudClientAPNSChannelManager monitoredChannelsWereUpdatedWithMessagesByChannelID:completion:]
+ -[ICCloudClientAPNSChannelManager unregisterAllUpdates]
+ -[ICCloudEntityUpdate initWithType:pushMessages:error:channelIDs:unsubscribeReason:resubscribeReason:]
+ -[ICCloudEntityUpdate pushMessages]
+ -[ICCloudEntityUpdateRegistrationToken _UUID]
+ -[ICCloudServiceStatusMonitor initWithUserIdentity:]
+ -[ICInAppMessageConfiguration syncEnabled]
+ -[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]
+ -[_ICCloudAPNSChannelRegistrationState initWithChannelID:entityType:storeID:reasons:expectedReleaseDate:registrationToken:lastProcessedGoLiveTimestamp:]
+ -[_ICCloudAPNSChannelRegistrationState lastProcessedGoLiveTimestamp]
+ -[_ICCloudAPNSChannelRegistrationState registrationToken]
+ -[_ICCloudUpdateRegistration initWithConfiguration:handler:token:]
+ -[_ICCloudUpdateRegistration lastProcessedGoLiveTimestamp]
+ -[_ICCloudUpdateRegistration setLastProcessedGoLiveTimestamp:]
+ -[_ICCloudUpdateRegistration token]
+ GCC_except_table1079
+ GCC_except_table1089
+ GCC_except_table1177
+ GCC_except_table1204
+ GCC_except_table1260
+ GCC_except_table1262
+ GCC_except_table1264
+ GCC_except_table1336
+ GCC_except_table1430
+ GCC_except_table1629
+ GCC_except_table1642
+ GCC_except_table1900
+ GCC_except_table2084
+ GCC_except_table2113
+ GCC_except_table2128
+ GCC_except_table2176
+ GCC_except_table2288
+ GCC_except_table2304
+ GCC_except_table2353
+ GCC_except_table2355
+ GCC_except_table2361
+ GCC_except_table2368
+ GCC_except_table2396
+ GCC_except_table2411
+ GCC_except_table2416
+ GCC_except_table2418
+ GCC_except_table2423
+ GCC_except_table2426
+ GCC_except_table2439
+ GCC_except_table2535
+ GCC_except_table2575
+ GCC_except_table2606
+ GCC_except_table2608
+ GCC_except_table2610
+ GCC_except_table2612
+ GCC_except_table275
+ GCC_except_table280
+ GCC_except_table2966
+ GCC_except_table300
+ GCC_except_table3018
+ GCC_except_table3182
+ GCC_except_table3199
+ GCC_except_table3212
+ GCC_except_table3236
+ GCC_except_table3246
+ GCC_except_table3345
+ GCC_except_table3624
+ GCC_except_table3630
+ GCC_except_table3633
+ GCC_except_table3648
+ GCC_except_table3659
+ GCC_except_table3678
+ GCC_except_table3718
+ GCC_except_table3734
+ GCC_except_table3847
+ GCC_except_table4008
+ GCC_except_table4175
+ GCC_except_table4218
+ GCC_except_table4328
+ GCC_except_table4332
+ GCC_except_table4334
+ GCC_except_table4338
+ GCC_except_table4345
+ GCC_except_table4349
+ GCC_except_table4364
+ GCC_except_table4368
+ GCC_except_table4547
+ GCC_except_table4600
+ GCC_except_table4607
+ GCC_except_table4612
+ GCC_except_table4676
+ GCC_except_table4718
+ GCC_except_table4722
+ GCC_except_table4724
+ GCC_except_table4791
+ GCC_except_table4868
+ GCC_except_table503
+ GCC_except_table5030
+ GCC_except_table5099
+ GCC_except_table510
+ GCC_except_table5180
+ GCC_except_table5340
+ GCC_except_table5597
+ GCC_except_table5701
+ GCC_except_table5748
+ GCC_except_table5772
+ GCC_except_table5813
+ GCC_except_table5814
+ GCC_except_table5889
+ GCC_except_table5907
+ GCC_except_table6167
+ GCC_except_table6175
+ GCC_except_table6183
+ GCC_except_table6195
+ GCC_except_table6196
+ GCC_except_table6197
+ GCC_except_table6198
+ GCC_except_table6203
+ GCC_except_table6208
+ GCC_except_table6213
+ GCC_except_table6224
+ GCC_except_table6240
+ GCC_except_table6242
+ GCC_except_table6257
+ GCC_except_table6267
+ GCC_except_table6301
+ GCC_except_table6344
+ GCC_except_table6351
+ GCC_except_table6352
+ GCC_except_table6412
+ GCC_except_table6415
+ GCC_except_table6435
+ GCC_except_table6458
+ GCC_except_table6493
+ GCC_except_table6496
+ GCC_except_table6499
+ GCC_except_table6600
+ GCC_except_table6813
+ GCC_except_table6820
+ GCC_except_table6994
+ GCC_except_table6998
+ GCC_except_table7000
+ GCC_except_table7027
+ GCC_except_table7073
+ GCC_except_table7247
+ GCC_except_table7379
+ GCC_except_table7499
+ GCC_except_table7513
+ GCC_except_table7540
+ GCC_except_table7617
+ GCC_except_table7632
+ GCC_except_table7666
+ GCC_except_table7709
+ GCC_except_table7710
+ GCC_except_table7711
+ GCC_except_table7712
+ GCC_except_table7713
+ GCC_except_table7754
+ GCC_except_table7772
+ GCC_except_table7824
+ GCC_except_table7838
+ GCC_except_table7847
+ GCC_except_table7894
+ GCC_except_table792
+ GCC_except_table8000
+ GCC_except_table8033
+ GCC_except_table806
+ GCC_except_table8099
+ GCC_except_table8520
+ GCC_except_table8524
+ GCC_except_table8528
+ GCC_except_table8550
+ GCC_except_table8557
+ GCC_except_table8570
+ GCC_except_table8575
+ GCC_except_table858
+ GCC_except_table8610
+ GCC_except_table8613
+ GCC_except_table8684
+ GCC_except_table8729
+ GCC_except_table8777
+ GCC_except_table8806
+ GCC_except_table8811
+ GCC_except_table8813
+ GCC_except_table8815
+ GCC_except_table8848
+ GCC_except_table8980
+ GCC_except_table8988
+ GCC_except_table8993
+ GCC_except_table9008
+ GCC_except_table9016
+ GCC_except_table9060
+ GCC_except_table9211
+ GCC_except_table9215
+ GCC_except_table9217
+ GCC_except_table9255
+ GCC_except_table9258
+ GCC_except_table9265
+ GCC_except_table9268
+ GCC_except_table9513
+ GCC_except_table9523
+ GCC_except_table9581
+ GCC_except_table9668
+ GCC_except_table9673
+ GCC_except_table974
+ GCC_except_table985
+ GCC_except_table9913
+ OBJC_IVAR_$_ICCloudAPNSChannelRegistrationConfiguration._lastProcessedGoLiveTimestamp
+ OBJC_IVAR_$_ICCloudAPNSChannelRegistrationConfiguration._registrationToken
+ OBJC_IVAR_$_ICCloudClientAPNSChannelManager._deliveryQueue
+ OBJC_IVAR_$_ICCloudClientAPNSChannelManager._pauseUpdates
+ OBJC_IVAR_$_ICCloudClientAPNSChannelManager._registrationsByChannel
+ OBJC_IVAR_$_ICCloudEntityUpdate._pushMessages
+ OBJC_IVAR_$_ICCloudServiceStatusMonitor._userIdentity
+ OBJC_IVAR_$__ICCloudAPNSChannelRegistrationState._lastProcessedGoLiveTimestamp
+ OBJC_IVAR_$__ICCloudAPNSChannelRegistrationState._registrationToken
+ OBJC_IVAR_$__ICCloudUpdateRegistration._lastProcessedGoLiveTimestamp
+ OBJC_IVAR_$__ICCloudUpdateRegistration._token
+ _ContentTypeForPayloadValue.sContentTypeDict
+ _ISO8601DateFormatterWithFractionalSeconds.sFormatter
+ _ISO8601DateFormatterWithFractionalSeconds.sOnceToken
+ _ServerDidCompleteSetup
+ __55-[ICCloudClientAPNSChannelManager unregisterAllUpdates]_block_invoke
+ __58-[ICCloudClientAPNSChannelManager _serverSetupDidComplete]_block_invoke
+ __61-[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]_block_invoke
+ __66-[ICCloudClientAPNSChannelManager _xpcUnregisterToken:completion:]_block_invoke
+ __71-[ICCloudClientAPNSChannelManager _xpcRegisterChannelState:completion:]_block_invoke
+ __85+[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
+ __OBJC_$_PROP_LIST_ICCloudEntityUpdateRegistrationToken
+ ___55-[ICCloudClientAPNSChannelManager unregisterAllUpdates]_block_invoke
+ ___58-[ICCloudClientAPNSChannelManager _serverSetupDidComplete]_block_invoke
+ ___61-[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]_block_invoke
+ ___61-[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]_block_invoke_2
+ ___66-[ICCloudClientAPNSChannelManager _xpcUnregisterToken:completion:]_block_invoke
+ ___71-[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]_block_invoke
+ ___71-[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]_block_invoke_2
+ ___71-[ICCloudClientAPNSChannelManager _xpcRegisterChannelState:completion:]_block_invoke
+ ___80-[ICCloudClientAPNSChannelManager _dispatchUpdate:toRegistrationsForChannelIDs:]_block_invoke
+ ___85+[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
+ ____ISO8601DateFormatterWithFractionalSeconds_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e49_v24?0"ICInAppMessageConfiguration"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e58_v24?0"ICCloudEntityUpdateRegistrationToken"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56bs64bs_e58_v24?0"ICCloudEntityUpdateRegistrationToken"8"NSError"16l
+ _objc_msgSend$_computeChannelStatesForResync
+ _objc_msgSend$_deliverMessages:forChannelID:group:
+ _objc_msgSend$_dispatchUpdate:toRegistrationsForChannelIDs:
+ _objc_msgSend$_performSyncIfEnabledWithCompletion:
+ _objc_msgSend$_resumeUpdates
+ _objc_msgSend$_xpcRegisterChannelState:completion:
+ _objc_msgSend$_xpcUnregisterToken:completion:
+ _objc_msgSend$allUpdatesPaused
+ _objc_msgSend$beginObservingCloudServiceStatusForUserIdentity:completionHandler:
+ _objc_msgSend$dateFromISO8601Timestamp:defaultFetchStartSeconds:
+ _objc_msgSend$goLiveDate
+ _objc_msgSend$initWithChannelID:entityType:storeID:reason:expectedReleaseDate:lastProcessedGoLiveTimestamp:registrationToken:
+ _objc_msgSend$initWithChannelID:entityType:storeID:reasons:expectedReleaseDate:registrationToken:lastProcessedGoLiveTimestamp:
+ _objc_msgSend$initWithConfiguration:handler:token:
+ _objc_msgSend$initWithType:pushMessages:error:channelIDs:unsubscribeReason:resubscribeReason:
+ _objc_msgSend$lastProcessedGoLiveTimestamp
+ _objc_msgSend$pushReceivedUpdateWithMessages:
+ _objc_msgSend$registerChannelState:completion:
+ _objc_msgSend$registrationToken
+ _objc_msgSend$requestCapabilitiesForUserIdentity:withPrivacyPromptPolicy:completionHandler:
+ _objc_msgSend$requestStorefrontCountryCodeForUserIdentity:completionHandler:
+ _objc_msgSend$requestStorefrontIdentifierForUserIdentity:completionHandler:
+ _objc_msgSend$revokeMusicKitUserTokensForAccountDSID:withCompletion:
+ _objc_msgSend$setFormatOptions:
+ _objc_msgSend$setLastProcessedGoLiveTimestamp:
+ _objc_msgSend$syncEnabled
+ _objc_msgSend$unregisterChannelWithToken:completion:
- +[ICCloudAPNSChannelPushMessage dateFromISO8601Timestamp:]
- +[ICCloudAPNSChannelPushMessage messageWithAPSIncomingMessage:]
- -[ICCloudClient unregisterUpdatesForChannelID:reason:]
- -[ICCloudClientAPNSChannelManager _snapshotChannelStatesForResync]
- -[ICCloudClientAPNSChannelManager _xpcUpdateReasonsWithState:completion:]
- -[ICCloudClientAPNSChannelManager handleCloudServerSetupCompleted]
- -[ICCloudClientAPNSChannelManager monitoredEntityWasUpdatedWithMessage:]
- -[ICCloudClientAPNSChannelManager unregisterUpdatesForChannelID:reason:]
- -[ICCloudEntityUpdate initWithType:pushMessage:error:channelIDs:unsubscribeReason:resubscribeReason:]
- -[ICCloudServiceStatusMonitor requestUserTokenForDeveloperToken:completionHandler:]
- -[_ICCloudUpdateRegistration initWithConfiguration:handler:]
- GCC_except_table1071
- GCC_except_table1081
- GCC_except_table1169
- GCC_except_table1196
- GCC_except_table1248
- GCC_except_table1252
- GCC_except_table1254
- GCC_except_table1328
- GCC_except_table1423
- GCC_except_table1622
- GCC_except_table1635
- GCC_except_table1893
- GCC_except_table2077
- GCC_except_table2106
- GCC_except_table2121
- GCC_except_table2167
- GCC_except_table2279
- GCC_except_table2295
- GCC_except_table2344
- GCC_except_table2346
- GCC_except_table2352
- GCC_except_table2359
- GCC_except_table2387
- GCC_except_table2402
- GCC_except_table2407
- GCC_except_table2409
- GCC_except_table2414
- GCC_except_table2417
- GCC_except_table2430
- GCC_except_table2526
- GCC_except_table2566
- GCC_except_table2597
- GCC_except_table2599
- GCC_except_table2601
- GCC_except_table2603
- GCC_except_table269
- GCC_except_table274
- GCC_except_table291
- GCC_except_table2957
- GCC_except_table3009
- GCC_except_table3174
- GCC_except_table3191
- GCC_except_table3204
- GCC_except_table3228
- GCC_except_table3238
- GCC_except_table3337
- GCC_except_table3616
- GCC_except_table3622
- GCC_except_table3625
- GCC_except_table3640
- GCC_except_table3651
- GCC_except_table3670
- GCC_except_table3710
- GCC_except_table3726
- GCC_except_table3839
- GCC_except_table4000
- GCC_except_table4167
- GCC_except_table4210
- GCC_except_table4310
- GCC_except_table4320
- GCC_except_table4322
- GCC_except_table4324
- GCC_except_table4337
- GCC_except_table4341
- GCC_except_table4356
- GCC_except_table4360
- GCC_except_table4539
- GCC_except_table4592
- GCC_except_table4596
- GCC_except_table4599
- GCC_except_table4668
- GCC_except_table4710
- GCC_except_table4714
- GCC_except_table4716
- GCC_except_table4783
- GCC_except_table4860
- GCC_except_table497
- GCC_except_table5022
- GCC_except_table504
- GCC_except_table5090
- GCC_except_table5171
- GCC_except_table5331
- GCC_except_table5588
- GCC_except_table5692
- GCC_except_table5739
- GCC_except_table5763
- GCC_except_table5804
- GCC_except_table5805
- GCC_except_table5880
- GCC_except_table5898
- GCC_except_table6158
- GCC_except_table6166
- GCC_except_table6174
- GCC_except_table6185
- GCC_except_table6186
- GCC_except_table6187
- GCC_except_table6188
- GCC_except_table6189
- GCC_except_table6199
- GCC_except_table6204
- GCC_except_table6215
- GCC_except_table6231
- GCC_except_table6233
- GCC_except_table6239
- GCC_except_table6258
- GCC_except_table6292
- GCC_except_table6335
- GCC_except_table6342
- GCC_except_table6343
- GCC_except_table6403
- GCC_except_table6406
- GCC_except_table6426
- GCC_except_table6449
- GCC_except_table6454
- GCC_except_table6460
- GCC_except_table6466
- GCC_except_table6591
- GCC_except_table6804
- GCC_except_table6811
- GCC_except_table6985
- GCC_except_table6989
- GCC_except_table6991
- GCC_except_table7018
- GCC_except_table7064
- GCC_except_table7237
- GCC_except_table7369
- GCC_except_table7489
- GCC_except_table7503
- GCC_except_table7529
- GCC_except_table7606
- GCC_except_table7621
- GCC_except_table7644
- GCC_except_table7698
- GCC_except_table7699
- GCC_except_table7700
- GCC_except_table7701
- GCC_except_table7702
- GCC_except_table7743
- GCC_except_table7761
- GCC_except_table7813
- GCC_except_table7816
- GCC_except_table7836
- GCC_except_table786
- GCC_except_table7883
- GCC_except_table7976
- GCC_except_table800
- GCC_except_table8009
- GCC_except_table8075
- GCC_except_table8496
- GCC_except_table8500
- GCC_except_table8504
- GCC_except_table852
- GCC_except_table8526
- GCC_except_table8533
- GCC_except_table8546
- GCC_except_table8551
- GCC_except_table8586
- GCC_except_table8589
- GCC_except_table8660
- GCC_except_table8705
- GCC_except_table8753
- GCC_except_table8782
- GCC_except_table8787
- GCC_except_table8789
- GCC_except_table8791
- GCC_except_table8824
- GCC_except_table8956
- GCC_except_table8964
- GCC_except_table8969
- GCC_except_table8984
- GCC_except_table8992
- GCC_except_table9036
- GCC_except_table9187
- GCC_except_table9191
- GCC_except_table9193
- GCC_except_table9231
- GCC_except_table9234
- GCC_except_table9241
- GCC_except_table9244
- GCC_except_table9489
- GCC_except_table9499
- GCC_except_table9557
- GCC_except_table9644
- GCC_except_table9649
- GCC_except_table966
- GCC_except_table977
- GCC_except_table9889
- OBJC_IVAR_$_ICCloudClientAPNSChannelManager._listenerEndpointProvider
- OBJC_IVAR_$_ICCloudClientAPNSChannelManager._tokensByChannelAndReason
- _ContentTypeForPayloadValue.__contentTypeDict
- __103-[ICCloudClientAPNSChannelManager registerForUpdatesWithConfiguration:updateHandler:completionHandler:]_block_invoke
- __52-[ICInAppMessageManager _performSyncWithCompletion:]_block_invoke
- __66-[ICCloudClientAPNSChannelManager handleCloudServerSetupCompleted]_block_invoke
- __73-[ICCloudClientAPNSChannelManager _xpcUpdateReasonsWithState:completion:]_block_invoke
- __83-[ICCloudClientAPNSChannelManager _tearDownAllRegistrationsWithError:notifyDaemon:]_block_invoke
- __85-[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
- ___52-[ICInAppMessageManager _performSyncWithCompletion:]_block_invoke_2
- ___62-[ICCloudClientAPNSChannelManager unregisterUpdatesForTokens:]_block_invoke
- ___64-[ICCloudClientAPNSChannelManager channelRegistrationsDisabled:]_block_invoke
- ___66-[ICCloudClientAPNSChannelManager handleCloudServerSetupCompleted]_block_invoke
- ___72-[ICCloudClientAPNSChannelManager monitoredEntityWasUpdatedWithMessage:]_block_invoke
- ___72-[ICCloudClientAPNSChannelManager unregisterUpdatesForChannelID:reason:]_block_invoke
- ___73-[ICCloudClientAPNSChannelManager _xpcUpdateReasonsWithState:completion:]_block_invoke
- ___85-[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
- ___block_descriptor_57_e8_32s40bs48bs_e17_v16?0"NSError"8l
- ___block_descriptor_98_e8_32s40s48s56s64s72s80bs_e5_v8?0l
- _objc_msgSend$_snapshotChannelStatesForResync
- _objc_msgSend$_xpcUpdateReasonsWithState:completion:
- _objc_msgSend$anyObject
- _objc_msgSend$beginObservingCloudServiceStatusWithCompletionHandler:
- _objc_msgSend$dateFromISO8601Timestamp:
- _objc_msgSend$handleCloudServerSetupCompleted
- _objc_msgSend$initWithChannelID:entityType:storeID:reason:expectedReleaseDate:
- _objc_msgSend$initWithChannelID:entityType:storeID:reasons:expectedReleaseDate:
- _objc_msgSend$initWithConfiguration:handler:
- _objc_msgSend$initWithType:pushMessage:error:channelIDs:unsubscribeReason:resubscribeReason:
- _objc_msgSend$pushReceivedUpdateWithMessage:
- _objc_msgSend$requestCapabilitiesWithPrivacyPromptPolicy:completionHandler:
- _objc_msgSend$requestStorefrontCountryCodeWithCompletionHandler:
- _objc_msgSend$requestStorefrontIdentifierWithCompletionHandler:
- _objc_msgSend$requestUserTokenForDeveloperToken:options:completionHandler:
- _objc_msgSend$unregisterUpdatesForChannelID:reason:
- _objc_msgSend$updateMonitoredReasonsWithChannelState:completion:
CStrings:
+ "%{public}@ Cancelling existing periodic poll task"
+ "%{public}@ Failed to load configuration for sync. err=%{public}@"
+ "%{public}@ Not scheduling periodic poll because in-app message syncing is disabled. err=%{public}@"
+ "%{public}@ Not syncing because in-app message syncing is disabled"
+ "<%@ %p channelID=%@ contentType=%ld storeID=%lld storefront=%@ goLiveDate=%@ relevanceBitmask=0x%llx receivedDate=%@>"
+ "<%@ %p channelID=%@ entityType=%ld storeID=%lld reason=%ld expectedReleaseDate=%@ lastProcessedGoLiveTimestamp=%@ registrationToken=%p observesAllLibraryAlbums=%d>"
+ "<%@ %p channelID=%@ entityType=%ld storeID=%lld reasons=%@ expectedReleaseDate=%@ registrationToken=%@ lastProcessedGoLiveTimestamp=%@>"
+ "<%@ %p type=%@ pushMessages=%@ error=%@ channelIDs=%@ unsubscribeReason=%@ resubscribeReason=%@>"
+ "<%@: %p %@>"
+ "ICCloudAPNSChannelPushMessage - Could not create date from time=%{public}@, setting to %{public}@"
+ "ICCloudChannelRegistrationAvailability - scheduling bag fetch retry delay=%.0f"
+ "ICCloudClient - not unregistering; token is nil."
+ "ICCloudClientAPNSChannelManager - dispatching a lifecycle update channels=%{public}@ handlers=%lu"
+ "ICCloudClientAPNSChannelManager - dispatching updates channelID=%{public}@ ordered=%lu unordered=%lu"
+ "ICCloudClientAPNSChannelManager - feature disabled daemonChannels=%{public}@ localOnly=%{public}@"
+ "ICCloudClientAPNSChannelManager - not able to registerChannelState channelID=%{public}@ err=%{public}@"
+ "ICCloudClientAPNSChannelManager - not able to send registerChannelState; proxy error. channelID=%{public}@ err=%{public}@"
+ "ICCloudClientAPNSChannelManager - not able to send unregisterChannelWithToken; proxy err=%{public}@"
+ "ICCloudClientAPNSChannelManager - not able to unregisterChannelWithToken err=%{public}@"
+ "ICCloudClientAPNSChannelManager - not delivering per-channel cancellation channelIDs=%{public}@; updates are paused"
+ "ICCloudClientAPNSChannelManager - not delivering pushes; feature is unavailable. channelCount=%lu"
+ "ICCloudClientAPNSChannelManager - not delivering pushes; updates are paused"
+ "ICCloudClientAPNSChannelManager - not dispatching a lifecycle update channels=%{public}@; updates are paused"
+ "ICCloudClientAPNSChannelManager - not dispatching observe-all update; updates are paused."
+ "ICCloudClientAPNSChannelManager - not dispatching updates; no handlers on channelID=%{public}@"
+ "ICCloudClientAPNSChannelManager - not registering; daemon minted no token channelID=%{public}@ err=%{public}@"
+ "ICCloudClientAPNSChannelManager - not resyncing after server setup; hasRegistrations=%{BOOL}u, updatesPaused=%{BOOL}u, _lastSetupCompletedResyncRequest=%{public}@"
+ "ICCloudClientAPNSChannelManager - not sending registerChannelState; no XPC connection. channelID=%{public}@"
+ "ICCloudClientAPNSChannelManager - not sending unregisterChannelWithToken; no XPC connection."
+ "ICCloudClientAPNSChannelManager - paused all updates registrations=%lu handlers=%lu"
+ "ICCloudClientAPNSChannelManager - pausing all updates"
+ "ICCloudClientAPNSChannelManager - receiving updates channelID=%{public}@ count=%lu"
+ "ICCloudClientAPNSChannelManager - registered token=%{public}@ channelID=%{public}@ reason=%ld"
+ "ICCloudClientAPNSChannelManager - resuming updates"
+ "ICCloudClientAPNSChannelManager - resyncing all existing registrations _pauseUpdates=%{BOOL}u."
+ "ICCloudClientAPNSChannelManager - sending registerChannelState state=%{public}@"
+ "ICCloudClientAPNSChannelManager - tearing down registrations tokens=%lu handlers=%lu notifyDaemon=%{BOOL}u paused=%{BOOL}u err=%{public}@"
+ "ICCloudClientAPNSChannelManager - updates are already paused"
+ "ICCloudServiceStatusMonitor %{public}@: Connection to %{public}@ failed to get remote object proxy: %{public}@"
+ "ICCloudServiceStatusMonitor %{public}@: Connection to %{public}@ service interrupted."
+ "ICCloudServiceStatusMonitor %{public}@: Connection to %{public}@ service invalidated."
+ "ICCloudServiceStatusMonitor %{public}@: Revocation of music user tokens completed"
+ "ICCloudServiceStatusMonitor %{public}@: Revocation of music user tokens completed error=%{public}@"
+ "ICCloudServiceStatusMonitor %{public}@: Revoking music user tokens DSID %{public}@"
+ "UpdatesPaused"
+ "com.apple.iTunesCloud.ICCloudClientAPNSChannelManager.deliveryQueue"
+ "inAppMessagesSyncEnabled"
+ "lastProcessedGoLiveTimestamp"
+ "registrationToken"
+ "v24@?0@\"ICCloudEntityUpdateRegistrationToken\"8@\"NSError\"16"
- "%{public}@: Revocation of music user tokens completed"
- "%{public}@: Revocation of music user tokens completed error=%{public}@"
- "%{public}@: Revoking music user tokens DSID %{public}@"
- "<%@ %p channelID=%@ contentType=%ld _storeID=%lld storefront=%@ goLiveDate=%@ relevanceBitmask=0x%llx receivedDate=%@>"
- "<%@ %p channelID=%@ entityType=%ld storeID=%lld reason=%ld expectedReleaseDate=%@ observesAllLibraryAlbums=%d>"
- "<%@ %p channelID=%@ entityType=%ld storeID=%lld reasons=%@ expectedReleaseDate=%@>"
- "<%@ %p type=%@ pushMessage=%@ error=%@ channelIDs=%@ unsubscribeReason=%@ resubscribeReason=%@>"
- "<%@: %p token=%@>"
- "Cannot unregister updates: token is nil."
- "ICCloudAPNSChannelPushMessage - not decoding push; missing storeID. payload=%{public}@"
- "ICCloudChannelRegistrationAvailability - scheduling bag fetch retry delay=%.0fs"
- "ICCloudClientAPNSChannelManager - dispatching update handlerCount=%lu channelID=%{public}@"
- "ICCloudClientAPNSChannelManager - feature disabled daemonChannels=%{public}@ localOnly=%{public}@ handlers=%lu"
- "ICCloudClientAPNSChannelManager - not able to add reason on daemon; committing locally channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not able to send updateMonitoredReasons; proxy err channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not able to update daemon channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not able to updateMonitoredReasons channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not able to updateMonitoredReasons during tear-down channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not able to updateMonitoredReasons for race-repair channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not delivering push; feature is unavailable. channelID=%{public}@"
- "ICCloudClientAPNSChannelManager - not dispatching update; no handlers on channelID=%{public}@"
- "ICCloudClientAPNSChannelManager - not registering; daemon update failed channelID=%{public}@ err=%{public}@"
- "ICCloudClientAPNSChannelManager - not resyncing after server setup; debounced."
- "ICCloudClientAPNSChannelManager - not resyncing after server setup; no registrations."
- "ICCloudClientAPNSChannelManager - not sending daemon updates; nothing to unregister."
- "ICCloudClientAPNSChannelManager - not sending updateMonitoredReasons; no XPC connection. channelID=%{public}@"
- "ICCloudClientAPNSChannelManager - not unregistering channel; no matching tokens channelID=%{public}@ reason=%ld"
- "ICCloudClientAPNSChannelManager - not unregistering; feature is unavailable. channelID=%{public}@ reason=%ld"
- "ICCloudClientAPNSChannelManager - not unregistering; invalid arguments channelID=%{public}@ reason=%ld"
- "ICCloudClientAPNSChannelManager - receiving update pushMessage=%{public}@"
- "ICCloudClientAPNSChannelManager - registering configuration=%{public}@ token=%{public}@"
- "ICCloudClientAPNSChannelManager - registering token=%{public}@ channelID=%{public}@ reason=%ld isRegisteredChannel=%{BOOL}u isRegisteredReason=%{BOOL}u"
- "ICCloudClientAPNSChannelManager - sending updateMonitoredReasons state=%{public}@"
- "ICCloudClientAPNSChannelManager - tearing down registrations xpcUpdates=%lu handlers=%lu notifyDaemon=%{BOOL}u err=%{public}@"
- "ICCloudClientAPNSChannelManager - unregistering channel channelID=%{public}@ reason=%ld"
- "ICCloudClientAPNSChannelManager - unregistering tokens count=%lu channelID=%{public}@ reason=%ld"
```
