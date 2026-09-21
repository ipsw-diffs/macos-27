## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-10.1.11.1.1
-  __TEXT.__text: 0x8e01d8
+10.1.13.1.1
+  __TEXT.__text: 0x8e1828
   __TEXT.__lazy_helpers: 0x2e98
-  __TEXT.__objc_methlist: 0x244ec
-  __TEXT.__const: 0xbad90
+  __TEXT.__objc_methlist: 0x245ac
+  __TEXT.__const: 0xbad50
   __TEXT.__dlopen_cstrs: 0x834
-  __TEXT.__cstring: 0x2ca8c
+  __TEXT.__cstring: 0x2cac8
   __TEXT.__swift5_typeref: 0x7a13
+  __TEXT.__swift5_reflstr: 0x41ce
+  __TEXT.__swift5_assocty: 0xfd8
   __TEXT.__constg_swiftt: 0x5ccc
   __TEXT.__swift5_builtin: 0x3e8
-  __TEXT.__swift5_reflstr: 0x41ad
-  __TEXT.__swift5_fieldmd: 0x5928
-  __TEXT.__swift5_assocty: 0xfd8
+  __TEXT.__swift5_fieldmd: 0x5940
   __TEXT.__swift5_proto: 0x1258
   __TEXT.__swift5_types: 0x708
   __TEXT.__swift_as_entry: 0x8d8

   __TEXT.__swift5_capture: 0x4188
   __TEXT.__swift5_mpenum: 0x9c
   __TEXT.__swift5_protos: 0x120
-  __TEXT.__oslogstring: 0x313da
-  __TEXT.__gcc_except_tab: 0x53c8
+  __TEXT.__oslogstring: 0x314d5
+  __TEXT.__gcc_except_tab: 0x5358
   __TEXT.__ustring: 0x262
-  __TEXT.__unwind_info: 0x16820
-  __TEXT.__eh_frame: 0x18484
+  __TEXT.__unwind_info: 0x16858
+  __TEXT.__eh_frame: 0x184c4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x4a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfdd0
+  __DATA_CONST.__objc_selrefs: 0xfe58
   __DATA_CONST.__objc_protorefs: 0x270
   __DATA_CONST.__objc_superrefs: 0xcf8
   __DATA_CONST.__objc_arraydata: 0x498
-  __DATA_CONST.__got: 0x1a30
-  __AUTH_CONST.__const: 0x451e0
-  __AUTH_CONST.__cfstring: 0x23600
-  __AUTH_CONST.__objc_const: 0x3fde0
+  __DATA_CONST.__got: 0x1a38
+  __AUTH_CONST.__const: 0x45210
+  __AUTH_CONST.__cfstring: 0x23640
+  __AUTH_CONST.__objc_const: 0x3fee8
   __AUTH_CONST.__lazy_load_got: 0x460
   __AUTH_CONST.__objc_intobj: 0xc60
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x2428
-  __AUTH.__objc_data: 0x9f50
-  __AUTH.__data: 0x3010
-  __DATA.__objc_ivar: 0x1a4c
-  __DATA.__data: 0x7e54
+  __AUTH_CONST.__auth_got: 0x2440
+  __AUTH.__objc_data: 0x9988
+  __AUTH.__data: 0x2c50
+  __DATA.__objc_ivar: 0x1a68
+  __DATA.__data: 0x7e30
   __DATA.__bss: 0x1c6d8
-  __DATA.__common: 0x1528
+  __DATA.__common: 0x1520
   __DATA_DIRTY.__objc_ivar: 0x6e4
-  __DATA_DIRTY.__objc_data: 0x5a90
-  __DATA_DIRTY.__data: 0x2e50
+  __DATA_DIRTY.__objc_data: 0x6058
+  __DATA_DIRTY.__data: 0x320c
   __DATA_DIRTY.__bss: 0x63b0
-  __DATA_DIRTY.__common: 0x88
+  __DATA_DIRTY.__common: 0x90
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 29803
-  Symbols:   32450
-  CStrings:  8949
+  Functions: 29831
+  Symbols:   32486
+  CStrings:  8954
 
