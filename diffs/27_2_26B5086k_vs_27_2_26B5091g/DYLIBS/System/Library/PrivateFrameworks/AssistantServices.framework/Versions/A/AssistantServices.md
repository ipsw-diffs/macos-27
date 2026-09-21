## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3605.23.1.4.1
-  __TEXT.__text: 0x19d828
-  __TEXT.__objc_methlist: 0x1ef0c
+3605.24.2.0.0
+  __TEXT.__text: 0x19e108
+  __TEXT.__objc_methlist: 0x1ef6c
   __TEXT.__const: 0x3f0
   __TEXT.__dlopen_cstrs: 0x421
-  __TEXT.__gcc_except_tab: 0x1fb8
-  __TEXT.__cstring: 0x3b683
-  __TEXT.__oslogstring: 0xee0c
+  __TEXT.__gcc_except_tab: 0x1fc0
+  __TEXT.__cstring: 0x3b773
+  __TEXT.__oslogstring: 0xeebf
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x9870
+  __TEXT.__unwind_info: 0x9898
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4288
+  __DATA_CONST.__const: 0x4290
   __DATA_CONST.__objc_classlist: 0xef8
   __DATA_CONST.__objc_catlist: 0x2a0
-  __DATA_CONST.__objc_protolist: 0x5e0
+  __DATA_CONST.__objc_protolist: 0x5e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbd40
+  __DATA_CONST.__objc_selrefs: 0xbd70
   __DATA_CONST.__objc_protorefs: 0x180
   __DATA_CONST.__objc_superrefs: 0xf10
-  __DATA_CONST.__objc_arraydata: 0x2440
-  __DATA_CONST.__got: 0x1658
+  __DATA_CONST.__objc_arraydata: 0x2450
+  __DATA_CONST.__got: 0x1660
   __AUTH_CONST.__const: 0x8300
-  __AUTH_CONST.__cfstring: 0x27dc0
-  __AUTH_CONST.__objc_const: 0x36268
-  __AUTH_CONST.__objc_intobj: 0x2700
+  __AUTH_CONST.__cfstring: 0x27e20
+  __AUTH_CONST.__objc_const: 0x36318
+  __AUTH_CONST.__objc_intobj: 0x2718
   __AUTH_CONST.__objc_dictobj: 0xd20
   __AUTH_CONST.__objc_arrayobj: 0x5d0
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__auth_got: 0x990
-  __AUTH.__objc_data: 0x8610
+  __AUTH.__objc_data: 0x84a8
   __AUTH.__data: 0xd0
-  __DATA.__objc_ivar: 0x2570
-  __DATA.__data: 0x4798
-  __DATA.__bss: 0xef8
+  __DATA.__objc_ivar: 0x2580
+  __DATA.__data: 0x47f8
+  __DATA.__bss: 0xef0
   __DATA.__common: 0x18
-  __DATA_DIRTY.__objc_data: 0xfa0
+  __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x20
-  __DATA_DIRTY.__bss: 0x1e0
+  __DATA_DIRTY.__bss: 0x1e8
   __DATA_DIRTY.__common: 0xf8
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11979
-  Symbols:   26378
-  CStrings:  8353
+  Functions: 11988
+  Symbols:   26400
+  CStrings:  8364
 
