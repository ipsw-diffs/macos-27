## PencilKit

> `/System/iOSSupport/System/Library/Frameworks/PencilKit.framework/Versions/A/PencilKit`

```diff

-622.2.2.0.0
-  __TEXT.__text: 0x31afcc
-  __TEXT.__objc_methlist: 0x2e61c
-  __TEXT.__const: 0x8ad4
+622.2.5.0.0
+  __TEXT.__text: 0x31d60c
+  __TEXT.__objc_methlist: 0x2e69c
+  __TEXT.__const: 0x8b84
   __TEXT.__dlopen_cstrs: 0x351
-  __TEXT.__constg_swiftt: 0x1d40
-  __TEXT.__swift5_typeref: 0x1e02
+  __TEXT.__constg_swiftt: 0x1d64
+  __TEXT.__swift5_typeref: 0x1e34
   __TEXT.__swift5_builtin: 0x118
-  __TEXT.__swift5_reflstr: 0x15a3
-  __TEXT.__swift5_fieldmd: 0x1988
+  __TEXT.__swift5_reflstr: 0x15cd
+  __TEXT.__swift5_fieldmd: 0x19b0
   __TEXT.__swift5_assocty: 0x6e0
-  __TEXT.__swift5_proto: 0x388
-  __TEXT.__swift5_types: 0x1c0
-  __TEXT.__cstring: 0xc971
-  __TEXT.__swift5_capture: 0xa30
-  __TEXT.__oslogstring: 0xc9fd
-  __TEXT.__swift_as_entry: 0xf0
-  __TEXT.__swift_as_cont: 0x218
-  __TEXT.__swift_as_ret: 0xac
+  __TEXT.__swift5_proto: 0x390
+  __TEXT.__swift5_types: 0x1c4
+  __TEXT.__cstring: 0xca25
+  __TEXT.__swift5_capture: 0xa48
+  __TEXT.__oslogstring: 0xcaa8
+  __TEXT.__swift_as_entry: 0xf4
+  __TEXT.__swift_as_cont: 0x224
+  __TEXT.__swift_as_ret: 0xb0
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x26250
+  __TEXT.__gcc_except_tab: 0x26444
   __TEXT.__ustring: 0x23a
-  __TEXT.__unwind_info: 0x12ce8
-  __TEXT.__eh_frame: 0x2af8
+  __TEXT.__unwind_info: 0x12db0
+  __TEXT.__eh_frame: 0x2b50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6868
+  __DATA_CONST.__const: 0x6980
   __DATA_CONST.__objc_classlist: 0x1018
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x778
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x17f10
+  __DATA_CONST.__objc_selrefs: 0x17f70
   __DATA_CONST.__objc_protorefs: 0x108
   __DATA_CONST.__objc_superrefs: 0xc68
   __DATA_CONST.__objc_arraydata: 0x950
-  __DATA_CONST.__got: 0x2068
-  __AUTH_CONST.__const: 0x7ee0
-  __AUTH_CONST.__cfstring: 0xe060
+  __DATA_CONST.__got: 0x2070
+  __AUTH_CONST.__const: 0x7fe0
+  __AUTH_CONST.__cfstring: 0xe080
   __AUTH_CONST.__objc_const: 0x47c90
   __AUTH_CONST.__weak_auth_got: 0x30
-  __AUTH_CONST.__objc_intobj: 0x8b8
+  __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_arrayobj: 0x6c0
   __AUTH_CONST.__objc_dictobj: 0x488
   __AUTH_CONST.__objc_doubleobj: 0xb0
-  __AUTH_CONST.__auth_got: 0x1c88
-  __AUTH.__objc_data: 0x9878
+  __AUTH_CONST.__auth_got: 0x1c98
+  __AUTH.__objc_data: 0x9880
   __AUTH.__data: 0xb80
   __DATA.__objc_ivar: 0x2828
-  __DATA.__data: 0x65b0
-  __DATA.__bss: 0x6c70
+  __DATA.__data: 0x65d8
+  __DATA.__bss: 0x6d70
   __DATA.__common: 0x100
   __DATA_DIRTY.__objc_ivar: 0x10e8
   __DATA_DIRTY.__objc_data: 0x1630
   __DATA_DIRTY.__data: 0x28
-  __DATA_DIRTY.__bss: 0x948
+  __DATA_DIRTY.__bss: 0x958
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib
   - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib
   - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19526
-  Symbols:   43250
-  CStrings:  3298
+  Functions: 19564
+  Symbols:   43342
+  CStrings:  3304
 
Symbols:
+ +[PKTextInputSingleElementFinder _isTappableViewOutsideElement:atPositionInWindow:]
+ +[PKTextInputSingleElementFinder _viewHasPencilTapGestureRecognizer:]
+ +[PKTextInputUtilities textRangeAdjustmentGestureRecognizerInView:]
+ -[PKRecognitionController fetchMappedTranscriptionForStrokes:cancelBlock:completion:]
+ -[PKRecognitionController fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:]
+ -[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]
+ -[PKRecognitionSessionManager fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:]
+ -[PKStroke _isWritingToolsGeneratedStroke]
+ -[PKStroke _setIsWritingToolsGeneratedStroke:]
+ -[PKTextInputInteraction _shouldAvoidStartingDrawingForSelectionHandleTouch:hitView:]
+ -[PKTextInputInteraction _touch:isInsideSelectionHandleHitRegionForGestureInView:]
+ -[PKTiledView _additionalStrokesAppliedForDrawing:]
+ GCC_except_table336
+ GCC_except_table343
+ GCC_except_table350
+ GCC_except_table352
+ GCC_except_table357
+ GCC_except_table360
+ GCC_except_table368
+ GCC_except_table375
+ GCC_except_table379
+ GCC_except_table384
+ GCC_except_table390
+ GCC_except_table396
+ GCC_except_table403
+ GCC_except_table409
+ GCC_except_table566
+ _$s15Synchronization6AtomicVMn
+ _$s15Synchronization6AtomicVySbGMR
+ _$s15Synchronization6AtomicVySbGMd
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO11presentableyA2EmFWC
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO16topTranscriptionyA2EmFWC
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO2eeoiySbAE_AEtFZ
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO4hash4intoys6HasherVz_tF
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO9hashValueSivg
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatO9hashValueSivpMV
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOAESQAAWL
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOAESQAAWl
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOMF
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOMa
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOMf
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOMn
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatON
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAAMc
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAAMcMK
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAASH13_rawHashValue4seedS2i_tFTW
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAASH4hash4intoys6HasherVz_tFTW
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAASH9hashValueSivgTW
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAASQWb
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSQAAMc
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSQAAMcMK
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOSQAASQ2eeoiySbx_xtFZTW
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOWV
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOwet
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOwst
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOwug
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOwui
+ _$s9PencilKit25RecognitionStrokeProviderC10TextFormatOwup
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaF
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFAGyYaYCXEfU_yScCyAGs5NeverOGXEfU_SbycfU_TA
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFAGyYaYCXEfU_yScCyAGs5NeverOGXEfU_yAGYbcfU0_
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFAGyYaYCXEfU_yScCyAGs5NeverOGXEfU_yAGYbcfU0_TA
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFTQ1_
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFTY0_
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFTY2_
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFTu
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokes6formatSSSgSayAA8PKStrokeVG_AC0G6FormatOtYaFyyXEfU0_TA
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFTQ0_
+ _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFTY1_
+ _$s9PencilKit30PKTiledViewAnimationControllerC019hideStrokesAndStartE033_EA3564AC04D8BA328C91CB29423F696CLL_2in05tiledD08durationSbSayAA8PKStrokeVG_AA9PKDrawingVSo0cD0CSdtYaFyScCySbs5NeverOGXEfU_yycfU_
+ _$s9PencilKit30PKTiledViewAnimationControllerC019hideStrokesAndStartE033_EA3564AC04D8BA328C91CB29423F696CLL_2in05tiledD08durationSbSayAA8PKStrokeVG_AA9PKDrawingVSo0cD0CSdtYaFyScCySbs5NeverOGXEfU_yycfU_TA
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ11_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ5_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ8_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY12_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY4_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY6_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY9_
+ _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFyScCyyts5NeverOGXEfU0_
+ _$sIeAgH_ytIeAgHr_TRTA.100TQ0_
+ _$sIeAgH_ytIeAgHr_TRTA.100Tu
+ _$sIeAgH_ytIeAgHr_TRTA.115TQ0_
+ _$sIeAgH_ytIeAgHr_TRTA.115Tu
+ _$sIeAgH_ytIeAgHr_TRTA.130TQ0_
+ _$sIeAgH_ytIeAgHr_TRTA.130Tu
+ _$sIeAgH_ytIeAgHr_TRTA.145TQ0_
+ _$sIeAgH_ytIeAgHr_TRTA.145Tu
+ _$sIeghH_IeAgH_TRTA.110TQ0_
+ _$sIeghH_IeAgH_TRTA.110Tu
+ _$sIeghH_IeAgH_TRTA.125TQ0_
+ _$sIeghH_IeAgH_TRTA.125Tu
+ _$sIeghH_IeAgH_TRTA.140TQ0_
+ _$sIeghH_IeAgH_TRTA.140Tu
+ _$sIeghH_IeAgH_TRTA.95TQ0_
+ _$sIeghH_IeAgH_TRTA.95Tu
+ _$sSSSgIeghg_So8NSStringCSgIeyBhy_TR
+ _$sSSSgMR
+ _$sSSSgMd
+ _$sSbIegd_SbIeyBd_TR
+ _$sScCySSSgs5NeverOGMR
+ _$sScCySSSgs5NeverOGMd
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tgq5TA.82TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tgq5TA.82Tu
+ _OBJC_CLASS_$_CHContextualTextResults
+ __OBJC_$_CLASS_METHODS_PKTextInputSingleElementFinder
+ ___67+[PKTextInputUtilities textRangeAdjustmentGestureRecognizerInView:]_block_invoke
+ ___72-[PKRecognitionController supportsRefinementForStrokes:completionBlock:]_block_invoke_2
+ ___85-[PKRecognitionController fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke
+ ___87-[PKRecognitionSessionManager fetchTranscriptionForStrokes:cancelBlock:withCompletion:]_block_invoke
+ ___87-[PKRecognitionSessionManager fetchTranscriptionForStrokes:cancelBlock:withCompletion:]_block_invoke_2
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke_2
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke_3
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke_4
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke_5
+ ___89-[PKRecognitionSessionManager fetchMappedTranscriptionForStrokes:cancelBlock:completion:]_block_invoke_6
+ ___99-[PKRecognitionSessionManager fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:]_block_invoke
+ ___99-[PKRecognitionSessionManager fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:]_block_invoke_2
+ ___99-[PKRecognitionSessionManager fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:]_block_invoke_3
+ ___block_descriptor_40_ea8_32bs_e33_v16?0"CHContextualTextResults"8ls32l8
+ ___block_descriptor_40_ea8_32bs_e35_v24?0"NSString"8"NSDictionary"16ls32l8
+ ___block_descriptor_48_ea8_32s40bs_e33_v16?0"CHContextualTextResults"8ls40l8s32l8
+ ___block_descriptor_48_ea8_32s40s_e33_v32?0"NSValue"8"NSArray"16^B24ls32l8s40l8
+ ___block_descriptor_64_ea8_32s40s48bs56bs_e5_v8?0ls32l8s48l8s56l8s40l8
+ ___block_descriptor_65_ea8_32s40s48bs56bs_e5_v8?0ls32l8s48l8s56l8s40l8
+ ___block_descriptor_72_ea8_32s40s48s56bs64bs_e5_v8?0ls56l8s64l8s32l8s40l8s48l8
+ ___swift_closure_destructor.64Tm
+ ___swift_closure_destructor.68Tm
+ _associated conformance 9PencilKit25RecognitionStrokeProviderC10TextFormatOSHAASQ
+ _objc_msgSend$_additionalStrokesAppliedForDrawing:
+ _objc_msgSend$_isTappableViewOutsideElement:atPositionInWindow:
+ _objc_msgSend$_shouldAvoidStartingDrawingForSelectionHandleTouch:hitView:
+ _objc_msgSend$_touch:isInsideSelectionHandleHitRegionForGestureInView:
+ _objc_msgSend$_viewHasPencilTapGestureRecognizer:
+ _objc_msgSend$fetchMappedTranscriptionForStrokes:cancelBlock:completion:
+ _objc_msgSend$fetchTranscriptionForStrokes:makePresentable:cancelBlock:completion:
+ _objc_msgSend$gestureRecognizer:shouldReceiveTouch:
+ _objc_msgSend$instancesRespondToSelector:
+ _objc_msgSend$presentableTranscription
+ _objc_msgSend$strokeIdentifierFromData:
+ _objc_msgSend$textRangeAdjustmentGestureRecognizerInView:
+ _objc_msgSend$textResults
+ _objc_msgSend$topTranscriptionWithStrokeMapping:
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic SSSg
+ _symbolic ScCySSSg_____G s5NeverO
+ _symbolic So11PKTiledViewC
+ _symbolic _____ 9PencilKit25RecognitionStrokeProviderC10TextFormatO
+ _symbolic _____ySbG 15Synchronization6AtomicV
- -[PKRecognitionController fetchTranscriptionForStrokes:withCompletion:]
- -[PKRecognitionSessionManager fetchTranscriptionForStrokes:callCompletionOnMainThread:cancelBlock:withCompletion:]
- GCC_except_table339
- GCC_except_table348
- GCC_except_table351
- GCC_except_table353
- GCC_except_table358
- GCC_except_table365
- GCC_except_table371
- GCC_except_table376
- GCC_except_table380
- GCC_except_table385
- GCC_except_table391
- GCC_except_table397
- GCC_except_table405
- GCC_except_table565
- _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFTQ1_
- _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFTY0_
- _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFTY2_
- _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFyScCySSs5NeverOGXEfU_ySSYbcfU_
- _$s9PencilKit25RecognitionStrokeProviderC14recognizedText7strokesSSSgSayAA8PKStrokeVG_tYaFyScCySSs5NeverOGXEfU_ySSYbcfU_TA
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ4_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ6_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTQ9_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY5_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFTY8_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFyScCyyts5NeverOGXEfU1_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFyScCyyts5NeverOGXEfU1_yycfU_
- _$s9PencilKit30PKTiledViewAnimationControllerC6refine4from2to2inSo13PKUndoCommandCSgSayAA8PKStrokeVG_AmA9PKDrawingVtYaFyScCyyts5NeverOGXEfU1_yycfU_TA
- _$sIeAgH_ytIeAgHr_TRTA.114TQ0_
- _$sIeAgH_ytIeAgHr_TRTA.114Tu
- _$sIeAgH_ytIeAgHr_TRTA.129TQ0_
- _$sIeAgH_ytIeAgHr_TRTA.129Tu
- _$sIeAgH_ytIeAgHr_TRTA.144TQ0_
- _$sIeAgH_ytIeAgHr_TRTA.144Tu
- _$sIeAgH_ytIeAgHr_TRTA.99TQ0_
- _$sIeAgH_ytIeAgHr_TRTA.99Tu
- _$sIeghH_IeAgH_TRTA.109TQ0_
- _$sIeghH_IeAgH_TRTA.109Tu
- _$sIeghH_IeAgH_TRTA.124TQ0_
- _$sIeghH_IeAgH_TRTA.124Tu
- _$sIeghH_IeAgH_TRTA.139TQ0_
- _$sIeghH_IeAgH_TRTA.139Tu
- _$sIeghH_IeAgH_TRTA.94TQ0_
- _$sIeghH_IeAgH_TRTA.94Tu
- _$sSSIeghg_So8NSStringCIeyBhy_TR
- _$sScCySSs5NeverOGMR
- _$sScCySSs5NeverOGMd
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tgq5TA.81TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tgq5TA.81Tu
- ___114-[PKRecognitionSessionManager fetchTranscriptionForStrokes:callCompletionOnMainThread:cancelBlock:withCompletion:]_block_invoke
- ___114-[PKRecognitionSessionManager fetchTranscriptionForStrokes:callCompletionOnMainThread:cancelBlock:withCompletion:]_block_invoke_2
- ___71-[PKRecognitionController fetchTranscriptionForStrokes:withCompletion:]_block_invoke
- ___swift_closure_destructor.63Tm
- ___swift_closure_destructor.67Tm
- _objc_msgSend$fetchTranscriptionForStrokes:callCompletionOnMainThread:cancelBlock:withCompletion:
- _objc_msgSend$fetchTranscriptionForStrokes:withCompletion:
- _symbolic ScCySS_____G s5NeverO
CStrings:
+ "Avoid element %@ because the touch is on tappable view %@ outside of it"
+ "Avoid starting to draw on view %@ because the touch is inside a text selection handle's hit region"
+ "UITextRangeAdjustmentGestureRecognizer"
+ "hideStrokesAndStartAnimation(_:in:tiledView:duration:)"
+ "recognizedText(strokes:format:)"
+ "v24@?0@\"NSString\"8@\"NSDictionary\"16"
+ "v32@?0@\"NSValue\"8@\"NSArray\"16^B24"
- "recognizedText(strokes:)"
```
