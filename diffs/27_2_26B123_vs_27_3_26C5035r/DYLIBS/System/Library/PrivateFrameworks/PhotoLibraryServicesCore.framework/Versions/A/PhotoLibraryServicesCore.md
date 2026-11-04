## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/Versions/A/PhotoLibraryServicesCore`

```diff

-916.58.114.0.0
-  __TEXT.__text: 0xd167c
-  __TEXT.__objc_methlist: 0x851c
-  __TEXT.__const: 0x22b4
+920.8.100.0.0
+  __TEXT.__text: 0xd56e8
+  __TEXT.__objc_methlist: 0x8584
+  __TEXT.__const: 0x2252
   __TEXT.__dlopen_cstrs: 0xe1
-  __TEXT.__gcc_except_tab: 0x57f4
-  __TEXT.__cstring: 0x158ea
-  __TEXT.__oslogstring: 0xb92d
+  __TEXT.__gcc_except_tab: 0x58ec
+  __TEXT.__cstring: 0x1595f
+  __TEXT.__oslogstring: 0xcdf5
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x4238
+  __TEXT.__unwind_info: 0x4298
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5100
+  __DATA_CONST.__objc_selrefs: 0x5150
   __DATA_CONST.__objc_protorefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x258
   __DATA_CONST.__objc_arraydata: 0x440
   __DATA_CONST.__got: 0xa20
-  __AUTH_CONST.__const: 0x5310
-  __AUTH_CONST.__cfstring: 0x11c20
-  __AUTH_CONST.__objc_const: 0xac78
+  __AUTH_CONST.__const: 0x5380
+  __AUTH_CONST.__cfstring: 0x11c60
+  __AUTH_CONST.__objc_const: 0xacb0
   __AUTH_CONST.__objc_intobj: 0x918
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x2b8
-  __AUTH_CONST.__auth_got: 0xd18
+  __AUTH_CONST.__auth_got: 0xd38
   __AUTH.__objc_data: 0xf0
-  __DATA.__objc_ivar: 0x698
+  __DATA.__objc_ivar: 0x69c
   __DATA.__data: 0x10e0
-  __DATA.__bss: 0x898
+  __DATA.__bss: 0x8c8
   __DATA_DIRTY.__objc_data: 0x2710
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__bss: 0x8b8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libperfcheck.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 4086
-  Symbols:   9544
-  CStrings:  3673
+  Functions: 4105
+  Symbols:   9583
+  CStrings:  3688
 
Symbols:
+ +[PLValidatedSavedAssetType maskForAllowedForFaceAnalysisInSPL]
+ +[PLValidatedSavedAssetType maskForAllowedForFaceAnalysis]
+ -[PLAssetsdPhotoKitClient importSyndicationAssetsWithUUIDs:importSource:options:sourceLibraryURL:completionHandler:]
+ -[PLLibraryBookmarkManager newSandboxExtensionDataForClient:clientOwnedPath:writable:]
+ -[PLLibraryServicesStateNode initWithLibraryServicesState:qualityOfService:logPrefix:libraryLogTag:]
+ -[PLLibraryServicesStateNode libraryLogTag]
+ -[PLPhotoLibraryPathManagerCore createPrivateDirectoryIfNeededWithBundleIdentifier:]
+ -[PLPhotoLibraryPathManagerCore internalCreateClientOwnedDirectoryAtPath:]
+ -[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:]
+ GCC_except_table10
+ GCC_except_table1007
+ GCC_except_table1010
+ GCC_except_table1013
+ GCC_except_table1016
+ GCC_except_table1019
+ GCC_except_table1022
+ GCC_except_table1025
+ GCC_except_table1028
+ GCC_except_table1031
+ GCC_except_table1037
+ GCC_except_table1045
+ GCC_except_table1048
+ GCC_except_table1051
+ GCC_except_table1054
+ GCC_except_table1057
+ GCC_except_table1060
+ GCC_except_table1063
+ GCC_except_table1065
+ GCC_except_table1068
+ GCC_except_table1071
+ GCC_except_table1074
+ GCC_except_table1092
+ GCC_except_table1095
+ GCC_except_table1103
+ GCC_except_table1106
+ GCC_except_table1109
+ GCC_except_table1112
+ GCC_except_table1115
+ GCC_except_table1118
+ GCC_except_table1121
+ GCC_except_table1124
+ GCC_except_table1127
+ GCC_except_table1130
+ GCC_except_table1132
+ GCC_except_table1134
+ GCC_except_table1139
+ GCC_except_table1143
+ GCC_except_table1146
+ GCC_except_table1149
+ GCC_except_table1152
+ GCC_except_table1155
+ GCC_except_table1158
+ GCC_except_table1165
+ GCC_except_table1174
+ GCC_except_table1177
+ GCC_except_table1180
+ GCC_except_table1181
+ GCC_except_table1182
+ GCC_except_table1183
+ GCC_except_table1184
+ GCC_except_table1185
+ GCC_except_table1186
+ GCC_except_table1190
+ GCC_except_table1195
+ GCC_except_table1201
+ GCC_except_table1204
+ GCC_except_table1207
+ GCC_except_table1210
+ GCC_except_table1213
+ GCC_except_table1218
+ GCC_except_table1221
+ GCC_except_table1224
+ GCC_except_table1228
+ GCC_except_table1232
+ GCC_except_table1235
+ GCC_except_table1239
+ GCC_except_table1243
+ GCC_except_table1249
+ GCC_except_table1252
+ GCC_except_table1260
+ GCC_except_table1263
+ GCC_except_table1267
+ GCC_except_table1271
+ GCC_except_table1274
+ GCC_except_table1277
+ GCC_except_table1280
+ GCC_except_table1281
+ GCC_except_table1284
+ GCC_except_table1288
+ GCC_except_table1293
+ GCC_except_table1296
+ GCC_except_table1299
+ GCC_except_table1303
+ GCC_except_table1306
+ GCC_except_table1313
+ GCC_except_table1316
+ GCC_except_table1321
+ GCC_except_table1324
+ GCC_except_table1328
+ GCC_except_table1331
+ GCC_except_table1334
+ GCC_except_table1337
+ GCC_except_table1340
+ GCC_except_table1344
+ GCC_except_table1348
+ GCC_except_table1355
+ GCC_except_table1359
+ GCC_except_table1363
+ GCC_except_table1374
+ GCC_except_table1383
+ GCC_except_table1392
+ GCC_except_table1395
+ GCC_except_table1398
+ GCC_except_table1403
+ GCC_except_table1419
+ GCC_except_table1422
+ GCC_except_table1431
+ GCC_except_table1444
+ GCC_except_table1454
+ GCC_except_table1512
+ GCC_except_table1520
+ GCC_except_table1546
+ GCC_except_table1597
+ GCC_except_table1629
+ GCC_except_table1641
+ GCC_except_table179
+ GCC_except_table180
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table188
+ GCC_except_table190
+ GCC_except_table193
+ GCC_except_table196
+ GCC_except_table2009
+ GCC_except_table2028
+ GCC_except_table208
+ GCC_except_table2174
+ GCC_except_table2194
+ GCC_except_table2196
+ GCC_except_table2238
+ GCC_except_table2246
+ GCC_except_table2378
+ GCC_except_table2394
+ GCC_except_table2402
+ GCC_except_table2413
+ GCC_except_table2418
+ GCC_except_table2419
+ GCC_except_table2766
+ GCC_except_table2771
+ GCC_except_table2779
+ GCC_except_table2784
+ GCC_except_table2929
+ GCC_except_table3010
+ GCC_except_table3095
+ GCC_except_table3103
+ GCC_except_table3109
+ GCC_except_table3180
+ GCC_except_table3309
+ GCC_except_table3368
+ GCC_except_table3380
+ GCC_except_table3386
+ GCC_except_table3405
+ GCC_except_table3408
+ GCC_except_table341
+ GCC_except_table355
+ GCC_except_table358
+ GCC_except_table3639
+ GCC_except_table3647
+ GCC_except_table3649
+ GCC_except_table3728
+ GCC_except_table373
+ GCC_except_table3764
+ GCC_except_table378
+ GCC_except_table3784
+ GCC_except_table3789
+ GCC_except_table381
+ GCC_except_table392
+ GCC_except_table3976
+ GCC_except_table3978
+ GCC_except_table400
+ GCC_except_table404
+ GCC_except_table4040
+ GCC_except_table408
+ GCC_except_table412
+ GCC_except_table416
+ GCC_except_table424
+ GCC_except_table428
+ GCC_except_table431
+ GCC_except_table438
+ GCC_except_table441
+ GCC_except_table444
+ GCC_except_table448
+ GCC_except_table452
+ GCC_except_table456
+ GCC_except_table459
+ GCC_except_table461
+ GCC_except_table465
+ GCC_except_table469
+ GCC_except_table473
+ GCC_except_table477
+ GCC_except_table481
+ GCC_except_table485
+ GCC_except_table493
+ GCC_except_table501
+ GCC_except_table505
+ GCC_except_table513
+ GCC_except_table521
+ GCC_except_table524
+ GCC_except_table528
+ GCC_except_table532
+ GCC_except_table536
+ GCC_except_table540
+ GCC_except_table544
+ GCC_except_table554
+ GCC_except_table557
+ GCC_except_table560
+ GCC_except_table564
+ GCC_except_table568
+ GCC_except_table572
+ GCC_except_table576
+ GCC_except_table580
+ GCC_except_table584
+ GCC_except_table588
+ GCC_except_table592
+ GCC_except_table596
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table604
+ GCC_except_table606
+ GCC_except_table607
+ GCC_except_table609
+ GCC_except_table614
+ GCC_except_table618
+ GCC_except_table620
+ GCC_except_table623
+ GCC_except_table626
+ GCC_except_table629
+ GCC_except_table635
+ GCC_except_table638
+ GCC_except_table642
+ GCC_except_table645
+ GCC_except_table648
+ GCC_except_table651
+ GCC_except_table654
+ GCC_except_table657
+ GCC_except_table659
+ GCC_except_table664
+ GCC_except_table668
+ GCC_except_table671
+ GCC_except_table674
+ GCC_except_table677
+ GCC_except_table680
+ GCC_except_table683
+ GCC_except_table686
+ GCC_except_table689
+ GCC_except_table692
+ GCC_except_table695
+ GCC_except_table701
+ GCC_except_table704
+ GCC_except_table707
+ GCC_except_table710
+ GCC_except_table713
+ GCC_except_table716
+ GCC_except_table719
+ GCC_except_table722
+ GCC_except_table725
+ GCC_except_table729
+ GCC_except_table742
+ GCC_except_table748
+ GCC_except_table751
+ GCC_except_table754
+ GCC_except_table757
+ GCC_except_table760
+ GCC_except_table763
+ GCC_except_table766
+ GCC_except_table769
+ GCC_except_table774
+ GCC_except_table776
+ GCC_except_table778
+ GCC_except_table781
+ GCC_except_table784
+ GCC_except_table787
+ GCC_except_table790
+ GCC_except_table793
+ GCC_except_table795
+ GCC_except_table798
+ GCC_except_table801
+ GCC_except_table804
+ GCC_except_table807
+ GCC_except_table810
+ GCC_except_table813
+ GCC_except_table817
+ GCC_except_table821
+ GCC_except_table824
+ GCC_except_table827
+ GCC_except_table830
+ GCC_except_table833
+ GCC_except_table836
+ GCC_except_table838
+ GCC_except_table841
+ GCC_except_table846
+ GCC_except_table849
+ GCC_except_table852
+ GCC_except_table856
+ GCC_except_table860
+ GCC_except_table879
+ GCC_except_table884
+ GCC_except_table887
+ GCC_except_table890
+ GCC_except_table894
+ GCC_except_table897
+ GCC_except_table902
+ GCC_except_table905
+ GCC_except_table908
+ GCC_except_table911
+ GCC_except_table914
+ GCC_except_table923
+ GCC_except_table929
+ GCC_except_table935
+ GCC_except_table938
+ GCC_except_table941
+ GCC_except_table944
+ GCC_except_table947
+ GCC_except_table950
+ GCC_except_table954
+ GCC_except_table959
+ GCC_except_table962
+ GCC_except_table965
+ GCC_except_table968
+ GCC_except_table971
+ GCC_except_table974
+ GCC_except_table977
+ GCC_except_table980
+ GCC_except_table983
+ GCC_except_table986
+ GCC_except_table988
+ GCC_except_table990
+ _OBJC_IVAR_$_PLLibraryServicesStateNode._libraryLogTag
+ _PLCanonicalParentPath
+ _PLCurrentLibraryLogTag
+ _PLInternLibraryLogTag
+ _PLInternLibraryLogTag.s_lock
+ _PLInternLibraryLogTag.s_tagsByIdentifier
+ _PLIsSharedCollectionsSearchFeatureEnabled
+ _PLPlatformLeoSupported
+ _PLSearchBackendFindExpanderGetLog
+ _PLSearchBackendFindExpanderGetLog.log
+ _PLSearchBackendFindExpanderGetLog.predicate
+ __PLSetCurrentLibraryLogTag
+ ___116-[PLAssetsdPhotoKitClient importSyndicationAssetsWithUUIDs:importSource:options:sourceLibraryURL:completionHandler:]_block_invoke
+ ___PLSearchBackendFindExpanderGetLog_block_invoke
+ ____libraryLogTagThreadKey_block_invoke
+ ___block_descriptor_40_e8_32bs_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24l
+ ___block_descriptor_64_e8_32s40s48s56r_e35_v32?0"NSString"8"NSNumber"16^B24l
+ ___block_descriptor_72_e8_32s40s48s56s64r_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64r
+ __libraryLogTagThreadKey.s_key
+ __libraryLogTagThreadKey.s_onceToken
+ _objc_msgSend$createPrivateDirectoryIfNeededWithBundleIdentifier:
+ _objc_msgSend$importSyndicationAssetsWithUUIDs:importSource:options:sourceLibraryURL:reply:
+ _objc_msgSend$internalCreateClientOwnedDirectoryAtPath:
+ _objc_msgSend$libraryLogTag
+ _objc_msgSend$maskForAllowedForFaceAnalysis
+ _objc_msgSend$newSandboxExtensionDataForClient:clientOwnedPath:writable:
+ _objc_msgSend$pointerValue
+ _objc_msgSend$privateDirectoryWithBundleIdentifier:
+ _objc_msgSend$valueWithPointer:
+ _pthread_getspecific
+ _pthread_key_create
+ _pthread_setspecific
+ _strdup
- -[PLLibraryServicesStateNode initWithLibraryServicesState:qualityOfService:logPrefix:]
- -[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:createIfNeeded:]
- GCC_except_table1008
- GCC_except_table1011
- GCC_except_table1014
- GCC_except_table1017
- GCC_except_table1020
- GCC_except_table1023
- GCC_except_table1026
- GCC_except_table1029
- GCC_except_table1036
- GCC_except_table1038
- GCC_except_table1044
- GCC_except_table1047
- GCC_except_table1050
- GCC_except_table1053
- GCC_except_table1055
- GCC_except_table1058
- GCC_except_table1061
- GCC_except_table1064
- GCC_except_table1067
- GCC_except_table1070
- GCC_except_table1073
- GCC_except_table1077
- GCC_except_table1081
- GCC_except_table1090
- GCC_except_table1093
- GCC_except_table1096
- GCC_except_table1157
- GCC_except_table1524
- GCC_except_table1539
- GCC_except_table1548
- GCC_except_table1665
- GCC_except_table1698
- GCC_except_table1705
- GCC_except_table1741
- GCC_except_table1759
- GCC_except_table178
- GCC_except_table1785
- GCC_except_table1789
- GCC_except_table1794
- GCC_except_table1797
- GCC_except_table1800
- GCC_except_table1803
- GCC_except_table1806
- GCC_except_table1809
- GCC_except_table1812
- GCC_except_table1815
- GCC_except_table1818
- GCC_except_table182
- GCC_except_table1821
- GCC_except_table1823
- GCC_except_table1825
- GCC_except_table1828
- GCC_except_table1831
- GCC_except_table1834
- GCC_except_table1837
- GCC_except_table1840
- GCC_except_table1842
- GCC_except_table1845
- GCC_except_table1848
- GCC_except_table1851
- GCC_except_table1854
- GCC_except_table1857
- GCC_except_table1860
- GCC_except_table1863
- GCC_except_table1866
- GCC_except_table1869
- GCC_except_table1872
- GCC_except_table1876
- GCC_except_table1880
- GCC_except_table1883
- GCC_except_table1886
- GCC_except_table1889
- GCC_except_table1892
- GCC_except_table1895
- GCC_except_table1898
- GCC_except_table1900
- GCC_except_table1903
- GCC_except_table1906
- GCC_except_table1909
- GCC_except_table1919
- GCC_except_table1927
- GCC_except_table1935
- GCC_except_table2037
- GCC_except_table2056
- GCC_except_table217
- GCC_except_table220
- GCC_except_table2208
- GCC_except_table221
- GCC_except_table2216
- GCC_except_table222
- GCC_except_table223
- GCC_except_table225
- GCC_except_table2266
- GCC_except_table2271
- GCC_except_table2272
- GCC_except_table2274
- GCC_except_table2277
- GCC_except_table2417
- GCC_except_table2498
- GCC_except_table2539
- GCC_except_table256
- GCC_except_table2573
- GCC_except_table2578
- GCC_except_table2581
- GCC_except_table2584
- GCC_except_table2589
- GCC_except_table2592
- GCC_except_table2595
- GCC_except_table2598
- GCC_except_table2601
- GCC_except_table2604
- GCC_except_table2607
- GCC_except_table2610
- GCC_except_table262
- GCC_except_table2624
- GCC_except_table2633
- GCC_except_table265
- GCC_except_table2681
- GCC_except_table2685
- GCC_except_table2689
- GCC_except_table2692
- GCC_except_table2697
- GCC_except_table270
- GCC_except_table2700
- GCC_except_table2703
- GCC_except_table2707
- GCC_except_table2711
- GCC_except_table2715
- GCC_except_table2718
- GCC_except_table2720
- GCC_except_table2724
- GCC_except_table2728
- GCC_except_table2732
- GCC_except_table2736
- GCC_except_table2740
- GCC_except_table2744
- GCC_except_table2748
- GCC_except_table2752
- GCC_except_table2756
- GCC_except_table276
- GCC_except_table2760
- GCC_except_table2764
- GCC_except_table2768
- GCC_except_table2772
- GCC_except_table2776
- GCC_except_table2780
- GCC_except_table2783
- GCC_except_table2787
- GCC_except_table279
- GCC_except_table2791
- GCC_except_table2795
- GCC_except_table2799
- GCC_except_table2803
- GCC_except_table2807
- GCC_except_table2810
- GCC_except_table2813
- GCC_except_table2816
- GCC_except_table2819
- GCC_except_table2823
- GCC_except_table2827
- GCC_except_table2831
- GCC_except_table2835
- GCC_except_table2839
- GCC_except_table284
- GCC_except_table2843
- GCC_except_table2847
- GCC_except_table2851
- GCC_except_table2855
- GCC_except_table2858
- GCC_except_table2860
- GCC_except_table2863
- GCC_except_table2865
- GCC_except_table2866
- GCC_except_table2868
- GCC_except_table2871
- GCC_except_table2875
- GCC_except_table2877
- GCC_except_table2880
- GCC_except_table2883
- GCC_except_table2886
- GCC_except_table2889
- GCC_except_table2892
- GCC_except_table2895
- GCC_except_table2898
- GCC_except_table2901
- GCC_except_table2904
- GCC_except_table2907
- GCC_except_table2910
- GCC_except_table2913
- GCC_except_table2916
- GCC_except_table2918
- GCC_except_table292
- GCC_except_table295
- GCC_except_table2974
- GCC_except_table298
- GCC_except_table3041
- GCC_except_table3044
- GCC_except_table307
- GCC_except_table3101
- GCC_except_table315
- GCC_except_table3156
- GCC_except_table3168
- GCC_except_table3170
- GCC_except_table3174
- GCC_except_table3176
- GCC_except_table3194
- GCC_except_table3202
- GCC_except_table3208
- GCC_except_table323
- GCC_except_table326
- GCC_except_table329
- GCC_except_table335
- GCC_except_table3363
- GCC_except_table3365
- GCC_except_table3367
- GCC_except_table3372
- GCC_except_table3376
- GCC_except_table3379
- GCC_except_table3385
- GCC_except_table3391
- GCC_except_table3443
- GCC_except_table3445
- GCC_except_table3480
- GCC_except_table3585
- GCC_except_table3656
- GCC_except_table3660
- GCC_except_table3667
- GCC_except_table3721
- GCC_except_table3724
- GCC_except_table3730
- GCC_except_table3733
- GCC_except_table3736
- GCC_except_table3739
- GCC_except_table3745
- GCC_except_table3751
- GCC_except_table3755
- GCC_except_table3759
- GCC_except_table3767
- GCC_except_table3788
- GCC_except_table3791
- GCC_except_table3800
- GCC_except_table3813
- GCC_except_table3831
- GCC_except_table3839
- GCC_except_table3841
- GCC_except_table3846
- GCC_except_table385
- GCC_except_table3850
- GCC_except_table3856
- GCC_except_table3861
- GCC_except_table3864
- GCC_except_table3867
- GCC_except_table3871
- GCC_except_table3874
- GCC_except_table3881
- GCC_except_table3884
- GCC_except_table3889
- GCC_except_table3892
- GCC_except_table3896
- GCC_except_table3899
- GCC_except_table3902
- GCC_except_table3905
- GCC_except_table3908
- GCC_except_table3912
- GCC_except_table3916
- GCC_except_table3930
- GCC_except_table3933
- GCC_except_table3977
- GCC_except_table4002
- GCC_except_table4003
- GCC_except_table4004
- GCC_except_table4006
- GCC_except_table4008
- GCC_except_table4010
- GCC_except_table4011
- GCC_except_table4013
- GCC_except_table4016
- GCC_except_table4017
- GCC_except_table4029
- GCC_except_table4042
- GCC_except_table4047
- GCC_except_table405
- GCC_except_table4055
- GCC_except_table4060
- GCC_except_table411
- GCC_except_table433
- GCC_except_table494
- GCC_except_table500
- GCC_except_table503
- GCC_except_table506
- GCC_except_table514
- GCC_except_table520
- GCC_except_table527
- GCC_except_table531
- GCC_except_table534
- GCC_except_table538
- GCC_except_table542
- GCC_except_table559
- GCC_except_table563
- GCC_except_table573
- GCC_except_table694
- GCC_except_table728
- GCC_except_table749
- GCC_except_table752
- GCC_except_table755
- GCC_except_table758
- GCC_except_table759
- GCC_except_table762
- GCC_except_table919
- GCC_except_table924
- GCC_except_table928
- GCC_except_table931
- GCC_except_table934
- GCC_except_table937
- GCC_except_table940
- GCC_except_table943
- GCC_except_table946
- GCC_except_table949
- GCC_except_table955
- GCC_except_table961
- GCC_except_table964
- GCC_except_table967
- GCC_except_table970
- GCC_except_table973
- GCC_except_table976
- GCC_except_table979
- GCC_except_table982
- GCC_except_table985
- GCC_except_table989
- ___block_descriptor_56_e8_32s40s48r_e35_v32?0"NSString"8"NSNumber"16^B24l
- ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0l
- _objc_msgSend$privateDirectoryWithBundleIdentifier:createIfNeeded:
CStrings:
+ "%{public}s  %@"
+ "%{public}s  %{public}@ = %{public}@"
+ "%{public}s  [...and %d more]"
+ "%{public}s  [job-%d] type %{public}@ uuid %{public}@"
+ "%{public}s#### Format %@ : %d x %d, crop %d"
+ "%{public}s#### fastFormatCount %lu"
+ "%{public}s#### fastTableFormats %@"
+ "%{public}s#### fastThumbPersistenceManagers %@"
+ "%{public}s##### %@ %@"
+ "%{public}s%@"
+ "%{public}s%@ for '%@' (%s)."
+ "%{public}s%@ for '%@' (%s): %@."
+ "%{public}s%@ has no bundle identifier. Will fallback on process ID"
+ "%{public}s%ld bytes written to %@"
+ "%{public}s%s Failed to open PHPhotoLibrary for the SPL, sending empty dictionary to handler: %@"
+ "%{public}s%s: failed to create context"
+ "%{public}s%s: failed to create directory: %@ with error: %@"
+ "%{public}s%{public}@ %@ hasExtension:%{public}@"
+ "%{public}s%{public}@ Removing power assertion: -🔌"
+ "%{public}s%{public}@ could not be created, error: %{public}s"
+ "%{public}s%{public}@ could not be created, error: %{public}s, dir creation %{public}@"
+ "%{public}s%{public}@ could not be removed, error: %{public}s"
+ "%{public}s%{public}@ taking power assertion: +🔌"
+ "%{public}s%{public}@, backtrace:\n%@"
+ "%{public}s%{public}@: Setting QoS of state node %{public}@ to %{public}@"
+ "%{public}s%{public}@: Unable to enqueue operation: %@"
+ "%{public}s%{public}s failed after exceeding maximum parent directory attempts on %@ [at path %@]"
+ "%{public}s%{public}s failed to remove %@ [%{public}@]"
+ "%{public}s%{public}s is only available in photolibraryd"
+ "%{public}s%{public}s: Could not read mobileCPL.plist at path %@: File doesn't exist"
+ "%{public}s%{public}s: Error reading mobileCPL.plist at path %@: %@"
+ "%{public}s%{public}s: failed to create directory: %@ with error: %@"
+ "%{public}s%{public}s: failed to get SecTask from %{public}@"
+ "%{public}s%{public}s: failed to get identifier from %{public}@"
+ "%{public}s%{public}s: missing required connection"
+ "%{public}s*** ImageTable expand: F_PREALLOCATE of %d %@ to %lld returned -1: error=%s"
+ "%{public}s*** ImageTable: ftruncate of %d %@ to %lld returned -1: error=%s"
+ "%{public}s--- BEGIN File diagnostics for %{public}@ ---"
+ "%{public}s--- END File diagnostics for %{public}@ ---"
+ "%{public}sABORT: %{public}s"
+ "%{public}sAdded owner read and write permission to %@ (was %o)"
+ "%{public}sAdjustments data file does not contain a data blob"
+ "%{public}sAdjustments property list contains an empty data blob"
+ "%{public}sAdjustments property list does not contain a data blob"
+ "%{public}sAppPrivateData invalid bundle root. Error: %@"
+ "%{public}sApplication state is not ready for limited library picker re-prompt"
+ "%{public}sAsk for help in #help-photos-disclosed"
+ "%{public}sBogus object ID from data: %{public}@"
+ "%{public}sBogus object ID in xpc data."
+ "%{public}sBogus value type in xpc, data %p = %p"
+ "%{public}sBogus value type in xpc, dictionary %p = %p"
+ "%{public}sBogus value type in xpc, error dictionary %p = %p"
+ "%{public}sBookmarked SPL changed: Updating SPL in defaults to %@"
+ "%{public}sCS_OPS_VALIDATION_CATEGORY failed for pid %d: %s"
+ "%{public}sCall stack that enabled multi-library mode:"
+ "%{public}sCalling XPC getLibrarySizesFromDB:%@ at QoS %@"
+ "%{public}sCalling addBarrierBlock: when NSXPCConnection has not been created"
+ "%{public}sCan't decypher process name"
+ "%{public}sCan't get process name for %@: %s"
+ "%{public}sCannot trim read-only table %@"
+ "%{public}sCleared IMMUTABLE flag from %@"
+ "%{public}sClient connection interrupted for URL %@, resetting bind state (previous result: %@)"
+ "%{public}sClient failed to access the proxy lock file path. Error: %@"
+ "%{public}sConnection to assetsd was interrupted (shutting down)"
+ "%{public}sConnection to assetsd was interrupted - photolibraryd exited, died, or closed the photo library"
+ "%{public}sConnection to assetsd was invalidated - connection cannot be formed, or remote endpoint/listener was invalidated. Setting connection object to nil."
+ "%{public}sConnection to assetsd was invalidated from client side. Setting connection object to nil."
+ "%{public}sConstructed legacy SPL URL based on unresolvable bookmark: %@"
+ "%{public}sConstructed legacy SPL URL from unresolvable bookmark: %@"
+ "%{public}sContent privacy default not set in domain %@. Defaulting to YES"
+ "%{public}sContextual video thumbnail identifier is not usable as part of a filename"
+ "%{public}sCoreAnalytics published event: %{public}@ payload: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: invalid parameter for event name: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: invalid parameter for event name: %{public}@ key: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: invalid parameter for event name: %{public}@ key: %{public}@ value: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: invalid parameter for event name: %{public}@ payload: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: invalid value for event name: %{public}@ key: %{public}@"
+ "%{public}sCoreAnalyticsEventManager: publish to Core Analytics is disabled for event: %{public}@"
+ "%{public}sCould not create PLPositionalImageTable at path %@: %s (%d)"
+ "%{public}sCould not open PLPositionalImageTable at path %@: %s (%d)"
+ "%{public}sCould not set file creation date on %@, error: %@"
+ "%{public}sCreating an autobinding proxy factory from a nil proxy factor for library URL: %@"
+ "%{public}sCreating an image format with an unknown type is an error"
+ "%{public}sCreating blackhole proxy for %@ from proxy factory %@ for library URL: %@"
+ "%{public}sData was corrupt; forcing +[NSKeyedUnarchiver unarchivedObjectOfClass:fromData:error:] to return nil, error: %@"
+ "%{public}sData was corrupt; forcing +[NSKeyedUnarchiver unarchivedObjectOfClasses:fromData:error:] to return nil, error: %@"
+ "%{public}sData was corrupt; forcing -[NSKeyedUnarchiver initForReadingFromData:error:] to return nil, error: %@"
+ "%{public}sDefault for excluding location when sharing is not set in domain %@. Defaulting to NO"
+ "%{public}sDetected thumbnail configuration change: from formats: %{public}@ to formats: %{public}@, tableChangesOnly: %d, migrationToCompressedTablesOnly: %d, fullRebuild: %d"
+ "%{public}sDisabling libnotify calls due to shutdown"
+ "%{public}sERROR: PLArrayFromXPCDictionary failed to deserialize array"
+ "%{public}sERROR: PLArrayFromXPCDictionary failed to deserialize array (root object not an array: %@)"
+ "%{public}sERROR: PLDictionaryFromXPCDictionary failed to deserialize dictionary"
+ "%{public}sERROR: PLDictionaryFromXPCDictionary failed to deserialize dictionary (root object not a dictionary: %@)"
+ "%{public}sEncountered exception attempting to determine application state for limited library picker reprompt: %{public}@"
+ "%{public}sError %d occurred while trying to call notify_post for: %s. (attempt number: %d of %d)"
+ "%{public}sError %d occurred while trying to connect notify handler for %s. (attempt number: %d of %d)"
+ "%{public}sError %{public}@ mobileCPL.plist, path is nil, pathManager: %@, error: %@"
+ "%{public}sError creating bookmark data for URL %@ : %@"
+ "%{public}sError creating code requirements from data: %ld"
+ "%{public}sError determining capabilities for %@: %@"
+ "%{public}sError fetching donated moment share from external client: %@"
+ "%{public}sError getting assetsd remote object proxy (%@)"
+ "%{public}sError getting filesystem size for libraryURL %@"
+ "%{public}sError getting master thumbnail %@ for %s: %@"
+ "%{public}sError getting photo library identifier for url %@: %@"
+ "%{public}sError getting photo library identifier: %@"
+ "%{public}sError getting photos XPC endpoint: %@"
+ "%{public}sError getting projectExtensionDataForProjectUuid = %@: %@"
+ "%{public}sError getting remote object proxy (%@)"
+ "%{public}sError getting remote object proxy for %s: %@"
+ "%{public}sError getting remote object proxy for %{public}s: %@"
+ "%{public}sError getting remote object proxy to open photo library with URL %s: %@ %@"
+ "%{public}sError getting resource values for %@: %@"
+ "%{public}sError getting resource values for default SPL URL %@: %@"
+ "%{public}sError getting size of resources to upload by CPL, error: %@"
+ "%{public}sError getting the real path for the provided url path: %@: %@."
+ "%{public}sError in reply for %s: %@"
+ "%{public}sError prefetching resources: %s %@"
+ "%{public}sError reading property list from %@"
+ "%{public}sError received from proxy factory %{public}@ in %{public}@: %@"
+ "%{public}sError removing old SPL group plist: %@"
+ "%{public}sError saving mobileCPL.plist: %@ at path %@: %@"
+ "%{public}sError setting client privacy options (%@)"
+ "%{public}sError setting photos XPC endpoint: %@"
+ "%{public}sError synchronously rebuilding moments and delete existing ones before: %d, error: %@"
+ "%{public}sError trying to remove mobileCPL.plist at path %@: %@"
+ "%{public}sError trying to serialize data: %@ to write to mobileCPL.plist at path %@: %@"
+ "%{public}sError waiting for search index existence: %@"
+ "%{public}sError: API misuse. Operating in multi library mode but calling single library mode API."
+ "%{public}sError: API misuse. Operating in single library mode for %@ but a different library was requested: %@"
+ "%{public}sExpected the home directory path to have fewer components than the provided url"
+ "%{public}sFailed bind after %lu attempts"
+ "%{public}sFailed to %@ %@ to %@: %@"
+ "%{public}sFailed to %{public}@ photos picker client log from %{public}@: %@"
+ "%{public}sFailed to access photos picker client log for client with invalid bundle identifier: %{public}@"
+ "%{public}sFailed to add owner read and write permission to %@ (%{public}s)."
+ "%{public}sFailed to archive errorData, error: %@"
+ "%{public}sFailed to bind to photo library %@, %@"
+ "%{public}sFailed to calloc buffer for PLPositionalImageTableNSDataReleaseInfo."
+ "%{public}sFailed to clear IMMUTABLE flag on %@ (%{public}s)."
+ "%{public}sFailed to clear backup backup exclusion marker [include], path: %@, error: %@"
+ "%{public}sFailed to clear backup exclusion marker [iCloud-iCPL-enabled], path: %@, error: %@"
+ "%{public}sFailed to clear backup exclusion marker [iCloud], path: %@, error: %@"
+ "%{public}sFailed to clear backup exclusion marker [include], path: %@, error: %@"
+ "%{public}sFailed to close database: %s (%d)."
+ "%{public}sFailed to create SecCodeRef for token: %ld."
+ "%{public}sFailed to create client-owned directory %@: %@"
+ "%{public}sFailed to create photos picker client log for client with empty bundle identifier: %{public}@"
+ "%{public}sFailed to create power assertion for migration. Result code: %d"
+ "%{public}sFailed to determine if internal originals subdirectory location resource is a directory at url: %@ Error: %@"
+ "%{public}sFailed to enable WAL - %d %s"
+ "%{public}sFailed to enumerate url %@ for relocated originals discovery. Error: %@"
+ "%{public}sFailed to execute \"%@\": %s (%d)"
+ "%{public}sFailed to issue advisory read for file: %d at path: %@ with error=%s"
+ "%{public}sFailed to issue set read ahead for file: %d at path: %@ with error=%s"
+ "%{public}sFailed to message privacy support client to reprompt alert"
+ "%{public}sFailed to open DB - %d"
+ "%{public}sFailed to open the stream"
+ "%{public}sFailed to persist to \"%@\": %@"
+ "%{public}sFailed to prepare \"%@\": %s (%d)"
+ "%{public}sFailed to present library picker alert on behalf of '%{public}@'"
+ "%{public}sFailed to produced availability snapshot, error: %@"
+ "%{public}sFailed to produced processing snapshot, error: %@"
+ "%{public}sFailed to register limited library picker"
+ "%{public}sFailed to release power assertion for migration. Result code: %d"
+ "%{public}sFailed to remove non-directory at client-owned path %@ (%{darwin.errno}d)"
+ "%{public}sFailed to remove replacement directory after cross-device replace %@: %@"
+ "%{public}sFailed to remove source file after cross-device replace %@: %@"
+ "%{public}sFailed to resolve real path for %@ (%{public}s)."
+ "%{public}sFailed to serialize adjustments property list: %@"
+ "%{public}sFailed to serialize backingDictionary. Error: %@"
+ "%{public}sFailed to set backup exclusion marker [all-DCIM], path: %@, error: %@"
+ "%{public}sFailed to set backup exclusion marker [all], path: %@, error: %@"
+ "%{public}sFailed to set backup exclusion marker [iCloud-DCIM], path: %@, error: %@"
+ "%{public}sFailed to set backup exclusion marker [iCloud-iCPL-enabled], path: %@, error: %@"
+ "%{public}sFailed to set backup exclusion marker [iCloud], path: %@, error: %@"
+ "%{public}sFailed to set backup exclusion marker [time-machine], path: %@, error: %@"
+ "%{public}sFailed to set lock_proxy_file (statement parse error) for path: %@"
+ "%{public}sFailed to set lock_proxy_file - %d %s"
+ "%{public}sFailed to set the backup exclusion marker for the library bundle. Error: %@"
+ "%{public}sFailed to stat %@ (%{public}s)."
+ "%{public}sFailed to stat thumbnail table with error=%s"
+ "%{public}sFailed to step statement: %s (%d)"
+ "%{public}sFailed to trim table %@ to %lld bytes: %s"
+ "%{public}sFailed to unarchive NSError, error: %@"
+ "%{public}sFailed to write SPL path to private group container"
+ "%{public}sFailed to write property list to %@. Error: %@"
+ "%{public}sFailed validity check on code requirements from data: %@"
+ "%{public}sFeatured content allowed default not set in domain %@. Defaulting to YES"
+ "%{public}sFetched adjustments data from file"
+ "%{public}sFile radar with sysdiagnose to component: Photos Backend Storage | all"
+ "%{public}sFileIdentifier - filenameUUID is nil for url: %@"
+ "%{public}sFinished table thumb rebuild with status: %@, for %s"
+ "%{public}sFooter data invalid at index: %lu (imageHeight: %d, imageWidth: %d), format side len: %d"
+ "%{public}sFound SPL path in group plist in container prefs location"
+ "%{public}sGet parent sync root failed for %{public}@ error %d %{public}s"
+ "%{public}sGet sync root flag failed for %{public}@ error %d %{public}s"
+ "%{public}sGot a bind failure for URL %@, resetting bind state: %@ (previous result: %@)"
+ "%{public}sGot a nil proxy from proxy factory %@ for library URL: %@"
+ "%{public}sImported Lithium SSB for %@"
+ "%{public}sIngest failed for %{public}@ : %{public}@ : %@"
+ "%{public}sIngesting %@ to %@ with ingestion type %@ option %lu"
+ "%{public}sInvalid format mode for ThumbFile (%@)"
+ "%{public}sInvalid subtype for internal location"
+ "%{public}sInvalid thumbnail identifier for file identifier: %@"
+ "%{public}sInvalid thumbnail identifier scheme: %@"
+ "%{public}sLegacy system library bookmark data is present but not resolvable: %@"
+ "%{public}sLegacy system photo library URL exists but it is not resolvable. Returning bogus URL: %@"
+ "%{public}sLegacy system photo library bookmark is present"
+ "%{public}sLibrary URL was found to contain \".backup\""
+ "%{public}sLibrary URL was found to contain \"Backups.backupdb\""
+ "%{public}sLibrary URL was found to have a HFS TimeMachine location"
+ "%{public}sLibrary URL was found to have the prefix \"/Volumes/.timemachine\""
+ "%{public}sLog archive recreated on %@"
+ "%{public}sLogging client %{public}@ (pid: %ld) access to photos (%{public}@)"
+ "%{public}sLogging client %{public}@ (pid: %ld) access to photos via picker"
+ "%{public}sLowering QoS for getLibrarySizes from %@ to UT"
+ "%{public}sMT library sizing done (%lu bytes)"
+ "%{public}sMT library sizing starting"
+ "%{public}sMain bundle path is nil"
+ "%{public}sMissing NSPhotoLibraryAddUsageDescription, will try photos access instead of add-only"
+ "%{public}sMissing path to get free space"
+ "%{public}sMissing thumbnail table for format %d"
+ "%{public}sMount point for %@: %@"
+ "%{public}sNegative interval: %f"
+ "%{public}sNil designated requirement data"
+ "%{public}sNo %{public}@ sandbox extension for path %@ for client pid %{public}ld (%{public}@)"
+ "%{public}sNo NSURLPathKey available from unresolvable bookmark"
+ "%{public}sNo PLPositionalImageTable file found at path %@"
+ "%{public}sNo SPL stored, and SPL from standard defaults was %@"
+ "%{public}sNo SSB on file for %@"
+ "%{public}sNo realpath for SPL URL %@, %@"
+ "%{public}sNo realpath for URL %@, %@"
+ "%{public}sNo trimming needed for table %@ (requested %lu, current %ld)"
+ "%{public}sNot a valid system library URL because it not a supported filesystem %@: %@"
+ "%{public}sNot creating client-owned directory %@: %@"
+ "%{public}sObject is nil, deleting key %@ from mobileCPL.plist"
+ "%{public}sPFFigCreateCGImageFromImageData %s returned %ld from %@"
+ "%{public}sPID %d: Waiting for: notifyutil -p %s\n"
+ "%{public}sPLCreateDirectoryIfNeededAndGetSandboxExtensionToken: failed to create directory=%@ error=%@"
+ "%{public}sPLFileBackedLogger: Backend logging failed to determine the url status for %{public}@. Error: %@"
+ "%{public}sPLFileBackedLogger: Backend logging failed to removed corrupt log file %{public}@. Error: %@"
+ "%{public}sPLFileBackedLogger: Backend logging requires a file URL with an expected path extension %{public}@"
+ "%{public}sPLFileBackedLogger: Backend logging requires a file URL. Url specified %{public}@"
+ "%{public}sPLFileBackedLogger: Backend logging requires a file URL. Url specified is a directory %{public}@"
+ "%{public}sPLFileBackedLogger: Failed to create logger record. Invalidating logger initialization. Error: %@"
+ "%{public}sPLFileBackedLogger: Failed to open log file at %@. Error: %@"
+ "%{public}sPLFileBackedLogger: Failed while logging to archive logger: %@"
+ "%{public}sPLFileBackedLogger: Tag length shorter than expected for identifier %{public}@"
+ "%{public}sPLFileBackedLogger: Unable to create a log file directory at %@, error:%@"
+ "%{public}sPLFileBackedLogger: Unable to write-open file descriptor at %@: Error: %@"
+ "%{public}sPLFileBackedLogger: cannot rotate %@ to %@: %@"
+ "%{public}sPLFileBackedLogger: cannot rotate %@ to %@: destination exists"
+ "%{public}sPLFileBackedLogger: close url backed logger: %@"
+ "%{public}sPLFileBackedLogger: decrement logger ref count to %d for log: %{public}@"
+ "%{public}sPLFileBackedLogger: error removing legacy log file %@: %@"
+ "%{public}sPLFileBackedLogger: open url backed logger: %@"
+ "%{public}sPLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %@"
+ "%{public}sPLFileBackedLogger: url backed logger ref count %d for log %{public}@"
+ "%{public}sPLImageFormat formatWithID returning: %@"
+ "%{public}sPLXPC ->reply: %@"
+ "%{public}sPLXPC request: -[%s %s]"
+ "%{public}sPXPreferenceAlwaysShareProvenanceData is not set in domain %@. Defaulting to not sharing provenance."
+ "%{public}sPXPreferenceTransferProvenanceDataOverPTP is not set in domain %@. Defaulting to not transferring provenance over PTP."
+ "%{public}sPath %@ must be an absolute path, retuning nil for mount point"
+ "%{public}sPhoto library TCCv2 access for client unknown, TCCv1 = %d"
+ "%{public}sPhotos notifications default %{public}@ not set in domain %{public}@. Defaulting to %d"
+ "%{public}sPrefetched resources: %ld"
+ "%{public}sPrefetching resources for highlights %@"
+ "%{public}sPresenting library picker alert on behalf of %{public}@"
+ "%{public}sPresenting limited library picker (%@)"
+ "%{public}sPresenting limited library picker re-prompt"
+ "%{public}sPreventing automatic limited access alert based on info.plist configuration"
+ "%{public}sPreventing automatic limited access alert for widget extension"
+ "%{public}sProcess other than photolibraryd writing to SPL to private group container"
+ "%{public}sProxy factory object does not respond to addBarrierBlock:"
+ "%{public}sQuery participants returned error. (%@)"
+ "%{public}sReading %@ from mobileCPL.plist: %@"
+ "%{public}sReceived XPC store endpoint %p"
+ "%{public}sReceived error cancelling reserved cloud identifiers, error: %@"
+ "%{public}sReceived error getting uuids for asset object IDs, error: %@"
+ "%{public}sReceived error getting uuids for local cloud identifiers, error: %@"
+ "%{public}sReceived error optimizing thumbnail tables, error: %@"
+ "%{public}sReceived error reserving cloud identifiers, error: %@"
+ "%{public}sReceived error retrieving reserved cloud identifiers, error: %@"
+ "%{public}sReceived error running asset containment, error: %@"
+ "%{public}sReceived error udpating asset person edges, error: %@"
+ "%{public}sReceived moment share donation URL from external client"
+ "%{public}sRecording nil error"
+ "%{public}sRecording noErr code for domain \"%@\""
+ "%{public}sRefusing to change permissions of symlink %@"
+ "%{public}sRemoved SPL path from private group container"
+ "%{public}sRemoved legacy SPL bookmark data"
+ "%{public}sRemoved old SPL group plist"
+ "%{public}sRemoving SPL path from NSUserDefaults"
+ "%{public}sRepeated bind for %lu attempts"
+ "%{public}sReplacing non-directory at client-owned path %@"
+ "%{public}sReported client %{public}@ (pid: %ld) use of photos service %{public}@ (rv=%d)"
+ "%{public}sReporting client %{public}@ (pid: %ld) use of photos service %{public}@"
+ "%{public}sRequesting sandbox extension URL for Music URL, which is not supported"
+ "%{public}sReset silent migration attributes failed. (%@)"
+ "%{public}sResetting persisted system photo library path"
+ "%{public}sResolved legacy system library path to %@"
+ "%{public}sReturning default system library path (%@) as SPL"
+ "%{public}sReturning override SPL path %@"
+ "%{public}sSPL is not defined, legacy SPL path is %@"
+ "%{public}sSearched up to '/Volumes', cannot find mount point for '%@', returning nil for mount point"
+ "%{public}sSending PLCapturePhotoSettings over proxy: %@"
+ "%{public}sSending batchSaveAssetsWithJobDictionaries:completionHander: with %d jobs"
+ "%{public}sSending cancel all prewarming"
+ "%{public}sSending prewarm with PLCapturePhotoSettings: %@"
+ "%{public}sSending saveAssetWithJobDictionary:imageSurface:previewImageSurface:completionHander: with job type %{public}@ uuid %{public}@"
+ "%{public}sSending sendDaemonJob:shouldRunSerially:replyHandler: with job %@"
+ "%{public}sSetting bind result to: %@"
+ "%{public}sSetting file %{public}@ date to %@ on %@"
+ "%{public}sShared Library suggestions default not set in domain %@. Defaulting to YES"
+ "%{public}sSilent migration validator failed. (%@)"
+ "%{public}sSilent migration validator for share %@ failed. (%@)"
+ "%{public}sSimulating crash with exception code: 0x%08lx, description %@"
+ "%{public}sSkipping limited library picker, will keep current selection"
+ "%{public}sSuccessfully bound to photo library: %@, %@"
+ "%{public}sSuccessfully fetched donated moment share %@ from external client"
+ "%{public}sSuccessfully read %@ from file %@"
+ "%{public}sSuccessfully trimmed table %@ to %lu entries"
+ "%{public}sSuccessfully wrote SPL path to private group container: %@"
+ "%{public}sSwallowing proxy invocation: %@ %@"
+ "%{public}sTCCAccessRequest %{public}@"
+ "%{public}sTCCAccessRequest returned %d"
+ "%{public}sTimeout waiting for library size"
+ "%{public}sTrimming table %@ from %ld to %lu entries"
+ "%{public}sURL is NOT on the same volume as the default SPL URL"
+ "%{public}sURL is on the same volume as the default SPL URL"
+ "%{public}sUS JIT Processing failed for %{public}@ : %{public}@ : %@"
+ "%{public}sUS JIT Processing failed for asset %{public}@ : %@"
+ "%{public}sUnable to accept moment share because XPC service returned an error. (%@)"
+ "%{public}sUnable to accept share with uuid: %@. (%@)"
+ "%{public}sUnable to activate library scope because XPC service returned an error. (%@)"
+ "%{public}sUnable to activate library scope with uuid: %@. (%@)"
+ "%{public}sUnable to bind to photo library URL %@: %@"
+ "%{public}sUnable to cancel migration of collection share to CPL because XPC service returned an error. (%@)"
+ "%{public}sUnable to cancel migration of collection share with uuid: %@. (%@)"
+ "%{public}sUnable to change device library configuration to: %ld. (%@)"
+ "%{public}sUnable to change purgeability because XPC service returned an error. (%@)"
+ "%{public}sUnable to check shared library ramp (%@)"
+ "%{public}sUnable to check silent migration eligibility because XPC service returned an error. (%@)"
+ "%{public}sUnable to confirm all remaining onboarding preview assets on library scope with uuid: %@. (%@)"
+ "%{public}sUnable to construct SecRequirementRef from string %@: %ld %@"
+ "%{public}sUnable to construct SecRequirementRef: %ld"
+ "%{public}sUnable to construct string from SecRequirementRef: %ld"
+ "%{public}sUnable to create DCIM dir: %@"
+ "%{public}sUnable to create XPC connection with error: %@"
+ "%{public}sUnable to deactivate library scope because XPC service returned an error. (%@)"
+ "%{public}sUnable to deactivate library scope with uuid: %@. (%@)"
+ "%{public}sUnable to decline collection share because XPC service returned an error. (%@)"
+ "%{public}sUnable to decline collection share with uuid: %@. (%@)"
+ "%{public}sUnable to decode ASTC KTX data of length: %ld to CGImage"
+ "%{public}sUnable to decode BC7 KTX data of length: %ld to CGImage"
+ "%{public}sUnable to delete thumbnail index: %lu that is out of range of the file (capacity: %lu)"
+ "%{public}sUnable to deserialize AccessRights.plist: %@"
+ "%{public}sUnable to determine if the Library URL is in a Time Machine backup location"
+ "%{public}sUnable to determine realpath for URL %@ error: %@"
+ "%{public}sUnable to determine thumbnail manager target config suppression state, can't determine libraryKey from path manager: %@"
+ "%{public}sUnable to exit shared scope with scope identifier (%@)"
+ "%{public}sUnable to fetch moment share because XPC service returned an error. (%@)"
+ "%{public}sUnable to fetch share from share url: %@. (%@)"
+ "%{public}sUnable to force sync collection share because XPC service returned an error. (%@)"
+ "%{public}sUnable to force sync moment share because XPC service returned an error. (%@)"
+ "%{public}sUnable to force sync moment share with uuid: %@. (%@)"
+ "%{public}sUnable to get CPLConfiguration value, XPC service returned an error. (%@)"
+ "%{public}sUnable to get XPC service from assetsd %{public}@: %@, callstack:\n%@"
+ "%{public}sUnable to get XPC service from assetsd %{public}@: %@@"
+ "%{public}sUnable to get asset stableHashes because XPC service returned an error. (%@)"
+ "%{public}sUnable to get file system attributes for %@: %@"
+ "%{public}sUnable to get library scope status counts for scope identifier %@. Error: %@"
+ "%{public}sUnable to get migration progress for collection share because XPC service returned an error. (%@)"
+ "%{public}sUnable to get object ID for %s, persistent store IDs: %@"
+ "%{public}sUnable to get silent migration candidates because XPC service returned an error. (%@)"
+ "%{public}sUnable to get silent migration status because XPC service returned an error. (%@)"
+ "%{public}sUnable to get the service proxy with error: %@"
+ "%{public}sUnable to get xattr for '%@' (%s)."
+ "%{public}sUnable to mark onboarding preview assets on library scope with uuid: %@. (%@)"
+ "%{public}sUnable to mark user viewed shared library participant asset trash notification (%@)"
+ "%{public}sUnable to migrate collection share to CPL because XPC service returned an error. (%@)"
+ "%{public}sUnable to migrate collection share with uuid: %@. (%@)"
+ "%{public}sUnable to open file %@ to save extended attributes (%{public}s)."
+ "%{public}sUnable to open file '%@' %@"
+ "%{public}sUnable to open file '%@' to retrieve extended attributes (%s)."
+ "%{public}sUnable to open image source for ASTC KTX data of length: %ld"
+ "%{public}sUnable to open image source for BC7 KTX data of length: %ld"
+ "%{public}sUnable to provide main bundle sandbox extension for %@"
+ "%{public}sUnable to publish share because XPC service returned an error. (%@)"
+ "%{public}sUnable to publish share with uuid: %{public}@ (%{public}@)"
+ "%{public}sUnable to query participants because XPC service returned an error. (%@)"
+ "%{public}sUnable to read indexes in range: %{public}@ for file: %d at path: %@ with error=%s"
+ "%{public}sUnable to refresh library scope for scope identifier %@. Error: %@"
+ "%{public}sUnable to refresh shared stream album because XPC service returned an error. (%@)"
+ "%{public}sUnable to remove extended attributes on '%@': (%s)."
+ "%{public}sUnable to remove participants (%@)"
+ "%{public}sUnable to remove participants from collection share with identifier: %@. (%@)"
+ "%{public}sUnable to remove participants from library scope with identifier: %@. (%@)"
+ "%{public}sUnable to remove xattr %s for '%@' (%s)."
+ "%{public}sUnable to report client %{public}@ (pid: %ld) use of photos service %{public}@"
+ "%{public}sUnable to report invitation as spam for collection share because XPC service returned an error. (%@)"
+ "%{public}sUnable to report invitation as spam for collection share with uuid: %@. (%@)"
+ "%{public}sUnable to resend invitations for participants of collection share because XPC service returned an error. (%@)"
+ "%{public}sUnable to resend invitations for participants of collection share with uuid: %@. (%@)"
+ "%{public}sUnable to reset local only library scopes and reset asset states: %@"
+ "%{public}sUnable to reset silent migration attributes because XPC service returned an error. (%@)"
+ "%{public}sUnable to resolve Lithium SSB: %@"
+ "%{public}sUnable to run silent migration validator because XPC service returned an error. (%@)"
+ "%{public}sUnable to run silent migration validator for share because XPC service returned an error. (%@)"
+ "%{public}sUnable to set collection share allowsAnonymousPublicAccess (%@)"
+ "%{public}sUnable to set collection share allowsAnonymousPublicAccess for UUID: %@. (%@)"
+ "%{public}sUnable to set collection share expiring state (%@)"
+ "%{public}sUnable to set collection share expiring state for UUID: %@. (%@)"
+ "%{public}sUnable to set collection share viewing mode (%@)"
+ "%{public}sUnable to set collection share viewing mode for UUID: %@. (%@)"
+ "%{public}sUnable to set extended attributes on '%@': (%s)."
+ "%{public}sUnable to start accessing security scoped URL: %@"
+ "%{public}sUnable to start exit from library scope with identifier: %@. (%@)"
+ "%{public}sUnable to unarchive migration of collection share to CPL because XPC service returned an error. (%@)"
+ "%{public}sUnable to unarchive migration of collection share with uuid: %@. (%@)"
+ "%{public}sUnable to update access request (%@)"
+ "%{public}sUnable to update access request for participant in collection share with identifier: %@. (%@)"
+ "%{public}sUnable to write empty data to index: %lu"
+ "%{public}sUnable to write thumbnail data to index NSNotFound."
+ "%{public}sUnderlying proxy creating object does not respond to addBarrierBlock:"
+ "%{public}sUnexpected auth right PLTCCAuthorizationRightLimited"
+ "%{public}sUnexpected process attempting to generate the  proxy lock file path"
+ "%{public}sUnexpected savedAssetType %d, returning %tu"
+ "%{public}sUnrecognized savedAssetType %d"
+ "%{public}sUnsupported client call to performBlockOnWriterQueue:"
+ "%{public}sUnsupported client call to persistMetadata:fileURL: with path %{public}@"
+ "%{public}sUser selected: %{public}@"
+ "%{public}sUsing high priority assetsd XPC client: %@"
+ "%{public}sUsing low priority assetsd XPC client: %@"
+ "%{public}sValidation failed, missing required DesignatedRequirementData data"
+ "%{public}sXPC connection error to assetsd %@ : %@"
+ "%{public}s_isPhotosAccessAllowedWithScope:%{public}@ resolved preflight status as %d"
+ "%{public}s_saveToFilesystem: exists? %@ isDirectory? %@ sandboxCanWrite? %@ properties: %@"
+ "%{public}sallKnownLibraryURLs: unable to resolve bookmark data for pathKey %@"
+ "%{public}sassetUUIDCharString is nil"
+ "%{public}scalculateTotalSizeOfFilesAtPath:%@ %llu files took %.3f sec"
+ "%{public}scodeRequirementFromStaticCode:%p SecRequirementCopyData() fails: %ld"
+ "%{public}sdefaultSPLVolumeURL is nil"
+ "%{public}send_property already set"
+ "%{public}serror checking code signature validity: %{public}@ (%d)"
+ "%{public}serror finding volume info for proxy lock path on %@: %{public}s:"
+ "%{public}serror geting SecRequirementRef for Apple anchor string: %{public}@ (%d)"
+ "%{public}serror getting SecCodeRef for current process (%d)"
+ "%{public}serror serializing lock info: %@"
+ "%{public}serror: %d %d"
+ "%{public}sfailed to obtain name for file backed log for type: %d"
+ "%{public}sfailed to stat the filesytem for library: %s. Error (%d) %s"
+ "%{public}sfindPhotoLibraryIdentifiersMatchingSearchCriteria failed: %@"
+ "%{public}sforceSyndicationIngestUpToDate failed with error %@"
+ "%{public}sfsctl error: %s, using HARDCODED desired threshold %llu for volume_size: %llu"
+ "%{public}sfsctl error: %s, using HARDCODED low threshold %llu for volume_size: %llu"
+ "%{public}sfsctl error: %s, using HARDCODED near low threshold %llu for volume_size: %llu"
+ "%{public}sfsctl error: %s, using HARDCODED very low threshold %llu for volume_size: %llu"
+ "%{public}shasThumbnailConfigMismatch (legacy) thumbnailVersion %d vs current %d, formats: %{public}@ vs desired: %{public}@"
+ "%{public}shasThumbnailConfigMismatch (modern) thumbnailVersion %d vs current %d, formats: %{public}@ vs desired: %{public}@"
+ "%{public}signoring request to cancel inactive PLDelayedActionTimer"
+ "%{public}signoring request to start timer while timer is active 0x%p"
+ "%{public}simportSyndicationAssetsWithUUIDs failed with error %@"
+ "%{public}sisValidFileIdentifierParameters failed validation with uuid: %{public}@, utiString: %{public}@, originalFilename: %@"
+ "%{public}smunmap(2) failed. (%s)"
+ "%{public}snil path for mountPoint"
+ "%{public}snotify_register_dispatch() returned %#x for %{public}s after number %d of %d"
+ "%{public}sobject being saved as SPL path is not valid: %@"
+ "%{public}sopenApplicationOwnedFoldersWithError failed with error %@"
+ "%{public}sopenApplicationOwnedFoldersWithError succeeded"
+ "%{public}sopenPhotoLibraryDatabase failed with error %@"
+ "%{public}sopenPhotoLibraryDatabase succeeded"
+ "%{public}sopenPhotoLibraryDatabase: Photo library is already open"
+ "%{public}sother: %d %d"
+ "%{public}spath: %@"
+ "%{public}sphotolibraryd does not have expected sandbox identifier %{public}@: %{public}@"
+ "%{public}sproperty already set"
+ "%{public}sregistered xpc activity and pushed to run state for identifier: %s"
+ "%{public}sregistered xpc activity check in for identifier: %s"
+ "%{public}ssaveImageJobToDisk [job objectForKey:kPLImageWriterDestinationAssetUUID] %@"
+ "%{public}ssaveImageJobToDisk extension %@"
+ "%{public}ssaveImageJobToDisk incomingDirectoryPath %@"
+ "%{public}ssaveImageJobToDisk incomingDirectoryPath_homeDirectory %@"
+ "%{public}ssaveImageJobToDisk photoFilePath %@"
+ "%{public}ssaveImageJobToDisk photoFileURL %@"
+ "%{public}sstart_property missing"
+ "%{public}sunable to stat volume %@: %s"
+ "%{public}sunexpected issue getting xttr length for %s %s: %s"
+ "%{public}suuid_parse failed for assetUUIDCharString: %s"
+ "%{public}svolumeURL is nil"
+ "%{public}s{"
+ "%{public}s}"
+ "-[PLAssetsdPhotoKitClient importSyndicationAssetsWithUUIDs:importSource:options:sourceLibraryURL:completionHandler:]_block_invoke"
+ "PLPhotosErrorGraphNextExternalIdentifierUnavailable"
+ "PLXPC Client: importSyndicationAssetsWithUUIDs:importSource:options:sourceLibraryURL:completionHandler:"
+ "SearchBackendFindExpander"
+ "SharedCollectionsSearch"
+ "[%@] "
+ "v32@?0@\"NSDictionary\"8@\"NSDictionary\"16@\"NSError\"24"
- "  %@"
- "  %{public}@ = %{public}@"
- "  [...and %d more]"
- "  [job-%d] type %{public}@ uuid %{public}@"
- "#### Format %@ : %d x %d, crop %d"
- "#### fastFormatCount %lu"
- "#### fastTableFormats %@"
- "#### fastThumbPersistenceManagers %@"
- "##### %@ %@"
- "%@ for '%@' (%s)."
- "%@ for '%@' (%s): %@."
- "%@ has no bundle identifier. Will fallback on process ID"
- "%ld bytes written to %@"
- "%s Failed to open PHPhotoLibrary for the SPL, sending empty dictionary to handler: %@"
- "%s: failed to create context"
- "%s: failed to create directory: %@ with error: %@"
- "%{public}@ %@ hasExtension:%{public}@"
- "%{public}@ Removing power assertion: -🔌"
- "%{public}@ could not be created, error: %{public}s"
- "%{public}@ could not be created, error: %{public}s, dir creation %{public}@"
- "%{public}@ could not be removed, error: %{public}s"
- "%{public}@ taking power assertion: +🔌"
- "%{public}@, backtrace:\n%@"
- "%{public}@: Setting QoS of state node %{public}@ to %{public}@"
- "%{public}@: Unable to enqueue operation: %@"
- "%{public}s failed after exceeding maximum parent directory attempts on %@ [at path %@]"
- "%{public}s failed to remove %@ [%{public}@]"
- "%{public}s is only available in photolibraryd"
- "%{public}s: Could not read mobileCPL.plist at path %@: File doesn't exist"
- "%{public}s: Error reading mobileCPL.plist at path %@: %@"
- "%{public}s: failed to create directory: %@ with error: %@"
- "%{public}s: failed to get SecTask from %{public}@"
- "%{public}s: failed to get identifier from %{public}@"
- "%{public}s: missing required connection"
- "*** ImageTable expand: F_PREALLOCATE of %d %@ to %lld returned -1: error=%s"
- "*** ImageTable: ftruncate of %d %@ to %lld returned -1: error=%s"
- "--- BEGIN File diagnostics for %{public}@ ---"
- "--- END File diagnostics for %{public}@ ---"
- "-[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:createIfNeeded:]"
- "-[PLPhotoLibraryPathManagerUBF _externalDirectoryWithBundleIdentifier:createIfNeeded:]"
- "ABORT: %{public}s"
- "Added owner read and write permission to %@ (was %o)"
- "Adjustments data file does not contain a data blob"
- "Adjustments property list contains an empty data blob"
- "Adjustments property list does not contain a data blob"
- "AppPrivateData invalid bundle root. Error: %@"
- "Application state is not ready for limited library picker re-prompt"
- "Ask for help in #help-photos-disclosed"
- "Bogus object ID from data: %{public}@"
- "Bogus object ID in xpc data."
- "Bogus value type in xpc, data %p = %p"
- "Bogus value type in xpc, dictionary %p = %p"
- "Bogus value type in xpc, error dictionary %p = %p"
- "Bookmarked SPL changed: Updating SPL in defaults to %@"
- "CS_OPS_VALIDATION_CATEGORY failed for pid %d: %s"
- "Call stack that enabled multi-library mode:"
- "Calling XPC getLibrarySizesFromDB:%@ at QoS %@"
- "Calling addBarrierBlock: when NSXPCConnection has not been created"
- "Can't decypher process name"
- "Can't get process name for %@: %s"
- "Cannot trim read-only table %@"
- "Cleared IMMUTABLE flag from %@"
- "Client connection interrupted for URL %@, resetting bind state (previous result: %@)"
- "Client failed to access the proxy lock file path. Error: %@"
- "Connection to assetsd was interrupted (shutting down)"
- "Connection to assetsd was interrupted - photolibraryd exited, died, or closed the photo library"
- "Connection to assetsd was invalidated - connection cannot be formed, or remote endpoint/listener was invalidated. Setting connection object to nil."
- "Connection to assetsd was invalidated from client side. Setting connection object to nil."
- "Constructed legacy SPL URL based on unresolvable bookmark: %@"
- "Constructed legacy SPL URL from unresolvable bookmark: %@"
- "Content privacy default not set in domain %@. Defaulting to YES"
- "Contextual video thumbnail identifier is not usable as part of a filename"
- "CoreAnalytics published event: %{public}@ payload: %{public}@"
- "CoreAnalyticsEventManager: invalid parameter for event name: %{public}@"
- "CoreAnalyticsEventManager: invalid parameter for event name: %{public}@ key: %{public}@"
- "CoreAnalyticsEventManager: invalid parameter for event name: %{public}@ key: %{public}@ value: %{public}@"
- "CoreAnalyticsEventManager: invalid parameter for event name: %{public}@ payload: %{public}@"
- "CoreAnalyticsEventManager: invalid value for event name: %{public}@ key: %{public}@"
- "CoreAnalyticsEventManager: publish to Core Analytics is disabled for event: %{public}@"
- "Could not create PLPositionalImageTable at path %@: %s (%d)"
- "Could not open PLPositionalImageTable at path %@: %s (%d)"
- "Could not set file creation date on %@, error: %@"
- "Creating an autobinding proxy factory from a nil proxy factor for library URL: %@"
- "Creating an image format with an unknown type is an error"
- "Creating blackhole proxy for %@ from proxy factory %@ for library URL: %@"
- "Data was corrupt; forcing +[NSKeyedUnarchiver unarchivedObjectOfClass:fromData:error:] to return nil, error: %@"
- "Data was corrupt; forcing +[NSKeyedUnarchiver unarchivedObjectOfClasses:fromData:error:] to return nil, error: %@"
- "Data was corrupt; forcing -[NSKeyedUnarchiver initForReadingFromData:error:] to return nil, error: %@"
- "Default for excluding location when sharing is not set in domain %@. Defaulting to NO"
- "Detected thumbnail configuration change: from formats: %{public}@ to formats: %{public}@, tableChangesOnly: %d, migrationToCompressedTablesOnly: %d, fullRebuild: %d"
- "Disabling libnotify calls due to shutdown"
- "ERROR: PLArrayFromXPCDictionary failed to deserialize array"
- "ERROR: PLArrayFromXPCDictionary failed to deserialize array (root object not an array: %@)"
- "ERROR: PLDictionaryFromXPCDictionary failed to deserialize dictionary"
- "ERROR: PLDictionaryFromXPCDictionary failed to deserialize dictionary (root object not a dictionary: %@)"
- "Encountered exception attempting to determine application state for limited library picker reprompt: %{public}@"
- "Error %d occurred while trying to call notify_post for: %s. (attempt number: %d of %d)"
- "Error %d occurred while trying to connect notify handler for %s. (attempt number: %d of %d)"
- "Error %{public}@ mobileCPL.plist, path is nil, pathManager: %@, error: %@"
- "Error creating bookmark data for URL %@ : %@"
- "Error creating code requirements from data: %ld"
- "Error determining capabilities for %@: %@"
- "Error fetching donated moment share from external client: %@"
- "Error getting assetsd remote object proxy (%@)"
- "Error getting filesystem size for libraryURL %@"
- "Error getting master thumbnail %@ for %s: %@"
- "Error getting photo library identifier for url %@: %@"
- "Error getting photo library identifier: %@"
- "Error getting photos XPC endpoint: %@"
- "Error getting projectExtensionDataForProjectUuid = %@: %@"
- "Error getting remote object proxy (%@)"
- "Error getting remote object proxy for %s: %@"
- "Error getting remote object proxy for %{public}s: %@"
- "Error getting remote object proxy to open photo library with URL %s: %@ %@"
- "Error getting resource values for %@: %@"
- "Error getting resource values for default SPL URL %@: %@"
- "Error getting size of resources to upload by CPL, error: %@"
- "Error getting the real path for the provided url path: %@: %@."
- "Error in reply for %s: %@"
- "Error prefetching resources: %s %@"
- "Error reading property list from %@"
- "Error received from proxy factory %{public}@ in %{public}@: %@"
- "Error removing old SPL group plist: %@"
- "Error saving mobileCPL.plist: %@ at path %@: %@"
- "Error setting client privacy options (%@)"
- "Error setting photos XPC endpoint: %@"
- "Error synchronously rebuilding moments and delete existing ones before: %d, error: %@"
- "Error trying to remove mobileCPL.plist at path %@: %@"
- "Error trying to serialize data: %@ to write to mobileCPL.plist at path %@: %@"
- "Error waiting for search index existence: %@"
- "Error: API misuse. Operating in multi library mode but calling single library mode API."
- "Error: API misuse. Operating in single library mode for %@ but a different library was requested: %@"
- "Expected the home directory path to have fewer components than the provided url"
- "Failed bind after %lu attempts"
- "Failed to %@ %@ to %@: %@"
- "Failed to %{public}@ photos picker client log from %{public}@: %@"
- "Failed to access photos picker client log for client with invalid bundle identifier: %{public}@"
- "Failed to add owner read and write permission to %@ (%{public}s)."
- "Failed to archive errorData, error: %@"
- "Failed to bind to photo library %@, %@"
- "Failed to calloc buffer for PLPositionalImageTableNSDataReleaseInfo."
- "Failed to clear IMMUTABLE flag on %@ (%{public}s)."
- "Failed to clear backup backup exclusion marker [include], path: %@, error: %@"
- "Failed to clear backup exclusion marker [iCloud-iCPL-enabled], path: %@, error: %@"
- "Failed to clear backup exclusion marker [iCloud], path: %@, error: %@"
- "Failed to clear backup exclusion marker [include], path: %@, error: %@"
- "Failed to close database: %s (%d)."
- "Failed to create SecCodeRef for token: %ld."
- "Failed to create photos picker client log for client with empty bundle identifier: %{public}@"
- "Failed to create power assertion for migration. Result code: %d"
- "Failed to determine if internal originals subdirectory location resource is a directory at url: %@ Error: %@"
- "Failed to enable WAL - %d %s"
- "Failed to enumerate url %@ for relocated originals discovery. Error: %@"
- "Failed to execute \"%@\": %s (%d)"
- "Failed to issue advisory read for file: %d at path: %@ with error=%s"
- "Failed to issue set read ahead for file: %d at path: %@ with error=%s"
- "Failed to message privacy support client to reprompt alert"
- "Failed to open DB - %d"
- "Failed to open the stream"
- "Failed to persist to \"%@\": %@"
- "Failed to prepare \"%@\": %s (%d)"
- "Failed to present library picker alert on behalf of '%{public}@'"
- "Failed to produced availability snapshot, error: %@"
- "Failed to produced processing snapshot, error: %@"
- "Failed to register limited library picker"
- "Failed to release power assertion for migration. Result code: %d"
- "Failed to remove replacement directory after cross-device replace %@: %@"
- "Failed to remove source file after cross-device replace %@: %@"
- "Failed to resolve real path for %@ (%{public}s)."
- "Failed to serialize adjustments property list: %@"
- "Failed to serialize backingDictionary. Error: %@"
- "Failed to set backup exclusion marker [all-DCIM], path: %@, error: %@"
- "Failed to set backup exclusion marker [all], path: %@, error: %@"
- "Failed to set backup exclusion marker [iCloud-DCIM], path: %@, error: %@"
- "Failed to set backup exclusion marker [iCloud-iCPL-enabled], path: %@, error: %@"
- "Failed to set backup exclusion marker [iCloud], path: %@, error: %@"
- "Failed to set backup exclusion marker [time-machine], path: %@, error: %@"
- "Failed to set lock_proxy_file (statement parse error) for path: %@"
- "Failed to set lock_proxy_file - %d %s"
- "Failed to set the backup exclusion marker for the library bundle. Error: %@"
- "Failed to stat %@ (%{public}s)."
- "Failed to stat thumbnail table with error=%s"
- "Failed to step statement: %s (%d)"
- "Failed to trim table %@ to %lld bytes: %s"
- "Failed to unarchive NSError, error: %@"
- "Failed to write SPL path to private group container"
- "Failed to write property list to %@. Error: %@"
- "Failed validity check on code requirements from data: %@"
- "Featured content allowed default not set in domain %@. Defaulting to YES"
- "Fetched adjustments data from file"
- "File radar with sysdiagnose to component: Photos Backend Storage | all"
- "FileIdentifier - filenameUUID is nil for url: %@"
- "Finished table thumb rebuild with status: %@, for %s"
- "Footer data invalid at index: %lu (imageHeight: %d, imageWidth: %d), format side len: %d"
- "Found SPL path in group plist in container prefs location"
- "Get parent sync root failed for %{public}@ error %d %{public}s"
- "Get sync root flag failed for %{public}@ error %d %{public}s"
- "Got a bind failure for URL %@, resetting bind state: %@ (previous result: %@)"
- "Got a nil proxy from proxy factory %@ for library URL: %@"
- "Imported Lithium SSB for %@"
- "Ingest failed for %{public}@ : %{public}@ : %@"
- "Ingesting %@ to %@ with ingestion type %@ option %lu"
- "Invalid format mode for ThumbFile (%@)"
- "Invalid subtype for internal location"
- "Invalid thumbnail identifier for file identifier: %@"
- "Invalid thumbnail identifier scheme: %@"
- "Legacy system library bookmark data is present but not resolvable: %@"
- "Legacy system photo library URL exists but it is not resolvable. Returning bogus URL: %@"
- "Legacy system photo library bookmark is present"
- "Library URL was found to contain \".backup\""
- "Library URL was found to contain \"Backups.backupdb\""
- "Library URL was found to have a HFS TimeMachine location"
- "Library URL was found to have the prefix \"/Volumes/.timemachine\""
- "Log archive recreated on %@"
- "Logging client %{public}@ (pid: %ld) access to photos (%{public}@)"
- "Logging client %{public}@ (pid: %ld) access to photos via picker"
- "Lowering QoS for getLibrarySizes from %@ to UT"
- "MT library sizing done (%lu bytes)"
- "MT library sizing starting"
- "Main bundle path is nil"
- "Missing NSPhotoLibraryAddUsageDescription, will try photos access instead of add-only"
- "Missing path to get free space"
- "Missing thumbnail table for format %d"
- "Mount point for %@: %@"
- "Negative interval: %f"
- "Nil designated requirement data"
- "No %{public}@ sandbox extension for path %@ for client pid %{public}ld (%{public}@)"
- "No NSURLPathKey available from unresolvable bookmark"
- "No PLPositionalImageTable file found at path %@"
- "No SPL stored, and SPL from standard defaults was %@"
- "No SSB on file for %@"
- "No realpath for SPL URL %@, %@"
- "No realpath for URL %@, %@"
- "No trimming needed for table %@ (requested %lu, current %ld)"
- "Not a valid system library URL because it not a supported filesystem %@: %@"
- "Object is nil, deleting key %@ from mobileCPL.plist"
- "PFFigCreateCGImageFromImageData %s returned %ld from %@"
- "PLCreateDirectoryIfNeededAndGetSandboxExtensionToken: failed to create directory=%@ error=%@"
- "PLFileBackedLogger: Backend logging failed to determine the url status for %{public}@. Error: %@"
- "PLFileBackedLogger: Backend logging failed to removed corrupt log file %{public}@. Error: %@"
- "PLFileBackedLogger: Backend logging requires a file URL with an expected path extension %{public}@"
- "PLFileBackedLogger: Backend logging requires a file URL. Url specified %{public}@"
- "PLFileBackedLogger: Backend logging requires a file URL. Url specified is a directory %{public}@"
- "PLFileBackedLogger: Failed to create logger record. Invalidating logger initialization. Error: %@"
- "PLFileBackedLogger: Failed to open log file at %@. Error: %@"
- "PLFileBackedLogger: Failed while logging to archive logger: %@"
- "PLFileBackedLogger: Tag length shorter than expected for identifier %{public}@"
- "PLFileBackedLogger: Unable to create a log file directory at %@, error:%@"
- "PLFileBackedLogger: Unable to write-open file descriptor at %@: Error: %@"
- "PLFileBackedLogger: cannot rotate %@ to %@: %@"
- "PLFileBackedLogger: cannot rotate %@ to %@: destination exists"
- "PLFileBackedLogger: close url backed logger: %@"
- "PLFileBackedLogger: decrement logger ref count to %d for log: %{public}@"
- "PLFileBackedLogger: error removing legacy log file %@: %@"
- "PLFileBackedLogger: open url backed logger: %@"
- "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %@"
- "PLFileBackedLogger: url backed logger ref count %d for log %{public}@"
- "PLImageFormat formatWithID returning: %@"
- "PLXPC ->reply: %@"
- "PLXPC request: -[%s %s]"
- "PXPreferenceAlwaysShareProvenanceData is not set in domain %@. Defaulting to not sharing provenance."
- "PXPreferenceTransferProvenanceDataOverPTP is not set in domain %@. Defaulting to not transferring provenance over PTP."
- "Path %@ must be an absolute path, retuning nil for mount point"
- "Photo library TCCv2 access for client unknown, TCCv1 = %d"
- "Photos notifications default %{public}@ not set in domain %{public}@. Defaulting to %d"
- "Prefetched resources: %ld"
- "Prefetching resources for highlights %@"
- "Presenting library picker alert on behalf of %{public}@"
- "Presenting limited library picker (%@)"
- "Presenting limited library picker re-prompt"
- "Preventing automatic limited access alert based on info.plist configuration"
- "Preventing automatic limited access alert for widget extension"
- "Process other than photolibraryd writing to SPL to private group container"
- "Proxy factory object does not respond to addBarrierBlock:"
- "Query participants returned error. (%@)"
- "Reading %@ from mobileCPL.plist: %@"
- "Received XPC store endpoint %p"
- "Received error cancelling reserved cloud identifiers, error: %@"
- "Received error getting uuids for asset object IDs, error: %@"
- "Received error getting uuids for local cloud identifiers, error: %@"
- "Received error optimizing thumbnail tables, error: %@"
- "Received error reserving cloud identifiers, error: %@"
- "Received error retrieving reserved cloud identifiers, error: %@"
- "Received error running asset containment, error: %@"
- "Received error udpating asset person edges, error: %@"
- "Received moment share donation URL from external client"
- "Recording nil error"
- "Recording noErr code for domain \"%@\""
- "Refusing to change permissions of symlink %@"
- "Removed SPL path from private group container"
- "Removed legacy SPL bookmark data"
- "Removed old SPL group plist"
- "Removing SPL path from NSUserDefaults"
- "Repeated bind for %lu attempts"
- "Reported client %{public}@ (pid: %ld) use of photos service %{public}@ (rv=%d)"
- "Reporting client %{public}@ (pid: %ld) use of photos service %{public}@"
- "Requesting sandbox extension URL for Music URL, which is not supported"
- "Reset silent migration attributes failed. (%@)"
- "Resetting persisted system photo library path"
- "Resolved legacy system library path to %@"
- "Returning default system library path (%@) as SPL"
- "Returning override SPL path %@"
- "SPL is not defined, legacy SPL path is %@"
- "Searched up to '/Volumes', cannot find mount point for '%@', returning nil for mount point"
- "Sending PLCapturePhotoSettings over proxy: %@"
- "Sending batchSaveAssetsWithJobDictionaries:completionHander: with %d jobs"
- "Sending cancel all prewarming"
- "Sending prewarm with PLCapturePhotoSettings: %@"
- "Sending saveAssetWithJobDictionary:imageSurface:previewImageSurface:completionHander: with job type %{public}@ uuid %{public}@"
- "Sending sendDaemonJob:shouldRunSerially:replyHandler: with job %@"
- "Setting bind result to: %@"
- "Setting file %{public}@ date to %@ on %@"
- "Shared Library suggestions default not set in domain %@. Defaulting to YES"
- "Silent migration validator failed. (%@)"
- "Silent migration validator for share %@ failed. (%@)"
- "Simulating crash with exception code: 0x%08lx, description %@"
- "Skipping limited library picker, will keep current selection"
- "Successfully bound to photo library: %@, %@"
- "Successfully fetched donated moment share %@ from external client"
- "Successfully read %@ from file %@"
- "Successfully trimmed table %@ to %lu entries"
- "Successfully wrote SPL path to private group container: %@"
- "Swallowing proxy invocation: %@ %@"
- "TCCAccessRequest %{public}@"
- "TCCAccessRequest returned %d"
- "Timeout waiting for library size"
- "Trimming table %@ from %ld to %lu entries"
- "URL is NOT on the same volume as the default SPL URL"
- "URL is on the same volume as the default SPL URL"
- "US JIT Processing failed for %{public}@ : %{public}@ : %@"
- "US JIT Processing failed for asset %{public}@ : %@"
- "Unable to accept moment share because XPC service returned an error. (%@)"
- "Unable to accept share with uuid: %@. (%@)"
- "Unable to activate library scope because XPC service returned an error. (%@)"
- "Unable to activate library scope with uuid: %@. (%@)"
- "Unable to bind to photo library URL %@: %@"
- "Unable to cancel migration of collection share to CPL because XPC service returned an error. (%@)"
- "Unable to cancel migration of collection share with uuid: %@. (%@)"
- "Unable to change device library configuration to: %ld. (%@)"
- "Unable to change purgeability because XPC service returned an error. (%@)"
- "Unable to check shared library ramp (%@)"
- "Unable to check silent migration eligibility because XPC service returned an error. (%@)"
- "Unable to confirm all remaining onboarding preview assets on library scope with uuid: %@. (%@)"
- "Unable to construct SecRequirementRef from string %@: %ld %@"
- "Unable to construct SecRequirementRef: %ld"
- "Unable to construct string from SecRequirementRef: %ld"
- "Unable to create DCIM dir: %@"
- "Unable to create XPC connection with error: %@"
- "Unable to deactivate library scope because XPC service returned an error. (%@)"
- "Unable to deactivate library scope with uuid: %@. (%@)"
- "Unable to decline collection share because XPC service returned an error. (%@)"
- "Unable to decline collection share with uuid: %@. (%@)"
- "Unable to decode ASTC KTX data of length: %ld to CGImage"
- "Unable to decode BC7 KTX data of length: %ld to CGImage"
- "Unable to delete thumbnail index: %lu that is out of range of the file (capacity: %lu)"
- "Unable to deserialize AccessRights.plist: %@"
- "Unable to determine if the Library URL is in a Time Machine backup location"
- "Unable to determine realpath for URL %@ error: %@"
- "Unable to determine thumbnail manager target config suppression state, can't determine libraryKey from path manager: %@"
- "Unable to exit shared scope with scope identifier (%@)"
- "Unable to fetch moment share because XPC service returned an error. (%@)"
- "Unable to fetch share from share url: %@. (%@)"
- "Unable to force sync collection share because XPC service returned an error. (%@)"
- "Unable to force sync moment share because XPC service returned an error. (%@)"
- "Unable to force sync moment share with uuid: %@. (%@)"
- "Unable to get CPLConfiguration value, XPC service returned an error. (%@)"
- "Unable to get XPC service from assetsd %{public}@: %@, callstack:\n%@"
- "Unable to get XPC service from assetsd %{public}@: %@@"
- "Unable to get asset stableHashes because XPC service returned an error. (%@)"
- "Unable to get file system attributes for %@: %@"
- "Unable to get library scope status counts for scope identifier %@. Error: %@"
- "Unable to get migration progress for collection share because XPC service returned an error. (%@)"
- "Unable to get object ID for %s, persistent store IDs: %@"
- "Unable to get silent migration candidates because XPC service returned an error. (%@)"
- "Unable to get silent migration status because XPC service returned an error. (%@)"
- "Unable to get the service proxy with error: %@"
- "Unable to get xattr for '%@' (%s)."
- "Unable to mark onboarding preview assets on library scope with uuid: %@. (%@)"
- "Unable to mark user viewed shared library participant asset trash notification (%@)"
- "Unable to migrate collection share to CPL because XPC service returned an error. (%@)"
- "Unable to migrate collection share with uuid: %@. (%@)"
- "Unable to open file %@ to save extended attributes (%{public}s)."
- "Unable to open file '%@' %@"
- "Unable to open file '%@' to retrieve extended attributes (%s)."
- "Unable to open image source for ASTC KTX data of length: %ld"
- "Unable to open image source for BC7 KTX data of length: %ld"
- "Unable to provide main bundle sandbox extension for %@"
- "Unable to publish share because XPC service returned an error. (%@)"
- "Unable to publish share with uuid: %{public}@ (%{public}@)"
- "Unable to query participants because XPC service returned an error. (%@)"
- "Unable to read indexes in range: %{public}@ for file: %d at path: %@ with error=%s"
- "Unable to refresh library scope for scope identifier %@. Error: %@"
- "Unable to refresh shared stream album because XPC service returned an error. (%@)"
- "Unable to remove extended attributes on '%@': (%s)."
- "Unable to remove participants (%@)"
- "Unable to remove participants from collection share with identifier: %@. (%@)"
- "Unable to remove participants from library scope with identifier: %@. (%@)"
- "Unable to remove xattr %s for '%@' (%s)."
- "Unable to report client %{public}@ (pid: %ld) use of photos service %{public}@"
- "Unable to report invitation as spam for collection share because XPC service returned an error. (%@)"
- "Unable to report invitation as spam for collection share with uuid: %@. (%@)"
- "Unable to resend invitations for participants of collection share because XPC service returned an error. (%@)"
- "Unable to resend invitations for participants of collection share with uuid: %@. (%@)"
- "Unable to reset local only library scopes and reset asset states: %@"
- "Unable to reset silent migration attributes because XPC service returned an error. (%@)"
- "Unable to resolve Lithium SSB: %@"
- "Unable to run silent migration validator because XPC service returned an error. (%@)"
- "Unable to run silent migration validator for share because XPC service returned an error. (%@)"
- "Unable to set collection share allowsAnonymousPublicAccess (%@)"
- "Unable to set collection share allowsAnonymousPublicAccess for UUID: %@. (%@)"
- "Unable to set collection share expiring state (%@)"
- "Unable to set collection share expiring state for UUID: %@. (%@)"
- "Unable to set collection share viewing mode (%@)"
- "Unable to set collection share viewing mode for UUID: %@. (%@)"
- "Unable to set extended attributes on '%@': (%s)."
- "Unable to start accessing security scoped URL: %@"
- "Unable to start exit from library scope with identifier: %@. (%@)"
- "Unable to unarchive migration of collection share to CPL because XPC service returned an error. (%@)"
- "Unable to unarchive migration of collection share with uuid: %@. (%@)"
- "Unable to update access request (%@)"
- "Unable to update access request for participant in collection share with identifier: %@. (%@)"
- "Unable to write empty data to index: %lu"
- "Unable to write thumbnail data to index NSNotFound."
- "Underlying proxy creating object does not respond to addBarrierBlock:"
- "Unexpected auth right PLTCCAuthorizationRightLimited"
- "Unexpected process attempting to generate the  proxy lock file path"
- "Unexpected savedAssetType %d, returning %tu"
- "Unsupported client call to performBlockOnWriterQueue:"
- "Unsupported client call to persistMetadata:fileURL: with path %{public}@"
- "User selected: %{public}@"
- "Using high priority assetsd XPC client: %@"
- "Using low priority assetsd XPC client: %@"
- "Validation failed, missing required DesignatedRequirementData data"
- "XPC connection error to assetsd %@ : %@"
- "_isPhotosAccessAllowedWithScope:%{public}@ resolved preflight status as %d"
- "_saveToFilesystem: exists? %@ isDirectory? %@ sandboxCanWrite? %@ properties: %@"
- "allKnownLibraryURLs: unable to resolve bookmark data for pathKey %@"
- "assetUUIDCharString is nil"
- "calculateTotalSizeOfFilesAtPath:%@ %llu files took %.3f sec"
- "codeRequirementFromStaticCode:%p SecRequirementCopyData() fails: %ld"
- "defaultSPLVolumeURL is nil"
- "end_property already set"
- "error checking code signature validity: %{public}@ (%d)"
- "error finding volume info for proxy lock path on %@: %{public}s:"
- "error geting SecRequirementRef for Apple anchor string: %{public}@ (%d)"
- "error getting SecCodeRef for current process (%d)"
- "error serializing lock info: %@"
- "error: %d %d"
- "failed to obtain name for file backed log for type: %d"
- "failed to stat the filesytem for library: %s. Error (%d) %s"
- "findPhotoLibraryIdentifiersMatchingSearchCriteria failed: %@"
- "forceSyndicationIngestUpToDate failed with error %@"
- "fsctl error: %s, using HARDCODED desired threshold %llu for volume_size: %llu"
- "fsctl error: %s, using HARDCODED low threshold %llu for volume_size: %llu"
- "fsctl error: %s, using HARDCODED near low threshold %llu for volume_size: %llu"
- "fsctl error: %s, using HARDCODED very low threshold %llu for volume_size: %llu"
- "hasThumbnailConfigMismatch (legacy) thumbnailVersion %d vs current %d, formats: %{public}@ vs desired: %{public}@"
- "hasThumbnailConfigMismatch (modern) thumbnailVersion %d vs current %d, formats: %{public}@ vs desired: %{public}@"
- "ignoring request to cancel inactive PLDelayedActionTimer"
- "ignoring request to start timer while timer is active 0x%p"
- "isValidFileIdentifierParameters failed validation with uuid: %{public}@, utiString: %{public}@, originalFilename: %@"
- "nil path for mountPoint"
- "notify_register_dispatch() returned %#x for %{public}s after number %d of %d"
- "object being saved as SPL path is not valid: %@"
- "openApplicationOwnedFoldersWithError failed with error %@"
- "openApplicationOwnedFoldersWithError succeeded"
- "openPhotoLibraryDatabase failed with error %@"
- "openPhotoLibraryDatabase succeeded"
- "openPhotoLibraryDatabase: Photo library is already open"
- "other: %d %d"
- "path: %@"
- "photolibraryd does not have expected sandbox identifier %{public}@: %{public}@"
- "property already set"
- "registered xpc activity and pushed to run state for identifier: %s"
- "registered xpc activity check in for identifier: %s"
- "saveImageJobToDisk [job objectForKey:kPLImageWriterDestinationAssetUUID] %@"
- "saveImageJobToDisk extension %@"
- "saveImageJobToDisk incomingDirectoryPath %@"
- "saveImageJobToDisk incomingDirectoryPath_homeDirectory %@"
- "saveImageJobToDisk photoFilePath %@"
- "saveImageJobToDisk photoFileURL %@"
- "start_property missing"
- "unable to stat volume %@: %s"
- "unexpected issue getting xttr length for %s %s: %s"
- "uuid_parse failed for assetUUIDCharString: %s"
- "volumeURL is nil"
- "{"
```