Symbols:
+ +[AFFeatureFlags(SWEFeatureFlags) isAppExclusionsEnabled]
+ -[AFConnection _cleanupRoutingStandby]
+ -[AFConnection _resetSpeechTimingForSpeechRequest:options:systemUptime:]
+ -[AFConnection scdaStandbyDidBegin]
+ -[AFConnection scdaStandbyDidEndAsWon:]
+ GCC_except_table10049
+ GCC_except_table1006
+ GCC_except_table10112
+ GCC_except_table10115
+ GCC_except_table10119
+ GCC_except_table10138
+ GCC_except_table10152
+ GCC_except_table10226
+ GCC_except_table10284
+ GCC_except_table10310
+ GCC_except_table10575
+ GCC_except_table10704
+ GCC_except_table10754
+ GCC_except_table10848
+ GCC_except_table10970
+ GCC_except_table10972
+ GCC_except_table10984
+ GCC_except_table11046
+ GCC_except_table11061
+ GCC_except_table11086
+ GCC_except_table11092
+ GCC_except_table11246
+ GCC_except_table11251
+ GCC_except_table11257
+ GCC_except_table11264
+ GCC_except_table1142
+ GCC_except_table11471
+ GCC_except_table11795
+ GCC_except_table11936
+ GCC_except_table11939
+ GCC_except_table11941
+ GCC_except_table1209
+ GCC_except_table1219
+ GCC_except_table1340
+ GCC_except_table1342
+ GCC_except_table1525
+ GCC_except_table1562
+ GCC_except_table1576
+ GCC_except_table1602
+ GCC_except_table1605
+ GCC_except_table1972
+ GCC_except_table2086
+ GCC_except_table2219
+ GCC_except_table2341
+ GCC_except_table2354
+ GCC_except_table2355
+ GCC_except_table2369
+ GCC_except_table2377
+ GCC_except_table2378
+ GCC_except_table2387
+ GCC_except_table2434
+ GCC_except_table2436
+ GCC_except_table2438
+ GCC_except_table2462
+ GCC_except_table2505
+ GCC_except_table2517
+ GCC_except_table2659
+ GCC_except_table2749
+ GCC_except_table2803
+ GCC_except_table3029
+ GCC_except_table3030
+ GCC_except_table3227
+ GCC_except_table3288
+ GCC_except_table3504
+ GCC_except_table3507
+ GCC_except_table3512
+ GCC_except_table3516
+ GCC_except_table3530
+ GCC_except_table3589
+ GCC_except_table3682
+ GCC_except_table3686
+ GCC_except_table377
+ GCC_except_table3796
+ GCC_except_table3861
+ GCC_except_table3863
+ GCC_except_table3865
+ GCC_except_table3885
+ GCC_except_table4010
+ GCC_except_table4014
+ GCC_except_table4019
+ GCC_except_table402
+ GCC_except_table4391
+ GCC_except_table4406
+ GCC_except_table4413
+ GCC_except_table4429
+ GCC_except_table4501
+ GCC_except_table4530
+ GCC_except_table4568
+ GCC_except_table4569
+ GCC_except_table4570
+ GCC_except_table4595
+ GCC_except_table4619
+ GCC_except_table4979
+ GCC_except_table5005
+ GCC_except_table5008
+ GCC_except_table5181
+ GCC_except_table5184
+ GCC_except_table5257
+ GCC_except_table5417
+ GCC_except_table5519
+ GCC_except_table5710
+ GCC_except_table5715
+ GCC_except_table5843
+ GCC_except_table6060
+ GCC_except_table6066
+ GCC_except_table6067
+ GCC_except_table6071
+ GCC_except_table608
+ GCC_except_table6261
+ GCC_except_table6434
+ GCC_except_table6462
+ GCC_except_table6563
+ GCC_except_table6567
+ GCC_except_table6596
+ GCC_except_table662
+ GCC_except_table7104
+ GCC_except_table7117
+ GCC_except_table7121
+ GCC_except_table7133
+ GCC_except_table7137
+ GCC_except_table7250
+ GCC_except_table7252
+ GCC_except_table7304
+ GCC_except_table7348
+ GCC_except_table7693
+ GCC_except_table7706
+ GCC_except_table7708
+ GCC_except_table7710
+ GCC_except_table7747
+ GCC_except_table7753
+ GCC_except_table7759
+ GCC_except_table7763
+ GCC_except_table7769
+ GCC_except_table7772
+ GCC_except_table7774
+ GCC_except_table7779
+ GCC_except_table7781
+ GCC_except_table7786
+ GCC_except_table7798
+ GCC_except_table7801
+ GCC_except_table7819
+ GCC_except_table7821
+ GCC_except_table7823
+ GCC_except_table7825
+ GCC_except_table7870
+ GCC_except_table7896
+ GCC_except_table7953
+ GCC_except_table7986
+ GCC_except_table8364
+ GCC_except_table865
+ GCC_except_table8652
+ GCC_except_table868
+ GCC_except_table875
+ GCC_except_table8859
+ GCC_except_table8917
+ GCC_except_table9285
+ GCC_except_table9289
+ GCC_except_table9334
+ GCC_except_table9340
+ GCC_except_table9367
+ GCC_except_table9374
+ GCC_except_table9585
+ GCC_except_table9659
+ GCC_except_table9670
+ GCC_except_table9703
+ GCC_except_table9706
+ GCC_except_table9782
+ GCC_except_table9786
+ GCC_except_table9796
+ GCC_except_table9807
+ GCC_except_table9822
+ GCC_except_table9907
+ GCC_except_table9909
+ GCC_except_table9933
+ OBJC_IVAR_$_AFConnection._isInRoutingStandby
+ OBJC_IVAR_$_AFLocalization._cachedVoiceMaps
+ OBJC_IVAR_$_AFLocalization._cachedVoiceMapsSource
+ OBJC_IVAR_$_AFLocalization._voiceMapsLock
+ _AFSiriActivationOdeonProxyVoiceTrigger
+ _OBJC_CLASS_$_SCDAStandbyObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCDAStandbyListening
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SCDAStandbyListening
+ __OBJC_$_PROTOCOL_REFS_SCDAStandbyListening
+ __OBJC_LABEL_PROTOCOL_$_SCDAStandbyListening
+ __OBJC_PROTOCOL_$_SCDAStandbyListening
+ ___35-[AFConnection scdaStandbyDidBegin]_block_invoke
+ ___39-[AFConnection scdaStandbyDidEndAsWon:]_block_invoke
+ ___66-[AFConnectionClientServiceDelegate requestSetReplayOverridePath:]_block_invoke_2
+ ___AFSiriActivationOdeonProxyVoiceTrigger_block_invoke
+ _objc_msgSend$_cleanupRoutingStandby
+ _objc_msgSend$_resetSpeechTimingForSpeechRequest:options:systemUptime:
+ _objc_msgSend$setListener:
- GCC_except_table1000
- GCC_except_table10040
- GCC_except_table10103
- GCC_except_table10106
- GCC_except_table10110
- GCC_except_table10129
- GCC_except_table10143
- GCC_except_table10217
- GCC_except_table10275
- GCC_except_table10301
- GCC_except_table10566
- GCC_except_table10695
- GCC_except_table10745
- GCC_except_table10839
- GCC_except_table10961
- GCC_except_table10963
- GCC_except_table10966
- GCC_except_table11037
- GCC_except_table11052
- GCC_except_table11077
- GCC_except_table11083
- GCC_except_table11233
- GCC_except_table11237
- GCC_except_table11239
- GCC_except_table11255
- GCC_except_table1136
- GCC_except_table11462
- GCC_except_table11786
- GCC_except_table11927
- GCC_except_table11930
- GCC_except_table11932
- GCC_except_table1203
- GCC_except_table1213
- GCC_except_table1334
- GCC_except_table1336
- GCC_except_table1519
- GCC_except_table1556
- GCC_except_table1564
- GCC_except_table1590
- GCC_except_table1599
- GCC_except_table1966
- GCC_except_table2080
- GCC_except_table2213
- GCC_except_table2335
- GCC_except_table2348
- GCC_except_table2349
- GCC_except_table2363
- GCC_except_table2371
- GCC_except_table2372
- GCC_except_table2375
- GCC_except_table2428
- GCC_except_table2430
- GCC_except_table2432
- GCC_except_table2450
- GCC_except_table2499
- GCC_except_table2511
- GCC_except_table2653
- GCC_except_table2743
- GCC_except_table2797
- GCC_except_table3023
- GCC_except_table3024
- GCC_except_table3221
- GCC_except_table3282
- GCC_except_table3498
- GCC_except_table3501
- GCC_except_table3506
- GCC_except_table3510
- GCC_except_table3524
- GCC_except_table3571
- GCC_except_table3676
- GCC_except_table3680
- GCC_except_table372
- GCC_except_table3790
- GCC_except_table3853
- GCC_except_table3855
- GCC_except_table3857
- GCC_except_table3873
- GCC_except_table390
- GCC_except_table4004
- GCC_except_table4008
- GCC_except_table4013
- GCC_except_table4385
- GCC_except_table4400
- GCC_except_table4407
- GCC_except_table4423
- GCC_except_table4495
- GCC_except_table4524
- GCC_except_table4562
- GCC_except_table4563
- GCC_except_table4564
- GCC_except_table4589
- GCC_except_table4613
- GCC_except_table4973
- GCC_except_table4978
- GCC_except_table4981
- GCC_except_table5173
- GCC_except_table5176
- GCC_except_table5249
- GCC_except_table5409
- GCC_except_table5511
- GCC_except_table5702
- GCC_except_table5707
- GCC_except_table5835
- GCC_except_table602
- GCC_except_table6052
- GCC_except_table6058
- GCC_except_table6059
- GCC_except_table6063
- GCC_except_table6253
- GCC_except_table6426
- GCC_except_table6454
- GCC_except_table6551
- GCC_except_table6555
- GCC_except_table656
- GCC_except_table6588
- GCC_except_table7096
- GCC_except_table7109
- GCC_except_table7113
- GCC_except_table7125
- GCC_except_table7129
- GCC_except_table7242
- GCC_except_table7244
- GCC_except_table7296
- GCC_except_table7340
- GCC_except_table7685
- GCC_except_table7692
- GCC_except_table7698
- GCC_except_table7702
- GCC_except_table7737
- GCC_except_table7739
- GCC_except_table7751
- GCC_except_table7755
- GCC_except_table7761
- GCC_except_table7764
- GCC_except_table7766
- GCC_except_table7771
- GCC_except_table7773
- GCC_except_table7778
- GCC_except_table7790
- GCC_except_table7793
- GCC_except_table7807
- GCC_except_table7809
- GCC_except_table7811
- GCC_except_table7813
- GCC_except_table7862
- GCC_except_table7888
- GCC_except_table7945
- GCC_except_table7978
- GCC_except_table8356
- GCC_except_table859
- GCC_except_table862
- GCC_except_table8644
- GCC_except_table869
- GCC_except_table8843
- GCC_except_table8909
- GCC_except_table9277
- GCC_except_table9281
- GCC_except_table9326
- GCC_except_table9332
- GCC_except_table9359
- GCC_except_table9366
- GCC_except_table9576
- GCC_except_table9650
- GCC_except_table9661
- GCC_except_table9694
- GCC_except_table9697
- GCC_except_table9773
- GCC_except_table9777
- GCC_except_table9787
- GCC_except_table9798
- GCC_except_table9813
- GCC_except_table9898
- GCC_except_table9900
- GCC_except_table9924
- __66-[AFConnectionClientServiceDelegate requestSetReplayOverridePath:]_block_invoke
CStrings:
+ "%s %p entering routing standby - suppressing interstitials"
+ "%s %p leaving routing standby (didWin = %d)"
+ "%s %p skipping interstitials while in routing standby (reason = %{public}@)"
+ "-[AFConnection scdaStandbyDidBegin]_block_invoke"
+ "-[AFConnection scdaStandbyDidEndAsWon:]_block_invoke"
+ "AFSiriActivationOdeonProxyVoiceTrigger"
+ "AppExclusions"
+ "odeonProxyVoiceTrigger"
+ "routing target standby began"
+ "routing target standby ended"
+ "\xf0\xf0\xf0\""
```
