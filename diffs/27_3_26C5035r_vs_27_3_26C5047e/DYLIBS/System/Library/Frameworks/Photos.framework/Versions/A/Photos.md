## Photos

> `/System/Library/Frameworks/Photos.framework/Versions/A/Photos`

```diff

-920.8.100.0.0
-  __TEXT.__text: 0x310bcc
-  __TEXT.__objc_methlist: 0x26774
-  __TEXT.__const: 0x1b08
+920.12.210.0.0
+  __TEXT.__text: 0x32504c
+  __TEXT.__objc_methlist: 0x2682c
+  __TEXT.__const: 0x1d58
   __TEXT.__dlopen_cstrs: 0x280
-  __TEXT.__constg_swiftt: 0x524
-  __TEXT.__swift5_typeref: 0x810
+  __TEXT.__constg_swiftt: 0x5b0
+  __TEXT.__swift5_typeref: 0x92c
   __TEXT.__swift5_builtin: 0x64
-  __TEXT.__swift5_reflstr: 0x370
-  __TEXT.__swift5_fieldmd: 0x304
+  __TEXT.__swift5_reflstr: 0x480
+  __TEXT.__swift5_fieldmd: 0x3e4
   __TEXT.__swift5_assocty: 0x108
-  __TEXT.__swift5_proto: 0x50
+  __TEXT.__swift5_proto: 0x58
   __TEXT.__swift5_types: 0x50
-  __TEXT.__swift5_capture: 0x2a0
-  __TEXT.__cstring: 0x33a68
-  __TEXT.__swift_as_entry: 0x2c
-  __TEXT.__swift_as_ret: 0x2c
-  __TEXT.__swift_as_cont: 0x28
+  __TEXT.__swift5_capture: 0x9f0
+  __TEXT.__cstring: 0x33ceb
+  __TEXT.__swift_as_entry: 0x60
+  __TEXT.__swift_as_ret: 0x68
+  __TEXT.__swift_as_cont: 0x9c
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__oslogstring: 0x27cb7
+  __TEXT.__oslogstring: 0x287a0
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x99d4
+  __TEXT.__gcc_except_tab: 0x99e4
   __TEXT.__ustring: 0x1e
-  __TEXT.__unwind_info: 0xbc38
-  __TEXT.__eh_frame: 0x880
+  __TEXT.__unwind_info: 0xbf48
+  __TEXT.__eh_frame: 0x10b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x32b8
+  __DATA_CONST.__const: 0x32b0
   __DATA_CONST.__objc_classlist: 0xf30
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x2e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x14440
+  __DATA_CONST.__objc_selrefs: 0x144b8
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0xc60
-  __DATA_CONST.__objc_arraydata: 0x898
-  __DATA_CONST.__got: 0x29d0
-  __AUTH_CONST.__const: 0xbdc0
-  __AUTH_CONST.__cfstring: 0x2d400
-  __AUTH_CONST.__objc_const: 0x41748
+  __DATA_CONST.__objc_arraydata: 0x8e0
+  __DATA_CONST.__got: 0x2a58
+  __AUTH_CONST.__const: 0xcf20
+  __AUTH_CONST.__cfstring: 0x2d540
+  __AUTH_CONST.__objc_const: 0x41868
   __AUTH_CONST.__objc_intobj: 0x2508
-  __AUTH_CONST.__objc_arrayobj: 0x810
+  __AUTH_CONST.__objc_arrayobj: 0x840
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_doubleobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x19d8
+  __AUTH_CONST.__auth_got: 0x1b40
   __AUTH.__objc_data: 0x5538
   __AUTH.__data: 0x3e0
-  __DATA.__objc_ivar: 0x3530
-  __DATA.__data: 0x2a8c
+  __DATA.__objc_ivar: 0x3548
+  __DATA.__data: 0x2b5c
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x17e8
+  __DATA.__bss: 0x18d8
   __DATA.__common: 0x49
   __DATA_DIRTY.__objc_data: 0x4300
   __DATA_DIRTY.__data: 0x98

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 15224
-  Symbols:   33904
-  CStrings:  8928
+  Functions: 15650
+  Symbols:   34087
+  CStrings:  8985
 
Symbols:
+ +[PHAsset descriptionByJoiningMediaSubtypeComponents:]
+ +[PHAsset descriptionComponentsForMediaSubtypes:]
+ +[PHAssetMediaAnalysisProperties currentAnalysisMajorVersion]
+ +[PHCloudFeedEntry fetchUnreadNotificationEntriesWithLastSeenDate:eventLogDate:options:]
+ +[PHFindPersonGrounder _peopleHomeOrderedUUIDs]
+ +[PHFindPersonGrounder _resultForMatches:]
+ +[PHFindPersonGrounder allCandidatesWithOptions:error:]
+ +[PHFindQueryExecutor _appendSharedCollectionAssetExclusionToTokens:context:]
+ +[PHQuery queryForUnreadNotificationEntriesWithLastSeenDate:eventLogDate:options:]
+ -[PHAsset hasEditableLivePhotoVideo]
+ -[PHAssetChangeRequest setTimeZone:]
+ -[PHAssetChangeRequest timeZone]
+ -[PHAssetExtendedMetadata timeZone]
+ -[PHAssetExtendedMetadataProperties timeZone]
+ -[PHFindQueryContext leoItemTypesForFindOptions:]
+ -[PHFindQueryOptions includeSharedCollectionAssets]
+ -[PHFindQueryOptions setIncludeSharedCollectionAssets:]
+ -[PHSearchQueryOptions includeSharedCollectionAssets]
+ -[PHSearchQueryOptions setIncludeSharedCollectionAssets:]
+ GCC_except_table10109
+ GCC_except_table10126
+ GCC_except_table10129
+ GCC_except_table1013
+ GCC_except_table10135
+ GCC_except_table10139
+ GCC_except_table10179
+ GCC_except_table10198
+ GCC_except_table10209
+ GCC_except_table10217
+ GCC_except_table10220
+ GCC_except_table10331
+ GCC_except_table10335
+ GCC_except_table1034
+ GCC_except_table10368
+ GCC_except_table10394
+ GCC_except_table10398
+ GCC_except_table10402
+ GCC_except_table10424
+ GCC_except_table10434
+ GCC_except_table10448
+ GCC_except_table10451
+ GCC_except_table10454
+ GCC_except_table10477
+ GCC_except_table10479
+ GCC_except_table10529
+ GCC_except_table10540
+ GCC_except_table10582
+ GCC_except_table10614
+ GCC_except_table10617
+ GCC_except_table10621
+ GCC_except_table10623
+ GCC_except_table10628
+ GCC_except_table10639
+ GCC_except_table1065
+ GCC_except_table10670
+ GCC_except_table10699
+ GCC_except_table1070
+ GCC_except_table1072
+ GCC_except_table10728
+ GCC_except_table1074
+ GCC_except_table10741
+ GCC_except_table1076
+ GCC_except_table10815
+ GCC_except_table10825
+ GCC_except_table10833
+ GCC_except_table10837
+ GCC_except_table10839
+ GCC_except_table10843
+ GCC_except_table10849
+ GCC_except_table1087
+ GCC_except_table10891
+ GCC_except_table10895
+ GCC_except_table10896
+ GCC_except_table10908
+ GCC_except_table10917
+ GCC_except_table10919
+ GCC_except_table11006
+ GCC_except_table11024
+ GCC_except_table11026
+ GCC_except_table11030
+ GCC_except_table11031
+ GCC_except_table11042
+ GCC_except_table11043
+ GCC_except_table11044
+ GCC_except_table11086
+ GCC_except_table11214
+ GCC_except_table11218
+ GCC_except_table11221
+ GCC_except_table1134
+ GCC_except_table11368
+ GCC_except_table11430
+ GCC_except_table11476
+ GCC_except_table1148
+ GCC_except_table11500
+ GCC_except_table11501
+ GCC_except_table11508
+ GCC_except_table11511
+ GCC_except_table11537
+ GCC_except_table11562
+ GCC_except_table11638
+ GCC_except_table11639
+ GCC_except_table11640
+ GCC_except_table11641
+ GCC_except_table11642
+ GCC_except_table11643
+ GCC_except_table11644
+ GCC_except_table11645
+ GCC_except_table11646
+ GCC_except_table11647
+ GCC_except_table11648
+ GCC_except_table11649
+ GCC_except_table11650
+ GCC_except_table11651
+ GCC_except_table11652
+ GCC_except_table11764
+ GCC_except_table11773
+ GCC_except_table11775
+ GCC_except_table11776
+ GCC_except_table11777
+ GCC_except_table11778
+ GCC_except_table11779
+ GCC_except_table11790
+ GCC_except_table11808
+ GCC_except_table11840
+ GCC_except_table11841
+ GCC_except_table11842
+ GCC_except_table11843
+ GCC_except_table11844
+ GCC_except_table11854
+ GCC_except_table1186
+ GCC_except_table11872
+ GCC_except_table11873
+ GCC_except_table11874
+ GCC_except_table11875
+ GCC_except_table11876
+ GCC_except_table11877
+ GCC_except_table11878
+ GCC_except_table11879
+ GCC_except_table1188
+ GCC_except_table11880
+ GCC_except_table11881
+ GCC_except_table11918
+ GCC_except_table11919
+ GCC_except_table12053
+ GCC_except_table12088
+ GCC_except_table12146
+ GCC_except_table12152
+ GCC_except_table12169
+ GCC_except_table12179
+ GCC_except_table12192
+ GCC_except_table12210
+ GCC_except_table12215
+ GCC_except_table12226
+ GCC_except_table12227
+ GCC_except_table12244
+ GCC_except_table1227
+ GCC_except_table12286
+ GCC_except_table12354
+ GCC_except_table12360
+ GCC_except_table12376
+ GCC_except_table12405
+ GCC_except_table12415
+ GCC_except_table12451
+ GCC_except_table12452
+ GCC_except_table12559
+ GCC_except_table12562
+ GCC_except_table12597
+ GCC_except_table12601
+ GCC_except_table12605
+ GCC_except_table12629
+ GCC_except_table12630
+ GCC_except_table12656
+ GCC_except_table12667
+ GCC_except_table12669
+ GCC_except_table12673
+ GCC_except_table12677
+ GCC_except_table12680
+ GCC_except_table12739
+ GCC_except_table12740
+ GCC_except_table12741
+ GCC_except_table12742
+ GCC_except_table12743
+ GCC_except_table12745
+ GCC_except_table12747
+ GCC_except_table12771
+ GCC_except_table12774
+ GCC_except_table12802
+ GCC_except_table12834
+ GCC_except_table12934
+ GCC_except_table1296
+ GCC_except_table12990
+ GCC_except_table13005
+ GCC_except_table13102
+ GCC_except_table13104
+ GCC_except_table13213
+ GCC_except_table13225
+ GCC_except_table13227
+ GCC_except_table13238
+ GCC_except_table13245
+ GCC_except_table13248
+ GCC_except_table13251
+ GCC_except_table13266
+ GCC_except_table13273
+ GCC_except_table13275
+ GCC_except_table13283
+ GCC_except_table13285
+ GCC_except_table13306
+ GCC_except_table13329
+ GCC_except_table13337
+ GCC_except_table13338
+ GCC_except_table13373
+ GCC_except_table13378
+ GCC_except_table13383
+ GCC_except_table13386
+ GCC_except_table13395
+ GCC_except_table13406
+ GCC_except_table13408
+ GCC_except_table13414
+ GCC_except_table13419
+ GCC_except_table13454
+ GCC_except_table13495
+ GCC_except_table13508
+ GCC_except_table13563
+ GCC_except_table1370
+ GCC_except_table13708
+ GCC_except_table1374
+ GCC_except_table13873
+ GCC_except_table14085
+ GCC_except_table14326
+ GCC_except_table14329
+ GCC_except_table14330
+ GCC_except_table14331
+ GCC_except_table14332
+ GCC_except_table14333
+ GCC_except_table14335
+ GCC_except_table14365
+ GCC_except_table14369
+ GCC_except_table14504
+ GCC_except_table1696
+ GCC_except_table1788
+ GCC_except_table1813
+ GCC_except_table1859
+ GCC_except_table1915
+ GCC_except_table1934
+ GCC_except_table2226
+ GCC_except_table2260
+ GCC_except_table2282
+ GCC_except_table2286
+ GCC_except_table2298
+ GCC_except_table2309
+ GCC_except_table2313
+ GCC_except_table2348
+ GCC_except_table2349
+ GCC_except_table2388
+ GCC_except_table2392
+ GCC_except_table2394
+ GCC_except_table2397
+ GCC_except_table2410
+ GCC_except_table2415
+ GCC_except_table2431
+ GCC_except_table2445
+ GCC_except_table2567
+ GCC_except_table2621
+ GCC_except_table2733
+ GCC_except_table2762
+ GCC_except_table2769
+ GCC_except_table2819
+ GCC_except_table2824
+ GCC_except_table2871
+ GCC_except_table2893
+ GCC_except_table2896
+ GCC_except_table2897
+ GCC_except_table2956
+ GCC_except_table2968
+ GCC_except_table3034
+ GCC_except_table3047
+ GCC_except_table3139
+ GCC_except_table3150
+ GCC_except_table3182
+ GCC_except_table3254
+ GCC_except_table3260
+ GCC_except_table3263
+ GCC_except_table3280
+ GCC_except_table3292
+ GCC_except_table3296
+ GCC_except_table3306
+ GCC_except_table3313
+ GCC_except_table3349
+ GCC_except_table3356
+ GCC_except_table3432
+ GCC_except_table3502
+ GCC_except_table3504
+ GCC_except_table3519
+ GCC_except_table3522
+ GCC_except_table3524
+ GCC_except_table3557
+ GCC_except_table3562
+ GCC_except_table3563
+ GCC_except_table3672
+ GCC_except_table3743
+ GCC_except_table3748
+ GCC_except_table3810
+ GCC_except_table3850
+ GCC_except_table3861
+ GCC_except_table3968
+ GCC_except_table3989
+ GCC_except_table3996
+ GCC_except_table4033
+ GCC_except_table423
+ GCC_except_table428
+ GCC_except_table442
+ GCC_except_table4444
+ GCC_except_table4448
+ GCC_except_table4452
+ GCC_except_table4512
+ GCC_except_table4545
+ GCC_except_table4547
+ GCC_except_table4688
+ GCC_except_table469
+ GCC_except_table4735
+ GCC_except_table4752
+ GCC_except_table4760
+ GCC_except_table4764
+ GCC_except_table481
+ GCC_except_table484
+ GCC_except_table4918
+ GCC_except_table4928
+ GCC_except_table4961
+ GCC_except_table5191
+ GCC_except_table524
+ GCC_except_table5536
+ GCC_except_table5548
+ GCC_except_table5568
+ GCC_except_table5583
+ GCC_except_table5611
+ GCC_except_table5613
+ GCC_except_table5626
+ GCC_except_table5628
+ GCC_except_table563
+ GCC_except_table5630
+ GCC_except_table5643
+ GCC_except_table5674
+ GCC_except_table5704
+ GCC_except_table5809
+ GCC_except_table5820
+ GCC_except_table5888
+ GCC_except_table5996
+ GCC_except_table6000
+ GCC_except_table6009
+ GCC_except_table6011
+ GCC_except_table6032
+ GCC_except_table6043
+ GCC_except_table6049
+ GCC_except_table6051
+ GCC_except_table6119
+ GCC_except_table6145
+ GCC_except_table6155
+ GCC_except_table6164
+ GCC_except_table6219
+ GCC_except_table6226
+ GCC_except_table6228
+ GCC_except_table6230
+ GCC_except_table6236
+ GCC_except_table6374
+ GCC_except_table6565
+ GCC_except_table6634
+ GCC_except_table6662
+ GCC_except_table6749
+ GCC_except_table6779
+ GCC_except_table6806
+ GCC_except_table6964
+ GCC_except_table6966
+ GCC_except_table6970
+ GCC_except_table6972
+ GCC_except_table6974
+ GCC_except_table6976
+ GCC_except_table6978
+ GCC_except_table6980
+ GCC_except_table6983
+ GCC_except_table6990
+ GCC_except_table6992
+ GCC_except_table6994
+ GCC_except_table7006
+ GCC_except_table7038
+ GCC_except_table7040
+ GCC_except_table7042
+ GCC_except_table7044
+ GCC_except_table7046
+ GCC_except_table7048
+ GCC_except_table7050
+ GCC_except_table7052
+ GCC_except_table7054
+ GCC_except_table7066
+ GCC_except_table7068
+ GCC_except_table7071
+ GCC_except_table7073
+ GCC_except_table7075
+ GCC_except_table7077
+ GCC_except_table7079
+ GCC_except_table7082
+ GCC_except_table7084
+ GCC_except_table7087
+ GCC_except_table7089
+ GCC_except_table7091
+ GCC_except_table7119
+ GCC_except_table7121
+ GCC_except_table7124
+ GCC_except_table7127
+ GCC_except_table7227
+ GCC_except_table7245
+ GCC_except_table7282
+ GCC_except_table7408
+ GCC_except_table7410
+ GCC_except_table7440
+ GCC_except_table7445
+ GCC_except_table7738
+ GCC_except_table7758
+ GCC_except_table7760
+ GCC_except_table7762
+ GCC_except_table7764
+ GCC_except_table7799
+ GCC_except_table7832
+ GCC_except_table7889
+ GCC_except_table7940
+ GCC_except_table7967
+ GCC_except_table7971
+ GCC_except_table7978
+ GCC_except_table8138
+ GCC_except_table8270
+ GCC_except_table8291
+ GCC_except_table8294
+ GCC_except_table8313
+ GCC_except_table8380
+ GCC_except_table8422
+ GCC_except_table8519
+ GCC_except_table8565
+ GCC_except_table8620
+ GCC_except_table8758
+ GCC_except_table8764
+ GCC_except_table8785
+ GCC_except_table8787
+ GCC_except_table8789
+ GCC_except_table8836
+ GCC_except_table8864
+ GCC_except_table8914
+ GCC_except_table9120
+ GCC_except_table9122
+ GCC_except_table9140
+ GCC_except_table9142
+ GCC_except_table9145
+ GCC_except_table9250
+ GCC_except_table9264
+ GCC_except_table9375
+ GCC_except_table9377
+ GCC_except_table9509
+ GCC_except_table9591
+ GCC_except_table9618
+ GCC_except_table9622
+ GCC_except_table9646
+ GCC_except_table9651
+ GCC_except_table9655
+ GCC_except_table966
+ GCC_except_table9665
+ GCC_except_table9724
+ GCC_except_table9728
+ GCC_except_table9733
+ GCC_except_table9807
+ GCC_except_table9847
+ GCC_except_table9851
+ GCC_except_table9853
+ GCC_except_table9855
+ GCC_except_table986
+ GCC_except_table9867
+ GCC_except_table9872
+ GCC_except_table9912
+ GCC_except_table9941
+ GCC_except_table999
+ _OBJC_IVAR_$_PHAssetChangeRequest._restoreTimeZoneFromMetadata
+ _OBJC_IVAR_$_PHAssetChangeRequest._timeZoneOffsetAtCreationDate
+ _OBJC_IVAR_$_PHAssetExtendedMetadata._timeZone
+ _OBJC_IVAR_$_PHAssetExtendedMetadataProperties._timeZone
+ _OBJC_IVAR_$_PHFindQueryOptions._includeSharedCollectionAssets
+ _OBJC_IVAR_$_PHSearchQueryOptions._includeSharedCollectionAssets
+ _OUTLINED_FUNCTION_100
+ _OUTLINED_FUNCTION_101
+ _OUTLINED_FUNCTION_102
+ _OUTLINED_FUNCTION_103
+ _OUTLINED_FUNCTION_104
+ _OUTLINED_FUNCTION_105
+ _OUTLINED_FUNCTION_106
+ _OUTLINED_FUNCTION_107
+ _OUTLINED_FUNCTION_108
+ _OUTLINED_FUNCTION_109
+ _OUTLINED_FUNCTION_110
+ _OUTLINED_FUNCTION_111
+ _OUTLINED_FUNCTION_112
+ _OUTLINED_FUNCTION_113
+ _OUTLINED_FUNCTION_114
+ _OUTLINED_FUNCTION_115
+ _OUTLINED_FUNCTION_116
+ _OUTLINED_FUNCTION_117
+ _OUTLINED_FUNCTION_118
+ _OUTLINED_FUNCTION_119
+ _OUTLINED_FUNCTION_120
+ _OUTLINED_FUNCTION_121
+ _OUTLINED_FUNCTION_122
+ _OUTLINED_FUNCTION_123
+ _OUTLINED_FUNCTION_124
+ _OUTLINED_FUNCTION_125
+ _OUTLINED_FUNCTION_126
+ _OUTLINED_FUNCTION_127
+ _OUTLINED_FUNCTION_128
+ _OUTLINED_FUNCTION_129
+ _OUTLINED_FUNCTION_130
+ _OUTLINED_FUNCTION_131
+ _OUTLINED_FUNCTION_132
+ _OUTLINED_FUNCTION_133
+ _OUTLINED_FUNCTION_134
+ _OUTLINED_FUNCTION_135
+ _OUTLINED_FUNCTION_136
+ _OUTLINED_FUNCTION_137
+ _OUTLINED_FUNCTION_138
+ _OUTLINED_FUNCTION_139
+ _OUTLINED_FUNCTION_140
+ _OUTLINED_FUNCTION_141
+ _OUTLINED_FUNCTION_142
+ _OUTLINED_FUNCTION_143
+ _OUTLINED_FUNCTION_144
+ _OUTLINED_FUNCTION_145
+ _OUTLINED_FUNCTION_146
+ _OUTLINED_FUNCTION_147
+ _OUTLINED_FUNCTION_148
+ _OUTLINED_FUNCTION_149
+ _OUTLINED_FUNCTION_150
+ _OUTLINED_FUNCTION_151
+ _OUTLINED_FUNCTION_152
+ _OUTLINED_FUNCTION_153
+ _OUTLINED_FUNCTION_154
+ _OUTLINED_FUNCTION_155
+ _OUTLINED_FUNCTION_156
+ _OUTLINED_FUNCTION_157
+ _OUTLINED_FUNCTION_158
+ _OUTLINED_FUNCTION_159
+ _OUTLINED_FUNCTION_160
+ _OUTLINED_FUNCTION_53
+ _OUTLINED_FUNCTION_54
+ _OUTLINED_FUNCTION_55
+ _OUTLINED_FUNCTION_56
+ _OUTLINED_FUNCTION_57
+ _OUTLINED_FUNCTION_58
+ _OUTLINED_FUNCTION_59
+ _OUTLINED_FUNCTION_60
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_62
+ _OUTLINED_FUNCTION_63
+ _OUTLINED_FUNCTION_64
+ _OUTLINED_FUNCTION_65
+ _OUTLINED_FUNCTION_66
+ _OUTLINED_FUNCTION_67
+ _OUTLINED_FUNCTION_68
+ _OUTLINED_FUNCTION_69
+ _OUTLINED_FUNCTION_70
+ _OUTLINED_FUNCTION_71
+ _OUTLINED_FUNCTION_72
+ _OUTLINED_FUNCTION_73
+ _OUTLINED_FUNCTION_74
+ _OUTLINED_FUNCTION_75
+ _OUTLINED_FUNCTION_76
+ _OUTLINED_FUNCTION_77
+ _OUTLINED_FUNCTION_78
+ _OUTLINED_FUNCTION_79
+ _OUTLINED_FUNCTION_80
+ _OUTLINED_FUNCTION_81
+ _OUTLINED_FUNCTION_82
+ _OUTLINED_FUNCTION_83
+ _OUTLINED_FUNCTION_84
+ _OUTLINED_FUNCTION_85
+ _OUTLINED_FUNCTION_86
+ _OUTLINED_FUNCTION_87
+ _OUTLINED_FUNCTION_88
+ _OUTLINED_FUNCTION_89
+ _OUTLINED_FUNCTION_90
+ _OUTLINED_FUNCTION_91
+ _OUTLINED_FUNCTION_92
+ _OUTLINED_FUNCTION_93
+ _OUTLINED_FUNCTION_94
+ _OUTLINED_FUNCTION_95
+ _OUTLINED_FUNCTION_96
+ _OUTLINED_FUNCTION_97
+ _OUTLINED_FUNCTION_98
+ _OUTLINED_FUNCTION_99
+ _PHCloudFeedEntryOptionsWithDefaultSort
+ _PLPhotoAnalysisPhotoLibraryServiceExtendedCuratedAssetsOptionsPurpose
+ _PLPhotoAnalysisPhotoLibraryServiceExtendedCuratedAssetsOptionsPurposeMemories
+ ___88+[PHCloudFeedEntry fetchUnreadNotificationEntriesWithLastSeenDate:eventLogDate:options:]_block_invoke
+ ___swift__destructor
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_closure_destructor.221Tm
+ ___swift_closure_destructor.72Tm
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ _archive_entry_filetype
+ _archive_entry_hardlink
+ _archive_entry_set_perm
+ _archive_entry_symlink
+ _associated conformance 6Photos28PHHastingsCurationJunkFilterO0E5ErrorO10Foundation09LocalizedF0AAs0F0
+ _kCGImagePropertyPixelHeight
+ _kCGImagePropertyPixelWidth
+ _objc_msgSend$_appendSharedCollectionAssetExclusionToTokens:context:
+ _objc_msgSend$_peopleHomeOrderedUUIDs
+ _objc_msgSend$_resultForMatches:
+ _objc_msgSend$descriptionByJoiningMediaSubtypeComponents:
+ _objc_msgSend$descriptionComponentsForMediaSubtypes:
+ _objc_msgSend$doubleForKey:
+ _objc_msgSend$extendedCuratedAssetsFromAssetUUIDs:options:operationID:reply:
+ _objc_msgSend$hasEditableLivePhotoVideo
+ _objc_msgSend$includeSharedCollectionAssets
+ _objc_msgSend$isCinematicCapableVideo
+ _objc_msgSend$leoItemTypesForFindOptions:
+ _objc_msgSend$localAnalysisMajorVersion
+ _objc_msgSend$predicateForUnreadNotificationEntriesSinceLastSeenDate:eventLogDate:
+ _objc_msgSend$quarantineDirectoryAtURL:error:
+ _objc_msgSend$queryForUnreadNotificationEntriesWithLastSeenDate:eventLogDate:options:
+ _objc_msgSend$realURLForURL:error:
+ _objc_msgSend$restoreTimeZoneFromMetadata
+ _objc_msgSend$setIncludeSharedCollectionAssets:
+ _objc_msgSend$shouldUpdateLocalAnalysisStageWithLocalMajorVersion:localAnalysisStage:newAnalysisStage:
+ _objc_msgSend$textDocumentNode
+ _objc_msgSend$timeZoneWithName:
+ _swift_beginAccess
+ _swift_dynamicCastClass
+ _symbolic SSSg
+ _symbolic SaySiG
+ _symbolic SaySiGIegr_
+ _symbolic SaySo14PHPhotoLibraryCG
+ _symbolic Say_____G 22PhotosIntelligenceCore8HastingsV5AssetV
+ _symbolic ScCySaySSG______pG s5ErrorP
+ _symbolic ScgyShySSG______pG s5ErrorP
+ _symbolic Sd
+ _symbolic SdIegd_
+ _symbolic ShySSG
+ _symbolic ShySSG______pIeghHrzo_ s5ErrorP
+ _symbolic So34PLPhotoAnalysisPhotoLibraryServiceC
+ _symbolic _____ 6Photos24HastingsCurationSettingsV
+ _symbolic _____ 6Photos24PHHastingsCurationEngineC0C6TargetO
+ _symbolic _____ 6Photos28PHHastingsCurationJunkFilterO
+ _symbolic _____ 6Photos28PHHastingsCurationJunkFilterO0E5ErrorO
+ _symbolic _____ 6Photos28PHHastingsCurationJunkFilterO18AssetUUIDsBySourceV
+ _symbolic _____ s15ContinuousClockV
+ _symbolic _____ s15ContinuousClockV7InstantV
+ _symbolic _____ s8DurationV
+ _symbolic _____XMT 6Photos24PHHastingsCurationEngineC
+ _symbolic _____ySSSgG s11_SetStorageC
+ _symbolic _____ySSSgG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic yp
- +[PHCollectionShare fetchCollectionSharesWithUnreadActivityWithOptions:]
- +[PHFindPersonGrounder _resultForMatches:options:error:]
- +[PHQuery queryForCollectionSharesWithUnreadActivityWithOptions:]
- -[PHResourceChooserListResourceInfo isNonRawImage]
- GCC_except_table10094
- GCC_except_table1010
- GCC_except_table10111
- GCC_except_table10114
- GCC_except_table10120
- GCC_except_table10124
- GCC_except_table10164
- GCC_except_table10183
- GCC_except_table10194
- GCC_except_table10202
- GCC_except_table10205
- GCC_except_table1031
- GCC_except_table10316
- GCC_except_table10320
- GCC_except_table10353
- GCC_except_table10379
- GCC_except_table10383
- GCC_except_table10387
- GCC_except_table10409
- GCC_except_table10419
- GCC_except_table10433
- GCC_except_table10436
- GCC_except_table10439
- GCC_except_table10462
- GCC_except_table10464
- GCC_except_table10514
- GCC_except_table10525
- GCC_except_table10567
- GCC_except_table10599
- GCC_except_table10602
- GCC_except_table10606
- GCC_except_table10608
- GCC_except_table10613
- GCC_except_table1062
- GCC_except_table10624
- GCC_except_table10655
- GCC_except_table1067
- GCC_except_table10684
- GCC_except_table1069
- GCC_except_table1071
- GCC_except_table10711
- GCC_except_table10713
- GCC_except_table1073
- GCC_except_table10800
- GCC_except_table10803
- GCC_except_table10810
- GCC_except_table1082
- GCC_except_table10822
- GCC_except_table10824
- GCC_except_table10828
- GCC_except_table10834
- GCC_except_table10876
- GCC_except_table10880
- GCC_except_table10881
- GCC_except_table10893
- GCC_except_table10902
- GCC_except_table10904
- GCC_except_table10991
- GCC_except_table11009
- GCC_except_table11011
- GCC_except_table11012
- GCC_except_table11013
- GCC_except_table11014
- GCC_except_table11015
- GCC_except_table11016
- GCC_except_table11071
- GCC_except_table11199
- GCC_except_table11203
- GCC_except_table11206
- GCC_except_table1129
- GCC_except_table11353
- GCC_except_table11415
- GCC_except_table1143
- GCC_except_table11461
- GCC_except_table11471
- GCC_except_table11485
- GCC_except_table11493
- GCC_except_table11496
- GCC_except_table11519
- GCC_except_table11520
- GCC_except_table11521
- GCC_except_table11522
- GCC_except_table11523
- GCC_except_table11524
- GCC_except_table11525
- GCC_except_table11526
- GCC_except_table11529
- GCC_except_table11530
- GCC_except_table11531
- GCC_except_table11532
- GCC_except_table11533
- GCC_except_table11542
- GCC_except_table11543
- GCC_except_table11567
- GCC_except_table11577
- GCC_except_table11748
- GCC_except_table11757
- GCC_except_table11758
- GCC_except_table11759
- GCC_except_table11760
- GCC_except_table11761
- GCC_except_table11762
- GCC_except_table11763
- GCC_except_table11792
- GCC_except_table1181
- GCC_except_table11825
- GCC_except_table11826
- GCC_except_table11827
- GCC_except_table11828
- GCC_except_table11829
- GCC_except_table1183
- GCC_except_table11839
- GCC_except_table11857
- GCC_except_table11858
- GCC_except_table11859
- GCC_except_table11860
- GCC_except_table11861
- GCC_except_table11862
- GCC_except_table11863
- GCC_except_table11864
- GCC_except_table11865
- GCC_except_table11866
- GCC_except_table11903
- GCC_except_table11904
- GCC_except_table12038
- GCC_except_table12074
- GCC_except_table12132
- GCC_except_table12138
- GCC_except_table12141
- GCC_except_table12151
- GCC_except_table12168
- GCC_except_table12178
- GCC_except_table12201
- GCC_except_table12212
- GCC_except_table12213
- GCC_except_table1222
- GCC_except_table12230
- GCC_except_table12272
- GCC_except_table12340
- GCC_except_table12346
- GCC_except_table12362
- GCC_except_table12391
- GCC_except_table12401
- GCC_except_table12437
- GCC_except_table12438
- GCC_except_table12545
- GCC_except_table12548
- GCC_except_table12583
- GCC_except_table12587
- GCC_except_table12591
- GCC_except_table12615
- GCC_except_table12616
- GCC_except_table12642
- GCC_except_table12653
- GCC_except_table12655
- GCC_except_table12659
- GCC_except_table12663
- GCC_except_table12666
- GCC_except_table12713
- GCC_except_table12719
- GCC_except_table12725
- GCC_except_table12726
- GCC_except_table12728
- GCC_except_table12729
- GCC_except_table12731
- GCC_except_table12746
- GCC_except_table12757
- GCC_except_table12788
- GCC_except_table12820
- GCC_except_table1291
- GCC_except_table12918
- GCC_except_table12974
- GCC_except_table12989
- GCC_except_table13086
- GCC_except_table13088
- GCC_except_table13197
- GCC_except_table13209
- GCC_except_table13211
- GCC_except_table13222
- GCC_except_table13229
- GCC_except_table13232
- GCC_except_table13235
- GCC_except_table13250
- GCC_except_table13257
- GCC_except_table13259
- GCC_except_table13267
- GCC_except_table13269
- GCC_except_table13290
- GCC_except_table13313
- GCC_except_table13321
- GCC_except_table13322
- GCC_except_table13357
- GCC_except_table13362
- GCC_except_table13367
- GCC_except_table13370
- GCC_except_table13379
- GCC_except_table13387
- GCC_except_table13390
- GCC_except_table13392
- GCC_except_table13398
- GCC_except_table13438
- GCC_except_table13479
- GCC_except_table13492
- GCC_except_table13547
- GCC_except_table1365
- GCC_except_table1369
- GCC_except_table13692
- GCC_except_table13857
- GCC_except_table14069
- GCC_except_table14310
- GCC_except_table14313
- GCC_except_table14314
- GCC_except_table14315
- GCC_except_table14316
- GCC_except_table14317
- GCC_except_table14319
- GCC_except_table14349
- GCC_except_table14353
- GCC_except_table14488
- GCC_except_table1689
- GCC_except_table1781
- GCC_except_table1806
- GCC_except_table1852
- GCC_except_table1908
- GCC_except_table1927
- GCC_except_table2212
- GCC_except_table2253
- GCC_except_table2275
- GCC_except_table2279
- GCC_except_table2284
- GCC_except_table2302
- GCC_except_table2306
- GCC_except_table2341
- GCC_except_table2342
- GCC_except_table2381
- GCC_except_table2385
- GCC_except_table2387
- GCC_except_table2390
- GCC_except_table2403
- GCC_except_table2408
- GCC_except_table2424
- GCC_except_table2438
- GCC_except_table2560
- GCC_except_table2614
- GCC_except_table2725
- GCC_except_table2754
- GCC_except_table2761
- GCC_except_table2811
- GCC_except_table2816
- GCC_except_table2863
- GCC_except_table2885
- GCC_except_table2888
- GCC_except_table2889
- GCC_except_table2948
- GCC_except_table2960
- GCC_except_table3026
- GCC_except_table3039
- GCC_except_table3131
- GCC_except_table3142
- GCC_except_table3174
- GCC_except_table3246
- GCC_except_table3252
- GCC_except_table3255
- GCC_except_table3272
- GCC_except_table3284
- GCC_except_table3288
- GCC_except_table3297
- GCC_except_table3298
- GCC_except_table3341
- GCC_except_table3348
- GCC_except_table3424
- GCC_except_table3486
- GCC_except_table3496
- GCC_except_table3511
- GCC_except_table3514
- GCC_except_table3516
- GCC_except_table3549
- GCC_except_table3554
- GCC_except_table3555
- GCC_except_table3664
- GCC_except_table3735
- GCC_except_table3740
- GCC_except_table3802
- GCC_except_table3842
- GCC_except_table3853
- GCC_except_table3957
- GCC_except_table3978
- GCC_except_table3985
- GCC_except_table4022
- GCC_except_table422
- GCC_except_table427
- GCC_except_table441
- GCC_except_table4435
- GCC_except_table4439
- GCC_except_table4443
- GCC_except_table4503
- GCC_except_table4536
- GCC_except_table4538
- GCC_except_table4679
- GCC_except_table468
- GCC_except_table4726
- GCC_except_table4743
- GCC_except_table4751
- GCC_except_table4755
- GCC_except_table480
- GCC_except_table483
- GCC_except_table4909
- GCC_except_table4919
- GCC_except_table4952
- GCC_except_table5182
- GCC_except_table522
- GCC_except_table5527
- GCC_except_table5539
- GCC_except_table5559
- GCC_except_table5574
- GCC_except_table559
- GCC_except_table5602
- GCC_except_table5604
- GCC_except_table5617
- GCC_except_table5619
- GCC_except_table5621
- GCC_except_table5634
- GCC_except_table5665
- GCC_except_table5695
- GCC_except_table5796
- GCC_except_table5807
- GCC_except_table5874
- GCC_except_table5980
- GCC_except_table5984
- GCC_except_table5993
- GCC_except_table5995
- GCC_except_table6016
- GCC_except_table6019
- GCC_except_table6027
- GCC_except_table6033
- GCC_except_table6103
- GCC_except_table6129
- GCC_except_table6139
- GCC_except_table6148
- GCC_except_table6203
- GCC_except_table6210
- GCC_except_table6212
- GCC_except_table6214
- GCC_except_table6220
- GCC_except_table6359
- GCC_except_table6550
- GCC_except_table6619
- GCC_except_table6647
- GCC_except_table6734
- GCC_except_table6764
- GCC_except_table6791
- GCC_except_table6949
- GCC_except_table6951
- GCC_except_table6955
- GCC_except_table6957
- GCC_except_table6959
- GCC_except_table6961
- GCC_except_table6963
- GCC_except_table6965
- GCC_except_table6968
- GCC_except_table6975
- GCC_except_table6977
- GCC_except_table6979
- GCC_except_table6991
- GCC_except_table7023
- GCC_except_table7025
- GCC_except_table7027
- GCC_except_table7029
- GCC_except_table7031
- GCC_except_table7033
- GCC_except_table7035
- GCC_except_table7037
- GCC_except_table7039
- GCC_except_table7041
- GCC_except_table7043
- GCC_except_table7045
- GCC_except_table7047
- GCC_except_table7049
- GCC_except_table7051
- GCC_except_table7053
- GCC_except_table7067
- GCC_except_table7069
- GCC_except_table7072
- GCC_except_table7074
- GCC_except_table7076
- GCC_except_table7104
- GCC_except_table7106
- GCC_except_table7109
- GCC_except_table7112
- GCC_except_table7212
- GCC_except_table7230
- GCC_except_table7267
- GCC_except_table7393
- GCC_except_table7395
- GCC_except_table7425
- GCC_except_table7430
- GCC_except_table7723
- GCC_except_table7743
- GCC_except_table7745
- GCC_except_table7747
- GCC_except_table7749
- GCC_except_table7784
- GCC_except_table7817
- GCC_except_table7874
- GCC_except_table7925
- GCC_except_table7952
- GCC_except_table7956
- GCC_except_table7963
- GCC_except_table8123
- GCC_except_table8255
- GCC_except_table8276
- GCC_except_table8279
- GCC_except_table8298
- GCC_except_table8365
- GCC_except_table8407
- GCC_except_table8504
- GCC_except_table8550
- GCC_except_table8605
- GCC_except_table8743
- GCC_except_table8749
- GCC_except_table8770
- GCC_except_table8772
- GCC_except_table8774
- GCC_except_table8821
- GCC_except_table8849
- GCC_except_table8899
- GCC_except_table9105
- GCC_except_table9107
- GCC_except_table9125
- GCC_except_table9127
- GCC_except_table9130
- GCC_except_table9235
- GCC_except_table9249
- GCC_except_table9360
- GCC_except_table9362
- GCC_except_table9494
- GCC_except_table9576
- GCC_except_table9603
- GCC_except_table9607
- GCC_except_table963
- GCC_except_table9631
- GCC_except_table9636
- GCC_except_table9640
- GCC_except_table9650
- GCC_except_table9709
- GCC_except_table9713
- GCC_except_table9718
- GCC_except_table9792
- GCC_except_table983
- GCC_except_table9832
- GCC_except_table9836
- GCC_except_table9838
- GCC_except_table9840
- GCC_except_table9852
- GCC_except_table9857
- GCC_except_table9897
- GCC_except_table9926
- GCC_except_table996
- _PHHastingsCurationResolvedTargetCount.registerDefaultsOnceToken
- ___72+[PHCollectionShare fetchCollectionSharesWithUnreadActivityWithOptions:]_block_invoke
- ___PHHastingsCurationResolvedTargetCount_block_invoke
- ___swift_memcpy64_8
- _objc_msgSend$_resultForMatches:options:error:
- _objc_msgSend$conformsToImage
- _objc_msgSend$isNonRawImage
- _objc_msgSend$predicateForCollectionSharesWithUnreadActivity
- _objc_msgSend$queryForCollectionSharesWithUnreadActivityWithOptions:
- _objc_msgSend$representsNonRawImage
- _symbolic Say_____G______t 22PhotosIntelligenceCore8HastingsV5AssetV 0A024PHHastingsCurationEngineC19ExclusionStatistics33_96AE3D1D78FAB595B52BAAD1EA2EF3D6LLV
- _type_layout_string 6Photos24PHHastingsCurationEngineC19ExclusionStatistics33_96AE3D1D78FAB595B52BAAD1EA2EF3D6LLV
CStrings:
+ " dejunkedDeduped="
+ " screenRecording="
+ " tastefullyBlurred="
+ " unpleasantLighting="
+ "%ld"
+ "%ld candidates don't exceed the target of %ld, so all of them are returned"
+ "%{public}s%{public}@ Excluding shared collection assets from the query (%tu lexemes)"
+ "%{public}s%{public}@ Failed to fetch shared collection asset lexemes, not excluding them: %@"
+ "%{public}s%{public}@ No shared collection assets in the index, nothing to exclude"
+ "%{public}sFailed to quarantine unzipped bundle (%@): %@"
+ "%{public}sFailed to read zipped bundle (bundle root is not a directory): %@"
+ "%{public}sFailed to read zipped bundle (entry outside destination): %@"
+ "%{public}sFailed to read zipped bundle (missing entry path)"
+ "%{public}sFailed to read zipped bundle (path traversal): %@"
+ "%{public}sFailed to read zipped bundle (unsupported entry type 0%o): %s"
+ "%{public}sFailed to resolve temporary directory to unzip bundle: %@"
+ "%{public}sPerson ranking failed to open the system library for People order. Error: %@"
+ "%{public}s[CCSS] Dropping MAD compute sync payload for asset %{public}@ since its analysis stage %d was not applied over %d.%d by client: %{public}@"
+ "%{public}s[RM]: PHImageIODecoder - decoded image (%zux%zu) does not satisfy max long side %ld, decoding full image"
+ ".."
+ "Curated %ld assets from %ld candidates for a target of %{public}s"
+ "Curating %ld identifiers across %ld libraries with a requested count of %ld"
+ "Curating %lu unique identifiers across %lu libraries: target count %lu requested, creation date sort %{public}@"
+ "Dejunked and deduped %ld system library assets to %ld in %{public}s, leaving %ld syndicated assets to the local junk check"
+ "Dejunker-deduper returned nothing for %ld system library assets after %{public}s, so the local junk check covers all %ld assets"
+ "Dejunking and deduping failed after %{public}s, so the local junk check covers all %ld assets: %{public}s"
+ "Excluded: %{public}s"
+ "Ignoring %{public}s of %f"
+ "Ignoring %{public}s of %ld"
+ "IncludeSharedCollectionAssets"
+ "IncludeSharedCollectionAssets: %@, "
+ "Libraries hold %s of %ld identifiers"
+ "No count given (%ld is below the minimum of %ld): %f of %ld candidates is %ld, the default is %ld, so the target is %ld from %{public}s"
+ "No system library among %ld libraries, so the local junk check covers all %ld assets"
+ "PHFindQueryOptions: photoLibrary: %td, resultTypes: %@, precisionMode: %@, clientIdentifier: %@, isCardQuery: %@, includeSharedCollectionAssets: %@, enableQueryMatchDetails: %@, enableResultItemBundleIdentifier: %@, disableMetadataSearch: %@, disableSemanticSearch: %@, fetchContextualThumbnailData: %@, allowedBundleIdentifiers: %@, sortDescriptors: %@, scopedIdentifiers: %@, momentExpansionOptions: %@>"
+ "PHHastingsCuration.dejunkDedupe"
+ "PHHastingsCuration:"
+ "PHHastingsCurationMaxSyndicationFraction"
+ "PHHastingsCurationMinimumTargetCount"
+ "PHHastingsCurationShrinkFraction"
+ "PHHastingsCurationTimeoutSeconds"
+ "Re-curating added %ld of %ld free slots"
+ "Re-curating failed, keeping %ld assets: %{public}s"
+ "Re-curating skipped: %ld free slots, %ld remaining system candidates; keeping %ld"
+ "Re-curating skipped: adding all %ld remaining system candidates for %ld free slots"
+ "Re-curating system candidates: keeping %ld system + %ld syndicated, adding %ld from %ld remaining"
+ "Requesting dejunking and deduping of %ld assets with operationID %{public}s"
+ "Running Hastings with %ld candidates, a target of %ld, %ld required and %ld shotlist entries"
+ "Skipping Hastings: %ld candidates, requested count %ld"
+ "Skipping dejunking and deduping because there is no time left, so the local junk check covers all %ld assets"
+ "Syndicated cap: %ld of %ld picked, cap %ld, effective cap %ld, %ld system candidates, target %ld"
+ "Target %ld is below the minimum of %ld, so all %ld candidates are returned"
+ "Target %ld: the caller asked for %ld, which is at least the minimum of %ld"
+ "The dejunker-deduper didn't finish within "
+ "The photo analysis client is unavailable"
+ "Timed out after %f s: returning the top %ld of %ld ranked identifiers, %{public}s creation dates"
+ "Timed out re-curating: keeping the %ld assets the first pass and the cap allowed"
+ "_createCheckedThrowingContinuation(_:)"
+ "cinematic capable"
+ "hi"
+ "ja"
+ "ko"
+ "ms"
+ "restoreTimeZoneFromMetadata"
+ "timeZoneOffsetAtCreationDate"
+ "vi"
+ "yue"
+ "zh"
- "Curated %ld assets from %ld candidates for a target count of %ld"
- "Curating %ld identifiers across %ld libraries with a target count of %ld"
- "Curating %lu unique identifiers across %lu libraries: target count %lu requested, %ld used (%{public}s), creation date sort %{public}@"
- "Excluded: screenshot=%ld screenRecording=%ld junk=%ld sharpness=%ld aesthetics=%ld failure=%ld tastefullyBlurred=%ld unpleasantLighting=%ld"
- "Library %ld holds %ld of the %ld identifiers"
- "Notifications"
- "PHFindQueryOptions: photoLibrary: %td, resultTypes: %@, precisionMode: %@, clientIdentifier: %@, isCardQuery: %@, enableQueryMatchDetails: %@, enableResultItemBundleIdentifier: %@, disableMetadataSearch: %@, disableSemanticSearch: %@, fetchContextualThumbnailData: %@, allowedBundleIdentifiers: %@, sortDescriptors: %@, scopedIdentifiers: %@, momentExpansionOptions: %@>"
- "Running Hastings with %ld candidates and %ld shotlist entries"
- "Skipping Hastings: %ld candidates fit within the target count of %ld"
- "as requested"
- "from the PHHastingsCurationDefaultTargetCount user default"
```