Symbols:
+ +[AMSDefaults cardEnrollmentWarmWindowCount]
+ +[AMSDefaults cardEnrollmentWarmWindowStart]
+ +[AMSDefaults setCardEnrollmentWarmWindowCount:]
+ +[AMSDefaults setCardEnrollmentWarmWindowStart:]
+ +[AMSProcessInfo _bundleInfoStringForKey:bundleIdentifier:record:]
+ -[AMSProcessInfo _bundleFactsLocked]
+ -[AMSProcessInfo _resolveBundleURLLocked]
+ -[AMSProcessInfo _resolveBundleVersionLocked]
+ -[AMSProcessInfo _resolveClientVersionLocked]
+ -[AMSProcessInfo _resolveCodablePropertiesLocked]
+ -[AMSProcessInfo _resolveDescriptionPropertiesLocked]
+ -[AMSProcessInfo _resolveEqualityPropertiesLocked]
+ -[AMSProcessInfo _resolveExecutableNameLocked]
+ -[AMSProcessInfo _resolveLocalizedNameLocked]
+ -[AMSProcessInfoBundleFacts _resolvedStringValue:generator:]
+ -[AMSProcessInfoBundleFacts _resolvedURLValue:generator:]
+ -[AMSProcessInfoBundleFacts initWithBundleURLGenerator:executableNameGenerator:localizedNameGenerator:bundleVersionGenerator:clientVersionGenerator:]
+ GCC_except_table134
+ GCC_except_table143
+ GCC_except_table207
+ GCC_except_table60
+ GCC_except_table81
+ GCC_except_table87
+ GCC_except_table90
+ OBJC_IVAR_$_AMSProcessInfo._bundleFacts
+ OBJC_IVAR_$_AMSProcessInfo._resolvesFromBundleFacts
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleURLGenerator
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleVersionGenerator
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._clientVersionGenerator
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._executableNameGenerator
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._localizedNameGenerator
+ OBJC_IVAR_$_AMSProcessInfoBundleFacts._lock
+ _AKCredentialCollectionIsLoud
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_2
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e12_"NSURL"8?0l
+ ___block_descriptor_40_e8_32s_e15_"NSString"8?0l
+ ___block_descriptor_64_e8_32s40s48s_e53_v24?0"AMSMetricsFigaroBagConfguration"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0l
+ _objc_msgSend$_bundleFactsLocked
+ _objc_msgSend$_bundleInfoStringForKey:bundleIdentifier:record:
+ _objc_msgSend$_resolveBundleURLLocked
+ _objc_msgSend$_resolveBundleVersionLocked
+ _objc_msgSend$_resolveClientVersionLocked
+ _objc_msgSend$_resolveCodablePropertiesLocked
+ _objc_msgSend$_resolveDescriptionPropertiesLocked
+ _objc_msgSend$_resolveEqualityPropertiesLocked
+ _objc_msgSend$_resolveExecutableNameLocked
+ _objc_msgSend$_resolveLocalizedNameLocked
+ _objc_msgSend$_resolvedStringValue:generator:
+ _objc_msgSend$_resolvedURLValue:generator:
+ _objc_msgSend$initWithBundleURLGenerator:executableNameGenerator:localizedNameGenerator:bundleVersionGenerator:clientVersionGenerator:
- -[AMSProcessInfo _ensureAllPropertiesResolved]
- -[AMSProcessInfo _resolveRecordPropertiesIfNeededLocked]
- GCC_except_table133
- GCC_except_table142
- GCC_except_table206
- GCC_except_table67
- GCC_except_table80
- GCC_except_table86
- GCC_except_table89
- GCC_except_table92
- OBJC_IVAR_$_AMSProcessInfo._recordPropertiesResolved
- ___block_descriptor_48_e8_32s40bs_e24_24?0^{__CFString=}8#16l
- ___block_descriptor_56_e8_32s40s48r_e15_"NSBundle"8?0l
- ___block_descriptor_56_e8_32s40s_e53_v24?0"AMSMetricsFigaroBagConfguration"8"NSError"16l
- _objc_msgSend$_ensureAllPropertiesResolved
- _objc_msgSend$_resolveRecordPropertiesIfNeededLocked
CStrings:
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld (no flush interval available)"
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld because one is already scheduled and pending; it may be one deferred until the app becomes active."
+ "%{public}@: [%{public}@] Cannot schedule flush for container %{public}@ with style %{public}ld because the style is currently not allowed."
+ "%{public}@: [%{public}@] Flush scheduled for container %{public}@. (style: %{public}ld, time: %{public}.3f)"
+ "%{public}@: [%{public}@] Not scheduling flush for container %{public}@ because we failed to get Figaro bag configuration: %{public}@"
+ "%{public}@authResults credential source AKCredentialCollectionIsLoud = %{public}@"
+ "@\"NSString\"8@?0"
+ "@\"NSURL\"8@?0"
+ "AMSCardEnrollmentWarmWindowCount"
+ "AMSCardEnrollmentWarmWindowStart"
+ "CardEnrollmentCacheWarming"
+ "PasscodeEngagement"
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld (no flush interval available)"
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld because one has already been scheduled and is pending."
- "%{public}@: [%{public}@] Cannot schedule flush with style %{public}ld because the style is currently not allowed."
- "%{public}@: [%{public}@] Flush scheduled. (style: %{public}ld, time: %{public}.3f)"
- "%{public}@: [%{public}@] Not scheduling flush because we failed to get Figaro bag configuration: %{public}@"
- "@\"NSBundle\"8@?0"
- "@24@?0^{__CFString=}8#16"
```
