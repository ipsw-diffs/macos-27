## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Versions/A/Spotlight`

```diff

-2465.1.9.0.0
-  __TEXT.__text: 0xe6f38
-  __TEXT.__objc_methlist: 0x5724
+2465.2.7.400.0
+  __TEXT.__text: 0xe885c
+  __TEXT.__objc_methlist: 0x5864
   __TEXT.__const: 0x2640
-  __TEXT.__gcc_except_tab: 0x43a0
-  __TEXT.__cstring: 0x6ee1
+  __TEXT.__gcc_except_tab: 0x43fc
+  __TEXT.__cstring: 0x6f41
   __TEXT.__oslogstring: 0x5c3f
   __TEXT.__ustring: 0x32
   __TEXT.__constg_swiftt: 0xa3c

   __TEXT.__swift5_capture: 0x6ac
   __TEXT.__swift5_assocty: 0x168
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__unwind_info: 0x30e0
+  __TEXT.__unwind_info: 0x3140
   __TEXT.__eh_frame: 0x1ce8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xd08
-  __DATA_CONST.__objc_classlist: 0x2b8
+  __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4850
-  __DATA_CONST.__objc_superrefs: 0x198
+  __DATA_CONST.__objc_selrefs: 0x48d0
+  __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0xa18
-  __DATA_CONST.__got: 0x15f8
-  __AUTH_CONST.__const: 0x49e8
-  __AUTH_CONST.__cfstring: 0x6fc0
-  __AUTH_CONST.__objc_const: 0x8550
+  __DATA_CONST.__got: 0x1648
+  __AUTH_CONST.__const: 0x4ad8
+  __AUTH_CONST.__cfstring: 0x7020
+  __AUTH_CONST.__objc_const: 0x8928
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x18b8
-  __AUTH.__objc_data: 0x900
+  __AUTH.__objc_data: 0x9f0
   __AUTH.__data: 0x88
-  __DATA.__objc_ivar: 0x608
+  __DATA.__objc_ivar: 0x634
   __DATA.__data: 0xc80
   __DATA.__bss: 0x2600
   __DATA.__common: 0x8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3507
-  Symbols:   6882
-  CStrings:  1528
+  Functions: 3540
+  Symbols:   6972
+  CStrings:  1532
 
Symbols:
+ +[SPBundleFilter applyFiltering:context:completionHandler:]
+ +[SPBundleFilter currentQueryFilters]
+ -[SPBundleFilterQueryFilters .cxx_destruct]
+ -[SPBundleFilterQueryFilters disabledBundleIdentifiers]
+ -[SPBundleFilterQueryFilters disabledFileProviderFilePaths]
+ -[SPBundleFilterQueryFilters filterQueries]
+ -[SPBundleFilterQueryFilters initWithFilterQueries:disabledBundleIdentifiers:disabledFileProviderFilePaths:]
+ -[SPBundleFilterResolvedDimensions blockedSet]
+ -[SPBundleFilterResolvedDimensions disableSearchInSpotlightExemptions]
+ -[SPBundleFilterResolvedDimensions verdicts]
+ -[SPBundleFilterVerdictStore .cxx_destruct]
+ -[SPBundleFilterVerdictStore init]
+ -[SPBundleFilterVerdictStore resultForItem:]
+ -[SPBundleFilterVerdictStore setResult:forItem:]
+ -[SPBundleFilteringContext blockedAppBundleIDs]
+ -[SPBundleFilteringContext disableSearchInSpotlightExemptions]
+ -[SPBundleFilteringContext setBlockedAppBundleIDs:]
+ -[SPBundleFilteringContext setDisableSearchInSpotlightExemptions:]
+ -[SPBundleFilteringContext setTimeout:]
+ -[SPBundleFilteringContext timeout]
+ -[SPBundleFilteringResult .cxx_destruct]
+ -[SPBundleFilteringResult initWithVerdicts:]
+ -[SPBundleFilteringResult verdictAtIndex:]
+ -[SPBundleFilteringResult verdicts]
+ GCC_except_table100
+ GCC_except_table76
+ GCC_except_table98
+ _OBJC_CLASS_$_SPBundleFilterQueryFilters
+ _OBJC_CLASS_$_SPBundleFilterVerdictStore
+ _OBJC_CLASS_$_SPBundleFilteringResult
+ _OBJC_IVAR_$_SPBundleFilterQueryFilters._disabledBundleIdentifiers
+ _OBJC_IVAR_$_SPBundleFilterQueryFilters._disabledFileProviderFilePaths
+ _OBJC_IVAR_$_SPBundleFilterQueryFilters._filterQueries
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._blockedSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._disableSearchInSpotlightExemptions
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._verdicts
+ _OBJC_IVAR_$_SPBundleFilterVerdictStore._results
+ _OBJC_IVAR_$_SPBundleFilteringContext._blockedAppBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._disableSearchInSpotlightExemptions
+ _OBJC_IVAR_$_SPBundleFilteringContext._timeout
+ _OBJC_IVAR_$_SPBundleFilteringResult._verdicts
+ _OBJC_METACLASS_$_SPBundleFilterQueryFilters
+ _OBJC_METACLASS_$_SPBundleFilterVerdictStore
+ _OBJC_METACLASS_$_SPBundleFilteringResult
+ _SPBundleFilterAllowedSetForOwnBundleID
+ _SPBundleFilterFinalizeUnevaluated
+ _SPBundleFilterRun
+ _SSApplicationBundleIdGeneralApplication
+ _SSCalendarAppBundleIdentifier
+ _SSCalendarBundleIdentifier
+ _SSContactsAppBundleIdentifier
+ _SSContactsDBundleIdentifier
+ _SSSafariBundleIdentifier
+ _SSTipsBundleIdentifier
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilterQueryFilters
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilterVerdictStore
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilteringResult
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilterQueryFilters
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilterVerdictStore
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilteringResult
+ __OBJC_$_PROP_LIST_SPBundleFilterQueryFilters
+ __OBJC_$_PROP_LIST_SPBundleFilteringResult
+ __OBJC_CLASS_RO_$_SPBundleFilterQueryFilters
+ __OBJC_CLASS_RO_$_SPBundleFilterVerdictStore
+ __OBJC_CLASS_RO_$_SPBundleFilteringResult
+ __OBJC_METACLASS_RO_$_SPBundleFilterQueryFilters
+ __OBJC_METACLASS_RO_$_SPBundleFilterVerdictStore
+ __OBJC_METACLASS_RO_$_SPBundleFilteringResult
+ ___41+[SPBundleFilter applyFiltering:context:]_block_invoke
+ ___59+[SPBundleFilter applyFiltering:context:completionHandler:]_block_invoke
+ ___SPBundleFilterRunServerXPCStep_block_invoke
+ ___SPBundleFilterRun_block_invoke
+ ___SPBundleFilterSendServerXPCRequest_block_invoke
+ ___block_descriptor_40_e8_32bs_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e48_v24?0"SPBundleFilterVerdictStore"8"NSError"16l
+ ___block_descriptor_56_e8_32bs40r48r_e39_v16?0"CSBundleFilterEvaluationReply"8l
+ ___block_descriptor_56_e8_32s40r48r_e48_v24?0"SPBundleFilterVerdictStore"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e39_v16?0"CSBundleFilterEvaluationReply"8l
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8l
+ ___copy_helper_block_e8_32b40r48r
+ ___copy_helper_block_e8_32s40s48b
+ _objc_msgSend$accountIdentifier
+ _objc_msgSend$blockedAppBundleIDs
+ _objc_msgSend$blockedSet
+ _objc_msgSend$disableSearchInSpotlightExemptions
+ _objc_msgSend$fileProviderBundleIDs
+ _objc_msgSend$initWithFileProviderContainerGroups:fileProviderExcludedBundleIDs:fileProviderAllowedBundleIDs:needsAppProtectionBundleIDs:needsMDMRestrictedBundleIDs:needsExcludedAppBundleIDs:attributeBackfillGroups:
+ _objc_msgSend$initWithFilterQueries:disabledBundleIdentifiers:disabledFileProviderFilePaths:
+ _objc_msgSend$initWithVerdicts:
+ _objc_msgSend$mapTableWithKeyOptions:valueOptions:
+ _objc_msgSend$messageType
+ _objc_msgSend$resultForItem:
+ _objc_msgSend$setResult:forItem:
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$timeout
+ _objc_msgSend$verdicts
- ___SPBundleFilterAwaitServerXPCReply_block_invoke
- ___block_descriptor_64_e8_32s40r48r56r_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16l
- ___copy_helper_block_e8_32s40r48r56r
- ___destroy_helper_block_e8_32s40r48r56r
- _objc_msgSend$filteringResult
- _objc_msgSend$initWithFileProviderContainerGroups:fileProviderExcludedBundleIDs:needsAppProtectionBundleIDs:needsMDMRestrictedBundleIDs:needsExcludedAppBundleIDs:attributeBackfillGroups:
CStrings:
+ "%\""
+ "tpbck"
+ "v12@?0B8"
+ "v16@?0@\"CSBundleFilterEvaluationReply\"8"
+ "v24@?0@\"SPBundleFilterVerdictStore\"8@\"NSError\"16"
- "$\""
```
