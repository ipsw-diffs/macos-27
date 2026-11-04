## CoreHAP

> `/System/Library/PrivateFrameworks/CoreHAP.framework/Versions/A/CoreHAP`

```diff

-1520.2.7.4.1
-  __TEXT.__text: 0x3012a0
-  __TEXT.__objc_methlist: 0x1b9d0
-  __TEXT.__const: 0x1798
-  __TEXT.__constg_swiftt: 0xc20
-  __TEXT.__swift5_typeref: 0x533
-  __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_reflstr: 0x851
-  __TEXT.__swift5_fieldmd: 0x6a4
-  __TEXT.__swift5_assocty: 0x138
-  __TEXT.__swift5_proto: 0x78
-  __TEXT.__swift5_types: 0x5c
-  __TEXT.__cstring: 0x16d06
-  __TEXT.__oslogstring: 0x42fda
+1535.0.0.0.2
+  __TEXT.__text: 0x315fd8
+  __TEXT.__objc_methlist: 0x1c090
+  __TEXT.__const: 0x1a28
+  __TEXT.__constg_swiftt: 0xd6c
+  __TEXT.__swift5_typeref: 0x567
+  __TEXT.__swift5_reflstr: 0x927
+  __TEXT.__swift5_fieldmd: 0x748
+  __TEXT.__swift5_builtin: 0xf0
+  __TEXT.__swift5_assocty: 0x198
+  __TEXT.__swift5_proto: 0x8c
+  __TEXT.__swift5_types: 0x64
+  __TEXT.__cstring: 0x187c9
+  __TEXT.__oslogstring: 0x4403c
+  __TEXT.__swift5_capture: 0x2c0
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__swift5_capture: 0x28c
-  __TEXT.__gcc_except_tab: 0x6964
-  __TEXT.__unwind_info: 0x99f8
-  __TEXT.__eh_frame: 0x1078
+  __TEXT.__gcc_except_tab: 0x6b20
+  __TEXT.__unwind_info: 0x9dc0
+  __TEXT.__eh_frame: 0x10e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2498
-  __DATA_CONST.__objc_classlist: 0xd78
-  __DATA_CONST.__objc_catlist: 0x30
+  __DATA_CONST.__const: 0x2758
+  __DATA_CONST.__objc_classlist: 0xdb0
+  __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x3c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9178
+  __DATA_CONST.__objc_selrefs: 0x92e0
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xb98
+  __DATA_CONST.__objc_superrefs: 0xbd8
   __DATA_CONST.__objc_arraydata: 0x200
-  __DATA_CONST.__got: 0x1150
-  __AUTH_CONST.__const: 0x5dd0
-  __AUTH_CONST.__cfstring: 0x10e80
-  __AUTH_CONST.__objc_const: 0x30ea8
+  __DATA_CONST.__got: 0x1188
+  __AUTH_CONST.__const: 0x6408
+  __AUTH_CONST.__cfstring: 0x11260
+  __AUTH_CONST.__objc_const: 0x31a88
   __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__objc_intobj: 0x5a0
+  __AUTH_CONST.__objc_intobj: 0x5d0
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x11b8
-  __AUTH.__objc_data: 0x8330
-  __AUTH.__data: 0x130
+  __AUTH_CONST.__auth_got: 0x1208
+  __AUTH.__objc_data: 0x86a0
+  __AUTH.__data: 0x138
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x28
-  __DATA.__objc_ivar: 0x1cd4
-  __DATA.__data: 0x2fd8
+  __DATA.__objc_ivar: 0x1d28
+  __DATA.__data: 0x3070
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x11a0
+  __DATA.__bss: 0x1cc0
   __DATA.__common: 0x90
   __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x40

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11078
-  Symbols:   22184
-  CStrings:  7135
+  Functions: 11316
+  Symbols:   22579
+  CStrings:  7365
 
Symbols:
+ +[HAPCharacteristicResponseTuple responseTupleForNullValueOfCharacteristic:]
+ +[HAPErrorEntry parsedFromData:error:]
+ +[HAPErrorStatus parsedFromData:error:]
+ +[HAPErrorStatusCodeWrapper parsedFromData:error:]
+ +[HAPIPAddressVersionWrapper parsedFromData:error:]
+ +[HAPTLVSessionTransportEndpointAddress parsedFromData:error:]
+ +[HAPTLVSessionTransportEndpointEntry parsedFromData:error:]
+ +[HAPTLVSessionTransportEndpointList parsedFromData:error:]
+ -[HAP2AccessoryDNSResolver _beginRetryLadderOnQueue]
+ -[HAP2AccessoryDNSResolver _clearPendingRetryRungOnQueue]
+ -[HAP2AccessoryDNSResolver _fireRetryRungOnQueueWithGeneration:]
+ -[HAP2AccessoryDNSResolver _scheduleNextRetryRungOnQueue]
+ -[HAP2AccessoryServer _cancelAccessoryDiscoveryRetry]
+ -[HAP2AccessoryServer _isKeepAliveActive]
+ -[HAP2AccessoryServer _startConfirming]
+ -[HAP2AccessoryServer accessoryDiscoveryRetryTimer]
+ -[HAP2AccessoryServer failedDiscoveryRetryCount]
+ -[HAP2AccessoryServer setAccessoryDiscoveryRetryTimer:]
+ -[HAP2AccessoryServer setFailedDiscoveryRetryCount:]
+ -[HAP2AccessoryServer(Paired) didChangeLocalEndpoints]
+ -[HAP2AccessoryServer(Paired) didRegisterTransportEndpoints:]
+ -[HAP2AccessoryServer(Paired) notifyReestablishedSecureSession]
+ -[HAP2AccessoryServer(Paired) readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServer(Paired) timerDidFire:]
+ -[HAP2AccessoryServerController closeClientOnTransport:completion:]
+ -[HAP2AccessoryServerController didRegisterTransportEndpoints:]
+ -[HAP2AccessoryServerController secureTransportDidChangeLocalEndpoints:]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem _restoreTransportDelegate]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem finishWithError:]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem previousTransportDelegate]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem setPreviousTransportDelegate:]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem setTakenOverTransport:]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem setTakeoverTransportDelegate:]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem takenOverTransport]
+ -[HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem takeoverTransportDelegate]
+ -[HAP2AccessoryServerSecureTransportBase closeClientOnTransport:completion:]
+ -[HAP2AccessoryServerSecureTransportBase didRegisterTransportEndpoints:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsSessionTransportEndpointList:]
+ -[HAP2AccessoryServerSecureTransportBase transportDidChangeLocalEndpoints:]
+ -[HAP2AccessoryServerTransportBase setSupportsSessionTransportEndpointList:]
+ -[HAP2AccessoryServerTransportBase supportsSessionTransportEndpointList]
+ -[HAP2AccessoryServerTransportCoAP _applyResolverAddressesOffQueue:]
+ -[HAP2AccessoryServerTransportCoAP _claimResolveTimeoutTimerExpecting:]
+ -[HAP2AccessoryServerTransportCoAP _enableRacingOnClient:transportType:]
+ -[HAP2AccessoryServerTransportCoAP _maybeApplyOffQueueWhileAwaitingInitialResolve:]
+ -[HAP2AccessoryServerTransportCoAP _notifyLocalEndpointsChanged]
+ -[HAP2AccessoryServerTransportCoAP _probeAcceptedLinkOnClient:transportType:attemptsLeft:]
+ -[HAP2AccessoryServerTransportCoAP _unsecuredClientWithTransportType:]
+ -[HAP2AccessoryServerTransportCoAP acceptedLinkProbeRetryInterval]
+ -[HAP2AccessoryServerTransportCoAP closeClientOnTransport:completion:]
+ -[HAP2AccessoryServerTransportCoAP didRegisterTransportEndpoints:]
+ -[HAP2AccessoryServerTransportCoAP setAcceptedLinkProbeRetryInterval:]
+ -[HAPAccessoryPairingRequest bestEffortNetworkCredentials]
+ -[HAPAccessoryPairingRequest requiredNetworkCredentials]
+ -[HAPAccessoryPairingRequest setBestEffortNetworkCredentials:]
+ -[HAPAccessoryPairingRequest setRequiredNetworkCredentials:]
+ -[HAPAccessoryServer didRegisterTransportEndpoints:]
+ -[HAPAccessoryServer readLocalEndpointsWithCompletion:]
+ -[HAPAccessoryServerBrowser pairSetupSession:pairSetupType:features:pairVerifyTLK:pairingRequest:error:]
+ -[HAPAccessoryServerHAP2Adapter accessoryServer:didUpdateLocalEndpoints:registeredEndpoints:]
+ -[HAPAccessoryServerHAP2Adapter accessoryServerReestablishedSecureSession:]
+ -[HAPAccessoryServerHAP2Adapter didRegisterTransportEndpoints:]
+ -[HAPAccessoryServerHAP2Adapter readLocalEndpointsWithCompletion:]
+ -[HAPCameraBufferActivityCommandRequest initWithStart:duration:activity:reason:]
+ -[HAPCameraBufferActivityCommandRequest reason]
+ -[HAPCameraBufferActivityCommandRequest setReason:]
+ -[HAPCameraVideoStreamCapabilities initWithIdentifier:quality:width:height:framesPerSecond:averageBitrate:peakBitrate:keyFrameInterval:videoCodec:]
+ -[HAPCameraVideoStreamCapabilities keyFrameInterval]
+ -[HAPCameraVideoStreamCapabilities setKeyFrameInterval:]
+ -[HAPCameraVideoStreamCapabilities setVideoCodec:]
+ -[HAPCameraVideoStreamCapabilities videoCodec]
+ -[HAPCharacteristicResponseTuple setValueIsNull:]
+ -[HAPCharacteristicResponseTuple valueIsNull]
+ -[HAPErrorEntry .cxx_destruct]
+ -[HAPErrorEntry copyWithZone:]
+ -[HAPErrorEntry description]
+ -[HAPErrorEntry errorCode]
+ -[HAPErrorEntry initWithErrorCode:manufacturerErrorInfo:]
+ -[HAPErrorEntry init]
+ -[HAPErrorEntry isEqual:]
+ -[HAPErrorEntry manufacturerErrorInfo]
+ -[HAPErrorEntry parseFromData:error:]
+ -[HAPErrorEntry serializeWithError:]
+ -[HAPErrorEntry setErrorCode:]
+ -[HAPErrorEntry setManufacturerErrorInfo:]
+ -[HAPErrorStatus .cxx_destruct]
+ -[HAPErrorStatus copyWithZone:]
+ -[HAPErrorStatus description]
+ -[HAPErrorStatus errorEntry]
+ -[HAPErrorStatus initWithErrorEntry:]
+ -[HAPErrorStatus init]
+ -[HAPErrorStatus isEqual:]
+ -[HAPErrorStatus parseFromData:error:]
+ -[HAPErrorStatus serializeWithError:]
+ -[HAPErrorStatus setErrorEntry:]
+ -[HAPErrorStatusCodeWrapper copyWithZone:]
+ -[HAPErrorStatusCodeWrapper description]
+ -[HAPErrorStatusCodeWrapper initWithValue:]
+ -[HAPErrorStatusCodeWrapper init]
+ -[HAPErrorStatusCodeWrapper isEqual:]
+ -[HAPErrorStatusCodeWrapper parseFromData:error:]
+ -[HAPErrorStatusCodeWrapper serializeWithError:]
+ -[HAPErrorStatusCodeWrapper setValue:]
+ -[HAPErrorStatusCodeWrapper value]
+ -[HAPIPAddressVersionWrapper copyWithZone:]
+ -[HAPIPAddressVersionWrapper description]
+ -[HAPIPAddressVersionWrapper initWithValue:]
+ -[HAPIPAddressVersionWrapper init]
+ -[HAPIPAddressVersionWrapper isEqual:]
+ -[HAPIPAddressVersionWrapper parseFromData:error:]
+ -[HAPIPAddressVersionWrapper serializeWithError:]
+ -[HAPIPAddressVersionWrapper setValue:]
+ -[HAPIPAddressVersionWrapper value]
+ -[HAPTLVSessionTransportEndpointAddress .cxx_destruct]
+ -[HAPTLVSessionTransportEndpointAddress IPAddressVersion]
+ -[HAPTLVSessionTransportEndpointAddress IPAddress]
+ -[HAPTLVSessionTransportEndpointAddress copyWithZone:]
+ -[HAPTLVSessionTransportEndpointAddress description]
+ -[HAPTLVSessionTransportEndpointAddress initWithIPAddressVersion:IPAddress:port:]
+ -[HAPTLVSessionTransportEndpointAddress init]
+ -[HAPTLVSessionTransportEndpointAddress isEqual:]
+ -[HAPTLVSessionTransportEndpointAddress parseFromData:error:]
+ -[HAPTLVSessionTransportEndpointAddress port]
+ -[HAPTLVSessionTransportEndpointAddress serializeWithError:]
+ -[HAPTLVSessionTransportEndpointAddress setIPAddress:]
+ -[HAPTLVSessionTransportEndpointAddress setIPAddressVersion:]
+ -[HAPTLVSessionTransportEndpointAddress setPort:]
+ -[HAPTLVSessionTransportEndpointEntry .cxx_destruct]
+ -[HAPTLVSessionTransportEndpointEntry copyWithZone:]
+ -[HAPTLVSessionTransportEndpointEntry description]
+ -[HAPTLVSessionTransportEndpointEntry endpointAddress]
+ -[HAPTLVSessionTransportEndpointEntry initWithTransportType:endpointAddress:]
+ -[HAPTLVSessionTransportEndpointEntry init]
+ -[HAPTLVSessionTransportEndpointEntry isEqual:]
+ -[HAPTLVSessionTransportEndpointEntry parseFromData:error:]
+ -[HAPTLVSessionTransportEndpointEntry serializeWithError:]
+ -[HAPTLVSessionTransportEndpointEntry setEndpointAddress:]
+ -[HAPTLVSessionTransportEndpointEntry setTransportType:]
+ -[HAPTLVSessionTransportEndpointEntry transportType]
+ -[HAPTLVSessionTransportEndpointList .cxx_destruct]
+ -[HAPTLVSessionTransportEndpointList copyWithZone:]
+ -[HAPTLVSessionTransportEndpointList description]
+ -[HAPTLVSessionTransportEndpointList entries]
+ -[HAPTLVSessionTransportEndpointList initWithEntries:]
+ -[HAPTLVSessionTransportEndpointList init]
+ -[HAPTLVSessionTransportEndpointList isEqual:]
+ -[HAPTLVSessionTransportEndpointList parseFromData:error:]
+ -[HAPTLVSessionTransportEndpointList serializeWithError:]
+ -[HAPTLVSessionTransportEndpointList setEntries:]
+ -[_HAPAccessoryServerBTLE200 _notifyDelegatesOfSecureSessionEstablished]
+ GCC_except_table10037
+ GCC_except_table10044
+ GCC_except_table1016
+ GCC_except_table10220
+ GCC_except_table10222
+ GCC_except_table10224
+ GCC_except_table10227
+ GCC_except_table10229
+ GCC_except_table10231
+ GCC_except_table10233
+ GCC_except_table10234
+ GCC_except_table10241
+ GCC_except_table10243
+ GCC_except_table10244
+ GCC_except_table1028
+ GCC_except_table1029
+ GCC_except_table1031
+ GCC_except_table1034
+ GCC_except_table1037
+ GCC_except_table1051
+ GCC_except_table1055
+ GCC_except_table1059
+ GCC_except_table1066
+ GCC_except_table1069
+ GCC_except_table1103
+ GCC_except_table1113
+ GCC_except_table1121
+ GCC_except_table1148
+ GCC_except_table1152
+ GCC_except_table1155
+ GCC_except_table1157
+ GCC_except_table1169
+ GCC_except_table1171
+ GCC_except_table1190
+ GCC_except_table1196
+ GCC_except_table1200
+ GCC_except_table1211
+ GCC_except_table1212
+ GCC_except_table1217
+ GCC_except_table1220
+ GCC_except_table1223
+ GCC_except_table1228
+ GCC_except_table1232
+ GCC_except_table1238
+ GCC_except_table1242
+ GCC_except_table1243
+ GCC_except_table1271
+ GCC_except_table1278
+ GCC_except_table1286
+ GCC_except_table1287
+ GCC_except_table1303
+ GCC_except_table1325
+ GCC_except_table1344
+ GCC_except_table1366
+ GCC_except_table1370
+ GCC_except_table1384
+ GCC_except_table1389
+ GCC_except_table1494
+ GCC_except_table1496
+ GCC_except_table2054
+ GCC_except_table2059
+ GCC_except_table2061
+ GCC_except_table2075
+ GCC_except_table2087
+ GCC_except_table2089
+ GCC_except_table2091
+ GCC_except_table2093
+ GCC_except_table2223
+ GCC_except_table2229
+ GCC_except_table2231
+ GCC_except_table2433
+ GCC_except_table2653
+ GCC_except_table2655
+ GCC_except_table2660
+ GCC_except_table2666
+ GCC_except_table2674
+ GCC_except_table2676
+ GCC_except_table2688
+ GCC_except_table2692
+ GCC_except_table2698
+ GCC_except_table2700
+ GCC_except_table2702
+ GCC_except_table2710
+ GCC_except_table2722
+ GCC_except_table2724
+ GCC_except_table2737
+ GCC_except_table2745
+ GCC_except_table2760
+ GCC_except_table2802
+ GCC_except_table2918
+ GCC_except_table2923
+ GCC_except_table2924
+ GCC_except_table2926
+ GCC_except_table2928
+ GCC_except_table2940
+ GCC_except_table2945
+ GCC_except_table2949
+ GCC_except_table2952
+ GCC_except_table2954
+ GCC_except_table2959
+ GCC_except_table2976
+ GCC_except_table2986
+ GCC_except_table2988
+ GCC_except_table2990
+ GCC_except_table2995
+ GCC_except_table2998
+ GCC_except_table3000
+ GCC_except_table3003
+ GCC_except_table3006
+ GCC_except_table3010
+ GCC_except_table3012
+ GCC_except_table3015
+ GCC_except_table3020
+ GCC_except_table3022
+ GCC_except_table3024
+ GCC_except_table3028
+ GCC_except_table3034
+ GCC_except_table3042
+ GCC_except_table3055
+ GCC_except_table3097
+ GCC_except_table3098
+ GCC_except_table3099
+ GCC_except_table3101
+ GCC_except_table3102
+ GCC_except_table3103
+ GCC_except_table3105
+ GCC_except_table3109
+ GCC_except_table3110
+ GCC_except_table3136
+ GCC_except_table3140
+ GCC_except_table3144
+ GCC_except_table3346
+ GCC_except_table3354
+ GCC_except_table3355
+ GCC_except_table3356
+ GCC_except_table3357
+ GCC_except_table3358
+ GCC_except_table3359
+ GCC_except_table3375
+ GCC_except_table3389
+ GCC_except_table3469
+ GCC_except_table3481
+ GCC_except_table356
+ GCC_except_table368
+ GCC_except_table3696
+ GCC_except_table3714
+ GCC_except_table3748
+ GCC_except_table3764
+ GCC_except_table3766
+ GCC_except_table3778
+ GCC_except_table3785
+ GCC_except_table379
+ GCC_except_table3807
+ GCC_except_table3821
+ GCC_except_table3822
+ GCC_except_table3823
+ GCC_except_table3834
+ GCC_except_table3841
+ GCC_except_table3844
+ GCC_except_table3849
+ GCC_except_table3854
+ GCC_except_table3859
+ GCC_except_table3900
+ GCC_except_table3917
+ GCC_except_table3920
+ GCC_except_table3925
+ GCC_except_table3927
+ GCC_except_table393
+ GCC_except_table3943
+ GCC_except_table3960
+ GCC_except_table3962
+ GCC_except_table3966
+ GCC_except_table3974
+ GCC_except_table398
+ GCC_except_table3982
+ GCC_except_table403
+ GCC_except_table4046
+ GCC_except_table4053
+ GCC_except_table4055
+ GCC_except_table4056
+ GCC_except_table4079
+ GCC_except_table4099
+ GCC_except_table412
+ GCC_except_table418
+ GCC_except_table420
+ GCC_except_table422
+ GCC_except_table4328
+ GCC_except_table434
+ GCC_except_table4403
+ GCC_except_table4410
+ GCC_except_table4414
+ GCC_except_table4416
+ GCC_except_table4418
+ GCC_except_table4420
+ GCC_except_table4424
+ GCC_except_table4427
+ GCC_except_table4433
+ GCC_except_table4444
+ GCC_except_table4462
+ GCC_except_table4469
+ GCC_except_table4479
+ GCC_except_table4482
+ GCC_except_table4493
+ GCC_except_table4494
+ GCC_except_table4496
+ GCC_except_table4498
+ GCC_except_table4501
+ GCC_except_table4505
+ GCC_except_table4507
+ GCC_except_table4510
+ GCC_except_table4525
+ GCC_except_table4527
+ GCC_except_table4531
+ GCC_except_table4535
+ GCC_except_table4539
+ GCC_except_table4544
+ GCC_except_table4557
+ GCC_except_table4576
+ GCC_except_table4605
+ GCC_except_table4609
+ GCC_except_table4613
+ GCC_except_table4615
+ GCC_except_table4618
+ GCC_except_table4620
+ GCC_except_table4622
+ GCC_except_table4629
+ GCC_except_table4630
+ GCC_except_table4631
+ GCC_except_table4632
+ GCC_except_table4633
+ GCC_except_table4635
+ GCC_except_table4636
+ GCC_except_table4637
+ GCC_except_table467
+ GCC_except_table4724
+ GCC_except_table4726
+ GCC_except_table4728
+ GCC_except_table4730
+ GCC_except_table4731
+ GCC_except_table4732
+ GCC_except_table4733
+ GCC_except_table4734
+ GCC_except_table4735
+ GCC_except_table4736
+ GCC_except_table4737
+ GCC_except_table4738
+ GCC_except_table482
+ GCC_except_table483
+ GCC_except_table4877
+ GCC_except_table4879
+ GCC_except_table4881
+ GCC_except_table4883
+ GCC_except_table4885
+ GCC_except_table492
+ GCC_except_table4922
+ GCC_except_table4934
+ GCC_except_table494
+ GCC_except_table496
+ GCC_except_table497
+ GCC_except_table4976
+ GCC_except_table4980
+ GCC_except_table4981
+ GCC_except_table4983
+ GCC_except_table4985
+ GCC_except_table4988
+ GCC_except_table4991
+ GCC_except_table4994
+ GCC_except_table4997
+ GCC_except_table5000
+ GCC_except_table5003
+ GCC_except_table5006
+ GCC_except_table5009
+ GCC_except_table5014
+ GCC_except_table5027
+ GCC_except_table5032
+ GCC_except_table5038
+ GCC_except_table505
+ GCC_except_table5055
+ GCC_except_table5070
+ GCC_except_table5076
+ GCC_except_table5077
+ GCC_except_table5080
+ GCC_except_table5081
+ GCC_except_table5099
+ GCC_except_table5103
+ GCC_except_table5104
+ GCC_except_table5107
+ GCC_except_table5116
+ GCC_except_table5118
+ GCC_except_table5127
+ GCC_except_table5129
+ GCC_except_table5131
+ GCC_except_table5145
+ GCC_except_table5156
+ GCC_except_table5158
+ GCC_except_table5169
+ GCC_except_table5173
+ GCC_except_table5179
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table530
+ GCC_except_table531
+ GCC_except_table536
+ GCC_except_table537
+ GCC_except_table543
+ GCC_except_table5461
+ GCC_except_table5467
+ GCC_except_table5484
+ GCC_except_table5488
+ GCC_except_table5506
+ GCC_except_table5512
+ GCC_except_table5526
+ GCC_except_table553
+ GCC_except_table556
+ GCC_except_table559
+ GCC_except_table560
+ GCC_except_table565
+ GCC_except_table5662
+ GCC_except_table568
+ GCC_except_table569
+ GCC_except_table572
+ GCC_except_table578
+ GCC_except_table583
+ GCC_except_table591
+ GCC_except_table5985
+ GCC_except_table5987
+ GCC_except_table5989
+ GCC_except_table5991
+ GCC_except_table607
+ GCC_except_table6181
+ GCC_except_table6190
+ GCC_except_table6191
+ GCC_except_table6204
+ GCC_except_table6246
+ GCC_except_table6249
+ GCC_except_table6250
+ GCC_except_table6251
+ GCC_except_table6252
+ GCC_except_table628
+ GCC_except_table629
+ GCC_except_table631
+ GCC_except_table632
+ GCC_except_table635
+ GCC_except_table6352
+ GCC_except_table6353
+ GCC_except_table6354
+ GCC_except_table6355
+ GCC_except_table6356
+ GCC_except_table6357
+ GCC_except_table6358
+ GCC_except_table6359
+ GCC_except_table636
+ GCC_except_table6361
+ GCC_except_table6382
+ GCC_except_table6393
+ GCC_except_table6395
+ GCC_except_table6400
+ GCC_except_table6403
+ GCC_except_table6406
+ GCC_except_table6410
+ GCC_except_table6414
+ GCC_except_table651
+ GCC_except_table654
+ GCC_except_table661
+ GCC_except_table664
+ GCC_except_table689
+ GCC_except_table691
+ GCC_except_table6965
+ GCC_except_table6966
+ GCC_except_table6995
+ GCC_except_table6998
+ GCC_except_table7003
+ GCC_except_table7006
+ GCC_except_table7011
+ GCC_except_table7280
+ GCC_except_table7284
+ GCC_except_table7344
+ GCC_except_table7348
+ GCC_except_table7350
+ GCC_except_table7352
+ GCC_except_table7528
+ GCC_except_table7536
+ GCC_except_table7538
+ GCC_except_table7540
+ GCC_except_table7542
+ GCC_except_table7548
+ GCC_except_table7561
+ GCC_except_table7580
+ GCC_except_table7591
+ GCC_except_table7605
+ GCC_except_table7611
+ GCC_except_table7616
+ GCC_except_table7618
+ GCC_except_table7622
+ GCC_except_table7624
+ GCC_except_table7700
+ GCC_except_table7707
+ GCC_except_table7711
+ GCC_except_table7712
+ GCC_except_table7713
+ GCC_except_table7714
+ GCC_except_table7723
+ GCC_except_table7739
+ GCC_except_table7775
+ GCC_except_table7776
+ GCC_except_table7777
+ GCC_except_table7797
+ GCC_except_table7809
+ GCC_except_table7812
+ GCC_except_table7817
+ GCC_except_table7819
+ GCC_except_table7833
+ GCC_except_table8110
+ GCC_except_table8123
+ GCC_except_table8128
+ GCC_except_table8131
+ GCC_except_table8132
+ GCC_except_table8134
+ GCC_except_table8135
+ GCC_except_table8167
+ GCC_except_table8191
+ GCC_except_table8195
+ GCC_except_table8199
+ GCC_except_table8204
+ GCC_except_table8208
+ GCC_except_table8212
+ GCC_except_table8216
+ GCC_except_table8220
+ GCC_except_table8228
+ GCC_except_table8230
+ GCC_except_table8234
+ GCC_except_table8298
+ GCC_except_table8299
+ GCC_except_table8300
+ GCC_except_table8301
+ GCC_except_table8302
+ GCC_except_table8303
+ GCC_except_table8304
+ GCC_except_table8369
+ GCC_except_table8383
+ GCC_except_table8384
+ GCC_except_table8389
+ GCC_except_table8390
+ GCC_except_table8397
+ GCC_except_table8417
+ GCC_except_table8419
+ GCC_except_table8425
+ GCC_except_table8429
+ GCC_except_table8449
+ GCC_except_table8452
+ GCC_except_table8453
+ GCC_except_table8458
+ GCC_except_table8461
+ GCC_except_table8468
+ GCC_except_table8471
+ GCC_except_table8485
+ GCC_except_table8498
+ GCC_except_table8507
+ GCC_except_table8509
+ GCC_except_table8515
+ GCC_except_table8516
+ GCC_except_table8523
+ GCC_except_table8547
+ GCC_except_table8548
+ GCC_except_table8553
+ GCC_except_table8557
+ GCC_except_table8558
+ GCC_except_table8561
+ GCC_except_table8567
+ GCC_except_table8571
+ GCC_except_table8575
+ GCC_except_table8577
+ GCC_except_table8583
+ GCC_except_table8737
+ GCC_except_table8774
+ GCC_except_table8832
+ GCC_except_table8835
+ GCC_except_table8848
+ GCC_except_table8855
+ GCC_except_table8856
+ GCC_except_table8872
+ GCC_except_table8876
+ GCC_except_table8877
+ GCC_except_table8878
+ GCC_except_table8927
+ GCC_except_table8928
+ GCC_except_table8930
+ GCC_except_table8933
+ GCC_except_table8960
+ GCC_except_table8961
+ GCC_except_table8966
+ GCC_except_table8986
+ GCC_except_table9005
+ GCC_except_table9013
+ GCC_except_table9018
+ GCC_except_table9021
+ GCC_except_table9022
+ GCC_except_table9027
+ GCC_except_table9029
+ GCC_except_table9041
+ GCC_except_table9044
+ GCC_except_table9046
+ GCC_except_table9048
+ GCC_except_table9051
+ GCC_except_table9055
+ GCC_except_table9060
+ GCC_except_table9061
+ GCC_except_table9062
+ GCC_except_table9078
+ GCC_except_table9080
+ GCC_except_table9083
+ GCC_except_table9089
+ GCC_except_table9097
+ GCC_except_table9102
+ GCC_except_table9115
+ GCC_except_table9127
+ GCC_except_table9128
+ GCC_except_table9133
+ GCC_except_table9145
+ GCC_except_table9146
+ GCC_except_table9149
+ GCC_except_table9151
+ GCC_except_table9157
+ GCC_except_table9178
+ GCC_except_table9180
+ GCC_except_table9181
+ GCC_except_table9207
+ GCC_except_table9372
+ GCC_except_table9435
+ GCC_except_table9467
+ GCC_except_table9470
+ GCC_except_table949
+ GCC_except_table959
+ GCC_except_table9637
+ GCC_except_table9675
+ GCC_except_table9712
+ GCC_except_table973
+ GCC_except_table984
+ GCC_except_table9840
+ GCC_except_table9842
+ GCC_except_table9844
+ GCC_except_table9846
+ GCC_except_table9848
+ GCC_except_table9850
+ GCC_except_table9852
+ GCC_except_table9860
+ GCC_except_table9863
+ GCC_except_table9865
+ GCC_except_table9867
+ GCC_except_table9876
+ GCC_except_table9887
+ GCC_except_table9890
+ GCC_except_table9903
+ GCC_except_table9906
+ GCC_except_table9932
+ GCC_except_table9935
+ GCC_except_table9936
+ GCC_except_table9960
+ GCC_except_table9961
+ GCC_except_table9962
+ GCC_except_table9964
+ GCC_except_table9965
+ GCC_except_table9967
+ GCC_except_table9968
+ GCC_except_table9969
+ GCC_except_table9971
+ GCC_except_table9972
+ GCC_except_table9974
+ GCC_except_table9978
+ GCC_except_table9979
+ GCC_except_table9985
+ _HAP2ResolverDNSSDCode
+ _HAPCharacteristicUUID_ErrorStatus
+ _HAPErrorStatusCodeAsString
+ _HAPIPAddressVersionAsString
+ _HAPTLVParseLimitedLengthContiguousTLVs
+ _OBJC_CLASS_$_HAPErrorEntry
+ _OBJC_CLASS_$_HAPErrorStatus
+ _OBJC_CLASS_$_HAPErrorStatusCodeWrapper
+ _OBJC_CLASS_$_HAPIPAddressVersionWrapper
+ _OBJC_CLASS_$_HAPTLVSessionTransportEndpointAddress
+ _OBJC_CLASS_$_HAPTLVSessionTransportEndpointEntry
+ _OBJC_CLASS_$_HAPTLVSessionTransportEndpointList
+ _OBJC_CLASS_$_HMFExponentialBackoffTimer
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._everDelivered
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._isSubscribed
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._retryGeneration
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._retryPending
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._retryRung
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._stopped
+ _OBJC_IVAR_$_HAP2AccessoryServer._accessoryDiscoveryRetryTimer
+ _OBJC_IVAR_$_HAP2AccessoryServer._failedDiscoveryRetryCount
+ _OBJC_IVAR_$_HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem._previousTransportDelegate
+ _OBJC_IVAR_$_HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem._takenOverTransport
+ _OBJC_IVAR_$_HAP2AccessoryServerPairingDriverSoftwareAuthWorkItem._takeoverTransportDelegate
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsSessionTransportEndpointList
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._acceptedLinkProbeRetryInterval
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._registeredTransportEndpoints
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolveTimeoutClaimLock
+ _OBJC_IVAR_$_HAPAccessoryPairingRequest._bestEffortNetworkCredentials
+ _OBJC_IVAR_$_HAPAccessoryPairingRequest._requiredNetworkCredentials
+ _OBJC_IVAR_$_HAPCameraBufferActivityCommandRequest._reason
+ _OBJC_IVAR_$_HAPCameraVideoStreamCapabilities._keyFrameInterval
+ _OBJC_IVAR_$_HAPCameraVideoStreamCapabilities._videoCodec
+ _OBJC_IVAR_$_HAPCharacteristicResponseTuple._valueIsNull
+ _OBJC_IVAR_$_HAPErrorEntry._errorCode
+ _OBJC_IVAR_$_HAPErrorEntry._manufacturerErrorInfo
+ _OBJC_IVAR_$_HAPErrorStatus._errorEntry
+ _OBJC_IVAR_$_HAPErrorStatusCodeWrapper._value
+ _OBJC_IVAR_$_HAPIPAddressVersionWrapper._value
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointAddress._IPAddress
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointAddress._IPAddressVersion
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointAddress._port
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointEntry._endpointAddress
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointEntry._transportType
+ _OBJC_IVAR_$_HAPTLVSessionTransportEndpointList._entries
+ _OBJC_METACLASS_$_HAPErrorEntry
+ _OBJC_METACLASS_$_HAPErrorStatus
+ _OBJC_METACLASS_$_HAPErrorStatusCodeWrapper
+ _OBJC_METACLASS_$_HAPIPAddressVersionWrapper
+ _OBJC_METACLASS_$_HAPTLVSessionTransportEndpointAddress
+ _OBJC_METACLASS_$_HAPTLVSessionTransportEndpointEntry
+ _OBJC_METACLASS_$_HAPTLVSessionTransportEndpointList
+ __OBJC_$_CLASS_METHODS_HAPErrorEntry
+ __OBJC_$_CLASS_METHODS_HAPErrorStatus
+ __OBJC_$_CLASS_METHODS_HAPErrorStatusCodeWrapper
+ __OBJC_$_CLASS_METHODS_HAPIPAddressVersionWrapper
+ __OBJC_$_CLASS_METHODS_HAPTLVSessionTransportEndpointAddress
+ __OBJC_$_CLASS_METHODS_HAPTLVSessionTransportEndpointEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVSessionTransportEndpointList
+ __OBJC_$_INSTANCE_METHODS_HAPErrorEntry
+ __OBJC_$_INSTANCE_METHODS_HAPErrorStatus
+ __OBJC_$_INSTANCE_METHODS_HAPErrorStatusCodeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPIPAddressVersionWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSessionTransportEndpointAddress
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSessionTransportEndpointEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSessionTransportEndpointList
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorStatus
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorStatusCodeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPIPAddressVersionWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSessionTransportEndpointAddress
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSessionTransportEndpointEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSessionTransportEndpointList
+ __OBJC_$_PROP_LIST_HAPErrorEntry
+ __OBJC_$_PROP_LIST_HAPErrorStatus
+ __OBJC_$_PROP_LIST_HAPErrorStatusCodeWrapper
+ __OBJC_$_PROP_LIST_HAPIPAddressVersionWrapper
+ __OBJC_$_PROP_LIST_HAPTLVSessionTransportEndpointAddress
+ __OBJC_$_PROP_LIST_HAPTLVSessionTransportEndpointEntry
+ __OBJC_$_PROP_LIST_HAPTLVSessionTransportEndpointList
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorStatus
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorStatusCodeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPIPAddressVersionWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSessionTransportEndpointAddress
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSessionTransportEndpointEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSessionTransportEndpointList
+ __OBJC_CLASS_RO_$_HAPErrorEntry
+ __OBJC_CLASS_RO_$_HAPErrorStatus
+ __OBJC_CLASS_RO_$_HAPErrorStatusCodeWrapper
+ __OBJC_CLASS_RO_$_HAPIPAddressVersionWrapper
+ __OBJC_CLASS_RO_$_HAPTLVSessionTransportEndpointAddress
+ __OBJC_CLASS_RO_$_HAPTLVSessionTransportEndpointEntry
+ __OBJC_CLASS_RO_$_HAPTLVSessionTransportEndpointList
+ __OBJC_METACLASS_RO_$_HAPErrorEntry
+ __OBJC_METACLASS_RO_$_HAPErrorStatus
+ __OBJC_METACLASS_RO_$_HAPErrorStatusCodeWrapper
+ __OBJC_METACLASS_RO_$_HAPIPAddressVersionWrapper
+ __OBJC_METACLASS_RO_$_HAPTLVSessionTransportEndpointAddress
+ __OBJC_METACLASS_RO_$_HAPTLVSessionTransportEndpointEntry
+ __OBJC_METACLASS_RO_$_HAPTLVSessionTransportEndpointList
+ ___44-[HAP2AccessoryServer(Paired) timerDidFire:]_block_invoke
+ ___54-[HAP2AccessoryServer(Paired) didChangeLocalEndpoints]_block_invoke
+ ___54-[HAP2AccessoryServer(Paired) didChangeLocalEndpoints]_block_invoke_2
+ ___57-[HAP2AccessoryDNSResolver _scheduleNextRetryRungOnQueue]_block_invoke
+ ___61-[HAP2AccessoryServer(Paired) didRegisterTransportEndpoints:]_block_invoke
+ ___61-[HAP2AccessoryServer(Paired) readLocalEndpointsWithHandler:]_block_invoke
+ ___63-[HAP2AccessoryServer(Paired) notifyReestablishedSecureSession]_block_invoke
+ ___63-[HAP2AccessoryServerController didRegisterTransportEndpoints:]_block_invoke
+ ___66-[HAP2AccessoryServerTransportCoAP didRegisterTransportEndpoints:]_block_invoke
+ ___67-[HAP2AccessoryServerController closeClientOnTransport:completion:]_block_invoke
+ ___67-[HAP2AccessoryServerController closeClientOnTransport:completion:]_block_invoke_2
+ ___70-[HAP2AccessoryServerTransportCoAP closeClientOnTransport:completion:]_block_invoke
+ ___72-[HAP2AccessoryServerSecureTransportBase didRegisterTransportEndpoints:]_block_invoke
+ ___72-[_HAPAccessoryServerBTLE200 _notifyDelegatesOfSecureSessionEstablished]_block_invoke
+ ___75-[HAP2AccessoryServerSecureTransportBase transportDidChangeLocalEndpoints:]_block_invoke
+ ___75-[HAPAccessoryServerHAP2Adapter accessoryServerReestablishedSecureSession:]_block_invoke
+ ___76-[HAP2AccessoryServerSecureTransportBase closeClientOnTransport:completion:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _probeAcceptedLinkOnClient:transportType:attemptsLeft:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _probeAcceptedLinkOnClient:transportType:attemptsLeft:]_block_invoke_2
+ ___block_descriptor_32_e1275_v24?0"HAP2CoAPClient"8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_40_e8_32w_e39_v24?0"NSDictionary"8"NSDictionary"16l
+ ___block_descriptor_48_e1275_v24?0"HAP2CoAPClient"8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32bs40r_e8_v16?0q8l
+ ___block_descriptor_48_e8_32bs40w_e1638_v24?0^{coap_context_t={coap_opt_filter_t=S[2S][6C]}^{coap_resource_t}^{coap_resource_t}^{coap_resource_t}^?Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^vI^?^?^?^?^v{coap_dtls_spsk_t=CC[6C]^?^v^?^v{coap_dtls_spsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}IIIIIIQ^{coap_cache_entry_t}^SQ^vI{fd_set=[32i]}{fd_set=[32i]}{fd_set=[32i]}[64^{coap_socket_t}]ICCCCI}8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32s40bs_e1638_v24?0^{coap_context_t={coap_opt_filter_t=S[2S][6C]}^{coap_resource_t}^{coap_resource_t}^{coap_resource_t}^?Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^vI^?^?^?^?^v{coap_dtls_spsk_t=CC[6C]^?^v^?^v{coap_dtls_spsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}IIIIIIQ^{coap_cache_entry_t}^SQ^vI{fd_set=[32i]}{fd_set=[32i]}{fd_set=[32i]}[64^{coap_socket_t}]ICCCCI}8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32s_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32s40s48bs_e1638_v24?0^{coap_context_t={coap_opt_filter_t=S[2S][6C]}^{coap_resource_t}^{coap_resource_t}^{coap_resource_t}^?Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^vI^?^?^?^?^v{coap_dtls_spsk_t=CC[6C]^?^v^?^v{coap_dtls_spsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}IIIIIIQ^{coap_cache_entry_t}^SQ^vI{fd_set=[32i]}{fd_set=[32i]}{fd_set=[32i]}[64^{coap_socket_t}]ICCCCI}8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_56_e8_32w40w_e8_v16?0q8l
+ ___block_descriptor_57_e8_32bs40w_e5_v8?0l
+ ___block_descriptor_64_e8_32bs40w48w_e5_v8?0l
+ ___block_descriptor_64_e8_32bs40w48w_e8_v12?0B8l
+ ___block_descriptor_64_e8_32s40w_e5_v8?0l
+ ___block_descriptor_64_e8_32w40w_e5_v8?0l
+ ___block_descriptor_68_e8_32s40s48bs_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_71_e8_32s40s48s_e1275_v24?0"HAP2CoAPClient"8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_72_e8_32s40bs48bs56r64w_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48bs56r64w_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56w_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48w_e5_v8?0l
+ ___block_descriptor_76_e8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56r64r72r_e39_v32?0"<HAP2AccessoryPrivate>"8Q16^B24l
+ ___block_descriptor_88_e8_32s40s48s56w_e28_v24?0"NSData"8"NSError"16l
+ ___copy_helper_block_e8_32s40b48b56r64w
+ ___copy_helper_block_e8_32s40s48b56r64w
+ ___copy_helper_block_e8_32w40w
+ ___destroy_helper_block_e8_32s40s48s56r64w
+ ___destroy_helper_block_e8_32w40w
+ ___swift_closure_destructor.242Tm
+ ___swift_memcpy24_8
+ _arc4random_uniform
+ _associated conformance So25HAPNetworkCredentialTypesVs10SetAlgebraSCSQ
+ _associated conformance So25HAPNetworkCredentialTypesVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So25HAPNetworkCredentialTypesVs9OptionSetSCSY
+ _associated conformance So25HAPNetworkCredentialTypesVs9OptionSetSCs0E7Algebra
+ _b_ipv4
+ _bcst_cnt
+ _cache_ignore_options
+ _check_freshness
+ _check_token_size
+ _cid_track_counter
+ _coap_add_block_b_data
+ _coap_add_data
+ _coap_add_data_large_internal
+ _coap_add_option_internal
+ _coap_address_equals
+ _coap_block_build_body
+ _coap_block_check_lg_xmit_timeouts
+ _coap_block_delete_lg_crcv
+ _coap_block_delete_lg_srcv
+ _coap_block_delete_lg_xmit
+ _coap_block_new_lg_crcv
+ _coap_cache_derive_key_w_ignore
+ _coap_cancel_observe_lkd
+ _coap_check_code_lg_xmit
+ _coap_check_send_need_lg_crcv
+ _coap_check_update_token
+ _coap_client_delay_first
+ _coap_delete_cache_entry
+ _coap_delete_node_lkd
+ _coap_delete_observer_internal
+ _coap_delete_observer_request
+ _coap_digest_update
+ _coap_dtls_close
+ _coap_dtls_establish
+ _coap_dtls_send
+ _coap_encode_var_safe8
+ _coap_endpoint_str
+ _coap_find_lg_xmit_response
+ _coap_find_lg_xmit_response.empty
+ _coap_find_observer_cache_key
+ _coap_get_block_b
+ _coap_get_data_large
+ _coap_get_query
+ _coap_get_resource_from_uri_path_lkd
+ _coap_get_uri_path.hex
+ _coap_handle_event_lkd
+ _coap_handle_request_put_block
+ _coap_handle_request_send_block
+ _coap_handle_response_get_block
+ _coap_insert_option
+ _coap_io_process_with_fds_lkd
+ _coap_is_bcast
+ _coap_is_mcast
+ _coap_layers_coap
+ _coap_netif_close
+ _coap_netif_dgrm_write
+ _coap_notify_observers
+ _coap_opt_encode
+ _coap_option_check_repeatable
+ _coap_pdu_duplicate_lkd
+ _coap_pdu_parse_opt.outbuf
+ _coap_pdu_parse_opt_base
+ _coap_pdu_parse_opt_csm
+ _coap_print_ip_addr
+ _coap_print_wellknown_lkd
+ _coap_print_wellknown_lkd._rt_attributes
+ _coap_prng_default
+ _coap_remove_option
+ _coap_send_ack_lkd
+ _coap_send_internal
+ _coap_send_message_type_lkd
+ _coap_send_test_extended_token
+ _coap_session_apply_rtt_sample
+ _coap_session_disconnected_lkd
+ _coap_session_establish
+ _coap_session_max_pdu_size_lkd
+ _coap_session_release_lkd
+ _coap_session_send_ping_lkd
+ _coap_session_set_ack_timeout
+ _coap_session_set_max_retransmit
+ _coap_socket_connect_udp
+ _coap_socket_recv
+ _coap_split_uri_sub
+ _coap_startup.well_known
+ _coap_update_option
+ _coap_update_token
+ _coap_uri_scheme
+ _fls
+ _flsll
+ _free_wellknown_response
+ _hnd_get_wellknown_lkd
+ _is_unescaped_in_path
+ _kAccessoryDiscoveryRetryMaximumFailures
+ _kHAP2DNSSDErrorDomain
+ _kHAP2ResolverRetryLadder
+ _last_refresh
+ _localtime_r
+ _logCategory._hmf_once_t905
+ _logCategory._hmf_once_v906
+ _messageIsPing
+ _msg_code_string
+ _next_option_safe
+ _objc_msgSend$IPAddress
+ _objc_msgSend$IPAddressVersion
+ _objc_msgSend$_applyResolverAddressesOffQueue:
+ _objc_msgSend$_beginRetryLadderOnQueue
+ _objc_msgSend$_claimResolveTimeoutTimerExpecting:
+ _objc_msgSend$_clearPendingRetryRungOnQueue
+ _objc_msgSend$_fireRetryRungOnQueueWithGeneration:
+ _objc_msgSend$_maybeApplyOffQueueWhileAwaitingInitialResolve:
+ _objc_msgSend$_notifyDelegatesOfSecureSessionEstablished
+ _objc_msgSend$_restoreTransportDelegate
+ _objc_msgSend$_scheduleNextRetryRungOnQueue
+ _objc_msgSend$acceptedLinkProbeRetryInterval
+ _objc_msgSend$accessory:didUpdateLocalEndpoints:registeredEndpoints:
+ _objc_msgSend$accessoryDiscoveryRetryTimer
+ _objc_msgSend$accessoryServer:didUpdateLocalEndpoints:registeredEndpoints:
+ _objc_msgSend$accessoryServerDidEstablishSecureSession:
+ _objc_msgSend$accessoryServerReestablishedSecureSession:
+ _objc_msgSend$bestEffortNetworkCredentials
+ _objc_msgSend$closeClientOnTransport:completion:
+ _objc_msgSend$didChangeLocalEndpoints
+ _objc_msgSend$didRegisterTransportEndpoints:
+ _objc_msgSend$endpointAddress
+ _objc_msgSend$errorCode
+ _objc_msgSend$errorEntry
+ _objc_msgSend$failedDiscoveryRetryCount
+ _objc_msgSend$initWithErrorCode:manufacturerErrorInfo:
+ _objc_msgSend$initWithErrorEntry:
+ _objc_msgSend$initWithIPAddressVersion:IPAddress:port:
+ _objc_msgSend$initWithIdentifier:quality:width:height:framesPerSecond:averageBitrate:peakBitrate:keyFrameInterval:videoCodec:
+ _objc_msgSend$initWithMinimumTimeInterval:maximumTimeInterval:exponentialFactor:options:
+ _objc_msgSend$initWithRole:pairSetupType:featureFlags:delegate:pairVerifyTLK:pairingRequest:
+ _objc_msgSend$initWithStart:duration:activity:reason:
+ _objc_msgSend$initWithTransportType:endpointAddress:
+ _objc_msgSend$keyFrameInterval
+ _objc_msgSend$manufacturerErrorInfo
+ _objc_msgSend$pairSetupSession:pairSetupType:features:pairVerifyTLK:pairingRequest:error:
+ _objc_msgSend$pairVerifyTLKForPairSetupSession:
+ _objc_msgSend$previousTransportDelegate
+ _objc_msgSend$processInfo
+ _objc_msgSend$requiredNetworkCredentials
+ _objc_msgSend$respondsToSelector:
+ _objc_msgSend$secureTransportDidChangeLocalEndpoints:
+ _objc_msgSend$setAccessoryDiscoveryRetryTimer:
+ _objc_msgSend$setBestEffortNetworkCredentials:
+ _objc_msgSend$setEndpointAddress:
+ _objc_msgSend$setErrorCode:
+ _objc_msgSend$setErrorEntry:
+ _objc_msgSend$setFailedDiscoveryRetryCount:
+ _objc_msgSend$setIPAddress:
+ _objc_msgSend$setIPAddressVersion:
+ _objc_msgSend$setKeyFrameInterval:
+ _objc_msgSend$setManufacturerErrorInfo:
+ _objc_msgSend$setPort:
+ _objc_msgSend$setPreviousTransportDelegate:
+ _objc_msgSend$setReason:
+ _objc_msgSend$setRequiredNetworkCredentials:
+ _objc_msgSend$setSupportsSessionTransportEndpointList:
+ _objc_msgSend$setTakenOverTransport:
+ _objc_msgSend$setTakeoverTransportDelegate:
+ _objc_msgSend$setValueIsNull:
+ _objc_msgSend$setVideoCodec:
+ _objc_msgSend$supportsSessionTransportEndpointList
+ _objc_msgSend$takenOverTransport
+ _objc_msgSend$takeoverTransportDelegate
+ _objc_msgSend$transportDidChangeLocalEndpoints:
+ _objc_msgSend$videoCodec
+ _random
+ _resource_uri_wellknown
+ _setup_block_b
+ _srandom
+ _strchr
+ _strcpy
+ _strstr
+ _symbolic Sd
+ _symbolic SdSg
+ _symbolic _____ 7CoreHAP24HAPSpakePairSetupSessionC8ParkedM533_FFB3B66732484B0775DD4AE3FA14FD0DLLV
+ _symbolic _____ So25HAPNetworkCredentialTypesV
+ _symbolic _____Sg 7CoreHAP24HAPSpakePairSetupSessionC8ParkedM533_FFB3B66732484B0775DD4AE3FA14FD0DLLV
+ _symbolic _____Sg So25HAPNetworkCredentialTypesV
+ _track_echo
+ _track_fetch_observe
+ _type_layout_string 7CoreHAP24HAPSpakePairSetupSessionC8ParkedM533_FFB3B66732484B0775DD4AE3FA14FD0DLLV
+ _type_layout_string So29HAPCHMThreadConnectivityStateV
+ _update_received_blocks
+ _write_char
- -[HAP2AccessoryServer _runLostDiscoveryAdvertisementSideEffectsWithWillSleep:]
- -[HAPAccessoryServer pairSetupM1ToM4Completed]
- -[HAPAccessoryServer pairSetupM1ToM4DurationMS]
- -[HAPAccessoryServer pairSetupM1ToM4Error]
- -[HAPAccessoryServer pairSetupM5ToM6Completed]
- -[HAPAccessoryServer pairSetupM5ToM6DurationMS]
- -[HAPAccessoryServer pairSetupM5ToM6Error]
- -[HAPAccessoryServer setPairSetupM1ToM4Completed:]
- -[HAPAccessoryServer setPairSetupM1ToM4DurationMS:]
- -[HAPAccessoryServer setPairSetupM1ToM4Error:]
- -[HAPAccessoryServer setPairSetupM5ToM6Completed:]
- -[HAPAccessoryServer setPairSetupM5ToM6DurationMS:]
- -[HAPAccessoryServer setPairSetupM5ToM6Error:]
- -[HAPAccessoryServer setTokenAuthCompleted:]
- -[HAPAccessoryServer setTokenAuthDurationMS:]
- -[HAPAccessoryServer setTokenAuthError:]
- -[HAPAccessoryServer tokenAuthCompleted]
- -[HAPAccessoryServer tokenAuthDurationMS]
- -[HAPAccessoryServer tokenAuthError]
- -[HAPAccessoryServerBrowser pairSetupSession:pairSetupType:features:pairVerifyTLK:error:]
- -[HAPAccessoryServerHAP2Adapter accessoryServer:didUpdateLocalEndpoints:]
- -[HAPAccessoryServerIP ensureNetworkMonitor]
- -[HAPAccessoryServerIP networkMonitor]
- -[HAPCameraBufferActivityCommandRequest initWithStart:duration:activity:]
- -[HAPCameraVideoStreamCapabilities initWithIdentifier:quality:width:height:framesPerSecond:averageBitrate:peakBitrate:]
- -[HAPSystemKeychainStore allLegacyAccessoryPairingKeys]
- -[HAPSystemKeychainStore deletePairingKeysForAccessory:error:]
- -[HAPSystemKeychainStore readAccessoryPairingKeyForAccessory:error:]
- -[HMFPairingIdentity(HAPKeyStore) isControllerKey]
- GCC_except_table10066
- GCC_except_table10068
- GCC_except_table10070
- GCC_except_table10073
- GCC_except_table10075
- GCC_except_table10077
- GCC_except_table10079
- GCC_except_table10080
- GCC_except_table10087
- GCC_except_table10089
- GCC_except_table10090
- GCC_except_table1012
- GCC_except_table1017
- GCC_except_table1164
- GCC_except_table1166
- GCC_except_table1233
- GCC_except_table1235
- GCC_except_table1237
- GCC_except_table1239
- GCC_except_table1779
- GCC_except_table1784
- GCC_except_table1788
- GCC_except_table1802
- GCC_except_table1816
- GCC_except_table1818
- GCC_except_table1820
- GCC_except_table1822
- GCC_except_table1952
- GCC_except_table1958
- GCC_except_table1960
- GCC_except_table2162
- GCC_except_table2378
- GCC_except_table2380
- GCC_except_table2385
- GCC_except_table2391
- GCC_except_table2393
- GCC_except_table2399
- GCC_except_table2401
- GCC_except_table2405
- GCC_except_table2413
- GCC_except_table2417
- GCC_except_table2423
- GCC_except_table2425
- GCC_except_table2427
- GCC_except_table2429
- GCC_except_table2435
- GCC_except_table2439
- GCC_except_table2447
- GCC_except_table2449
- GCC_except_table2462
- GCC_except_table2470
- GCC_except_table2477
- GCC_except_table2481
- GCC_except_table2485
- GCC_except_table2527
- GCC_except_table2646
- GCC_except_table2651
- GCC_except_table2652
- GCC_except_table2654
- GCC_except_table2656
- GCC_except_table2673
- GCC_except_table2677
- GCC_except_table2682
- GCC_except_table2687
- GCC_except_table2716
- GCC_except_table2718
- GCC_except_table2723
- GCC_except_table2726
- GCC_except_table2728
- GCC_except_table2731
- GCC_except_table2734
- GCC_except_table2738
- GCC_except_table2740
- GCC_except_table2743
- GCC_except_table2748
- GCC_except_table2750
- GCC_except_table2762
- GCC_except_table2770
- GCC_except_table2783
- GCC_except_table2826
- GCC_except_table2827
- GCC_except_table2828
- GCC_except_table2830
- GCC_except_table2831
- GCC_except_table2832
- GCC_except_table2834
- GCC_except_table2838
- GCC_except_table2839
- GCC_except_table2865
- GCC_except_table2869
- GCC_except_table2873
- GCC_except_table3075
- GCC_except_table3083
- GCC_except_table3084
- GCC_except_table3085
- GCC_except_table3086
- GCC_except_table3087
- GCC_except_table3088
- GCC_except_table3104
- GCC_except_table3118
- GCC_except_table3198
- GCC_except_table3210
- GCC_except_table3414
- GCC_except_table3423
- GCC_except_table3441
- GCC_except_table3475
- GCC_except_table3491
- GCC_except_table3493
- GCC_except_table3505
- GCC_except_table3512
- GCC_except_table3534
- GCC_except_table3548
- GCC_except_table3549
- GCC_except_table3550
- GCC_except_table3553
- GCC_except_table3562
- GCC_except_table3569
- GCC_except_table3572
- GCC_except_table3577
- GCC_except_table3582
- GCC_except_table3587
- GCC_except_table3628
- GCC_except_table3645
- GCC_except_table3648
- GCC_except_table3653
- GCC_except_table3655
- GCC_except_table3671
- GCC_except_table3689
- GCC_except_table3693
- GCC_except_table3701
- GCC_except_table3709
- GCC_except_table3773
- GCC_except_table3780
- GCC_except_table3782
- GCC_except_table3783
- GCC_except_table3806
- GCC_except_table4054
- GCC_except_table4129
- GCC_except_table4136
- GCC_except_table4140
- GCC_except_table4142
- GCC_except_table4144
- GCC_except_table4146
- GCC_except_table4150
- GCC_except_table4153
- GCC_except_table4159
- GCC_except_table4170
- GCC_except_table4172
- GCC_except_table4173
- GCC_except_table4175
- GCC_except_table4178
- GCC_except_table4180
- GCC_except_table4181
- GCC_except_table4185
- GCC_except_table4186
- GCC_except_table4188
- GCC_except_table4195
- GCC_except_table4205
- GCC_except_table4208
- GCC_except_table4219
- GCC_except_table4220
- GCC_except_table4222
- GCC_except_table4224
- GCC_except_table4227
- GCC_except_table4231
- GCC_except_table4233
- GCC_except_table4236
- GCC_except_table4239
- GCC_except_table4251
- GCC_except_table4253
- GCC_except_table4257
- GCC_except_table4261
- GCC_except_table4265
- GCC_except_table4270
- GCC_except_table4283
- GCC_except_table4302
- GCC_except_table4325
- GCC_except_table4331
- GCC_except_table4335
- GCC_except_table4339
- GCC_except_table4341
- GCC_except_table4344
- GCC_except_table4346
- GCC_except_table4348
- GCC_except_table4355
- GCC_except_table4356
- GCC_except_table4357
- GCC_except_table4358
- GCC_except_table4359
- GCC_except_table4361
- GCC_except_table4362
- GCC_except_table4363
- GCC_except_table4364
- GCC_except_table4448
- GCC_except_table4450
- GCC_except_table4451
- GCC_except_table4453
- GCC_except_table4456
- GCC_except_table4457
- GCC_except_table4458
- GCC_except_table4601
- GCC_except_table4603
- GCC_except_table4649
- GCC_except_table4670
- GCC_except_table4678
- GCC_except_table4689
- GCC_except_table4703
- GCC_except_table4706
- GCC_except_table4711
- GCC_except_table4719
- GCC_except_table4740
- GCC_except_table4773
- GCC_except_table4776
- GCC_except_table4777
- GCC_except_table4783
- GCC_except_table4785
- GCC_except_table4792
- GCC_except_table4797
- GCC_except_table4798
- GCC_except_table4804
- GCC_except_table4813
- GCC_except_table4815
- GCC_except_table4818
- GCC_except_table4819
- GCC_except_table4824
- GCC_except_table4827
- GCC_except_table4828
- GCC_except_table4834
- GCC_except_table4841
- GCC_except_table4845
- GCC_except_table4846
- GCC_except_table4860
- GCC_except_table4876
- GCC_except_table4893
- GCC_except_table4894
- GCC_except_table4896
- GCC_except_table4897
- GCC_except_table4900
- GCC_except_table4901
- GCC_except_table4916
- GCC_except_table4931
- GCC_except_table4938
- GCC_except_table4958
- GCC_except_table4968
- GCC_except_table4970
- GCC_except_table5040
- GCC_except_table5043
- GCC_except_table5045
- GCC_except_table5048
- GCC_except_table5051
- GCC_except_table5054
- GCC_except_table5057
- GCC_except_table5060
- GCC_except_table5066
- GCC_except_table5069
- GCC_except_table5074
- GCC_except_table5087
- GCC_except_table5092
- GCC_except_table5096
- GCC_except_table5098
- GCC_except_table5121
- GCC_except_table5128
- GCC_except_table5135
- GCC_except_table5138
- GCC_except_table5139
- GCC_except_table5157
- GCC_except_table5159
- GCC_except_table5161
- GCC_except_table5162
- GCC_except_table5165
- GCC_except_table5174
- GCC_except_table5176
- GCC_except_table5183
- GCC_except_table5185
- GCC_except_table5187
- GCC_except_table5190
- GCC_except_table5201
- GCC_except_table5212
- GCC_except_table5214
- GCC_except_table5225
- GCC_except_table5227
- GCC_except_table5229
- GCC_except_table5235
- GCC_except_table5517
- GCC_except_table5523
- GCC_except_table5562
- GCC_except_table5568
- GCC_except_table5582
- GCC_except_table5596
- GCC_except_table5600
- GCC_except_table571
- GCC_except_table5744
- GCC_except_table598
- GCC_except_table610
- GCC_except_table6202
- GCC_except_table6211
- GCC_except_table6212
- GCC_except_table6225
- GCC_except_table6267
- GCC_except_table6270
- GCC_except_table6271
- GCC_except_table6272
- GCC_except_table6273
- GCC_except_table6372
- GCC_except_table6373
- GCC_except_table6374
- GCC_except_table6375
- GCC_except_table6376
- GCC_except_table6377
- GCC_except_table6378
- GCC_except_table6379
- GCC_except_table6381
- GCC_except_table6402
- GCC_except_table6413
- GCC_except_table6415
- GCC_except_table6420
- GCC_except_table6423
- GCC_except_table6426
- GCC_except_table6430
- GCC_except_table6434
- GCC_except_table644
- GCC_except_table656
- GCC_except_table657
- GCC_except_table659
- GCC_except_table662
- GCC_except_table665
- GCC_except_table683
- GCC_except_table687
- GCC_except_table694
- GCC_except_table697
- GCC_except_table6986
- GCC_except_table7005
- GCC_except_table7015
- GCC_except_table7018
- GCC_except_table7023
- GCC_except_table7026
- GCC_except_table7031
- GCC_except_table7300
- GCC_except_table7304
- GCC_except_table731
- GCC_except_table7364
- GCC_except_table7368
- GCC_except_table7370
- GCC_except_table7372
- GCC_except_table741
- GCC_except_table749
- GCC_except_table7587
- GCC_except_table7595
- GCC_except_table7597
- GCC_except_table7599
- GCC_except_table7601
- GCC_except_table7607
- GCC_except_table7620
- GCC_except_table7638
- GCC_except_table7644
- GCC_except_table7658
- GCC_except_table7664
- GCC_except_table7669
- GCC_except_table7671
- GCC_except_table7675
- GCC_except_table7677
- GCC_except_table776
- GCC_except_table7771
- GCC_except_table7778
- GCC_except_table7782
- GCC_except_table7783
- GCC_except_table7784
- GCC_except_table7785
- GCC_except_table7792
- GCC_except_table780
- GCC_except_table7808
- GCC_except_table783
- GCC_except_table7844
- GCC_except_table7845
- GCC_except_table7846
- GCC_except_table785
- GCC_except_table7866
- GCC_except_table7878
- GCC_except_table7881
- GCC_except_table7886
- GCC_except_table7888
- GCC_except_table7902
- GCC_except_table797
- GCC_except_table799
- GCC_except_table8150
- GCC_except_table8155
- GCC_except_table8158
- GCC_except_table8159
- GCC_except_table8161
- GCC_except_table8162
- GCC_except_table8164
- GCC_except_table818
- GCC_except_table8194
- GCC_except_table8218
- GCC_except_table8222
- GCC_except_table8226
- GCC_except_table8231
- GCC_except_table8235
- GCC_except_table8239
- GCC_except_table824
- GCC_except_table8243
- GCC_except_table8247
- GCC_except_table8255
- GCC_except_table8257
- GCC_except_table8261
- GCC_except_table828
- GCC_except_table8325
- GCC_except_table8326
- GCC_except_table8327
- GCC_except_table8328
- GCC_except_table8329
- GCC_except_table8330
- GCC_except_table8331
- GCC_except_table839
- GCC_except_table8396
- GCC_except_table840
- GCC_except_table8410
- GCC_except_table8416
- GCC_except_table8441
- GCC_except_table8443
- GCC_except_table8445
- GCC_except_table845
- GCC_except_table8450
- GCC_except_table8456
- GCC_except_table8470
- GCC_except_table8473
- GCC_except_table8474
- GCC_except_table8479
- GCC_except_table848
- GCC_except_table8482
- GCC_except_table8489
- GCC_except_table8506
- GCC_except_table851
- GCC_except_table8513
- GCC_except_table8519
- GCC_except_table8528
- GCC_except_table8530
- GCC_except_table8536
- GCC_except_table8537
- GCC_except_table8544
- GCC_except_table856
- GCC_except_table8568
- GCC_except_table8569
- GCC_except_table8574
- GCC_except_table8578
- GCC_except_table8582
- GCC_except_table8588
- GCC_except_table8592
- GCC_except_table8596
- GCC_except_table8598
- GCC_except_table860
- GCC_except_table8600
- GCC_except_table8604
- GCC_except_table866
- GCC_except_table870
- GCC_except_table871
- GCC_except_table8723
- GCC_except_table8760
- GCC_except_table8818
- GCC_except_table8821
- GCC_except_table8828
- GCC_except_table8834
- GCC_except_table8841
- GCC_except_table8859
- GCC_except_table8863
- GCC_except_table8864
- GCC_except_table8865
- GCC_except_table8914
- GCC_except_table8915
- GCC_except_table8917
- GCC_except_table8920
- GCC_except_table8947
- GCC_except_table8948
- GCC_except_table8953
- GCC_except_table8973
- GCC_except_table899
- GCC_except_table8991
- GCC_except_table8992
- GCC_except_table8993
- GCC_except_table8998
- GCC_except_table8999
- GCC_except_table9001
- GCC_except_table9003
- GCC_except_table9007
- GCC_except_table9014
- GCC_except_table9024
- GCC_except_table9031
- GCC_except_table9036
- GCC_except_table9054
- GCC_except_table9056
- GCC_except_table906
- GCC_except_table9063
- GCC_except_table9070
- GCC_except_table9075
- GCC_except_table9081
- GCC_except_table9093
- GCC_except_table9094
- GCC_except_table9099
- GCC_except_table9116
- GCC_except_table9117
- GCC_except_table9121
- GCC_except_table9123
- GCC_except_table9125
- GCC_except_table9129
- GCC_except_table914
- GCC_except_table915
- GCC_except_table9150
- GCC_except_table9152
- GCC_except_table9179
- GCC_except_table931
- GCC_except_table9344
- GCC_except_table9407
- GCC_except_table9439
- GCC_except_table9442
- GCC_except_table953
- GCC_except_table9609
- GCC_except_table9647
- GCC_except_table9684
- GCC_except_table972
- GCC_except_table9762
- GCC_except_table9764
- GCC_except_table9766
- GCC_except_table9768
- GCC_except_table9770
- GCC_except_table9772
- GCC_except_table9774
- GCC_except_table9780
- GCC_except_table9782
- GCC_except_table9785
- GCC_except_table9787
- GCC_except_table9789
- GCC_except_table9798
- GCC_except_table9804
- GCC_except_table9809
- GCC_except_table9812
- GCC_except_table9817
- GCC_except_table9822
- GCC_except_table9825
- GCC_except_table9828
- GCC_except_table9854
- GCC_except_table9857
- GCC_except_table9877
- GCC_except_table9878
- GCC_except_table9879
- GCC_except_table9881
- GCC_except_table9884
- GCC_except_table9885
- GCC_except_table9886
- GCC_except_table9888
- GCC_except_table9889
- GCC_except_table9891
- GCC_except_table9896
- GCC_except_table994
- GCC_except_table9951
- GCC_except_table9958
- GCC_except_table998
- _OBJC_CLASS_$_HMFNetMonitor
- _OBJC_CLASS_$_NSCondition
- _OBJC_IVAR_$_HAP2AccessoryDNSResolver._immediateRetrySpent
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4Completed
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4DurationMS
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4Error
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6Completed
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6DurationMS
- _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6Error
- _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthCompleted
- _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthDurationMS
- _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthError
- _OBJC_IVAR_$_HAPAccessoryServerIP._networkMonitor
- __OBJC_$_CATEGORY_HMFPairingIdentity_$_HAPKeyStore
- __OBJC_$_CATEGORY_INSTANCE_METHODS_HMFPairingIdentity_$_HAPKeyStore
- __OBJC_$_PROP_LIST_HMFPairingIdentity_$_HAPKeyStore
- ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_2
- ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_3
- ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke
- ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke_2
- ___block_descriptor_32_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___block_descriptor_40_e8_32w_e22_v16?0"NSDictionary"8l
- ___block_descriptor_48_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___block_descriptor_48_e8_32bs40w_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___block_descriptor_48_e8_32s40bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___block_descriptor_48_e8_32w_e8_v12?0B8l
- ___block_descriptor_56_e8_32s40s48bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___block_descriptor_60_e8_32s40bs_e28_v24?0"NSData"8"NSError"16l
- ___block_descriptor_60_e8_32s40bs_e5_v8?0l
- ___block_descriptor_71_e8_32s40s48s_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
- ___swift_closure_destructor.198Tm
- _accept
- _arc4random_buf
- _coapNetworkRead
- _coap_add_data_after
- _coap_add_option
- _coap_cancel_session_messages
- _coap_delete_node
- _coap_get_block
- _coap_get_context_server_hint
- _coap_get_context_server_psk
- _coap_get_data
- _coap_get_log_level
- _coap_get_resource_from_uri_path
- _coap_get_session_client_psk
- _coap_handle_event
- _coap_network_read
- _coap_network_send
- _coap_pdu_parse_header
- _coap_pdu_parse_header_size
- _coap_pdu_parse_opt
- _coap_print_wellknown
- _coap_print_wellknown._rt_attributes
- _coap_send
- _coap_send_message_type
- _coap_session_disconnected
- _coap_session_max_pdu_size
- _coap_session_release
- _coap_session_send_csm
- _coap_session_send_ping
- _coap_session_write
- _coap_set_log_level
- _coap_touch_observer
- _coap_wellknown_response
- _getsockopt
- _logCategory._hmf_once_t903
- _logCategory._hmf_once_v904
- _no_response
- _objc_msgSend$accessory:didUpdateLocalEndpoints:
- _objc_msgSend$accessoryServer:didUpdateLocalEndpoints:
- _objc_msgSend$broadcast
- _objc_msgSend$getLocalPairingIdentity:
- _objc_msgSend$initWithIdentifier:quality:width:height:framesPerSecond:averageBitrate:peakBitrate:
- _objc_msgSend$initWithStart:duration:activity:
- _objc_msgSend$networkMonitor
- _objc_msgSend$pairSetupSession:pairSetupType:features:pairVerifyTLK:error:
- _objc_msgSend$viewHintForType:
- _perror
- _symbolic So11NSConditionC
- _type_layout_string So15HAPFeatureFlagsV
CStrings:
+ "   %s: mid=0x%04x: mcast response delayed for %u.%03u secs\n"
+ "   %s: mid=0x%04x: response dropped\n"
+ "!Aq\xa1"
+ "%.*s "
+ "%.*s URI scheme unknown\n"
+ "%@ Backoff timer fired with no attribute database — requesting another read"
+ "%@ Failed to merge discovered services for accessory %lu"
+ "%@ Giving up on attribute database read after %lu attempts"
+ "%@ HDS-over-TCP peer selected: %s from %s thread=%{BOOL}d (%{private}@)"
+ "%@ Ignoring request to identify an already paired accessory"
+ "%@ NLM Probe: Transport %lu not yet accepted; not probing"
+ "%@ NLM keep-alive listener active with an attribute database, skipping reachability client"
+ "%@ NLM: Cannot hand over registered transport endpoints, transport missing or unsupported"
+ "%@ Scheduling attribute database re-read after failed discovery"
+ "%s\n"
+ "%s:%d"
+ "%skc=0x"
+ "%skid=0x"
+ "%spIV=0x"
+ "%u/%c/BERT"
+ "%u/%c/BERT(%zu)"
+ "%{private}@ Restored the transport delegate"
+ "(resource_param.length + 1) <= query_filter->length"
+ "*  %s: netif: failed to read %zd bytes (%s)\n"
+ "*  %s: netif: failed to read %zd bytes (%s) state %d\n"
+ "*  %s: netif: failed to send %zd bytes (%s) state %d\n"
+ "*  %s: netif: recv %4zd bytes\n"
+ "*  %s: netif: sent %4zd bytes\n"
+ "*  %s: netif: sent %4zd of %4zd bytes\n"
+ "**  %s: mid=0x%04x: already in-use - dropped\n"
+ "** %s: coap_add_data_large: COAP_BLOCK_USE_LIBCOAP not enabled\n"
+ "** %s: coap_cancel_observe: COAP_BLOCK_USE_LIBCOAP not enabled\n"
+ "** %s: coap_socket_recv: %s\n"
+ "** %s: coap_socket_recv: ICMP: %s\n"
+ "** %s: large body receive internal issue\n"
+ "** %s: lg_crcv %p initialized - stateless token xxxx%012llx\n"
+ "** %s: lg_crcv %p released\n"
+ "** %s: lg_srcv %p initialized\n"
+ "** %s: lg_srcv %p released\n"
+ "** %s: lg_xmit %p initialized\n"
+ "** %s: lg_xmit %p released\n"
+ "** %s: mid=0x%04x: added to retransmit queue (%ums)\n"
+ "** %s: mid=0x%04x: delayed\n"
+ "** %s: mid=0x%04x: give up after %d attempts\n"
+ "** %s: mid=0x%04x: mcast delayed transmission\n"
+ "** %s: mid=0x%04x: not transmitted after disconnect\n"
+ "** %s: mid=0x%04x: removed (1)\n"
+ "** %s: mid=0x%04x: removed (2)\n"
+ "** %s: mid=0x%04x: removed (3)\n"
+ "** %s: mid=0x%04x: removed (4)\n"
+ "** %s: mid=0x%04x: removed (6)\n"
+ "** %s: mid=0x%04x: retransmission #%d (next %ums)\n"
+ "** %s: mid=0x%04x: transmitted after delay\n"
+ "** %s: timeout waiting for CSM response\n"
+ "** %s: timeout waiting for first response\n"
+ "***%s: CID: New Client Session\n"
+ "***%s: CID: Old Client Session\n"
+ "***%s: session %p: closed\n"
+ "***%s: session %p: created outgoing session\n"
+ "***%s: session %p: duplicate - already exists\n"
+ "***%s: session %p: new incoming session\n"
+ "***%s: session ICMP issue (%s)\n"
+ "***%s: session ack_random_factor set to %u.%03u\n"
+ "***%s: session ack_timeout set to %u.%03u\n"
+ "***%s: session disconnected (%s)\n"
+ "***%s: session max_retransmit set to %u\n"
+ "***EVENT: %s\n"
+ "*opt == COAP_PAYLOAD_START"
+ "*optp"
+ ".%03u"
+ ".well-known/core: truncating data length to %zu from %zu\n"
+ "00000279-0000-1000-8000-0026BB765291"
+ "00000330-0000-1000-8000-0026BB765291"
+ "<HAPCameraBufferActivityCommandRequest start=%@, duration=%@, activity=%@, reason=%@>"
+ "<HAPCameraVideoStreamCapabilities identifier=%@, quality=%@, width=%@, height=%@, framesPerSecond=%@, averageBitrate=%@, peakBitrate=%@, keyFrameInterval=%@, videoCodec=%@>"
+ "<HAPErrorEntry errorCode=%@, manufacturerErrorInfo=%@>"
+ "<HAPErrorStatus errorEntry=%@>"
+ "<HAPErrorStatusCodeWrapper value=%@>"
+ "<HAPIPAddressVersionWrapper value=%@>"
+ "<HAPTLVSessionTransportEndpointAddress IPAddressVersion=%@, IPAddress=%@, port=%@>"
+ "<HAPTLVSessionTransportEndpointEntry transportType=%@, endpointAddress=%@>"
+ "<HAPTLVSessionTransportEndpointList entries=%@>"
+ "<libcoap> Unhandled log level (%u) for message: %{private}s"
+ "Alrt"
+ "Bad Response"
+ "Block-Wise-Transfer"
+ "COAP_EVENT_BAD_PACKET"
+ "COAP_EVENT_KEEPALIVE_FAILURE"
+ "COAP_EVENT_MSG_RETRANSMITTED"
+ "COAP_EVENT_OSCORE_DECODE_ERROR"
+ "COAP_EVENT_OSCORE_DECRYPTION_FAILURE"
+ "COAP_EVENT_OSCORE_INTERNAL_ERROR"
+ "COAP_EVENT_OSCORE_NOT_ENABLED"
+ "COAP_EVENT_OSCORE_NO_PROTECTED_PAYLOAD"
+ "COAP_EVENT_OSCORE_NO_SECURITY"
+ "COAP_EVENT_PARTIAL_BLOCK"
+ "COAP_EVENT_SERVER_SESSION_DEL"
+ "COAP_EVENT_SERVER_SESSION_NEW"
+ "COAP_EVENT_SESSION_CLOSED"
+ "COAP_EVENT_SESSION_CONNECTED"
+ "COAP_EVENT_SESSION_FAILED"
+ "COAP_EVENT_WS_CLOSED"
+ "COAP_EVENT_WS_CONNECTED"
+ "COAP_EVENT_WS_PACKET_SIZE"
+ "COAP_EVENT_XMIT_BLOCK_FAIL"
+ "COAP_NACK_BAD_RESPONSE"
+ "COAP_NACK_ICMP_ISSUE"
+ "COAP_NACK_NOT_DELIVERABLE"
+ "COAP_NACK_RST"
+ "COAP_NACK_TLS_FAILED"
+ "COAP_NACK_TLS_LAYER_FAILED"
+ "COAP_NACK_TOO_MANY_RETRIES"
+ "COAP_NACK_WS_FAILED"
+ "COAP_NACK_WS_LAYER_FAILED"
+ "Changing blocksize during request invalid"
+ "Client app version of updated PDU\n"
+ "Client app version of updated PDU (3)\n"
+ "Conflict"
+ "Content-Format mismatch"
+ "Content-Format option mismatch\n"
+ "Crit"
+ "DTLS"
+ "Data body updated during receipt - new request started\n"
+ "Debg"
+ "Deferring network credential fetch until commit"
+ "Duplicate request with mid=0x%04x - not processed\n"
+ "Echo"
+ "Emrg"
+ "Err "
+ "Extended Token requested size support not available\n"
+ "Extended Token support available\n"
+ "Extended Token support not available\n"
+ "Extended-Token-Length"
+ "Failed to drain wakeup pipe: %d"
+ "Failed to run coap_io_process_with_fds"
+ "Failed to update keychain item to set invisible with error: %@"
+ "Failed to update keychain item to set invisible with error: %d"
+ "Failed to update token\n"
+ "Failing HAP Browser instantiation - nil delegate"
+ "Fetching Thread credentials for M5"
+ "Fetching WiFi credentials for M5"
+ "HAP2DNSSDErrorDomain"
+ "HAPErrorStatusCodeAudioFailure"
+ "HAPErrorStatusCodeBulbFailure"
+ "HAPErrorStatusCodeCalibrationError"
+ "HAPErrorStatusCodeConnectivityFailure"
+ "HAPErrorStatusCodeCoolingFailure"
+ "HAPErrorStatusCodeDeviceDamaged"
+ "HAPErrorStatusCodeDeviceOverheating"
+ "HAPErrorStatusCodeExcessiveBatteryDrain"
+ "HAPErrorStatusCodeFreezeRisk"
+ "HAPErrorStatusCodeHeatingFailure"
+ "HAPErrorStatusCodeJammed"
+ "HAPErrorStatusCodePowerInstability"
+ "HAPErrorStatusCodeSafetyTemperatureExceeded"
+ "HAPErrorStatusCodeSensorFailure"
+ "HAPErrorStatusCodeSuddenTemperatureChange"
+ "HAPIPAddressVersionIPv4"
+ "HAPIPAddressVersionIPv6"
+ "Hop Limit Reached"
+ "Hop-Limit"
+ "Illegal block requested (%d > last = %zu)\n"
+ "Info"
+ "Invalid Hop Limit\n"
+ "Invalid multicast packet received RFC7252 8.1\n"
+ "M4: accessory presented no MFi software token — prompting uncertified"
+ "M5 network credentials: threadRequired=%{bool,public}d threadBestEffort=%{bool,public}d wifiRequired=%{bool,public}d wifi=%{public}s thread=%{public}s waited=%{public}ldms fetchAge=%{public}ldms -> %{public}s"
+ "M5 network-credential gate changed after the fetches started"
+ "M5 waiting up to %{public}ldms for network credentials"
+ "M5: owner ECDSA public key is not a valid P-256 raw key (%ld bytes), failing pair-setup"
+ "Memory issue"
+ "Missing block 0"
+ "Missing interim block"
+ "NLM: %@ Accepted list does not hold the current link on transport %ld"
+ "NLM: %@ Accessory accepted the link on transport %ld, racing enabled"
+ "NLM: %@ Disconnected link is no longer held by the transport; ignoring"
+ "NLM: %@ Failed to close client for transport %ld: %@"
+ "NLM: %@ Live address arrived while awaiting initial resolve; applying inline instead of behind the deadlocked open operation"
+ "NLM: %@ No live %{public}s address to reopen on"
+ "NLM: %@ Probe on the accepted link on transport %ld failed: %ld (%lu attempt(s) left)"
+ "NLM: %@ Registered endpoints arrived with no second link to accept"
+ "NLM: %@ Secured client disconnected and the accessory never acknowledged the other link, tearing down transport to re-verify"
+ "NLM: %@ Secured over Thread, WiFi not acknowledged: sending request via secondary client [MID:%u]"
+ "NLM: %@ Stale link on transport %ld: client %{BOOL}d, secured %{public}s, other %{BOOL}d connected %{BOOL}d registered %{BOOL}d, endpoint list %{BOOL}d, supports WiFi %{BOOL}d Thread %{BOOL}d"
+ "NLM: %@ Transport capabilities - WiFi:%@ Thread:%@ KeepAlive:%@ EndpointList:%@"
+ "NLM: %@ applyResolverAddresses dropped empty delivery"
+ "NLM: %@ session local address family: %d (AF_INET=%d, AF_INET6=%d)"
+ "NLM: Close transport client"
+ "NLM: Connectivity restored with no attribute database — updating accessories"
+ "NLM: Received Empty CON ping (MID=%d)"
+ "NLM: Transport %ld controller was replaced before the close-client answer; dropping the decision"
+ "NLM: Transport %ld controller was replaced before the stale answer; dropping the decision"
+ "NLM: Transport %ld destination is unadvertised; rebuilding the link, keeping the session"
+ "NLM: Transport %ld destination is unadvertised; transport not open, leaving the session"
+ "NLM: Transport %ld unknown close-client result %ld; closing session"
+ "Not all blocks have ETag option\n"
+ "Note"
+ "OSC "
+ "Observe PDU presented to app.\n"
+ "Option Block2 has invalid set M bit - cleared\n"
+ "Option number %d is not defined as repeatable\n"
+ "Option number %d is not defined as repeatable - dropped\n"
+ "Oscore"
+ "PDU presented by app\n"
+ "PDU presented by app.\n"
+ "PDU presented to app.\n"
+ "Pair verify TLK not available on demand - failing pair setup"
+ "Pair-setup ended during the TLK request; not creating its session"
+ "Pair-setup stopped while M5 waited for network credentials; not sending M5"
+ "Pair-setup stopped while M5 was being assembled; not sending M5"
+ "Pair-setup: session wrapper released before M5; not sending M5"
+ "Pre-warmed pair-setup committed without a pairing request; M5 won't wait for credentials"
+ "Proxy loop detected '%s'\n"
+ "Proxy return has bad hop limit count '%zu'\n"
+ "Proxy-%s code %d.%02d handler not supported\n"
+ "Proxy-%s support not configured\n"
+ "Proxy-Scheme requires Uri-Host\n"
+ "Proxy-URI not decodable\n"
+ "Q-Block1"
+ "Q-Block2"
+ "Received nack for message id %i with reason %d but no matching sent message, ignoring"
+ "Reliable: type != CON\n"
+ "Replaced option Q-Block1 with Block1\n"
+ "Replaced option Q-Block2 with Block2\n"
+ "Request-Tag"
+ "Resolver: abandoning retry ladder at rung %lu on stop for deviceID=%{public}@"
+ "Resolver: audit found unsubscribed resolver for deviceID=%{public}@ (pipelineStarted=%d tornDown=%d); starting retry ladder"
+ "Resolver: first delivery for deviceID=%{public}@ (primary=%lu secondary=%lu)"
+ "Resolver: pipeline arm FAILED for deviceID=%{public}@ serviceName='%{private}@' (factory returned nil; not subscribed)"
+ "Resolver: pipeline armed for deviceID=%{public}@ serviceName='%{private}@' (subscribed; rung=%lu everDelivered=%d)"
+ "Resolver: pipeline delivered error for deviceID=%{public}@ domain=%{public}@ code=%ld dnssd=%{public}@ marker=%ld voidsSubscription=%d"
+ "Resolver: retry ladder exhausted for deviceID=%{public}@ after %lu attempts; deferring to audit"
+ "Resolver: retry rung firing for deviceID=%{public}@ (attempt %lu)"
+ "Resolver: scheduling retry rung %lu/%lu in %.2fs for deviceID=%{public}@"
+ "Scheme"
+ "Server app version of updated PDU\n"
+ "Size of large buffer restricted to 0x%lx bytes\n"
+ "Skipping Thread credential fetch - neither required nor best-effort"
+ "Skipping network credential fetch - accessory does not support AES-CCM"
+ "TCP "
+ "TLS "
+ "Testing for Extended Token support\n"
+ "Thread credentials required for pair-setup are unavailable"
+ "Timed out waiting for Thread credential pre-warm before M5"
+ "Token reused - see https://rfc-editor.org/rfc/rfc9175.html#section-4.2\n"
+ "Too Many Requests"
+ "Too many missing blocks"
+ "Tuple change for CID failed\n"
+ "UDP "
+ "Unknown HAPErrorStatusCode %ld"
+ "Unknown HAPIPAddressVersion %ld"
+ "Unknown nack reason %d, treating as not deliverable"
+ "Unprocessable"
+ "Unsupported URI type %d\n"
+ "Uri"
+ "WS  "
+ "WSS "
+ "Wakeup pipe closed unexpectedly"
+ "Warn"
+ "WebSocket: type != CON\n"
+ "Wi-Fi credentials required for pair-setup are unavailable"
+ "[%s]:%d"
+ "[%{public}@] Failed to update keychain item to set invisible with error: %@"
+ "[%{public}@] Failed to update keychain item to set invisible with error: %d"
+ "[%{public}@] Failing HAP Browser instantiation - nil delegate"
+ "[%{public}@] Pair-setup ended during the TLK request; not creating its session"
+ "[%{public}@] didRegisterTransportEndpoints called -- NOP"
+ "application/ace+cbor"
+ "application/coap-group+json"
+ "application/cwt"
+ "application/dots+cbor"
+ "application/missing-blocks+cbor-seq"
+ "application/oscore"
+ "application/rdf+xml"
+ "block: Oversized packet - reduced to %u from %zu\n"
+ "block: Oversized packet - reduced to %zu from %zu\n"
+ "block: Undersized packet - expected %u, got %zu\n"
+ "block: Undersized packet chunk %u got %zu\n"
+ "buf"
+ "c"
+ "cache_entry"
+ "call custom handler for resource '%*.*s' (3)\n"
+ "call custom handler for resource '%*.*s' (4)\n"
+ "call handler for pseudo resource '%*.*s' (3)\n"
+ "cannot send response for mid=0x%04x\n"
+ "coap"
+ "coap+tcp"
+ "coap+tcp URI scheme not supported in this version of libcoap\n"
+ "coap+ws"
+ "coap+ws URI scheme not supported in this version of libcoap\n"
+ "coap_add_data: PDU already contains data\n"
+ "coap_add_data_large: PDU already contains data\n"
+ "coap_add_data_large_internal"
+ "coap_add_option_internal"
+ "coap_add_optlist_pdu: PDU already contains data\n"
+ "coap_add_resource_lkd"
+ "coap_add_token: Insufficient space for token. Token ignored\n"
+ "coap_add_token: Token size too large. PDU ignored\n"
+ "coap_add_token: Token size too large. Token ignored\n"
+ "coap_address.c"
+ "coap_block.c"
+ "coap_block_new_lg_crcv"
+ "coap_cache.c"
+ "coap_client_delay_first"
+ "coap_client_delay_first: timeout\n"
+ "coap_delete_cache_entry"
+ "coap_delete_observers"
+ "coap_dispatch: Received invalid PDU code (%d.%02d)\n"
+ "coap_dtls_hello: ContentType Connection-IS dropped\n"
+ "coap_encode.c"
+ "coap_encode_var_safe"
+ "coap_encode_var_safe8"
+ "coap_find_observer_cache_key"
+ "coap_free_endpoint_lkd"
+ "coap_get_data_large"
+ "coap_handle_dgram: UDP version not supported\n"
+ "coap_insert_option"
+ "coap_io_prepare_io_lkd"
+ "coap_is_bcst: Cannot determine any broadcast addresses\n"
+ "coap_is_bcst: Insufficient space for broadcast addresses\n"
+ "coap_net.c"
+ "coap_netif.c"
+ "coap_netif_dgrm_write"
+ "coap_new_string"
+ "coap_option.c"
+ "coap_pdu.c"
+ "coap_pdu_init"
+ "coap_pdu_parse: %d.%02d: offset %u malformed option\n"
+ "coap_pdu_parse: %d.%02d: offset %u option %u has bad length %u\n"
+ "coap_pdu_parse_opt"
+ "coap_print_ip_addr: inet_ntop\n"
+ "coap_print_wellknown_lkd"
+ "coap_remove_option"
+ "coap_resource.c"
+ "coap_send: Invalid PDU code (%d.%02d)\n"
+ "coap_send: PDU dropped as token too long (%zu > %u)\n"
+ "coap_send: Socket closed\n"
+ "coap_send: Using coap_cancel_observe() to do OBSERVE cancellation\n"
+ "coap_session_release_lkd"
+ "coap_socket_connect_udp: connect: %s (%d)\n"
+ "coap_socket_connect_udp: local address family != remote address family\n"
+ "coap_socket_connect_udp: setsockopt SO_BROADCAST: %s\n"
+ "coap_socket_connect_udp: unsupported sa_family %d\n"
+ "coap_socket_recv: %s\n"
+ "coap_socket_send: %s\n"
+ "coap_startup() should be called before any other coap_*() functions are called\n"
+ "coap_str.c"
+ "coap_write_block_b_opt"
+ "coaps"
+ "coaps URI scheme not supported in this version of libcoap\n"
+ "coaps+tcp"
+ "coaps+tcp URI scheme not supported in this version of libcoap\n"
+ "coaps+ws"
+ "coaps+ws URI scheme not supported in this version of libcoap\n"
+ "code <= 0xff"
+ "could not create response PDU\n"
+ "create new subscription %p key 0x%02x%02x%02x%02x\n"
+ "didRegisterTransportEndpoints called -- NOP"
+ "dropped ACK with request code (%d.%02d)\n"
+ "dropped client"
+ "found Block option, block is BERT, block nr. %u (%zu)\n"
+ "found Block option, block is BERT, block nr. %u, M %d\n"
+ "found Block option, block size is %u, block nr. %u\n"
+ "found Block option, block size is %u, block nr. %u, M %d\n"
+ "got RST for mid=0x%04x\n"
+ "handle_request: Invalid PDU response code (%d.%02d)\n"
+ "hnd_get_wellknown_lkd"
+ "http"
+ "https"
+ "ignoring request to change Block size from %u to %u\n"
+ "ignoring request to increase Block size, (%u > %u)\n"
+ "ignoring request to increase Block size, next block is not aligned on requested block size boundary. (%zu x %u mod %u = %zu != 0)\n"
+ "len <= (size_t)wkc_len"
+ "mcast delay: insufficient memory\n"
+ "mid >= 0 && mid <= 0xffff"
+ "n <= length"
+ "new Block size is %u, block number %u completed\n"
+ "next_option != NULL"
+ "not enough space, even the smallest block does not fit (1)\n"
+ "not enough space, even the smallest block does not fit (2)\n"
+ "not enough space, even the smallest block does not fit (3)\n"
+ "observe: unexpected action %d\n"
+ "option != NULL"
+ "other link"
+ "pdu->data"
+ "pdu->hdr_size == 2"
+ "removed subscription %p with token '%s' key 0x%02x%02x%02x%02x\n"
+ "resource->context == NULL"
+ "resource->subscribers"
+ "s->ref > 1"
+ "session->ref == 1"
+ "setup_block_b"
+ "size+1 != 0"
+ "stale link"
+ "start <= total"
+ "type <= 0x3"
+ "v16@?0q8"
+ "v24@?0@\"HAP2CoAPClient\"8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16"
+ "v24@?0^{coap_context_t={coap_opt_filter_t=S[2S][6C]}^{coap_resource_t}^{coap_resource_t}^{coap_resource_t}^?Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^vI^?^?^?^?^v{coap_dtls_spsk_t=CC[6C]^?^v^?^v{coap_dtls_spsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}IIIIIIQ^{coap_cache_entry_t}^SQ^vI{fd_set=[32i]}{fd_set=[32i]}{fd_set=[32i]}[64^{coap_socket_t}]ICCCCI}8^{coap_session_t=iiiIQQQ{coap_addr_hash_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}Si}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}{coap_sockaddr_un=C[27c]})}[3{?=^?^?^?^?}]}^{coap_endpoint_t}^{coap_context_t}^vSCCi^{coap_queue_t}^{coap_lg_xmit_t}^{coap_lg_crcv_t}^{coap_lg_srcv_t}Q[8C]Q^{coap_pdu_t}QQQQQ{coap_dtls_cpsk_t=CCC[5C]^?^v*{coap_dtls_cpsk_info_t={coap_bin_const_t=Q*}{coap_bin_const_t=Q*}}}^{coap_bin_const_t}^{coap_bin_const_t}^{coap_bin_const_t}^v{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}SS{coap_fixed_point_t=SS}IIiIICCCCCCCCCCiIQ^{coap_bin_const_t}^{coap_bin_const_t}iii^{coap_bin_const_t}dddIddddCddI[32{?=SdC}]}16"
+ "v:Reliable c:%s {"
+ "v:WebSocket c:%s {"
+ "\x81\xf0\xe1!"
+ "\xf01\xf0A"
- " DTLS"
- " NONE"
- " TCP "
- " TLS "
- " UDP "
- "!Aq\x81"
- "%@ HDS-over-TCP peer selected: %s from %s (%{private}@)"
- "%s     IPV6_PKTINFO: ifindex=%d, addr=%s\n"
- "%s     IPV6_TCLASS: 0x%02x (DSCP 0x%02x)\n"
- "%s     IP_PKTINFO: ifindex=%d, ipi_spec_dst=%s, ipi_addr=%s\n"
- "%s     IP_TOS: 0x%02x (DSCP 0x%02x)\n"
- "%s     SO_TRAFFIC_CLASS: %d\n"
- "%s   No control messages.\n"
- "%s   cmsg: level=%d, type=%d, len=%u\n"
- "%s   iov[%d]: base=%p, len=%zu\n"
- "%s --- End msghdr Info ---\n"
- "%s --- msghdr Info ---\n"
- "%s msg_controllen: %u\n"
- "%s msg_flags: 0x%x ["
- "%s msg_iovlen: %d\n"
- "%s msg_name: AF_INET %s:%d (len %d)\n"
- "%s msg_name: AF_INET6 %s:%d (len %d)\n"
- "%s msg_name: NULL (len %d)\n"
- "%s msg_name: Unknown Family %d (len %d)\n"
- "'%s'"
- "(resource_param.length + 1) <= coap_opt_length(query_filter)"
- "*   %s: failed to send %zd bytes\n"
- "*  %s: failed to send %zd bytes\n"
- "*  %s: read error\n"
- "*  %s: received %zd bytes\n"
- "*  %s: sent %zd bytes\n"
- "**  %s: tid=%d: already in-use - dropped\n"
- "** %s: tid=%d: added to retransmit queue (%ums)\n"
- "** %s: tid=%d: delayed\n"
- "** %s: tid=%d: give up after %d attempts\n"
- "** %s: tid=%d: not transmitted after disconnect\n"
- "** %s: tid=%d: removed\n"
- "** %s: tid=%d: retransmission #%d\n"
- "** %s: tid=%d: transmitted after delay\n"
- "** removed observer %s\n"
- "***%s: new incoming session\n"
- "***%s: new outgoing session\n"
- "***%s: sending CSM\n"
- "***%s: session ack_random_factor set to %d.%03d\n"
- "***%s: session closed\n"
- "***%s: session disconnected (reason %d)\n"
- "***EVENT: 0x%04x\n"
- ":%d"
- "<HAPCameraBufferActivityCommandRequest start=%@, duration=%@, activity=%@>"
- "<HAPCameraVideoStreamCapabilities identifier=%@, quality=%@, width=%@, height=%@, framesPerSecond=%@, averageBitrate=%@, peakBitrate=%@>"
- "<libcoap> Unknown log level (%u) for message: %{private}s"
- "Also setting SO_TRAFFIC_CLASS to %d (mapped from DSCP %d)\n"
- "Block-wise-Transfer"
- "CIPH"
- "COAP_PROTO_RELIABLE(session->proto)"
- "Chosen sock->fd = %d, flags = %d\n"
- "Coap Network Read"
- "Coap_write timeout %u, requested time %u"
- "Could not get next control message header for AQM.\n"
- "Failed to run coap_run_once"
- "Failed to updated keychain item to set invisible with error: %@"
- "Failed to updated keychain item to set invisible with error: %d"
- "Failing HAP Browser instantioation - nil delegate"
- "ICMP port unreachable; failing this session's queued messages now"
- "Invalid socket file descriptor (fd = -1).\n"
- "MSG_CTRUNC "
- "MSG_TRUNC "
- "NLM keep-alive listener active, skipping reachability client"
- "NLM: %@ Transport capabilities - WiFi:%@ Thread:%@ KeepAlive:%@"
- "NLM: %@ session->addr_info.local family: %d (AF_INET=%d, AF_INET6=%d)"
- "NLM: Received Empty CON ping (MID=%d), sending RST"
- "Pipe closed unexpectedly"
- "Pre-warming Thread credentials during M1"
- "Pre-warming WiFi credentials during M1"
- "Resolver pipeline factory returned nil"
- "Resolver: never-delivered health-check restart for deviceID=%{public}@"
- "Resolver: pipeline delivered fatal error for deviceID=%{public}@ domain=%{public}@ code=%ld marker=%ld"
- "Resolver: pipeline factory failed for deviceID=%{public}@"
- "Setting IPV6_TCLASS to 0x%x (DSCP %d)\n"
- "Setting IP_TOS to 0x%x (DSCP %d)\n"
- "Skipping network credential pre-warming - accessory does not support AES-CCM"
- "TX: "
- "Unsupported address family for DSCP/AQM. Sending without it.\n"
- "Using connected socket path (msg_name=NULL).\n"
- "Using unconnected socket path (msg_name set).\n"
- "[%{public}@] Failed to updated keychain item to set invisible with error: %@"
- "[%{public}@] Failed to updated keychain item to set invisible with error: %d"
- "[%{public}@] Failing HAP Browser instantioation - nil delegate"
- "]\n"
- "address.c"
- "block.c"
- "call custom handler for resource '%*.*s'\n"
- "cannot generate response\r\n"
- "cannot send response for message %d\n"
- "cannot send response for transaction %d\n"
- "cannot send response for transaction %u\n"
- "coap_encode_var_safe(buf, sizeof(buf), COAP_MEDIATYPE_APPLICATION_LINK_FORMAT) == 1"
- "coap_free_endpoint"
- "coap_get_data"
- "coap_network_read"
- "coap_network_read: %s\n"
- "coap_network_read: unreachable\n"
- "coap_network_send"
- "coap_network_send: %s\n"
- "coap_pdu_parse: missing payload start code\n"
- "coap_pdu_parse_header_size"
- "coap_pdu_parse_header_size(proto, data) <= length"
- "coap_pdu_parse_size"
- "coap_print_wellknown"
- "coap_send_pdu_dscp"
- "coap_send_pdu_dscp failed: %s (%d)\n"
- "coap_send_pdu_dscp: Session state = %d\n"
- "coap_session_release"
- "coap_session_send"
- "coap_session_send_csm"
- "coap_socket_accept_tcp: accept: %s\n"
- "coap_socket_accept_tcp: getsockname: %s\n"
- "coap_socket_accept_tcp: ioctl FIONBIO: %s\n"
- "coap_socket_connect_tcp1: bind: %s\n"
- "coap_socket_connect_tcp1: connect: %s\n"
- "coap_socket_connect_tcp1: getpeername: %s\n"
- "coap_socket_connect_tcp1: getsockname: %s\n"
- "coap_socket_connect_tcp1: ioctl FIONBIO: %s\n"
- "coap_socket_connect_tcp1: setsockopt IPV6_V6ONLY: %s\n"
- "coap_socket_connect_tcp1: setsockopt SO_REUSEADDR: %s\n"
- "coap_socket_connect_tcp1: socket: %s\n"
- "coap_socket_connect_tcp1: unsupported sa_family\n"
- "coap_socket_connect_tcp: getpeername: %s\n"
- "coap_socket_connect_tcp: getsockname: %s\n"
- "coap_socket_connect_udp: connect: %s\n"
- "coap_socket_connect_udp: unsupported sa_family\n"
- "coap_socket_finish_connect_tcp: connect failed: %s\n"
- "coap_socket_finish_connect_tcp: getsockopt: %s\n"
- "coap_socket_read: recv: %s\n"
- "coap_socket_write: send: %s\n"
- "coap_wellknown_response"
- "coap_wellknown_response: cannot add Block2 option\n"
- "coap_wellknown_response: cannot add token\n"
- "coap_wellknown_response: cannot create PDU\n"
- "coap_wellknown_response: coap_add_data failed\n"
- "coap_wellknown_response: insufficient storage space\n"
- "coap_wellknown_response: message to small even for szx == 0\n"
- "coap_wellknown_response: undefined resource\n"
- "coap_write_block_opt"
- "create block\n"
- "create default response for %s\n"
- "create new subscription\n"
- "get_wkc_len: coap_print_wellknown() returned %zu\n"
- "got RST for message %d\n"
- "handle_request"
- "have wellknown response %p\n"
- "insufficient space for block option\n"
- "method not allowed for .well-known/core\n"
- "net.c"
- "no_response"
- "not enough space, even the smallest block does not fit"
- "option.c"
- "packet"
- "pdu->data == NULL"
- "pdu->max_hdr_size >= 2"
- "pdu->max_hdr_size >= 3"
- "pdu->max_hdr_size >= 6"
- "pdu->used_size >= pdu->token_length"
- "pdu.c"
- "proto == COAP_PROTO_TCP || proto == COAP_PROTO_TLS"
- "removed observer tid %s\n"
- "resource.c"
- "resp->used_size <= resp->max_size"
- "response == NULL"
- "sock"
- "v24@?0@\"HAP2CoAPClient\"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16"
- "v24@?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16"
- "\x91\xf0\xf0Q!"
```
