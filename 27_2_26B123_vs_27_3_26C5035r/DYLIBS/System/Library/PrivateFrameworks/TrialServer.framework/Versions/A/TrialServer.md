## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/Versions/A/TrialServer`

```diff

-511.1.2.0.0
-  __TEXT.__text: 0x166b48
+511.2.2.0.0
+  __TEXT.__text: 0x167838
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa28
   __TEXT.__lazy_helpers: 0xe8
-  __TEXT.__objc_methlist: 0xc7e4
+  __TEXT.__objc_methlist: 0xc834
   __TEXT.__const: 0xefc
   __TEXT.__dlopen_cstrs: 0x54
-  __TEXT.__cstring: 0x16fcb
+  __TEXT.__cstring: 0x170c6
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x14
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__oslogstring: 0x1e0ea
+  __TEXT.__oslogstring: 0x1e2d2
   __TEXT.__gcc_except_tab: 0x7f58
-  __TEXT.__unwind_info: 0x52b8
+  __TEXT.__unwind_info: 0x52d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1248
+  __DATA_CONST.__const: 0x1268
   __DATA_CONST.__objc_classlist: 0x9c0
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x65a0
+  __DATA_CONST.__objc_selrefs: 0x65d0
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x630
   __DATA_CONST.__objc_arraydata: 0x390
   __DATA_CONST.__got: 0x1438
-  __AUTH_CONST.__const: 0x7a60
-  __AUTH_CONST.__cfstring: 0xf240
-  __AUTH_CONST.__objc_const: 0x18248
+  __AUTH_CONST.__const: 0x7a90
+  __AUTH_CONST.__cfstring: 0xf300
+  __AUTH_CONST.__objc_const: 0x18268
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_arrayobj: 0x360

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x10f0
   __AUTH.__data: 0x6e0
-  __DATA.__objc_ivar: 0x968
+  __DATA.__objc_ivar: 0x96c
   __DATA.__data: 0x2ae8
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xa0

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 5130
-  Symbols:   12230
-  CStrings:  4276
+  Functions: 5140
+  Symbols:   12252
+  CStrings:  4291
 
Symbols:
+ +[TRIExternalConfigurationChangeProcessor processAdsMapsBucketIdChangeIfNecessaryForBucketId:withServerContext:withTaskQueue:]
+ +[TRISystemInfo _adsMapsBucketId:]
+ -[TRIExperimentUpdateProcessor _rewriteActiveFactorProviders]
+ -[TRIExperimentUpdateProcessor initWithServerContext:]
+ -[TRIExperimentUpdateScheduler initWithServerContext:taskQueue:]
+ -[TRINamespaceResolverStorage _overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:factorPackMap:]
+ -[TRINamespaceResolverStorage _processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:setStorage:]
+ -[TRIPersistentUserSettings persistAdsMapsBucketId:]
+ -[TRIPersistentUserSettings persistedAdsMapsBucketId]
+ -[TRISystemConfiguration adsMapsBucketId]
+ -[TRISystemInfo adsMapsBucketId]
+ -[TRISystemInfo setAdsMapsBucketId:]
+ GCC_except_table44
+ _OBJC_IVAR_$_TRIExperimentUpdateProcessor._serverContext
+ _OBJC_IVAR_$_TRISystemInfo._adsMapsBucketId
+ _TRIAdsNamespaceAppStore
+ _TRIAdsNamespaceMaps
+ _TRIPersistentAdsMapsBucket
+ _TRISystemCovariate_AdsMapsBucketId
+ ___261-[TRINamespaceResolverStorage _processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:setStorage:]_block_invoke
+ ___286-[TRINamespaceResolverStorage _overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:factorPackMap:]_block_invoke
+ ___61-[TRIExperimentUpdateProcessor _rewriteActiveFactorProviders]_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104s_e33_v24?0"TRIExperimentRecord"8^B16l
+ ___block_descriptor_56_e8_32s40s48s_e33_v24?0"TRIExperimentRecord"8^B16l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s
+ _objc_msgSend$_adsMapsBucketId:
+ _objc_msgSend$_overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:factorPackMap:
+ _objc_msgSend$_processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:experimentEndDatesMap:setStorage:
+ _objc_msgSend$_rewriteActiveFactorProviders
+ _objc_msgSend$adsMapsBucketId
+ _objc_msgSend$persistAdsMapsBucketId:
+ _objc_msgSend$persistedAdsMapsBucketId
+ _objc_msgSend$processAdsMapsBucketIdChangeIfNecessaryForBucketId:withServerContext:withTaskQueue:
- -[TRIExperimentUpdateProcessor initWithExperimentDatabase:]
- -[TRIExperimentUpdateScheduler experimentDatabase]
- -[TRIExperimentUpdateScheduler initWithExperimentDatabase:taskQueue:]
- -[TRINamespaceResolverStorage _overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:factorPackMap:]
- -[TRINamespaceResolverStorage _processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:setStorage:]
- _OBJC_IVAR_$_TRIExperimentUpdateScheduler._experimentDatabase
- ___239-[TRINamespaceResolverStorage _processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:setStorage:]_block_invoke
- ___264-[TRINamespaceResolverStorage _overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:factorPackMap:]_block_invoke
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96s_e33_v24?0"TRIExperimentRecord"8^B16l
- _objc_msgSend$_overwriteActiveFactorProvidersUsingGlobalPath:withNamespaceMap:rolloutDeploymentMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:factorPackMap:
- _objc_msgSend$_processExperimentRecord:isStaging:namespaceMap:fpNamespaceMap:experimentDeploymentMap:stagedExperimentDeploymentMap:experimentTreatmentMap:treatmentFactorPackSetIdsMap:counterfactualTreatmentsMap:setStorage:
- _objc_msgSend$initWithExperimentDatabase:
CStrings:
+ "+[TRIExternalConfigurationChangeProcessor processAdsMapsBucketIdChangeIfNecessaryForBucketId:withServerContext:withTaskQueue:]"
+ "Ads: maps bucket id: %@"
+ "AdsMapsBucketId"
+ "Experiment %{public}@ has already expired (end date: %{public}@), rejecting end date extension"
+ "MAPS"
+ "Oct 29 2026"
+ "Persisted Ads Maps Bucket Id: %@"
+ "Skipping expired experiment %@ from activeEnvVarNamespaces"
+ "Skipping expired experiment %@ from activeSysctlNamespaces"
+ "Skipping expired experiment from experimentIdsWithEnrollmentAndPostEnrollmentStateAndNamespaceName %{public}@"
+ "TrialXP-511.2.2"
+ "Unable to fetch Ads Maps Bucket Id."
+ "Unable to update the factor providers after experiment end date update."
+ "adsMapsBucketId"
+ "adsMapsBucketId != nil"
+ "com.apple.triald.persisted.Ads.Maps.BucketId"
+ "experimentEndDates"
- "Oct  3 2026"
- "TrialXP-511.1.2"
```
