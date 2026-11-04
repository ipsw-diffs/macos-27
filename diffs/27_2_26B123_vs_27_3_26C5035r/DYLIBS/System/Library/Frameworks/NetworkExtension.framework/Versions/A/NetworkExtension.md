## NetworkExtension

> `/System/Library/Frameworks/NetworkExtension.framework/Versions/A/NetworkExtension`

```diff

-2365.40.3.0.2
-  __TEXT.__text: 0x22c194
-  __TEXT.__objc_methlist: 0xf660
+2365.60.12.0.0
+  __TEXT.__text: 0x22d144
+  __TEXT.__objc_methlist: 0xf690
   __TEXT.__const: 0x36d0
   __TEXT.__swift5_typeref: 0xdf0
   __TEXT.__swift5_capture: 0x1038

   __TEXT.__swift_as_cont: 0x1f4
   __TEXT.__swift5_fieldmd: 0x680
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__cstring: 0x19e0d
-  __TEXT.__oslogstring: 0x26c47
+  __TEXT.__cstring: 0x19e2a
+  __TEXT.__oslogstring: 0x26ccb
   __TEXT.__gcc_except_tab: 0x51e4
-  __TEXT.__unwind_info: 0x6be0
+  __TEXT.__unwind_info: 0x6bf8
   __TEXT.__eh_frame: 0x2bd8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x54f0
+  __DATA_CONST.__objc_selrefs: 0x5508
   __DATA_CONST.__objc_protorefs: 0x158
   __DATA_CONST.__objc_superrefs: 0x728
   __DATA_CONST.__objc_arraydata: 0x148
   __DATA_CONST.__got: 0x17f8
   __AUTH_CONST.__const: 0x7c50
-  __AUTH_CONST.__cfstring: 0x196c0
-  __AUTH_CONST.__objc_const: 0x23498
+  __AUTH_CONST.__cfstring: 0x19720
+  __AUTH_CONST.__objc_const: 0x234b8
   __AUTH_CONST.__objc_intobj: 0x420
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x23f8
-  __DATA.__objc_ivar: 0x1c50
+  __DATA.__objc_ivar: 0x1c54
   __DATA.__data: 0x570
   __DATA.__bss: 0x1570
   __DATA.__common: 0x188

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8425
-  Symbols:   16685
-  CStrings:  7413
+  Functions: 8430
+  Symbols:   16693
+  CStrings:  7418
 
Symbols:
+ +[NEPolicyResult scopeSocketToInterfaceNameWithFlags:flags:]
+ +[NEPolicyResult tunnelIPToInterfaceNameWithFlags:secondaryResultType:flags:]
+ -[NEAppRule setMatchSigningIdentifier:]
+ -[NEPathController updateAppRulesForUID:]
+ -[NEPolicyResult appendInterfaceNameAndResultFlagsToData:]
+ GCC_except_table1033
+ GCC_except_table1037
+ GCC_except_table1039
+ GCC_except_table1087
+ GCC_except_table1180
+ GCC_except_table1240
+ GCC_except_table1247
+ GCC_except_table1415
+ GCC_except_table1426
+ GCC_except_table1432
+ GCC_except_table1438
+ GCC_except_table1451
+ GCC_except_table1463
+ GCC_except_table1592
+ GCC_except_table1718
+ GCC_except_table1723
+ GCC_except_table1726
+ GCC_except_table1793
+ GCC_except_table1798
+ GCC_except_table1802
+ GCC_except_table1805
+ GCC_except_table1814
+ GCC_except_table1821
+ GCC_except_table1852
+ GCC_except_table1880
+ GCC_except_table2091
+ GCC_except_table293
+ GCC_except_table3008
+ GCC_except_table3254
+ GCC_except_table3259
+ GCC_except_table3265
+ GCC_except_table3268
+ GCC_except_table3287
+ GCC_except_table3301
+ GCC_except_table3312
+ GCC_except_table3396
+ GCC_except_table3447
+ GCC_except_table3505
+ GCC_except_table3522
+ GCC_except_table3531
+ GCC_except_table3533
+ GCC_except_table3558
+ GCC_except_table3568
+ GCC_except_table3582
+ GCC_except_table3622
+ GCC_except_table3630
+ GCC_except_table3632
+ GCC_except_table3667
+ GCC_except_table3670
+ GCC_except_table3763
+ GCC_except_table3793
+ GCC_except_table4035
+ GCC_except_table4063
+ GCC_except_table4065
+ GCC_except_table4151
+ GCC_except_table4220
+ GCC_except_table4227
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table4325
+ GCC_except_table4340
+ GCC_except_table4346
+ GCC_except_table4369
+ GCC_except_table4373
+ GCC_except_table4379
+ GCC_except_table4385
+ GCC_except_table4393
+ GCC_except_table4466
+ GCC_except_table4474
+ GCC_except_table4576
+ GCC_except_table4578
+ GCC_except_table4674
+ GCC_except_table4860
+ GCC_except_table4865
+ GCC_except_table4872
+ GCC_except_table4903
+ GCC_except_table4913
+ GCC_except_table4917
+ GCC_except_table4929
+ GCC_except_table4951
+ GCC_except_table4959
+ GCC_except_table502
+ GCC_except_table5052
+ GCC_except_table5125
+ GCC_except_table5145
+ GCC_except_table5149
+ GCC_except_table5163
+ GCC_except_table524
+ GCC_except_table5268
+ GCC_except_table5310
+ GCC_except_table5356
+ GCC_except_table5358
+ GCC_except_table5423
+ GCC_except_table5426
+ GCC_except_table5464
+ GCC_except_table5484
+ GCC_except_table5486
+ GCC_except_table5488
+ GCC_except_table5500
+ GCC_except_table5541
+ GCC_except_table5545
+ GCC_except_table5548
+ GCC_except_table5592
+ GCC_except_table5613
+ GCC_except_table5616
+ GCC_except_table5713
+ GCC_except_table6043
+ GCC_except_table6081
+ GCC_except_table6082
+ GCC_except_table6085
+ GCC_except_table6151
+ GCC_except_table6157
+ GCC_except_table6158
+ GCC_except_table6166
+ GCC_except_table6169
+ GCC_except_table6179
+ GCC_except_table6197
+ GCC_except_table6198
+ GCC_except_table6201
+ GCC_except_table6204
+ GCC_except_table6205
+ GCC_except_table6208
+ GCC_except_table6214
+ GCC_except_table6223
+ GCC_except_table6226
+ GCC_except_table6230
+ GCC_except_table6309
+ GCC_except_table6310
+ GCC_except_table6457
+ GCC_except_table6458
+ GCC_except_table6459
+ GCC_except_table6460
+ GCC_except_table6461
+ GCC_except_table6475
+ GCC_except_table6476
+ GCC_except_table6482
+ GCC_except_table6508
+ GCC_except_table6589
+ GCC_except_table6590
+ GCC_except_table6591
+ GCC_except_table6592
+ GCC_except_table681
+ GCC_except_table687
+ GCC_except_table693
+ GCC_except_table700
+ GCC_except_table708
+ GCC_except_table805
+ GCC_except_table872
+ GCC_except_table879
+ GCC_except_table929
+ GCC_except_table934
+ GCC_except_table952
+ GCC_except_table961
+ GCC_except_table989
+ _OBJC_IVAR_$_NEPolicyResult._resultFlags
+ _objc_msgSend$isDefaultPathRule
+ _objc_msgSend$setMatchSigningIdentifier:
- GCC_except_table1027
- GCC_except_table1034
- GCC_except_table1038
- GCC_except_table1086
- GCC_except_table1179
- GCC_except_table1238
- GCC_except_table1244
- GCC_except_table1413
- GCC_except_table1417
- GCC_except_table1431
- GCC_except_table1436
- GCC_except_table1450
- GCC_except_table1461
- GCC_except_table1591
- GCC_except_table1716
- GCC_except_table1722
- GCC_except_table1725
- GCC_except_table1776
- GCC_except_table1797
- GCC_except_table1801
- GCC_except_table1804
- GCC_except_table1812
- GCC_except_table1820
- GCC_except_table1851
- GCC_except_table1879
- GCC_except_table2090
- GCC_except_table292
- GCC_except_table3007
- GCC_except_table3253
- GCC_except_table3258
- GCC_except_table3264
- GCC_except_table3267
- GCC_except_table3284
- GCC_except_table3300
- GCC_except_table3310
- GCC_except_table3395
- GCC_except_table3446
- GCC_except_table3504
- GCC_except_table3521
- GCC_except_table3530
- GCC_except_table3532
- GCC_except_table3555
- GCC_except_table3567
- GCC_except_table3581
- GCC_except_table3621
- GCC_except_table3629
- GCC_except_table3631
- GCC_except_table3666
- GCC_except_table3668
- GCC_except_table3762
- GCC_except_table3792
- GCC_except_table4034
- GCC_except_table4059
- GCC_except_table4064
- GCC_except_table4150
- GCC_except_table4219
- GCC_except_table4226
- GCC_except_table427
- GCC_except_table429
- GCC_except_table4324
- GCC_except_table4339
- GCC_except_table4345
- GCC_except_table4360
- GCC_except_table4372
- GCC_except_table4377
- GCC_except_table4384
- GCC_except_table4391
- GCC_except_table4464
- GCC_except_table4473
- GCC_except_table4570
- GCC_except_table4577
- GCC_except_table4672
- GCC_except_table4858
- GCC_except_table4863
- GCC_except_table4870
- GCC_except_table4901
- GCC_except_table4911
- GCC_except_table4915
- GCC_except_table4927
- GCC_except_table4947
- GCC_except_table4955
- GCC_except_table501
- GCC_except_table5049
- GCC_except_table5120
- GCC_except_table5140
- GCC_except_table5144
- GCC_except_table5158
- GCC_except_table523
- GCC_except_table5258
- GCC_except_table5305
- GCC_except_table5351
- GCC_except_table5353
- GCC_except_table5418
- GCC_except_table5421
- GCC_except_table5459
- GCC_except_table5479
- GCC_except_table5481
- GCC_except_table5483
- GCC_except_table5495
- GCC_except_table5535
- GCC_except_table5536
- GCC_except_table5538
- GCC_except_table5587
- GCC_except_table5608
- GCC_except_table5611
- GCC_except_table5708
- GCC_except_table6038
- GCC_except_table6076
- GCC_except_table6077
- GCC_except_table6080
- GCC_except_table6146
- GCC_except_table6152
- GCC_except_table6153
- GCC_except_table6161
- GCC_except_table6164
- GCC_except_table6174
- GCC_except_table6189
- GCC_except_table6190
- GCC_except_table6191
- GCC_except_table6192
- GCC_except_table6193
- GCC_except_table6203
- GCC_except_table6209
- GCC_except_table6218
- GCC_except_table6221
- GCC_except_table6225
- GCC_except_table6304
- GCC_except_table6305
- GCC_except_table6436
- GCC_except_table6437
- GCC_except_table6438
- GCC_except_table6439
- GCC_except_table6440
- GCC_except_table6465
- GCC_except_table6471
- GCC_except_table6472
- GCC_except_table6503
- GCC_except_table6584
- GCC_except_table6585
- GCC_except_table6586
- GCC_except_table6587
- GCC_except_table674
- GCC_except_table686
- GCC_except_table691
- GCC_except_table699
- GCC_except_table706
- GCC_except_table804
- GCC_except_table871
- GCC_except_table878
- GCC_except_table928
- GCC_except_table933
- GCC_except_table951
- GCC_except_table957
- GCC_except_table988
Functions:
+ -[NEAppRule setMatchSigningIdentifier:]
~ -[NEConfiguration configurePluginWithPayload:pluginType:payloadType:vpnType:] : 4384 -> 4980
~ ___59-[NEAppPushManager saveToPreferencesWithCompletionHandler:]_block_invoke.47 : 352 -> 412
+ -[NEPathController updateAppRulesForUID:]
~ -[NEDeclarationInstaller dictionaryForVPNConfiguration:] : 6480 -> 7932
+ +[NEPolicyResult scopeSocketToInterfaceNameWithFlags:flags:]
+ +[NEPolicyResult tunnelIPToInterfaceNameWithFlags:secondaryResultType:flags:]
~ -[NEPolicyResult descriptionWithIndent:options:] : 416 -> 448
+ -[NEPolicyResult appendInterfaceNameAndResultFlagsToData:]
~ -[NEPolicySession addPolicy:storeLocally:] : 6300 -> 6208
~ -[NEUtilConfigurationClient setDNSProxyWithParameters:errorStr:] : 304 -> 392
~ -[NEUtilConfigurationClient setAppPushParameters:errorStr:] : 488 -> 584
CStrings:
+ "%@ configurePluginWithPayload: unsupported or incomplete authentication, type %@, user name %@, password %@."
+ "%@ dictionaryForVPNConfiguration unsupported protocol type %ld"
+ "%@ found DDM sourced persistent reference [%@] for the password"
+ "Adding %lu plugin path rules"
+ "e"
+ "missing"
+ "present"
+ "result-flags"
- "%@ configurePluginWithPayload: unsupported authen type %@."
- "%@ dictionaryForVPNConfiguration failed to find protocol object for ipsec"
- "U"
```
