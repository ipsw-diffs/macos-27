## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/Versions/A/LinkServices`

```diff

-301.2.7.2.0
-  __TEXT.__text: 0x150238
-  __TEXT.__objc_methlist: 0xae80
+301.2.12.2.0
+  __TEXT.__text: 0x15378c
+  __TEXT.__objc_methlist: 0xb078
   __TEXT.__dlopen_cstrs: 0x605
-  __TEXT.__const: 0x7818
-  __TEXT.__constg_swiftt: 0x1b28
-  __TEXT.__swift5_typeref: 0x2f0c
+  __TEXT.__const: 0x7888
+  __TEXT.__constg_swiftt: 0x1b98
+  __TEXT.__swift5_typeref: 0x2f66
   __TEXT.__swift5_builtin: 0x258
-  __TEXT.__swift5_reflstr: 0xe6c
-  __TEXT.__swift5_fieldmd: 0x11d8
+  __TEXT.__swift5_reflstr: 0xe9c
+  __TEXT.__swift5_fieldmd: 0x121c
   __TEXT.__swift5_assocty: 0x2b8
-  __TEXT.__cstring: 0xc96d
+  __TEXT.__cstring: 0xcb9b
   __TEXT.__swift5_proto: 0x284
-  __TEXT.__swift5_types: 0x1a0
-  __TEXT.__swift5_protos: 0x44
+  __TEXT.__swift5_types: 0x1a4
   __TEXT.__swift5_capture: 0x12b8
-  __TEXT.__oslogstring: 0x99f6
+  __TEXT.__oslogstring: 0x9b12
   __TEXT.__swift_as_entry: 0x114
   __TEXT.__swift_as_ret: 0x130
   __TEXT.__swift_as_cont: 0x1c4
+  __TEXT.__swift5_protos: 0x44
   __TEXT.__swift5_mpenum: 0x68
-  __TEXT.__gcc_except_tab: 0x1e0c
-  __TEXT.__unwind_info: 0x6a48
-  __TEXT.__eh_frame: 0x4bb8
+  __TEXT.__gcc_except_tab: 0x1ea0
+  __TEXT.__unwind_info: 0x6ad8
+  __TEXT.__eh_frame: 0x4c00
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe68
-  __DATA_CONST.__objc_classlist: 0x868
+  __DATA_CONST.__const: 0xef0
+  __DATA_CONST.__objc_classlist: 0x880
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5290
+  __DATA_CONST.__objc_selrefs: 0x5370
   __DATA_CONST.__objc_protorefs: 0x100
-  __DATA_CONST.__objc_superrefs: 0x5e8
+  __DATA_CONST.__objc_superrefs: 0x5f8
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x1950
-  __AUTH_CONST.__const: 0x8240
-  __AUTH_CONST.__cfstring: 0x8dc0
-  __AUTH_CONST.__objc_const: 0x166d8
+  __DATA_CONST.__got: 0x19f8
+  __AUTH_CONST.__const: 0x8290
+  __AUTH_CONST.__cfstring: 0x91c0
+  __AUTH_CONST.__objc_const: 0x16c48
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1728
-  __AUTH.__objc_data: 0x3e00
-  __AUTH.__data: 0x12a0
-  __DATA.__objc_ivar: 0xacc
-  __DATA.__data: 0x2768
+  __AUTH_CONST.__auth_got: 0x1808
+  __AUTH.__objc_data: 0x3ec0
+  __AUTH.__data: 0x1340
+  __DATA.__objc_ivar: 0xb08
+  __DATA.__data: 0x27b0
   __DATA.__bss: 0x47f8
   __DATA.__common: 0x78
   __DATA_DIRTY.__objc_data: 0x2350

   - /System/Library/PrivateFrameworks/LinkMetadata.framework/Versions/A/LinkMetadata
   - /System/Library/PrivateFrameworks/RunningBoardServices.framework/Versions/A/RunningBoardServices
   - /System/Library/PrivateFrameworks/SceneHosting.framework/Versions/A/SceneHosting
+  - /System/Library/PrivateFrameworks/SessionAssertion.framework/Versions/A/SessionAssertion
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8859
-  Symbols:   11321
-  CStrings:  2238
+  Functions: 8920
+  Symbols:   11437
+  CStrings:  2277
 
Symbols:
+ +[LNSnippetContentMargins supportsSecureCoding]
+ +[LNSnippetTextStyleSpecification supportsSecureCoding]
+ -[LNActionExecutor didInvalidateLiveActivityBackgroundAssertion:error:]
+ -[LNActionExecutor liveActivityAssertion]
+ -[LNActionExecutor setLiveActivityAssertion:]
+ -[LNRegisteredBundleMetadata codeSignatureValidationCategory]
+ -[LNRegisteredBundleMetadata initWithBundleIdentifier:installIdentifier:codeSignatureValidationCategory:]
+ -[LNRegisteredBundleMetadata initWithBundleIdentifier:installIdentifier:codeSignatureValidationCategory:quarantineStatus:]
+ -[LNRegisteredBundleMetadata quarantineStatus]
+ -[LNSnippetContentMargins bottom]
+ -[LNSnippetContentMargins encodeWithCoder:]
+ -[LNSnippetContentMargins hash]
+ -[LNSnippetContentMargins initWithCoder:]
+ -[LNSnippetContentMargins initWithTop:leading:bottom:trailing:]
+ -[LNSnippetContentMargins isEqual:]
+ -[LNSnippetContentMargins leading]
+ -[LNSnippetContentMargins top]
+ -[LNSnippetContentMargins trailing]
+ -[LNSnippetEnvironment contentMargins]
+ -[LNSnippetEnvironment initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:]
+ -[LNSnippetEnvironment initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:textStyles:]
+ -[LNSnippetEnvironment initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:textStyles:contentMargins:]
+ -[LNSnippetEnvironment interfaceIdiom]
+ -[LNSnippetEnvironment textStyles]
+ -[LNSnippetTextStyleSpecification .cxx_destruct]
+ -[LNSnippetTextStyleSpecification baseTextStyle]
+ -[LNSnippetTextStyleSpecification encodeWithCoder:]
+ -[LNSnippetTextStyleSpecification hash]
+ -[LNSnippetTextStyleSpecification initWithCoder:]
+ -[LNSnippetTextStyleSpecification initWithSize:weight:lineHeight:]
+ -[LNSnippetTextStyleSpecification initWithSize:weight:lineHeight:baseTextStyle:tightLeading:]
+ -[LNSnippetTextStyleSpecification isEqual:]
+ -[LNSnippetTextStyleSpecification lineHeight]
+ -[LNSnippetTextStyleSpecification size]
+ -[LNSnippetTextStyleSpecification tightLeading]
+ -[LNSnippetTextStyleSpecification weight]
+ GCC_except_table1003
+ GCC_except_table1048
+ GCC_except_table1054
+ GCC_except_table1056
+ GCC_except_table1074
+ GCC_except_table1144
+ GCC_except_table1147
+ GCC_except_table1149
+ GCC_except_table1159
+ GCC_except_table1160
+ GCC_except_table1163
+ GCC_except_table1171
+ GCC_except_table1197
+ GCC_except_table1213
+ GCC_except_table1215
+ GCC_except_table1216
+ GCC_except_table1217
+ GCC_except_table1249
+ GCC_except_table1253
+ GCC_except_table1257
+ GCC_except_table1261
+ GCC_except_table1287
+ GCC_except_table1288
+ GCC_except_table1289
+ GCC_except_table1296
+ GCC_except_table1304
+ GCC_except_table1305
+ GCC_except_table1306
+ GCC_except_table1307
+ GCC_except_table1322
+ GCC_except_table1346
+ GCC_except_table1363
+ GCC_except_table1387
+ GCC_except_table1428
+ GCC_except_table1451
+ GCC_except_table1455
+ GCC_except_table1632
+ GCC_except_table1735
+ GCC_except_table1746
+ GCC_except_table1771
+ GCC_except_table1801
+ GCC_except_table1804
+ GCC_except_table1809
+ GCC_except_table1810
+ GCC_except_table1813
+ GCC_except_table1815
+ GCC_except_table1816
+ GCC_except_table1954
+ GCC_except_table1965
+ GCC_except_table1974
+ GCC_except_table2014
+ GCC_except_table2026
+ GCC_except_table2042
+ GCC_except_table2095
+ GCC_except_table2136
+ GCC_except_table2138
+ GCC_except_table2140
+ GCC_except_table2152
+ GCC_except_table2164
+ GCC_except_table2176
+ GCC_except_table2188
+ GCC_except_table2204
+ GCC_except_table2215
+ GCC_except_table2239
+ GCC_except_table2261
+ GCC_except_table2275
+ GCC_except_table2285
+ GCC_except_table2297
+ GCC_except_table2324
+ GCC_except_table2338
+ GCC_except_table2349
+ GCC_except_table2375
+ GCC_except_table2376
+ GCC_except_table2386
+ GCC_except_table2395
+ GCC_except_table2686
+ GCC_except_table3144
+ GCC_except_table3149
+ GCC_except_table3154
+ GCC_except_table3292
+ GCC_except_table3304
+ GCC_except_table3354
+ GCC_except_table3359
+ GCC_except_table3363
+ GCC_except_table3376
+ GCC_except_table3400
+ GCC_except_table3404
+ GCC_except_table3538
+ GCC_except_table3553
+ GCC_except_table641
+ GCC_except_table650
+ GCC_except_table662
+ GCC_except_table663
+ GCC_except_table668
+ GCC_except_table673
+ GCC_except_table678
+ GCC_except_table683
+ GCC_except_table687
+ GCC_except_table688
+ GCC_except_table695
+ GCC_except_table700
+ GCC_except_table705
+ GCC_except_table710
+ GCC_except_table711
+ GCC_except_table715
+ GCC_except_table720
+ GCC_except_table725
+ GCC_except_table730
+ GCC_except_table741
+ GCC_except_table764
+ GCC_except_table778
+ GCC_except_table787
+ GCC_except_table792
+ GCC_except_table797
+ GCC_except_table801
+ GCC_except_table811
+ GCC_except_table814
+ GCC_except_table819
+ GCC_except_table824
+ GCC_except_table829
+ GCC_except_table834
+ GCC_except_table839
+ GCC_except_table844
+ GCC_except_table845
+ GCC_except_table849
+ GCC_except_table850
+ GCC_except_table854
+ GCC_except_table855
+ GCC_except_table859
+ GCC_except_table860
+ GCC_except_table864
+ GCC_except_table871
+ GCC_except_table876
+ GCC_except_table881
+ GCC_except_table886
+ _LNSnippetTextStyleBody
+ _LNSnippetTextStyleCallout
+ _LNSnippetTextStyleCaption
+ _LNSnippetTextStyleCaption2
+ _LNSnippetTextStyleFootnote
+ _LNSnippetTextStyleHeadline
+ _LNSnippetTextStyleLargeTitle
+ _LNSnippetTextStyleSubheadline
+ _LNSnippetTextStyleTitle
+ _LNSnippetTextStyleTitle2
+ _LNSnippetTextStyleTitle3
+ _OBJC_CLASS_$_LNRecurrenceRuleBridge
+ _OBJC_CLASS_$_LNSnippetContentMargins
+ _OBJC_CLASS_$_LNSnippetTextStyleSpecification
+ _OBJC_CLASS_$_SNAAssertion
+ _OBJC_CLASS_$_SNAAssertionTarget
+ _OBJC_IVAR_$_LNActionExecutor._liveActivityAssertion
+ _OBJC_IVAR_$_LNRegisteredBundleMetadata._codeSignatureValidationCategory
+ _OBJC_IVAR_$_LNRegisteredBundleMetadata._quarantineStatus
+ _OBJC_IVAR_$_LNSnippetContentMargins._bottom
+ _OBJC_IVAR_$_LNSnippetContentMargins._leading
+ _OBJC_IVAR_$_LNSnippetContentMargins._top
+ _OBJC_IVAR_$_LNSnippetContentMargins._trailing
+ _OBJC_IVAR_$_LNSnippetEnvironment._contentMargins
+ _OBJC_IVAR_$_LNSnippetEnvironment._interfaceIdiom
+ _OBJC_IVAR_$_LNSnippetEnvironment._textStyles
+ _OBJC_IVAR_$_LNSnippetTextStyleSpecification._baseTextStyle
+ _OBJC_IVAR_$_LNSnippetTextStyleSpecification._lineHeight
+ _OBJC_IVAR_$_LNSnippetTextStyleSpecification._size
+ _OBJC_IVAR_$_LNSnippetTextStyleSpecification._tightLeading
+ _OBJC_IVAR_$_LNSnippetTextStyleSpecification._weight
+ _OBJC_METACLASS_$_LNSnippetContentMargins
+ _OBJC_METACLASS_$_LNSnippetTextStyleSpecification
+ __DATA__TtCO12LinkServices27LNRecurrenceRuleDescriptionP33_03FA4C28A8965BB29D54C9498E01DB302__
+ __METACLASS_DATA__TtCO12LinkServices27LNRecurrenceRuleDescriptionP33_03FA4C28A8965BB29D54C9498E01DB302__
+ __OBJC_$_CLASS_METHODS_LNSnippetContentMargins
+ __OBJC_$_CLASS_METHODS_LNSnippetTextStyleSpecification
+ __OBJC_$_CLASS_PROP_LIST_LNSnippetContentMargins
+ __OBJC_$_CLASS_PROP_LIST_LNSnippetTextStyleSpecification
+ __OBJC_$_INSTANCE_METHODS_LNSnippetContentMargins
+ __OBJC_$_INSTANCE_METHODS_LNSnippetTextStyleSpecification
+ __OBJC_$_INSTANCE_VARIABLES_LNSnippetContentMargins
+ __OBJC_$_INSTANCE_VARIABLES_LNSnippetTextStyleSpecification
+ __OBJC_$_PROP_LIST_LNSnippetContentMargins
+ __OBJC_$_PROP_LIST_LNSnippetTextStyleSpecification
+ __OBJC_CLASS_PROTOCOLS_$_LNSnippetContentMargins
+ __OBJC_CLASS_PROTOCOLS_$_LNSnippetTextStyleSpecification
+ __OBJC_CLASS_RO_$_LNSnippetContentMargins
+ __OBJC_CLASS_RO_$_LNSnippetTextStyleSpecification
+ __OBJC_METACLASS_RO_$_LNSnippetContentMargins
+ __OBJC_METACLASS_RO_$_LNSnippetTextStyleSpecification
+ ___44-[LNActionExecutor performWithoutValidation]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e34_v24?0"SNAAssertion"8"NSError"16l
+ _objc_msgSend$baseTextStyle
+ _objc_msgSend$bottom
+ _objc_msgSend$codeSignatureValidationCategory
+ _objc_msgSend$contentMargins
+ _objc_msgSend$decodeDictionaryWithKeysOfClass:objectsOfClass:forKey:
+ _objc_msgSend$didInvalidateLiveActivityBackgroundAssertion:error:
+ _objc_msgSend$initWithBundleIdentifier:installIdentifier:codeSignatureValidationCategory:
+ _objc_msgSend$initWithBundleIdentifier:installIdentifier:codeSignatureValidationCategory:quarantineStatus:
+ _objc_msgSend$initWithExplanation:target:invalidationHandler:
+ _objc_msgSend$initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:
+ _objc_msgSend$initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:textStyles:
+ _objc_msgSend$initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:interfaceIdiom:textStyles:contentMargins:
+ _objc_msgSend$initWithSize:weight:lineHeight:baseTextStyle:tightLeading:
+ _objc_msgSend$initWithTop:leading:bottom:trailing:
+ _objc_msgSend$invalidationReason
+ _objc_msgSend$leading
+ _objc_msgSend$lineHeight
+ _objc_msgSend$liveActivityAssertion
+ _objc_msgSend$quarantineStatus
+ _objc_msgSend$sessionIdentifiers
+ _objc_msgSend$setLiveActivityAssertion:
+ _objc_msgSend$setStartedLiveActivity:
+ _objc_msgSend$textStyles
+ _objc_msgSend$tightLeading
+ _objc_msgSend$top
+ _objc_msgSend$trailing
+ _objc_msgSend$weight
+ _swift_stdlib_random
+ _symbolic _____ 12LinkServices27LNRecurrenceRuleDescriptionO
+ _symbolic _____ 12LinkServices27LNRecurrenceRuleDescriptionO2__33_03FA4C28A8965BB29D54C9498E01DB30LLC
+ _symbolic _____Sg 10Foundation8CalendarV14RecurrenceRuleV
+ _symbolic _____ySiG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____SaySSGG 10Foundation15ListFormatStyleV AA06StringD0V
+ _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV0B4TypeO AA06StringD0V
+ _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV5WidthO AA06StringD0V
- +[LNFeatureFlags isSnippetContentLayersEnabled]
- +[LNFeatureFlags resetSnippetContentLayersOverride]
- +[LNFeatureFlags setIsSnippetContentLayersEnabled:]
- GCC_except_table1019
- GCC_except_table1025
- GCC_except_table1027
- GCC_except_table1045
- GCC_except_table1115
- GCC_except_table1118
- GCC_except_table1120
- GCC_except_table1130
- GCC_except_table1131
- GCC_except_table1134
- GCC_except_table1142
- GCC_except_table1168
- GCC_except_table1184
- GCC_except_table1186
- GCC_except_table1187
- GCC_except_table1188
- GCC_except_table1220
- GCC_except_table1224
- GCC_except_table1228
- GCC_except_table1232
- GCC_except_table1258
- GCC_except_table1259
- GCC_except_table1260
- GCC_except_table1267
- GCC_except_table1275
- GCC_except_table1276
- GCC_except_table1277
- GCC_except_table1278
- GCC_except_table1293
- GCC_except_table1317
- GCC_except_table1334
- GCC_except_table1358
- GCC_except_table1399
- GCC_except_table1422
- GCC_except_table1426
- GCC_except_table1603
- GCC_except_table1703
- GCC_except_table1714
- GCC_except_table1739
- GCC_except_table1750
- GCC_except_table1769
- GCC_except_table1772
- GCC_except_table1777
- GCC_except_table1778
- GCC_except_table1780
- GCC_except_table1781
- GCC_except_table1920
- GCC_except_table1931
- GCC_except_table1940
- GCC_except_table1958
- GCC_except_table1980
- GCC_except_table2008
- GCC_except_table2061
- GCC_except_table2096
- GCC_except_table2102
- GCC_except_table2104
- GCC_except_table2106
- GCC_except_table2118
- GCC_except_table2142
- GCC_except_table2154
- GCC_except_table2170
- GCC_except_table2181
- GCC_except_table2193
- GCC_except_table2205
- GCC_except_table2217
- GCC_except_table2241
- GCC_except_table2263
- GCC_except_table2290
- GCC_except_table2304
- GCC_except_table2315
- GCC_except_table2327
- GCC_except_table2341
- GCC_except_table2342
- GCC_except_table2352
- GCC_except_table2652
- GCC_except_table3110
- GCC_except_table3115
- GCC_except_table3120
- GCC_except_table3254
- GCC_except_table3266
- GCC_except_table3316
- GCC_except_table3321
- GCC_except_table3325
- GCC_except_table3338
- GCC_except_table3362
- GCC_except_table3366
- GCC_except_table3503
- GCC_except_table3518
- GCC_except_table612
- GCC_except_table621
- GCC_except_table625
- GCC_except_table633
- GCC_except_table634
- GCC_except_table639
- GCC_except_table643
- GCC_except_table644
- GCC_except_table648
- GCC_except_table649
- GCC_except_table653
- GCC_except_table658
- GCC_except_table659
- GCC_except_table666
- GCC_except_table667
- GCC_except_table671
- GCC_except_table676
- GCC_except_table681
- GCC_except_table686
- GCC_except_table691
- GCC_except_table712
- GCC_except_table749
- GCC_except_table758
- GCC_except_table763
- GCC_except_table768
- GCC_except_table772
- GCC_except_table776
- GCC_except_table777
- GCC_except_table781
- GCC_except_table782
- GCC_except_table785
- GCC_except_table786
- GCC_except_table790
- GCC_except_table791
- GCC_except_table795
- GCC_except_table796
- GCC_except_table800
- GCC_except_table816
- GCC_except_table821
- GCC_except_table826
- GCC_except_table830
- GCC_except_table831
- GCC_except_table842
- GCC_except_table847
- GCC_except_table852
- GCC_except_table857
- GCC_except_table974
- __kLSOpenOptionOverrideBackgroundPriorityDomainNameKey
- _isSnippetContentLayersOverride
- _objc_msgSend$dictionaryWithDictionary:
- _objc_msgSend$initWithBundleIdentifier:installIdentifier:
- _objc_msgSend$isSnippetContentLayersEnabled
CStrings:
+ "#"
+ "%@ is running an App Intent (%@::%@) that may start a session"
+ "%{public}@"
+ "%{public}@ with error: %{public}@."
+ "<%@: %p, bundleIdentifier: %@, installIdentifier: %@, codeSignatureValidationCategory: %@, quarantineStatus: %@>"
+ "Client process is not entitled to allow applications to start Live Activities."
+ "Live Activity assertion invalidated"
+ "Reached the limit of %ld execution events for this process"
+ "Recurrence rule has no dialog description"
+ "Requested a Live Activity assertion for %@::%@"
+ "ad-hoc"
+ "baseTextStyle"
+ "body"
+ "bottom"
+ "callout"
+ "caption"
+ "caption2"
+ "codeSignatureValidationCategory"
+ "com.apple.generativeassistanttools."
+ "com.apple.private.sessionkit.assertionRequester"
+ "com.apple.sessionservices"
+ "contentMargins"
+ "development"
+ "footnote"
+ "headline"
+ "largeTitle"
+ "leading"
+ "lineHeight"
+ "not quarantined"
+ "platform"
+ "quarantineStatus"
+ "quarantined"
+ "subheadline"
+ "testflight"
+ "textStyles"
+ "tightLeading"
+ "title2"
+ "title3"
+ "top"
+ "trailing"
+ "unverified"
+ "v24@?0@\"SNAAssertion\"8@\"NSError\"16"
+ "weight"
- "<%@: %p, bundleIdentifier: %@, installIdentifier: %@>"
- "LaunchRoleUserInteractiveNonFocal"
- "Snippet Content Layers"
- "snippetContentLayers"
```
