## ChatKit

> `/System/iOSSupport/System/Library/PrivateFrameworks/ChatKit.framework/Versions/A/ChatKit`

```diff

-1491.200.95.0.0
-  __TEXT.__text: 0xb6338c
+1491.200.101.1.2
+  __TEXT.__text: 0xb68778
   __TEXT.__delay_stubs: 0x100
   __TEXT.__delay_helper: 0x2358
-  __TEXT.__objc_methlist: 0x72694
-  __TEXT.__const: 0x3ca34
-  __TEXT.__gcc_except_tab: 0x1fa28
-  __TEXT.__cstring: 0x3d56b
-  __TEXT.__oslogstring: 0x52b47
+  __TEXT.__objc_methlist: 0x72b2c
+  __TEXT.__const: 0x3cac4
+  __TEXT.__gcc_except_tab: 0x1fa98
+  __TEXT.__cstring: 0x3d63b
+  __TEXT.__oslogstring: 0x52fb7
   __TEXT.__dlopen_cstrs: 0x5a8
   __TEXT.__ustring: 0x20a
-  __TEXT.__constg_swiftt: 0x1c5fc
-  __TEXT.__swift5_typeref: 0x41fc2
-  __TEXT.__swift5_fieldmd: 0xffbc
-  __TEXT.__swift5_reflstr: 0x11e13
+  __TEXT.__constg_swiftt: 0x1c674
+  __TEXT.__swift5_typeref: 0x41fe0
+  __TEXT.__swift5_fieldmd: 0x10000
+  __TEXT.__swift5_reflstr: 0x11e63
   __TEXT.__swift5_builtin: 0x910
   __TEXT.__swift5_assocty: 0x44b8
   __TEXT.__swift5_proto: 0x1b30
-  __TEXT.__swift5_types: 0x1360
+  __TEXT.__swift5_types: 0x1368
   __TEXT.__swift5_capture: 0x86a0
   __TEXT.__swift_as_entry: 0x5c8
   __TEXT.__swift_as_ret: 0x530
   __TEXT.__swift_as_cont: 0xc54
   __TEXT.__swift5_protos: 0xd0
   __TEXT.__swift5_mpenum: 0x128
-  __TEXT.__unwind_info: 0x3ab68
+  __TEXT.__unwind_info: 0x3add0
   __TEXT.__eh_frame: 0x10eb8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xf198
-  __DATA_CONST.__objc_classlist: 0x2ed0
+  __DATA_CONST.__const: 0xf260
+  __DATA_CONST.__objc_classlist: 0x2f08
   __DATA_CONST.__objc_catlist: 0x560
   __DATA_CONST.__objc_protolist: 0x12e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x36f90
+  __DATA_CONST.__objc_selrefs: 0x371a0
   __DATA_CONST.__objc_protorefs: 0x508
-  __DATA_CONST.__objc_superrefs: 0x1950
+  __DATA_CONST.__objc_superrefs: 0x1968
   __DATA_CONST.__objc_arraydata: 0xec0
-  __DATA_CONST.__got: 0x7730
-  __AUTH_CONST.__const: 0x3b610
-  __AUTH_CONST.__cfstring: 0x232e0
-  __AUTH_CONST.__objc_const: 0x9b500
+  __DATA_CONST.__got: 0x77c0
+  __AUTH_CONST.__const: 0x3b5f0
+  __AUTH_CONST.__cfstring: 0x233c0
+  __AUTH_CONST.__objc_const: 0x9bbd8
   __AUTH_CONST.__objc_intobj: 0xf18
   __AUTH_CONST.__objc_arrayobj: 0xde0
   __AUTH_CONST.__objc_doubleobj: 0x850
   __AUTH_CONST.__objc_floatobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x1e0
-  __AUTH_CONST.__auth_got: 0x66f0
-  __AUTH.__objc_data: 0x221b8
-  __AUTH.__data: 0x13600
-  __DATA.__objc_ivar: 0x4a10
-  __DATA.__data: 0x1ecc4
+  __AUTH_CONST.__auth_got: 0x66f8
+  __AUTH.__objc_data: 0x22438
+  __AUTH.__data: 0x13720
+  __DATA.__objc_ivar: 0x4a44
+  __DATA.__data: 0x1ef14
   __DATA.__objc_stublist: 0x38
   __DATA.__bss: 0x39e28
-  __DATA.__common: 0x11e8
+  __DATA.__common: 0x1208
   __DATA_DIRTY.__objc_data: 0xf540
   __DATA_DIRTY.__data: 0x32a8
   __DATA_DIRTY.__bss: 0x7090

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 72468
-  Symbols:   95448
-  CStrings:  12781
+  Functions: 72617
+  Symbols:   95656
+  CStrings:  12801
 
Symbols:
+ +[CKComposition(UIPasteboard) compositionByMergingResolvedCompositions:itemProviders:]
+ +[CKComposition(UIPasteboard) requestCompositionsFromItemProviders:completion:]
+ -[CKBalloonDoubleTapGestureRecognizer _ck_balloonHasActiveTextSelection]
+ -[CKBalloonDoubleTapGestureRecognizer hasDirectTouchSequence]
+ -[CKBalloonDoubleTapGestureRecognizer reset]
+ -[CKBalloonDoubleTapGestureRecognizer setHasDirectTouchSequence:]
+ -[CKBalloonDoubleTapGestureRecognizer shouldBeRequiredToFailByGestureRecognizer:]
+ -[CKBalloonDoubleTapGestureRecognizer touchesBegan:withEvent:]
+ -[CKBalloonView hasDragConflictingWithPanGesture:]
+ -[CKChatController _conversationCanSendComposition:error:]
+ -[CKChatController _detailsPresentationDecision]
+ -[CKChatController _tapCanPresentDetailsViewController]
+ -[CKChatController appendCompositionFromItemProviders:dragItems:]
+ -[CKChatController isConversationBlockedByCommunicationLimits]
+ -[CKChatController isPerformingAnimatedCompositionChange]
+ -[CKChatController messageEntryViewIsBlockedByCommunicationLimits:]
+ -[CKChatController setIsPerformingAnimatedCompositionChange:]
+ -[CKChatController setStagedDropCoordinator:]
+ -[CKChatController stagedDropCoordinator]
+ -[CKChatItem allowsCopyingMessage]
+ -[CKComposeChatController _askToManagingParentAllowedByScreenTime]
+ -[CKComposeChatController _isAskToRequestCompose]
+ -[CKComposeChatController _recipientSelectionControllerFrame]
+ -[CKComposeChatController askToAllowedByScreenTime]
+ -[CKComposeChatController askToScreenTimeHandleIDs]
+ -[CKComposeChatController conversationAllowedByScreenTime]
+ -[CKComposeChatController isChatAllowedByScreenTime:]
+ -[CKComposeChatController isConversationBlockedByCommunicationLimits]
+ -[CKComposeChatController recipientSelectionControllerShouldAllowManagingParentsWhenBlocked:]
+ -[CKComposeChatController setAskToAllowedByScreenTime:]
+ -[CKComposeChatController setAskToScreenTimeHandleIDs:]
+ -[CKCompositionResolutionSlot .cxx_destruct]
+ -[CKCompositionResolutionSlot dealloc]
+ -[CKCompositionResolutionSlot initWithDispatchGroup:]
+ -[CKCompositionResolutionSlot leave]
+ -[CKConversation canSendComposition:allowedByScreenTime:error:]
+ -[CKConversationListCollectionViewController _updateConversationListVisibilityForSearchPresented:animated:]
+ -[CKDetailsPresentationDecision .cxx_destruct]
+ -[CKDetailsPresentationDecision canPresentDetails]
+ -[CKDetailsPresentationDecision initWithCanPresentDetails:viewControllerForPresentingDetailsOverride:]
+ -[CKDetailsPresentationDecision setCanPresentDetails:]
+ -[CKDetailsPresentationDecision setViewControllerForPresentingDetailsOverride:]
+ -[CKDetailsPresentationDecision viewControllerForPresentingDetailsOverride]
+ -[CKMessageEntryRichTextView stagedImageViewForTransferGUID:]
+ -[CKPhotoStackBalloonView gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[CKRecipientSelectionController _updateSearchResultsSafeAreaExtensionView]
+ -[CKRecipientSelectionController isObservingConversationContext]
+ -[CKRecipientSelectionController searchResultsSafeAreaExtensionView]
+ -[CKRecipientSelectionController setIsObservingConversationContext:]
+ -[CKRecipientSelectionController setSearchResultsSafeAreaExtensionView:]
+ -[CKReportSpamChatItem senderIsUnknownInternational]
+ -[CKReportSpamChatItem unknownSenderTranscriptText]
+ -[CKReusableVideoPlayer playerViewController:willTransitionToVisibilityOfPlaybackControls:withAnimationCoordinator:]
+ -[CKSMSComposeController supportsInterweavedCompositionTextInsertion]
+ -[CKSearchViewController _updateTraitOverridesForCurrentSplitViewEnvironment]
+ -[CKTextBalloonView allowsTextSelection]
+ -[CKTextBalloonView hasDragConflictingWithPanGesture:]
+ -[CKTextBalloonView setAllowsTextSelection:]
+ -[CKTextBalloonView supportsTextSelection]
+ -[CKTextMessagePartChatItem allowsCopyingMessage]
+ -[CKTextReplyPreviewBalloonView supportsTextSelection]
+ -[CKTranscriptCollectionView _anyBalloonHasDragConflictingWithPanGesture:]
+ -[CKTranscriptCollectionViewController _handleTapOnBalloonView:withModifierFlags:selectedText:allowsSelection:]
+ -[CKTranscriptCollectionViewController _showsTapbacksOnMacForDoubleTapOnBalloonView:atIndexPath:]
+ -[CKTranscriptCollectionViewController balloonViewDirectTouchDoubleTapped:]
+ -[CKTranscriptCollectionViewController balloonViewDirectTouchTapped:]
+ -[CKUITheme _primarySplitViewColumnBackgroundColor]
+ -[CKVideoPlayerBalloonView _isPointInInlinePlaybackControlsZone:]
+ -[CKVideoPlayerBalloonView hasDragConflictingWithPanGesture:]
+ -[CKVideoPlayerBalloonView isShowingInlinePlaybackControls]
+ -[CKVideoPlayerBalloonView isShowingInlinePlayer]
+ -[CKVideoPlayerBalloonView reusablePlayer:didChangeVisibilityOfPlaybackControls:]
+ -[CKVideoPlayerBalloonView setShowingInlinePlaybackControls:]
+ -[UIGestureRecognizer(CKTextSelectionHelpers) _ck_waitsForBalloonDoubleTap]
+ -[UITextInteraction(CKTextSelectionHelpers) _ck_requireSingleTapToWaitForTapAndAHalf]
+ GCC_except_table1001
+ GCC_except_table1011
+ GCC_except_table1014
+ GCC_except_table1022
+ GCC_except_table1027
+ GCC_except_table1031
+ GCC_except_table1048
+ GCC_except_table1058
+ GCC_except_table1075
+ GCC_except_table1109
+ GCC_except_table1111
+ GCC_except_table1139
+ GCC_except_table1141
+ GCC_except_table1186
+ GCC_except_table1188
+ GCC_except_table1190
+ GCC_except_table1193
+ GCC_except_table1197
+ GCC_except_table1201
+ GCC_except_table1206
+ GCC_except_table1208
+ GCC_except_table1209
+ GCC_except_table1211
+ GCC_except_table1213
+ GCC_except_table1221
+ GCC_except_table1238
+ GCC_except_table1249
+ GCC_except_table178
+ GCC_except_table185
+ GCC_except_table206
+ GCC_except_table211
+ GCC_except_table214
+ GCC_except_table243
+ GCC_except_table251
+ GCC_except_table253
+ GCC_except_table262
+ GCC_except_table270
+ GCC_except_table294
+ GCC_except_table301
+ GCC_except_table307
+ GCC_except_table316
+ GCC_except_table319
+ GCC_except_table329
+ GCC_except_table330
+ GCC_except_table336
+ GCC_except_table343
+ GCC_except_table353
+ GCC_except_table355
+ GCC_except_table357
+ GCC_except_table360
+ GCC_except_table367
+ GCC_except_table368
+ GCC_except_table369
+ GCC_except_table379
+ GCC_except_table383
+ GCC_except_table405
+ GCC_except_table407
+ GCC_except_table421
+ GCC_except_table427
+ GCC_except_table430
+ GCC_except_table431
+ GCC_except_table439
+ GCC_except_table441
+ GCC_except_table446
+ GCC_except_table457
+ GCC_except_table458
+ GCC_except_table462
+ GCC_except_table463
+ GCC_except_table464
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table473
+ GCC_except_table474
+ GCC_except_table478
+ GCC_except_table482
+ GCC_except_table483
+ GCC_except_table484
+ GCC_except_table501
+ GCC_except_table511
+ GCC_except_table512
+ GCC_except_table520
+ GCC_except_table522
+ GCC_except_table526
+ GCC_except_table527
+ GCC_except_table529
+ GCC_except_table533
+ GCC_except_table537
+ GCC_except_table539
+ GCC_except_table543
+ GCC_except_table545
+ GCC_except_table547
+ GCC_except_table553
+ GCC_except_table556
+ GCC_except_table559
+ GCC_except_table560
+ GCC_except_table577
+ GCC_except_table583
+ GCC_except_table584
+ GCC_except_table587
+ GCC_except_table590
+ GCC_except_table605
+ GCC_except_table611
+ GCC_except_table620
+ GCC_except_table621
+ GCC_except_table625
+ GCC_except_table626
+ GCC_except_table629
+ GCC_except_table637
+ GCC_except_table638
+ GCC_except_table641
+ GCC_except_table644
+ GCC_except_table647
+ GCC_except_table650
+ GCC_except_table651
+ GCC_except_table657
+ GCC_except_table660
+ GCC_except_table668
+ GCC_except_table677
+ GCC_except_table681
+ GCC_except_table685
+ GCC_except_table693
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table702
+ GCC_except_table703
+ GCC_except_table707
+ GCC_except_table710
+ GCC_except_table713
+ GCC_except_table718
+ GCC_except_table725
+ GCC_except_table727
+ GCC_except_table728
+ GCC_except_table729
+ GCC_except_table731
+ GCC_except_table740
+ GCC_except_table742
+ GCC_except_table746
+ GCC_except_table756
+ GCC_except_table763
+ GCC_except_table765
+ GCC_except_table767
+ GCC_except_table768
+ GCC_except_table772
+ GCC_except_table775
+ GCC_except_table777
+ GCC_except_table784
+ GCC_except_table785
+ GCC_except_table799
+ GCC_except_table800
+ GCC_except_table803
+ GCC_except_table810
+ GCC_except_table812
+ GCC_except_table813
+ GCC_except_table817
+ GCC_except_table843
+ GCC_except_table844
+ GCC_except_table859
+ GCC_except_table860
+ GCC_except_table880
+ GCC_except_table883
+ GCC_except_table885
+ GCC_except_table908
+ GCC_except_table911
+ GCC_except_table924
+ GCC_except_table929
+ GCC_except_table932
+ GCC_except_table933
+ GCC_except_table936
+ GCC_except_table944
+ GCC_except_table945
+ GCC_except_table948
+ GCC_except_table949
+ GCC_except_table959
+ GCC_except_table963
+ GCC_except_table966
+ GCC_except_table973
+ GCC_except_table981
+ GCC_except_table988
+ GCC_except_table989
+ GCC_except_table991
+ GCC_except_table999
+ OBJC_IVAR_$_CKBalloonDoubleTapGestureRecognizer._hasDirectTouchSequence
+ OBJC_IVAR_$_CKChatController._isPerformingAnimatedCompositionChange
+ OBJC_IVAR_$_CKChatController._stagedDropCoordinator
+ OBJC_IVAR_$_CKComposeChatController._askToAllowedByScreenTime
+ OBJC_IVAR_$_CKComposeChatController._askToScreenTimeHandleIDs
+ OBJC_IVAR_$_CKCompositionResolutionSlot._didLeave
+ OBJC_IVAR_$_CKCompositionResolutionSlot._dispatchGroup
+ OBJC_IVAR_$_CKDetailsPresentationDecision._canPresentDetails
+ OBJC_IVAR_$_CKDetailsPresentationDecision._viewControllerForPresentingDetailsOverride
+ OBJC_IVAR_$_CKRecipientSelectionController._isObservingConversationContext
+ OBJC_IVAR_$_CKRecipientSelectionController._searchResultsSafeAreaExtensionView
+ OBJC_IVAR_$_CKTextBalloonView._allowsTextSelection
+ OBJC_IVAR_$_CKVideoPlayerBalloonView._showingInlinePlaybackControls
+ _IMBalloonBundleIDIsAskToRequest
+ _IMSharedHelperCurrentRegionStrengthensUnknownSenderScamWarnings
+ _OBJC_CLASS_$_CKBalloonDoubleTapGestureRecognizer
+ _OBJC_CLASS_$_CKCompositionResolutionSlot
+ _OBJC_CLASS_$_CKDetailsPresentationDecision
+ _OBJC_CLASS_$_CKStagedDropCoordinator
+ _OBJC_CLASS_$_CKStagedImageTextAttachment
+ _OBJC_CLASS_$_LPHomeAccessoryInfo
+ _OBJC_METACLASS_$_CKBalloonDoubleTapGestureRecognizer
+ _OBJC_METACLASS_$_CKCompositionResolutionSlot
+ _OBJC_METACLASS_$_CKDetailsPresentationDecision
+ _OBJC_METACLASS_$_CKStagedDropCoordinator
+ _OBJC_METACLASS_$_CKStagedImageTextAttachment
+ _OBJC_METACLASS_$__TtC7ChatKitP33_46950E96D597C3C2B2F6D28ED528938B39CKStagedImageTextAttachmentViewProvider
+ __CLASS_METHODS_CKStagedImageTextAttachment
+ __CLASS_PROPERTIES_CKStagedImageTextAttachment
+ __DATA_CKStagedDropCoordinator
+ __DATA_CKStagedImageTextAttachment
+ __DATA__TtC7ChatKitP33_43F7786CC9C2682E0D21B0BB8AA55ED016CKStagedDropItem
+ __DATA__TtC7ChatKitP33_46950E96D597C3C2B2F6D28ED528938B39CKStagedImageTextAttachmentViewProvider
+ __INSTANCE_METHODS_CKStagedDropCoordinator
+ __INSTANCE_METHODS_CKStagedImageTextAttachment
+ __INSTANCE_METHODS__TtC7ChatKitP33_46950E96D597C3C2B2F6D28ED528938B39CKStagedImageTextAttachmentViewProvider
+ __IVARS_CKStagedImageTextAttachment
+ __IVARS__TtC7ChatKitP33_43F7786CC9C2682E0D21B0BB8AA55ED016CKStagedDropItem
+ __METACLASS_DATA_CKStagedDropCoordinator
+ __METACLASS_DATA_CKStagedImageTextAttachment
+ __METACLASS_DATA__TtC7ChatKitP33_43F7786CC9C2682E0D21B0BB8AA55ED016CKStagedDropItem
+ __METACLASS_DATA__TtC7ChatKitP33_46950E96D597C3C2B2F6D28ED528938B39CKStagedImageTextAttachmentViewProvider
+ __OBJC_$_INSTANCE_METHODS_CKBalloonDoubleTapGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS_CKCompositionResolutionSlot
+ __OBJC_$_INSTANCE_METHODS_CKDetailsPresentationDecision
+ __OBJC_$_INSTANCE_VARIABLES_CKBalloonDoubleTapGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES_CKCompositionResolutionSlot
+ __OBJC_$_INSTANCE_VARIABLES_CKDetailsPresentationDecision
+ __OBJC_$_PROP_LIST_CKBalloonDoubleTapGestureRecognizer
+ __OBJC_$_PROP_LIST_CKDetailsPresentationDecision
+ __OBJC_CLASS_RO_$_CKBalloonDoubleTapGestureRecognizer
+ __OBJC_CLASS_RO_$_CKCompositionResolutionSlot
+ __OBJC_CLASS_RO_$_CKDetailsPresentationDecision
+ __OBJC_METACLASS_RO_$_CKBalloonDoubleTapGestureRecognizer
+ __OBJC_METACLASS_RO_$_CKCompositionResolutionSlot
+ __OBJC_METACLASS_RO_$_CKDetailsPresentationDecision
+ __PROPERTIES_CKStagedImageTextAttachment
+ ___107-[CKConversationListCollectionViewController _updateConversationListVisibilityForSearchPresented:animated:]_block_invoke
+ ___107-[CKConversationListCollectionViewController _updateConversationListVisibilityForSearchPresented:animated:]_block_invoke_2
+ ___116-[CKReusableVideoPlayer playerViewController:willTransitionToVisibilityOfPlaybackControls:withAnimationCoordinator:]_block_invoke
+ ___51-[CKUITheme _primarySplitViewColumnBackgroundColor]_block_invoke
+ ___65-[CKChatController appendCompositionFromItemProviders:dragItems:]_block_invoke
+ ___65-[CKChatController appendCompositionFromItemProviders:dragItems:]_block_invoke_2
+ ___65-[CKChatController appendCompositionFromItemProviders:dragItems:]_block_invoke_3
+ ___71-[CKChatController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke_6
+ ___79+[CKComposition(UIPasteboard) requestCompositionsFromItemProviders:completion:]_block_invoke
+ ___79+[CKComposition(UIPasteboard) requestCompositionsFromItemProviders:completion:]_block_invoke_2
+ ___79+[CKComposition(UIPasteboard) requestCompositionsFromItemProviders:completion:]_block_invoke_3
+ ___86+[CKComposition(UIPasteboard) compositionByMergingResolvedCompositions:itemProviders:]_block_invoke
+ ___block_descriptor_40_e8_32r_e15_v32?08Q16^B24lr32l8
+ ___block_descriptor_49_e8_32s_e8_v12?0B8ls32l8
+ ___block_descriptor_56_e8_32s40s48w_e17_v16?0"NSArray"8lw48l8s32l8s40l8
+ ___block_descriptor_57_e8_32s40s_e31_v32?0"NSItemProvider"8Q16^B24ls32l8s40l8
+ ___block_descriptor_58_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ _objc_msgSend$_anyBalloonHasDragConflictingWithPanGesture:
+ _objc_msgSend$_askToManagingParentAllowedByScreenTime
+ _objc_msgSend$_ck_balloonHasActiveTextSelection
+ _objc_msgSend$_ck_requireSingleTapToWaitForTapAndAHalf
+ _objc_msgSend$_ck_waitsForBalloonDoubleTap
+ _objc_msgSend$_conversationCanSendComposition:error:
+ _objc_msgSend$_detailsPresentationDecision
+ _objc_msgSend$_handleTapOnBalloonView:withModifierFlags:selectedText:allowsSelection:
+ _objc_msgSend$_isAskToRequestCompose
+ _objc_msgSend$_isPointInInlinePlaybackControlsZone:
+ _objc_msgSend$_primarySplitViewColumnBackgroundColor
+ _objc_msgSend$_recipientSelectionControllerFrame
+ _objc_msgSend$_showsTapbacksOnMacForDoubleTapOnBalloonView:atIndexPath:
+ _objc_msgSend$_tapCanPresentDetailsViewController
+ _objc_msgSend$_updateConversationListVisibilityForSearchPresented:animated:
+ _objc_msgSend$_updateSearchResultsSafeAreaExtensionView
+ _objc_msgSend$_updateTraitOverridesForCurrentSplitViewEnvironment
+ _objc_msgSend$addCoordinatedAnimations:completion:
+ _objc_msgSend$allowedToShowConversationWithHandleIDs:sync:allowingManagingParents:context:
+ _objc_msgSend$allowsCopyingMessage
+ _objc_msgSend$allowsTextSelection
+ _objc_msgSend$appendCompositionFromItemProviders:dragItems:
+ _objc_msgSend$askToAllowedByScreenTime
+ _objc_msgSend$askToScreenTimeHandleIDs
+ _objc_msgSend$attachStagedViewsForDragItems:inEntryView:
+ _objc_msgSend$balloonViewDirectTouchDoubleTapped:
+ _objc_msgSend$balloonViewDirectTouchTapped:
+ _objc_msgSend$canPresentDetails
+ _objc_msgSend$canSendComposition:allowedByScreenTime:error:
+ _objc_msgSend$compositionByMergingResolvedCompositions:itemProviders:
+ _objc_msgSend$contentLine1
+ _objc_msgSend$contentLine2
+ _objc_msgSend$dropAnimationDidFinishForDragItem:
+ _objc_msgSend$dropSessionDidEndWithDragItems:
+ _objc_msgSend$hasDirectTouchSequence
+ _objc_msgSend$hasDragConflictingWithPanGesture:
+ _objc_msgSend$iconSymbolName
+ _objc_msgSend$initWithCanPresentDetails:viewControllerForPresentingDetailsOverride:
+ _objc_msgSend$initWithDispatchGroup:
+ _objc_msgSend$initWithTextAttachment:parentView:textLayoutManager:location:
+ _objc_msgSend$introductionsLabelStyle
+ _objc_msgSend$isConversationBlockedByCommunicationLimits
+ _objc_msgSend$isEnabledByDefault
+ _objc_msgSend$isObservingConversationContext
+ _objc_msgSend$isPerformingAnimatedCompositionChange
+ _objc_msgSend$isShowingInlinePlaybackControls
+ _objc_msgSend$isShowingInlinePlayer
+ _objc_msgSend$messageEntryViewIsBlockedByCommunicationLimits:
+ _objc_msgSend$populateAccessoryInfoMetadata:fileMetadata:fromFile:
+ _objc_msgSend$recipientSelectionControllerShouldAllowManagingParentsWhenBlocked:
+ _objc_msgSend$recordStagedTransfersForDragItems:resolvedCompositions:
+ _objc_msgSend$requestCompositionsFromItemProviders:completion:
+ _objc_msgSend$reusablePlayer:didChangeVisibilityOfPlaybackControls:
+ _objc_msgSend$senderIsUnknownInternational
+ _objc_msgSend$setAllowsTextSelection:
+ _objc_msgSend$setAskToAllowedByScreenTime:
+ _objc_msgSend$setAskToScreenTimeHandleIDs:
+ _objc_msgSend$setCanPresentDetails:
+ _objc_msgSend$setHasDirectTouchSequence:
+ _objc_msgSend$setIntroductionsLabelStyle:
+ _objc_msgSend$setIsObservingConversationContext:
+ _objc_msgSend$setIsPerformingAnimatedCompositionChange:
+ _objc_msgSend$setNeedsDropPreviewUpdate
+ _objc_msgSend$setShowingInlinePlaybackControls:
+ _objc_msgSend$setViewControllerForPresentingDetailsOverride:
+ _objc_msgSend$stagedDropCoordinator
+ _objc_msgSend$stagedImageView
+ _objc_msgSend$stagedImageViewForTransferGUID:
+ _objc_msgSend$stagedPreviewForDragItem:inTextView:
+ _objc_msgSend$supportsTextSelection
+ _objc_msgSend$textInputView
+ _objc_msgSend$unknownSenderTranscriptText
+ _objc_msgSend$viewControllerForPresentingDetailsOverride
+ _symbolic So10UIDragItemC_ypt
+ _symbolic _____ 7ChatKit16CKStagedDropItem33_43F7786CC9C2682E0D21B0BB8AA55ED0LLC
+ _symbolic _____ 7ChatKit39CKStagedImageTextAttachmentViewProvider33_46950E96D597C3C2B2F6D28ED528938BLLC
- -[CKBalloonView isTextSelectionDragActive]
- -[CKChatController appendCompositionFromItemProviders:]
- -[CKTextBalloonView isTextSelectionDragActive]
- -[CKTranscriptCollectionView _hasActiveTextSelectionDrag]
- -[CKTranscriptCollectionViewController _shouldBlockUnknownSenderRichLinks]
- -[CKTranscriptCollectionViewController updateTranscriptChatItems:inserted:removed:reload:regenerate:animated:checkFiltered:completion:]
- -[CKUITheme _conversationListBackgroundColor]
- GCC_except_table1005
- GCC_except_table1008
- GCC_except_table1025
- GCC_except_table1042
- GCC_except_table1052
- GCC_except_table1055
- GCC_except_table1102
- GCC_except_table1104
- GCC_except_table1127
- GCC_except_table1132
- GCC_except_table1179
- GCC_except_table1181
- GCC_except_table1183
- GCC_except_table1185
- GCC_except_table1187
- GCC_except_table1195
- GCC_except_table1196
- GCC_except_table1200
- GCC_except_table1203
- GCC_except_table1205
- GCC_except_table1207
- GCC_except_table1215
- GCC_except_table1232
- GCC_except_table1243
- GCC_except_table166
- GCC_except_table173
- GCC_except_table179
- GCC_except_table201
- GCC_except_table219
- GCC_except_table244
- GCC_except_table250
- GCC_except_table252
- GCC_except_table256
- GCC_except_table260
- GCC_except_table274
- GCC_except_table280
- GCC_except_table281
- GCC_except_table290
- GCC_except_table305
- GCC_except_table309
- GCC_except_table331
- GCC_except_table332
- GCC_except_table352
- GCC_except_table354
- GCC_except_table356
- GCC_except_table363
- GCC_except_table364
- GCC_except_table365
- GCC_except_table366
- GCC_except_table380
- GCC_except_table384
- GCC_except_table386
- GCC_except_table398
- GCC_except_table401
- GCC_except_table417
- GCC_except_table424
- GCC_except_table425
- GCC_except_table426
- GCC_except_table435
- GCC_except_table437
- GCC_except_table450
- GCC_except_table451
- GCC_except_table452
- GCC_except_table455
- GCC_except_table468
- GCC_except_table469
- GCC_except_table475
- GCC_except_table477
- GCC_except_table488
- GCC_except_table490
- GCC_except_table495
- GCC_except_table496
- GCC_except_table509
- GCC_except_table515
- GCC_except_table518
- GCC_except_table523
- GCC_except_table530
- GCC_except_table532
- GCC_except_table534
- GCC_except_table536
- GCC_except_table540
- GCC_except_table542
- GCC_except_table549
- GCC_except_table550
- GCC_except_table551
- GCC_except_table555
- GCC_except_table572
- GCC_except_table578
- GCC_except_table579
- GCC_except_table581
- GCC_except_table582
- GCC_except_table585
- GCC_except_table588
- GCC_except_table597
- GCC_except_table600
- GCC_except_table603
- GCC_except_table615
- GCC_except_table616
- GCC_except_table618
- GCC_except_table627
- GCC_except_table633
- GCC_except_table634
- GCC_except_table642
- GCC_except_table645
- GCC_except_table646
- GCC_except_table652
- GCC_except_table653
- GCC_except_table656
- GCC_except_table666
- GCC_except_table667
- GCC_except_table670
- GCC_except_table680
- GCC_except_table686
- GCC_except_table688
- GCC_except_table689
- GCC_except_table692
- GCC_except_table698
- GCC_except_table699
- GCC_except_table700
- GCC_except_table704
- GCC_except_table709
- GCC_except_table716
- GCC_except_table719
- GCC_except_table720
- GCC_except_table721
- GCC_except_table723
- GCC_except_table735
- GCC_except_table736
- GCC_except_table737
- GCC_except_table739
- GCC_except_table753
- GCC_except_table754
- GCC_except_table760
- GCC_except_table761
- GCC_except_table764
- GCC_except_table771
- GCC_except_table782
- GCC_except_table783
- GCC_except_table795
- GCC_except_table796
- GCC_except_table801
- GCC_except_table806
- GCC_except_table807
- GCC_except_table811
- GCC_except_table837
- GCC_except_table838
- GCC_except_table847
- GCC_except_table854
- GCC_except_table874
- GCC_except_table877
- GCC_except_table879
- GCC_except_table902
- GCC_except_table905
- GCC_except_table918
- GCC_except_table923
- GCC_except_table926
- GCC_except_table927
- GCC_except_table930
- GCC_except_table938
- GCC_except_table939
- GCC_except_table942
- GCC_except_table943
- GCC_except_table951
- GCC_except_table953
- GCC_except_table960
- GCC_except_table965
- GCC_except_table967
- GCC_except_table970
- GCC_except_table975
- GCC_except_table979
- GCC_except_table987
- GCC_except_table992
- GCC_except_table995
- _IMServiceCapabilityDisplayUnknownSenderLinks
- ___45-[CKUITheme _conversationListBackgroundColor]_block_invoke
- ___55-[CKChatController appendCompositionFromItemProviders:]_block_invoke
- ___55-[CKChatController appendCompositionFromItemProviders:]_block_invoke_2
- ___55-[CKChatController appendCompositionFromItemProviders:]_block_invoke_3
- ___55-[CKChatController appendCompositionFromItemProviders:]_block_invoke_4
- _objc_msgSend$_conversationListBackgroundColor
- _objc_msgSend$_hasActiveTextSelectionDrag
- _objc_msgSend$_shouldBlockUnknownSenderRichLinks
- _objc_msgSend$appendCompositionFromItemProviders:
- _objc_msgSend$chatWantsIntroductionsLabel
- _objc_msgSend$isTextSelectionDragActive
- _objc_msgSend$muteIdentifiersForChat:
- _objc_msgSend$setShouldDisplayRichLink:
- _objc_msgSend$setShouldShowIntroductionsLabel:
- _objc_msgSend$shouldShowIntroductionsLabel
- _objc_msgSend$updateTranscriptChatItems:inserted:removed:reload:regenerate:animated:checkFiltered:completion:
- searchControllerObscuresConversationList.sBehavior
CStrings:
+ "-[CKTranscriptCollectionViewController _handleTapOnBalloonView:withModifierFlags:selectedText:allowsSelection:]"
+ "Balloon view %p was double tapped by direct touch delegate=<%@:%p>"
+ "Balloon view %p was tapped by direct touch delegate=<%@:%p>"
+ "Calling into delegate to handle touch balloon double tap with indexPath %@, delegate: %@"
+ "Drop preview generation failed because the entry view's text view is not in a window. UIDragPreviewTarget requires that its container be in a window."
+ "DropInteraction returned a staged image preview"
+ "Ignoring direct touch tap on balloonView %@ because it is showing an inline player"
+ "Ignoring touch balloon double tap: no index path for balloonView %@"
+ "Not starting text selection: copying is not allowed for this message"
+ "REPORT_SPAM_SCAM_STATUS"
+ "Received balloonViewDirectTouchDoubleTapped: callback for balloonView %@"
+ "Received balloonViewDirectTouchTapped: callback for balloonView %@"
+ "Refusing to copy: copying is not allowed for any selected message"
+ "SENDER_IS_UNKNOWN_INTERNATIONAL_SENDER_SCAM_STATUS"
+ "UITextInteractionNameDoubleTap"
+ "UITextInteractionNameSingleTap"
+ "UITextInteractionNameTapAndAHalf"
+ "Unexpectedly had no destination imageView available to morph into."
+ "Unexpectedly had to skip a dragItem because no transferGUID was available."
+ "Unexpectedly had to skip a dragItem because there was no stagedItem already prepared."
+ "Updating conversation list view visibility for searchPresented=%{BOOL}d, shouldHideConversationList=%{BOOL}d, animated=%{BOOL}d"
+ "com.apple.Music"
+ "com.apple.home.accessoryinfo"
+ "stagedPreviewForDragItem has valid target view, and will center at (%f, %f)"
- "-[CKTranscriptCollectionViewController balloonViewTapped:withModifierFlags:selectedText:]"
- ": NOT muted (expired "
- "Drop preview generation failed because the entry view is not in a window. UIDragPreviewTarget requires that its container (the entry view in this case) be in a window."
- "Mute Identifiers"
```
