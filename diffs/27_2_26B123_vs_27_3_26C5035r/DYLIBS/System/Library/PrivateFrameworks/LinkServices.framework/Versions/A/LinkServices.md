## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/Versions/A/LinkServices`

```diff

-301.1.16.0.0
-  __TEXT.__text: 0x14d754
-  __TEXT.__objc_methlist: 0xaed0
-  __TEXT.__dlopen_cstrs: 0x5ba
-  __TEXT.__const: 0x77f8
-  __TEXT.__constg_swiftt: 0x1afc
-  __TEXT.__swift5_typeref: 0x2ec8
+301.2.7.2.0
+  __TEXT.__text: 0x150238
+  __TEXT.__objc_methlist: 0xae80
+  __TEXT.__dlopen_cstrs: 0x605
+  __TEXT.__const: 0x7818
+  __TEXT.__constg_swiftt: 0x1b28
+  __TEXT.__swift5_typeref: 0x2f0c
   __TEXT.__swift5_builtin: 0x258
-  __TEXT.__swift5_reflstr: 0xe3c
-  __TEXT.__swift5_fieldmd: 0x11a8
+  __TEXT.__swift5_reflstr: 0xe6c
+  __TEXT.__swift5_fieldmd: 0x11d8
   __TEXT.__swift5_assocty: 0x2b8
-  __TEXT.__cstring: 0xc7ff
+  __TEXT.__cstring: 0xc96d
   __TEXT.__swift5_proto: 0x284
   __TEXT.__swift5_types: 0x1a0
   __TEXT.__swift5_protos: 0x44
-  __TEXT.__swift5_capture: 0x12a0
-  __TEXT.__oslogstring: 0x97a2
+  __TEXT.__swift5_capture: 0x12b8
+  __TEXT.__oslogstring: 0x99f6
   __TEXT.__swift_as_entry: 0x114
   __TEXT.__swift_as_ret: 0x130
   __TEXT.__swift_as_cont: 0x1c4
   __TEXT.__swift5_mpenum: 0x68
-  __TEXT.__gcc_except_tab: 0x1dcc
-  __TEXT.__unwind_info: 0x69c0
-  __TEXT.__eh_frame: 0x4b40
+  __TEXT.__gcc_except_tab: 0x1e0c
+  __TEXT.__unwind_info: 0x6a48
+  __TEXT.__eh_frame: 0x4bb8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe40
-  __DATA_CONST.__objc_classlist: 0x878
+  __DATA_CONST.__const: 0xe68
+  __DATA_CONST.__objc_classlist: 0x868
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5230
+  __DATA_CONST.__objc_selrefs: 0x5290
   __DATA_CONST.__objc_protorefs: 0x100
-  __DATA_CONST.__objc_superrefs: 0x5f8
+  __DATA_CONST.__objc_superrefs: 0x5e8
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x1930
-  __AUTH_CONST.__const: 0x81b8
-  __AUTH_CONST.__cfstring: 0x8d60
-  __AUTH_CONST.__objc_const: 0x16840
+  __DATA_CONST.__got: 0x1950
+  __AUTH_CONST.__const: 0x8240
+  __AUTH_CONST.__cfstring: 0x8dc0
+  __AUTH_CONST.__objc_const: 0x166d8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1710
-  __AUTH.__objc_data: 0x3e18
-  __AUTH.__data: 0x12b0
-  __DATA.__objc_ivar: 0xad8
-  __DATA.__data: 0x2738
-  __DATA.__bss: 0x47d8
+  __AUTH_CONST.__auth_got: 0x1728
+  __AUTH.__objc_data: 0x3e00
+  __AUTH.__data: 0x12a0
+  __DATA.__objc_ivar: 0xacc
+  __DATA.__data: 0x2768
+  __DATA.__bss: 0x47f8
   __DATA.__common: 0x78
-  __DATA_DIRTY.__objc_data: 0x23a0
-  __DATA_DIRTY.__data: 0x68
+  __DATA_DIRTY.__objc_data: 0x2350
+  __DATA_DIRTY.__data: 0x78
   __DATA_DIRTY.__bss: 0x2b0
   - /System/Library/Frameworks/AppIntentsTypeSupport.framework/Versions/A/AppIntentsTypeSupport
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8817
-  Symbols:   11313
-  CStrings:  2221
+  Functions: 8859
+  Symbols:   11321
+  CStrings:  2238
 
Symbols:
+ +[LNFeatureFlags isSideEffectConfirmationSPIEnabled]
+ +[LNFeatureFlags isSnippetContentLayersEnabled]
+ +[LNFeatureFlags resetSideEffectConfirmationSPIOverride]
+ +[LNFeatureFlags resetSnippetContentLayersOverride]
+ +[LNFeatureFlags setIsSideEffectConfirmationSPIEnabled:]
+ +[LNFeatureFlags setIsSnippetContentLayersEnabled:]
+ -[LNActionExecutor linkUndoManagerToMainAppIfNecessary:undoToken:completionHandler:]
+ -[LNActionExecutorOptions setSideEffectConfirmationDeferredToApp:]
+ -[LNActionExecutorOptions sideEffectConfirmationDeferredToApp]
+ -[LNMetadataProvider bundlesWithSkillsWithError:]
+ -[LNMetadataProvider skillForBundleIdentifier:skillName:error:]
+ -[LNMetadataProvider skillsForBundleIdentifier:error:]
+ -[LNPerformActionConnectionOperation actionGrantingColorBundleAccessToRecipient]
+ -[LNSnippetEnvironment initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:]
+ -[LNSnippetEnvironment supportsContentLayers]
+ -[LNSpotlightCascadeTranslator createMessageAttributesFromAttributeSet:options:error:]
+ -[LNSpotlightCascadeTranslator createSpotlightDefinedAttributesFromAttributeSet:options:error:]
+ -[LNSpotlightCascadeTranslator translateSpotlightPersonWithAttributeKey:fromAttributeSet:options:error:]
+ GCC_except_table1019
+ GCC_except_table1025
+ GCC_except_table1027
+ GCC_except_table1045
+ GCC_except_table1118
+ GCC_except_table1120
+ GCC_except_table1130
+ GCC_except_table1131
+ GCC_except_table1134
+ GCC_except_table1142
+ GCC_except_table1168
+ GCC_except_table1184
+ GCC_except_table1186
+ GCC_except_table1187
+ GCC_except_table1188
+ GCC_except_table1220
+ GCC_except_table1224
+ GCC_except_table1228
+ GCC_except_table1232
+ GCC_except_table1258
+ GCC_except_table1259
+ GCC_except_table1260
+ GCC_except_table1267
+ GCC_except_table1275
+ GCC_except_table1276
+ GCC_except_table1277
+ GCC_except_table1278
+ GCC_except_table1293
+ GCC_except_table1317
+ GCC_except_table1334
+ GCC_except_table1358
+ GCC_except_table1399
+ GCC_except_table1422
+ GCC_except_table1426
+ GCC_except_table1603
+ GCC_except_table1703
+ GCC_except_table1714
+ GCC_except_table1739
+ GCC_except_table1750
+ GCC_except_table1769
+ GCC_except_table1778
+ GCC_except_table1780
+ GCC_except_table1781
+ GCC_except_table1782
+ GCC_except_table1920
+ GCC_except_table1931
+ GCC_except_table1940
+ GCC_except_table1958
+ GCC_except_table1980
+ GCC_except_table1992
+ GCC_except_table2008
+ GCC_except_table2061
+ GCC_except_table2102
+ GCC_except_table2104
+ GCC_except_table2106
+ GCC_except_table2118
+ GCC_except_table2130
+ GCC_except_table2142
+ GCC_except_table2154
+ GCC_except_table2170
+ GCC_except_table2181
+ GCC_except_table2193
+ GCC_except_table2205
+ GCC_except_table2217
+ GCC_except_table2227
+ GCC_except_table2241
+ GCC_except_table2251
+ GCC_except_table2263
+ GCC_except_table2290
+ GCC_except_table2304
+ GCC_except_table2315
+ GCC_except_table2327
+ GCC_except_table2341
+ GCC_except_table2342
+ GCC_except_table2352
+ GCC_except_table2361
+ GCC_except_table2652
+ GCC_except_table3110
+ GCC_except_table3115
+ GCC_except_table3120
+ GCC_except_table3254
+ GCC_except_table3266
+ GCC_except_table3316
+ GCC_except_table3321
+ GCC_except_table3325
+ GCC_except_table3338
+ GCC_except_table3362
+ GCC_except_table3366
+ GCC_except_table3503
+ GCC_except_table3518
+ GCC_except_table612
+ GCC_except_table621
+ GCC_except_table625
+ GCC_except_table633
+ GCC_except_table634
+ GCC_except_table639
+ GCC_except_table643
+ GCC_except_table648
+ GCC_except_table649
+ GCC_except_table653
+ GCC_except_table658
+ GCC_except_table666
+ GCC_except_table667
+ GCC_except_table671
+ GCC_except_table672
+ GCC_except_table676
+ GCC_except_table681
+ GCC_except_table686
+ GCC_except_table691
+ GCC_except_table696
+ GCC_except_table701
+ GCC_except_table706
+ GCC_except_table712
+ GCC_except_table735
+ GCC_except_table749
+ GCC_except_table758
+ GCC_except_table763
+ GCC_except_table776
+ GCC_except_table785
+ GCC_except_table790
+ GCC_except_table795
+ GCC_except_table800
+ GCC_except_table805
+ GCC_except_table810
+ GCC_except_table815
+ GCC_except_table820
+ GCC_except_table825
+ GCC_except_table830
+ GCC_except_table835
+ GCC_except_table842
+ GCC_except_table847
+ GCC_except_table852
+ GCC_except_table857
+ GCC_except_table974
+ _LNConsumeSandboxExtensionToken
+ _LNSpotlightAppEntityKeyDisplayRepresentationImageColorization
+ _LNStaticDefaultValueForColor
+ _MDItemMessageRead
+ _NSSelectorFromString
+ _OBJC_CLASS_$_LNColor
+ _OBJC_CLASS_$_LNSkillMetadata
+ _OBJC_IVAR_$_LNActionExecutorOptions._sideEffectConfirmationDeferredToApp
+ _OBJC_IVAR_$_LNSnippetEnvironment._supportsContentLayers
+ ___49-[LNMetadataProvider bundlesWithSkillsWithError:]_block_invoke
+ ___49-[LNMetadataProvider bundlesWithSkillsWithError:]_block_invoke_2
+ ___49-[LNMetadataProvider bundlesWithSkillsWithError:]_block_invoke_3
+ ___49-[LNMetadataProvider bundlesWithSkillsWithError:]_block_invoke_4
+ ___54-[LNMetadataProvider skillsForBundleIdentifier:error:]_block_invoke
+ ___54-[LNMetadataProvider skillsForBundleIdentifier:error:]_block_invoke_2
+ ___54-[LNMetadataProvider skillsForBundleIdentifier:error:]_block_invoke_3
+ ___54-[LNMetadataProvider skillsForBundleIdentifier:error:]_block_invoke_4
+ ___63-[LNMetadataProvider skillForBundleIdentifier:skillName:error:]_block_invoke
+ ___63-[LNMetadataProvider skillForBundleIdentifier:skillName:error:]_block_invoke_2
+ ___63-[LNMetadataProvider skillForBundleIdentifier:skillName:error:]_block_invoke_3
+ ___63-[LNMetadataProvider skillForBundleIdentifier:skillName:error:]_block_invoke_4
+ ___80-[LNPerformActionConnectionOperation actionGrantingColorBundleAccessToRecipient]_block_invoke
+ ___84-[LNActionExecutor linkUndoManagerToMainAppIfNecessary:undoToken:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e37_v24?0"LNSkillMetadata"8"NSError"16l
+ ___block_descriptor_90_e8_32s40s48s56s64s72s80s_e5_v8?0l
+ __kLSOpenOptionOverrideBackgroundPriorityDomainNameKey
+ _actionGrantingColorBundleAccessToRecipient.grantSelector
+ _actionGrantingColorBundleAccessToRecipient.onceToken
+ _isSideEffectConfirmationSPIOverride
+ _isSnippetContentLayersOverride
+ _objc_msgSend$actionGrantingColorBundleAccessToRecipient
+ _objc_msgSend$bundlesWithSkillsWithReply:
+ _objc_msgSend$createMessageAttributesFromAttributeSet:options:error:
+ _objc_msgSend$createSpotlightDefinedAttributesFromAttributeSet:options:error:
+ _objc_msgSend$deferConfirmationToApp
+ _objc_msgSend$dictionaryWithDictionary:
+ _objc_msgSend$fetchEntitySnippetForValue:snippetType:environment:completionHandler:
+ _objc_msgSend$hasConfirmationHandlerClosure
+ _objc_msgSend$initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:supportsContentLayers:
+ _objc_msgSend$isSideEffectConfirmationSPIEnabled
+ _objc_msgSend$isSnippetContentLayersEnabled
+ _objc_msgSend$linkAppUndoManager:undoToken:completionHandler:
+ _objc_msgSend$linkUndoManager:undoToken:completionHandler:
+ _objc_msgSend$linkUndoManagerToMainAppIfNecessary:undoToken:completionHandler:
+ _objc_msgSend$ln_valueWithColor:
+ _objc_msgSend$setSideEffectConfirmationDeferredToApp:
+ _objc_msgSend$sideEffectConfirmationDeferredToApp
+ _objc_msgSend$skillForBundleIdentifier:skillName:reply:
+ _objc_msgSend$skillsForBundleIdentifier:reply:
+ _objc_msgSend$sourceBundleIdentifier
+ _objc_msgSend$supportsContentLayers
+ _objc_msgSend$translateSpotlightPersonWithAttributeKey:fromAttributeSet:options:error:
+ _sandbox_extension_consume
+ _symbolic SDySSSo8LNEntityCG16hydratedEntities_t
+ _symbolic So20LNSnippetEnvironmentCSg
- +[LNIntentEnablement disabledWithReason:]
- +[LNIntentEnablement enabled]
- +[LNIntentEnablement supportsSecureCoding]
- -[LNActionExecutor linkUndoManagerToMainAppIfNecessary:completionHandler:]
- -[LNFetchAppIntentStateConnectionOperation .cxx_destruct]
- -[LNFetchAppIntentStateConnectionOperation appIntentIdentifiers]
- -[LNFetchAppIntentStateConnectionOperation completionHandler]
- -[LNFetchAppIntentStateConnectionOperation finishWithError:]
- -[LNFetchAppIntentStateConnectionOperation initWithConnectionInterface:appIntentIdentifiers:queue:completionHandler:]
- -[LNFetchAppIntentStateConnectionOperation results]
- -[LNFetchAppIntentStateConnectionOperation setAppIntentIdentifiers:]
- -[LNFetchAppIntentStateConnectionOperation setCompletionHandler:]
- -[LNFetchAppIntentStateConnectionOperation setResults:]
- -[LNFetchAppIntentStateConnectionOperation start]
- -[LNIntentEnablement .cxx_destruct]
- -[LNIntentEnablement copyWithZone:]
- -[LNIntentEnablement description]
- -[LNIntentEnablement disabledReason]
- -[LNIntentEnablement encodeWithCoder:]
- -[LNIntentEnablement hash]
- -[LNIntentEnablement initWithCoder:]
- -[LNIntentEnablement initWithValue:disabledReason:]
- -[LNIntentEnablement isEqual:]
- -[LNIntentEnablement value]
- -[LNSpotlightCascadeTranslator createMessageAttributesFromAttributeSet:error:]
- -[LNSpotlightCascadeTranslator createSpotlightDefinedAttributesFromAttributeSet:error:]
- -[LNSpotlightCascadeTranslator translateSpotlightPersonWithAttributeKey:fromAttributeSet:error:]
- GCC_except_table1014
- GCC_except_table1020
- GCC_except_table1022
- GCC_except_table1040
- GCC_except_table1110
- GCC_except_table1113
- GCC_except_table1125
- GCC_except_table1126
- GCC_except_table1129
- GCC_except_table1137
- GCC_except_table1163
- GCC_except_table1179
- GCC_except_table1181
- GCC_except_table1182
- GCC_except_table1183
- GCC_except_table1215
- GCC_except_table1219
- GCC_except_table1223
- GCC_except_table1227
- GCC_except_table1253
- GCC_except_table1254
- GCC_except_table1255
- GCC_except_table1262
- GCC_except_table1270
- GCC_except_table1271
- GCC_except_table1272
- GCC_except_table1273
- GCC_except_table1288
- GCC_except_table1312
- GCC_except_table1329
- GCC_except_table1353
- GCC_except_table1394
- GCC_except_table1417
- GCC_except_table1421
- GCC_except_table1598
- GCC_except_table1698
- GCC_except_table1709
- GCC_except_table1734
- GCC_except_table1745
- GCC_except_table1764
- GCC_except_table1767
- GCC_except_table1773
- GCC_except_table1775
- GCC_except_table1776
- GCC_except_table1913
- GCC_except_table1924
- GCC_except_table1933
- GCC_except_table1951
- GCC_except_table1973
- GCC_except_table1985
- GCC_except_table2001
- GCC_except_table2055
- GCC_except_table2090
- GCC_except_table2098
- GCC_except_table2100
- GCC_except_table2112
- GCC_except_table2124
- GCC_except_table2136
- GCC_except_table2148
- GCC_except_table2160
- GCC_except_table2176
- GCC_except_table2187
- GCC_except_table2199
- GCC_except_table2211
- GCC_except_table2223
- GCC_except_table2233
- GCC_except_table2247
- GCC_except_table2257
- GCC_except_table2269
- GCC_except_table2294
- GCC_except_table2308
- GCC_except_table2319
- GCC_except_table2331
- GCC_except_table2345
- GCC_except_table2346
- GCC_except_table2356
- GCC_except_table2365
- GCC_except_table2654
- GCC_except_table3112
- GCC_except_table3117
- GCC_except_table3122
- GCC_except_table3256
- GCC_except_table3268
- GCC_except_table3318
- GCC_except_table3323
- GCC_except_table3327
- GCC_except_table3340
- GCC_except_table3364
- GCC_except_table3368
- GCC_except_table3499
- GCC_except_table3514
- GCC_except_table610
- GCC_except_table632
- GCC_except_table636
- GCC_except_table645
- GCC_except_table650
- GCC_except_table655
- GCC_except_table660
- GCC_except_table664
- GCC_except_table665
- GCC_except_table669
- GCC_except_table670
- GCC_except_table678
- GCC_except_table683
- GCC_except_table687
- GCC_except_table688
- GCC_except_table692
- GCC_except_table693
- GCC_except_table697
- GCC_except_table702
- GCC_except_table708
- GCC_except_table731
- GCC_except_table745
- GCC_except_table754
- GCC_except_table759
- GCC_except_table764
- GCC_except_table773
- GCC_except_table778
- GCC_except_table787
- GCC_except_table792
- GCC_except_table801
- GCC_except_table802
- GCC_except_table811
- GCC_except_table812
- GCC_except_table817
- GCC_except_table822
- GCC_except_table827
- GCC_except_table838
- GCC_except_table843
- GCC_except_table848
- GCC_except_table853
- GCC_except_table970
- _OBJC_CLASS_$_LNFetchAppIntentStateConnectionOperation
- _OBJC_CLASS_$_LNIntentEnablement
- _OBJC_IVAR_$_LNFetchAppIntentStateConnectionOperation._appIntentIdentifiers
- _OBJC_IVAR_$_LNFetchAppIntentStateConnectionOperation._completionHandler
- _OBJC_IVAR_$_LNFetchAppIntentStateConnectionOperation._results
- _OBJC_IVAR_$_LNIntentEnablement._disabledReason
- _OBJC_IVAR_$_LNIntentEnablement._value
- _OBJC_METACLASS_$_LNFetchAppIntentStateConnectionOperation
- _OBJC_METACLASS_$_LNIntentEnablement
- __OBJC_$_CLASS_METHODS_LNIntentEnablement
- __OBJC_$_CLASS_PROP_LIST_LNIntentEnablement
- __OBJC_$_INSTANCE_METHODS_LNFetchAppIntentStateConnectionOperation
- __OBJC_$_INSTANCE_METHODS_LNIntentEnablement
- __OBJC_$_INSTANCE_VARIABLES_LNFetchAppIntentStateConnectionOperation
- __OBJC_$_INSTANCE_VARIABLES_LNIntentEnablement
- __OBJC_$_PROP_LIST_LNFetchAppIntentStateConnectionOperation
- __OBJC_$_PROP_LIST_LNIntentEnablement
- __OBJC_CLASS_PROTOCOLS_$_LNIntentEnablement
- __OBJC_CLASS_RO_$_LNFetchAppIntentStateConnectionOperation
- __OBJC_CLASS_RO_$_LNIntentEnablement
- __OBJC_METACLASS_RO_$_LNFetchAppIntentStateConnectionOperation
- __OBJC_METACLASS_RO_$_LNIntentEnablement
- ___117-[LNFetchAppIntentStateConnectionOperation initWithConnectionInterface:appIntentIdentifiers:queue:completionHandler:]_block_invoke
- ___49-[LNFetchAppIntentStateConnectionOperation start]_block_invoke
- ___74-[LNActionExecutor linkUndoManagerToMainAppIfNecessary:completionHandler:]_block_invoke
- ___89-[LNConnection(FetchAppIntentState) fetchStateForAppIntentIdentifiers:completionHandler:]_block_invoke
- ___block_descriptor_89_e8_32s40s48s56s64s72s80s_e5_v8?0l
- _objc_msgSend$appIntentIdentifiers
- _objc_msgSend$createMessageAttributesFromAttributeSet:error:
- _objc_msgSend$createSpotlightDefinedAttributesFromAttributeSet:error:
- _objc_msgSend$disabledReason
- _objc_msgSend$fetchStateForAppIntentIdentifiers:completionHandler:
- _objc_msgSend$initWithConnectionInterface:appIntentIdentifiers:queue:completionHandler:
- _objc_msgSend$initWithSize:locale:dynamicTypeSize:legibilityWeight:layoutDirection:colorScheme:colorSchemeContrast:displayScale:displayGamut:accessibilityDifferentiateWithoutColor:accessibilityInvertColors:accessibilityReduceMotion:accessibilityReduceTransparency:
- _objc_msgSend$initWithValue:disabledReason:
- _objc_msgSend$isConditionallyEnabledIntentsEnabled
- _objc_msgSend$linkAppUndoManager:completionHandler:
- _objc_msgSend$linkUndoManager:completionHandler:
- _objc_msgSend$linkUndoManagerToMainAppIfNecessary:completionHandler:
- _objc_msgSend$translateSpotlightPersonWithAttributeKey:fromAttributeSet:error:
CStrings:
+ "-[LNMetadataProvider bundlesWithSkillsWithError:]_block_invoke"
+ "-[LNMetadataProvider skillForBundleIdentifier:skillName:error:]_block_invoke"
+ "-[LNMetadataProvider skillsForBundleIdentifier:error:]_block_invoke"
+ "Failed to consume sandbox extension token: %{darwin.errno}d"
+ "Granted bundle access for %lu color parameter(s) of `%{public}@`"
+ "LaunchRoleUserInteractiveNonFocal"
+ "Pre-confirmation for action %{public}s: metadataBundleIdentifier=%{public}s sourceBundleIdentifier=%{public}s"
+ "Pre-confirmation hydration incomplete for action %{public}s: %{public}ld of %{public}ld entity parameter(s) unresolved (%{public}s)"
+ "Pre-confirmation: deferring to the app's confirmation closure"
+ "Pre-confirmation: deferring to the confirmation closure of action %{public}s in the app"
+ "Pre-confirmation: skipping shared-entity confirmation for action %{public}s without full hydration. Reasons: %{public}s"
+ "Refusing to consume a NULL sandbox extension token"
+ "Side Effect Confirmation SPI"
+ "Snippet Content Layers"
+ "_kMDItemAppEntityDisplayRepresentationImageColorization"
+ "appintents:fetch bundles with skills"
+ "appintents:fetch skill for bundle"
+ "appintents:fetch skills for bundle"
+ "deferToApp"
+ "ln_valueGrantingColorBundleAccessToRecipient:"
+ "sideEffectConfirmationDeferredToApp"
+ "sideEffectConfirmationSPI"
+ "snippetContentLayers"
+ "softlink:o:path:/System/Library/Frameworks/AppIntents.framework/AppIntents"
+ "supportsContentLayers"
+ "v24@?0@\"LNSkillMetadata\"8@\"NSError\"16"
- "<%@: %p, value: %ld, disabledReason: %@>"
- "Conditionally Enabled Intents"
- "Fetching intent state"
- "LNFetchAppIntentStateConnectionOperation.m"
- "Pre-confirmation hydration incomplete for action %{public}s: %{public}ld of %{public}ld entity parameter(s) unresolved (%{public}s); confirming with the generic dialog"
- "appIntentIdentifiers"
- "appintents:fetch intent state"
- "conditionallyEnabledIntents"
- "disabledReason"
```
