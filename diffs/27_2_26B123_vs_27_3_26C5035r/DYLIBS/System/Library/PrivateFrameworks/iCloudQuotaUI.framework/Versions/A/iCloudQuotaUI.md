## iCloudQuotaUI

> `/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/Versions/A/iCloudQuotaUI`

```diff

-301.24.1.5.0
-  __TEXT.__text: 0x9d774
-  __TEXT.__objc_methlist: 0x1f5c
-  __TEXT.__const: 0x7464
-  __TEXT.__gcc_except_tab: 0x64c
-  __TEXT.__cstring: 0x4e0a
-  __TEXT.__oslogstring: 0x376b
+301.24.2.4.0
+  __TEXT.__text: 0x9f31c
+  __TEXT.__objc_methlist: 0x1fcc
+  __TEXT.__const: 0x7594
+  __TEXT.__gcc_except_tab: 0x6e4
+  __TEXT.__cstring: 0x505a
+  __TEXT.__oslogstring: 0x3bab
   __TEXT.__dlopen_cstrs: 0x218
-  __TEXT.__swift5_typeref: 0x74d6
-  __TEXT.__swift5_reflstr: 0x14e2
-  __TEXT.__swift5_assocty: 0x8b8
-  __TEXT.__constg_swiftt: 0x20f4
-  __TEXT.__swift5_fieldmd: 0x1794
-  __TEXT.__swift5_proto: 0x3b0
-  __TEXT.__swift5_types: 0x1d0
+  __TEXT.__swift5_typeref: 0x760a
+  __TEXT.__swift5_reflstr: 0x1532
+  __TEXT.__swift5_assocty: 0x8f0
+  __TEXT.__constg_swiftt: 0x2118
+  __TEXT.__swift5_fieldmd: 0x17b0
+  __TEXT.__swift5_proto: 0x3b8
+  __TEXT.__swift5_types: 0x1d4
   __TEXT.__swift5_capture: 0x7c4
   __TEXT.__swift_as_entry: 0x90
   __TEXT.__swift_as_ret: 0x78
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift_as_cont: 0x3c
-  __TEXT.__unwind_info: 0x3408
+  __TEXT.__unwind_info: 0x3480
   __TEXT.__eh_frame: 0x1298
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x538
+  __DATA_CONST.__const: 0x550
   __DATA_CONST.__objc_classlist: 0x120
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d18
+  __DATA_CONST.__objc_selrefs: 0x1d98
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x478
-  __DATA_CONST.__got: 0xac8
-  __AUTH_CONST.__const: 0x4b30
-  __AUTH_CONST.__cfstring: 0x3360
+  __DATA_CONST.__got: 0xae0
+  __AUTH_CONST.__const: 0x4be0
+  __AUTH_CONST.__cfstring: 0x3520
   __AUTH_CONST.__objc_const: 0x4f98
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_arrayobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x13e0
+  __AUTH_CONST.__auth_got: 0x1430
   __AUTH.__objc_data: 0x988
   __AUTH.__data: 0x1960
   __DATA.__objc_ivar: 0x1f8
   __DATA.__data: 0x2160
-  __DATA.__bss: 0x8260
+  __DATA.__bss: 0x8370
   __DATA.__common: 0x258
   __DATA_DIRTY.__objc_data: 0x3d8
   __DATA_DIRTY.__data: 0x58

   - /System/Library/PrivateFrameworks/IconServices.framework/Versions/A/IconServices
   - /System/Library/PrivateFrameworks/LiftUI.framework/Versions/A/LiftUI
   - /System/Library/PrivateFrameworks/NetworkServiceProxy.framework/Versions/A/NetworkServiceProxy
+  - /System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit
   - /System/Library/PrivateFrameworks/Settings.framework/Versions/A/Settings
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /System/Library/PrivateFrameworks/_IconServices_SwiftUI.framework/Versions/A/_IconServices_SwiftUI

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3775
-  Symbols:   3337
-  CStrings:  924
+  Functions: 3815
+  Symbols:   3380
+  CStrings:  952
 
Symbols:
+ +[ICQInAppAlert alertForReason:placement:inOffer:]
+ +[ICQInAppMessage(Examples) _aiMessageWithReason:contentType:title:subTitle:link:]
+ +[ICQInAppMessage(Examples) aiLimitReached]
+ +[ICQInAppMessage(Examples) aiPlanUpgradeRequired]
+ +[ICQInAppMessage(Examples) approachingAILimit]
+ -[ICQInAppAlert initWithOffer:alertKey:pendingItemsCount:albumName:]
+ -[ICQInAppMessaging _actionsForBannerSpecification:offer:pendingItemsCount:albumName:]
+ -[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:albumName:completion:]
+ -[ICQInAppMessaging aiMessageForReason:defaultOffer:]
+ -[ICQInAppMessaging fetchMessageForReason:placement:pendingItemsCount:albumName:withCompletion:]
+ -[ICQInAppMessaging fetchMessageWithPlacement:pendingItemsCount:albumName:completion:]
+ -[ICQInAppMessaging sharedAlbumMessageForOffer:placement:pendingItemsCount:albumName:]
+ -[ICQLinkInAppAction addAlertFromLink:offer:pendingItemsCount:albumName:]
+ -[ICQLinkInAppAction initWithLink:inOffer:pendingItemsCount:albumName:]
+ GCC_except_table105
+ GCC_except_table35
+ GCC_except_table52
+ GCC_except_table60
+ GCC_except_table61
+ GCC_except_table71
+ GCC_except_table91
+ _ICQUIInAppMessageReasonAILimitReached
+ _ICQUIInAppMessageReasonAIPlanUpgradeRequired
+ _ICQUIInAppMessageReasonApproachingAILimit
+ _OBJC_CLASS_$_OBBundle
+ _OBJC_CLASS_$_OBPrivacyLinkController
+ __ICQIsAIReason
+ ___104-[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:albumName:completion:]_block_invoke
+ ___62-[ICQInAppMessaging fetchAlertForReason:placement:completion:]_block_invoke
+ ___68-[ICQInAppAlert initWithOffer:alertKey:pendingItemsCount:albumName:]_block_invoke
+ ___74-[ICQInAppMessaging uploadFailureMessageForPendingItemCount:defaultOffer:]_block_invoke
+ ___74-[ICQInAppMessaging uploadFailureMessageForPendingItemCount:defaultOffer:]_block_invoke_2
+ ___86-[ICQInAppMessaging sharedAlbumMessageForOffer:placement:pendingItemsCount:albumName:]_block_invoke
+ ___86-[ICQInAppMessaging sharedAlbumMessageForOffer:placement:pendingItemsCount:albumName:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e28_"NSString"16?0"NSString"8l
+ _associated conformance 13iCloudQuotaUI25AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV05SwiftC00H0AA4BodyAeFP_AeF
+ _associated conformance 13iCloudQuotaUI25AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV05SwiftC029NSViewControllerRepresentableAaE0H0
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyAA6ToggleVyAA6HStackVyAA05TupleD0VyACyAA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQOyAL05AsyncI5ImageVyAA0O0VG_Qo_AA13_OffsetEffectVG_AA6VStackVyAIyAGyAIyACyACyAA6CircleVAA12_FrameLayoutVGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGG_AA4TextVQPGG_A13_AA012_ConditionalD0VyACy011iCloudQuotaB0021AboutPrivateRelayLinkH033_B1AE8FEA7473F77196D422B62389E5ADLLVAA06_FixedlU0VGA13_GACyACyACyA13_A6_yAA19SymbolRenderingModeVSgGGAA016_ForegroundStyleY0VyAA22HierarchicalShapeStyleVGGA6_yAA4FontVSgGGSgQPGGQPGGGAA023AccessibilityAttachmentY0VGAA01_vw9TransformY0VySbGGAaJHPA50_AaJHPA47_AaJHPyHC_A49_AA0hY0HPyHCHC_A53_AAA55_HPyHCHC
+ _objc_msgSend$_actionsForBannerSpecification:offer:pendingItemsCount:albumName:
+ _objc_msgSend$_aiMessageWithReason:contentType:title:subTitle:link:
+ _objc_msgSend$_fetchSharedAlbumMessageForReason:placement:pendingItemsCount:albumName:completion:
+ _objc_msgSend$addAlertFromLink:offer:pendingItemsCount:albumName:
+ _objc_msgSend$aiMessageForReason:defaultOffer:
+ _objc_msgSend$alertForReason:placement:inOffer:
+ _objc_msgSend$bundleWithIdentifier:
+ _objc_msgSend$exactMessageSpecificationForReason:bundleId:
+ _objc_msgSend$filledTemplate:itemCount:albumName:
+ _objc_msgSend$filledTemplateForItemCount:albumName:lookup:
+ _objc_msgSend$inAppAlertKeyForReason:placement:
+ _objc_msgSend$initWithLink:inOffer:pendingItemsCount:albumName:
+ _objc_msgSend$initWithOffer:alertKey:
+ _objc_msgSend$initWithOffer:alertKey:pendingItemsCount:albumName:
+ _objc_msgSend$linkWithBundleIdentifier:
+ _objc_msgSend$localizedButtonTitle
+ _objc_msgSend$normalizedAlbumName:
+ _objc_msgSend$privacyFlow
+ _objc_msgSend$setPendingItemsCount:
+ _objc_msgSend$sharedAlbumMessageForOffer:placement:pendingItemsCount:albumName:
+ _symbolic $s7SwiftUI29NSViewControllerRepresentableP
+ _symbolic So23OBPrivacyLinkControllerC
+ _symbolic _____ 13iCloudQuotaUI25AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV
+ _symbolic _____ s5NeverO
+ _symbolic _____yAAy_____y_____y_____yAAy_____y_____y_____G_Qo______G______yADyACyADyAAyAAy__________G_____y_____SgGG______QPGG_AT_____yAAy__________GATGAAyAAyAAyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG_____G_____ySbGG 7SwiftUI15ModifiedContentV AA6ToggleV AA6HStackV AA05TupleD0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalD0V 011iCloudQuotaB0021AboutPrivateRelayLinkH033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixedlU0V AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV AA023AccessibilityAttachmentY0V AA01_vw9TransformY0V
+ _symbolic _____y___________y_____yACy_____yAEy__________G_____y_____SgGG______QPGG_AN_____yAEy__________GANGAEyAEyAEyAnIy_____SgGG_____y_____GGAIy_____SgGGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA6HStackV AA08ModifiedI0V AA6CircleV AA06_FrameG0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalI0V 011iCloudQuotaB0021AboutPrivateRelayLinkD033_B1AE8FEA7473F77196D422B62389E5ADLLV AA010_FixedSizeG0V AA19SymbolRenderingModeV AA016_ForegroundStyleQ0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y___________y_____y_____y_____y_____G_Qo______G______yACy_____yACyADyADy__________G_____y_____SgGG______QPGG_AU_____yADy__________GAUGADyADyADyAuPy_____SgGG_____y_____GGAPy_____SgGGSgQPGGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA0D0P014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AN05AsyncK5ImageV AA0Q0V AA13_OffsetEffectV AA6VStackV AA0F0V AA6CircleV AA06_FrameG0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalI0V 011iCloudQuotaB0021AboutPrivateRelayLinkD033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixednG0V AA19SymbolRenderingModeV AA016_ForegroundStyleZ0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y_____y_____yABy_____yADy__________G_____y_____SgGG______QPGG_AM_____yADy__________GAMGADyADyADyAmHy_____SgGG_____y_____GGAHy_____SgGGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA6HStackV AA08ModifiedE0V AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalE0V 011iCloudQuotaB025AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV AA010_FixedSizeJ0V AA19SymbolRenderingModeV AA016_ForegroundStyleN0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y_____y_____yACy__________G_____y_____SgGG______QPGG_AL_____yACy__________GALGACyACyACyAlGy_____SgGG_____y_____GGAGy_____SgGGSgt 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalE0V 011iCloudQuotaB025AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV AA010_FixedSizeI0V AA19SymbolRenderingModeV AA016_ForegroundStyleM0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y_____y_____y_____G_Qo______G______y_____y_____yAIyAAyAAy__________G_____y_____SgGG______QPGG_AS_____yAAy__________GASGAAyAAyAAyAsNy_____SgGG_____y_____GGANy_____SgGGSgQPGGt 7SwiftUI15ModifiedContentV AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AF05AsyncF5ImageV AA0L0V AA13_OffsetEffectV AA6VStackV AA05TupleD0V AA6HStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalD0V 011iCloudQuotaB0021AboutPrivateRelayLinkE033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixediT0V AA19SymbolRenderingModeV AA016_ForegroundStyleX0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y_____y_____y_____yAAy_____y_____y_____G_Qo______G______yADyACyADyAAyAAy__________G_____y_____SgGG______QPGG_AT_____yAAy__________GATGAAyAAyAAyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG_____G 7SwiftUI15ModifiedContentV AA6ToggleV AA6HStackV AA05TupleD0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalD0V 011iCloudQuotaB0021AboutPrivateRelayLinkH033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixedlU0V AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV AA023AccessibilityAttachmentY0V
+ _symbolic _____y_____y_____y_____y_____y_____G_Qo______G______yAByAAyAByACyACy__________G_____y_____SgGG______QPGG_AS_____yACy__________GASGACyACyACyAsNy_____SgGG_____y_____GGANy_____SgGGSgQPGGQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AJ05AsyncH5ImageV AA0N0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalE0V 011iCloudQuotaB0021AboutPrivateRelayLinkG033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixedkT0V AA19SymbolRenderingModeV AA016_ForegroundStyleX0V AA22HierarchicalShapeStyleV AA4FontV
+ _symbolic _____y_____y_____y_____y_____y_____y_____G_Qo______G______yACyAByACyADyADy__________G_____y_____SgGG______QPGG_AT_____yADy__________GATGADyADyADyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG 7SwiftUI6ToggleV AA6HStackV AA12TupleContentV AA08ModifiedF0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA012_ConditionalF0V 011iCloudQuotaB0021AboutPrivateRelayLinkH033_B1AE8FEA7473F77196D422B62389E5ADLLV AA06_FixedlU0V AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV
+ _type_layout_string 13iCloudQuotaUI25AboutPrivateRelayLinkView33_B1AE8FEA7473F77196D422B62389E5ADLLV
- -[ICQInAppMessaging _actionsForBannerSpecification:offer:pendingItemsCount:]
- -[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:completion:]
- -[ICQInAppMessaging sharedAlbumMessageForOffer:placement:pendingItemsCount:]
- -[ICQLinkInAppAction addAlertFromLink:offer:pendingItemsCount:]
- GCC_except_table48
- GCC_except_table49
- GCC_except_table54
- GCC_except_table55
- GCC_except_table68
- GCC_except_table82
- _OBJC_CLASS_$__ICQHelperFunctions
- ___94-[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:completion:]_block_invoke
- _get_witness_table 7SwiftUI15ModifiedContentVyACyAA6ToggleVyAA6HStackVyAA05TupleD0VyACyAA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQOyAL05AsyncI5ImageVyAA0O0VG_Qo_AA13_OffsetEffectVG_AA6VStackVyAIyAGyAIyACyACyAA6CircleVAA12_FrameLayoutVGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGG_AA4TextVQPGG_A13_A13_ACyACyACyA13_A6_yAA19SymbolRenderingModeVSgGGAA016_ForegroundStyleY0VyAA22HierarchicalShapeStyleVGGA6_yAA4FontVSgGGSgQPGGQPGGGAA023AccessibilityAttachmentY0VGAA01_vw9TransformY0VySbGGAaJHPA40_AaJHPA37_AaJHPyHC_A39_AA0hY0HPyHCHC_A43_AAA45_HPyHCHC
- _objc_msgSend$_actionsForBannerSpecification:offer:pendingItemsCount:
- _objc_msgSend$_fetchSharedAlbumMessageForReason:placement:pendingItemsCount:completion:
- _objc_msgSend$addAlertFromLink:offer:pendingItemsCount:
- _objc_msgSend$replaceWordsIn:with:
- _objc_msgSend$sharedAlbumMessageForOffer:placement:pendingItemsCount:
- _objc_msgSend$templateKeyForItemCount:
- _objc_msgSend$wordsToReplaceForItemCount:
- _symbolic _____yAAy_____y_____y_____yAAy_____y_____y_____G_Qo______G______yADyACyADyAAyAAy__________G_____y_____SgGG______QPGG_A2tAyAAyAAyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG_____G_____ySbGG 7SwiftUI15ModifiedContentV AA6ToggleV AA6HStackV AA05TupleD0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV AA023AccessibilityAttachmentY0V AA01_vw9TransformY0V
- _symbolic _____y___________y_____yACy_____yAEy__________G_____y_____SgGG______QPGG_A2nEyAEyAEyAnIy_____SgGG_____y_____GGAIy_____SgGGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA6HStackV AA08ModifiedI0V AA6CircleV AA06_FrameG0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleQ0V AA017HierarchicalShapeX0V AA4FontV
- _symbolic _____y___________y_____y_____y_____y_____G_Qo______G______yACy_____yACyADyADy__________G_____y_____SgGG______QPGG_A2uDyADyADyAuPy_____SgGG_____y_____GGAPy_____SgGGSgQPGGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA0D0P014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AN05AsyncK5ImageV AA0Q0V AA13_OffsetEffectV AA6VStackV AA0F0V AA6CircleV AA06_FrameG0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleZ0V AA22HierarchicalShapeStyleV AA4FontV
- _symbolic _____y_____y_____yABy_____yADy__________G_____y_____SgGG______QPGG_A2mDyADyADyAmHy_____SgGG_____y_____GGAHy_____SgGGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA6HStackV AA08ModifiedE0V AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleN0V AA017HierarchicalShapeU0V AA4FontV
- _symbolic _____y_____y_____yACy__________G_____y_____SgGG______QPGG_A2lCyACyACyAlGy_____SgGG_____y_____GGAGy_____SgGGSgt 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleM0V AA017HierarchicalShapeT0V AA4FontV
- _symbolic _____y_____y_____y_____G_Qo______G______y_____y_____yAIyAAyAAy__________G_____y_____SgGG______QPGG_A2sAyAAyAAyAsNy_____SgGG_____y_____GGANy_____SgGGSgQPGGt 7SwiftUI15ModifiedContentV AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AF05AsyncF5ImageV AA0L0V AA13_OffsetEffectV AA6VStackV AA05TupleD0V AA6HStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleX0V AA22HierarchicalShapeStyleV AA4FontV
- _symbolic _____y_____y_____y_____yAAy_____y_____y_____G_Qo______G______yADyACyADyAAyAAy__________G_____y_____SgGG______QPGG_A2tAyAAyAAyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG_____G 7SwiftUI15ModifiedContentV AA6ToggleV AA6HStackV AA05TupleD0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV AA023AccessibilityAttachmentY0V
- _symbolic _____y_____y_____y_____y_____y_____G_Qo______G______yAByAAyAByACyACy__________G_____y_____SgGG______QPGG_A2sCyACyACyAsNy_____SgGG_____y_____GGANy_____SgGGSgQPGGQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AJ05AsyncH5ImageV AA0N0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleX0V AA22HierarchicalShapeStyleV AA4FontV
- _symbolic _____y_____y_____y_____y_____y_____y_____G_Qo______G______yACyAByACyADyADy__________G_____y_____SgGG______QPGG_A2tDyADyADyAtOy_____SgGG_____y_____GGAOy_____SgGGSgQPGGQPGGG 7SwiftUI6ToggleV AA6HStackV AA12TupleContentV AA08ModifiedF0V AA4ViewP014_IconServices_aB0E8iconSizeyQrSo6CGSizeVSgFQO AL05AsyncI5ImageV AA0O0V AA13_OffsetEffectV AA6VStackV AA6CircleV AA12_FrameLayoutV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA4TextV AA19SymbolRenderingModeV AA016_ForegroundStyleY0V AA22HierarchicalShapeStyleV AA4FontV
CStrings:
+ "%s Using mock offer"
+ "-[ICQInAppMessaging fetchAlertForReason:placement:completion:]_block_invoke"
+ "@\"NSString\"16@?0@\"NSString\"8"
+ "AILimitReached"
+ "AIPlanUpgradeRequired"
+ "ApproachingAILimit"
+ "Learn More"
+ "No %{public}@ message for bundle %{public}@ in default offer %{public}@"
+ "OBBundle returned no localizedButtonTitle for %{public}s; falling back to the hardcoded About Private Relay link"
+ "Offer %{public}@ has no inlineAlertInfo entry for alertKey: %{public}@"
+ "Returning %{public}@ server message for bundle %{public}@ (default offer: %{public}@)"
+ "Returning icqctl override message for reason %{public}@ to bundle %{public}@"
+ "Shared Collections: fetchMessageForReason:placement:pendingItemsCount:albumName: called with reason: %@, placement: %@, count: %@, albumName: %{private}@"
+ "Unable to find in-app message for reason %{public}@"
+ "Upgrade"
+ "Upgrade to iCloud+ to use this feature."
+ "You're approaching your daily limit."
+ "You've reached your daily limit. Upgrade to iCloud+ for higher limits."
+ "[icqctl] Approaching Daily Limit"
+ "[icqctl] Daily Limit Reached"
+ "[icqctl] Upgrade to iCloud+"
+ "com.apple.onboarding.privaterelay"
+ "fetchAlertForReason:%{public}@ placement:%{public}@ found no alert for bundle %{public}@ in regular offer %{public}@ or default offer %{public}@"
+ "fetchAlertForReason:%{public}@ placement:%{public}@ has no offers loaded for bundle %{public}@ (observing: %{public}@)"
+ "fetchAlertForReason:%{public}@ placement:%{public}@ returning alert from offer %{public}@: %@"
+ "fetchMessageForReason:%{public}@ for bundle %{public}@ (observing: %{public}@, default offer: %{public}@)"
+ "fetchMessageWithPlacement:pendingItemsCount:albumName: called with placement: %@, count: %@, albumName: %{private}@"
+ "https://icq.icloud.com?context=test&universalLinkAction=LAUNCH_CLOUD_FM"
+ "https://icq.icloud.com?context=test&universalLinkAction=default"
+ "https://support.apple.com/127901"
+ "none"
- "INTERNET_PRIVACY_OPEN_SYSTEM_STATUS_BUTTON_TITLE"
- "Unable to find in-app message for reason %@"
- "fetchAlertForReason:%{public}@ placement:%{public}@ not yet implemented, returning unavailable error."
```
