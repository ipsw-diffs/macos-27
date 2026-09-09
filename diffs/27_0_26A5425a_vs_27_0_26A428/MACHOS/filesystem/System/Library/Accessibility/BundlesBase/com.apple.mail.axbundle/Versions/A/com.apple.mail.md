## com.apple.mail

> `/System/Library/Accessibility/BundlesBase/com.apple.mail.axbundle/Versions/A/com.apple.mail`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xb1d4
+  __TEXT.__text: 0xac10
   __TEXT.__auth_stubs: 0x310
   __TEXT.__objc_stubs: 0x19e0
   __TEXT.__objc_methlist: 0x1114

   __TEXT.__objc_methname: 0x1888
   __TEXT.__objc_methtype: 0x13f
   __TEXT.__oslogstring: 0x71
-  __TEXT.__unwind_info: 0x488
+  __TEXT.__unwind_info: 0x538
   __DATA_CONST.__const: 0x4a0
   __DATA_CONST.__cfstring: 0x2cc0
   __DATA_CONST.__objc_classlist: 0x2f0
Functions:
~ +[ComposeSpellCheckerAccessibility _accessibilityPerformValidations:] : 268 -> 256
~ -[ComposeSpellCheckerAccessibility setPostCompletedNotification:forSpellDocumentWithTag:] : 456 -> 432
~ -[ComposeSpellCheckerAccessibility _axcObjectForSpellDocumentTag:] : 260 -> 248
~ ___66-[ComposeSpellCheckerAccessibility _axcObjectForSpellDocumentTag:]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[ComposeSpellCheckerAccessibility _axcCreateUserInfoDictionaryWithTag:spellCheckingSucceeded:] : 224 -> 212
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ +[NSSearchToolbarItemViewAccessibility__Mail__AppKit _accessibilityPerformValidations:] : 204 -> 192
~ +[NSFontAccessibility__Mail__AppKit _accessibilityPerformValidations:] : 224 -> 212
~ +[NSFontAccessibility__Mail__AppKit messageListFont] : 664 -> 652
~ ___52+[NSFontAccessibility__Mail__AppKit messageListFont]_block_invoke : 80 -> 68
~ __52+[NSFontAccessibility__Mail__AppKit messageListFont]_block_invoke.375 : 96 -> 84
~ +[MailTableViewAccessibility _accessibilityPerformValidations:] : 156 -> 144
~ -[MailTableViewAccessibility accessibilityIdentifier] : 108 -> 96
~ +[NSCollectionViewSectionAccessibilityAccessibility__Mail__AppKit _accessibilityPerformValidations:] : 284 -> 272
~ -[NSCollectionViewSectionAccessibilityAccessibility__Mail__AppKit accessibilityLabel] : 516 -> 504
~ -[NSCollectionViewSectionAccessibilityAccessibility__Mail__AppKit _accessibilitySearchSectionLabelForKey:] : 188 -> 176
~ ___106-[NSCollectionViewSectionAccessibilityAccessibility__Mail__AppKit _accessibilitySearchSectionLabelForKey:]_block_invoke : 256 -> 244
~ +[MailSuggestionAttachmentCellAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ -[MailSuggestionAttachmentCellAccessibility accessibilityValueAttribute] : 260 -> 248
~ +[MessageViewerAccessibility _accessibilityPerformValidations:] : 632 -> 620
~ -[MessageViewerAccessibility touchBar:makeItemForIdentifier:] : 1240 -> 1228
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ +[MessageViewerAccessibility _axcAllMessageViewers] : 344 -> 332
~ ___51+[MessageViewerAccessibility _axcAllMessageViewers]_block_invoke : 80 -> 68
~ -[MessageViewerAccessibility _axcMoveToFolderSegmentedControl] : 332 -> 320
~ ___62-[MessageViewerAccessibility _axcMoveToFolderSegmentedControl]_block_invoke : 80 -> 68
~ -[MessageViewerAccessibility _axcMoveToFolderSegmentedControlCell] : 332 -> 320
~ ___66-[MessageViewerAccessibility _axcMoveToFolderSegmentedControlCell]_block_invoke : 100 -> 88
~ -[MessageViewerAccessibility _axcMailboxPredictionForSelection] : 316 -> 304
~ ___63-[MessageViewerAccessibility _axcMailboxPredictionForSelection]_block_invoke : 80 -> 68
~ -[MessageViewerAccessibility _axcMailBoxDisplayName] : 384 -> 372
~ ___52-[MessageViewerAccessibility _axcMailBoxDisplayName]_block_invoke : 80 -> 68
~ +[MessageViewerAccessibility _axcUpdateUserFont] : 204 -> 192
~ +[MessageViewerAccessibility _axcUpdateUserFixedPitchFont] : 204 -> 192
~ -[DocumentCollectionViewItemAccessibility accessibilityLabel] : 324 -> 312
~ ___61-[DocumentCollectionViewItemAccessibility accessibilityLabel]_block_invoke : 140 -> 128
~ _accessibilityGetLabelForConversationMember : 792 -> 780
~ ___accessibilityGetLabelForConversationMember_block_invoke : 88 -> 76
~ +[AttachmentViewControllerAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[_PaddedTextAttachmentCellAccessibility accessibilityLabel] : 244 -> 232
~ -[TransparentImageViewAccessibility accessibilityChildren] : 80 -> 68
~ +[FlagButtonImageViewAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[FlagButtonImageViewAccessibility accessibilityLabel] : 132 -> 120
~ +[MailTrackingProtectionOnboardingButtonAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ -[MailTrackingProtectionOnboardingButtonAccessibility accessibilityValue] : 64 -> 52
~ -[MailTrackingProtectionOnboardingButtonAccessibility accessibilityLabel] : 360 -> 348
~ +[MailboxBadgeCellAccessibility _accessibilityPerformValidations:] : 276 -> 264
~ -[MailboxBadgeCellAccessibility accessibilityLabel] : 516 -> 504
~ +[HeaderTruncationAttachmentCellAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[HeaderTruncationAttachmentCellAccessibility accessibilityActionNames] : 256 -> 244
~ +[_FavoriteButtonCellAccessibility _accessibilityPerformValidations:] : 268 -> 256
~ -[_FavoriteButtonCellAccessibility accessibilityLabel] : 88 -> 76
~ -[_FavoriteButtonCellAccessibility accessibilityRoleDescription] : 192 -> 180
~ -[_FavoriteButtonCellAccessibility accessibilityActionNames] : 168 -> 156
~ -[_FavoriteButtonCellAccessibility accessibilityActionDescription:] : 188 -> 176
~ +[HeaderViewControllerAccessibility _accessibilityPerformValidations:] : 324 -> 312
~ +[HeaderViewControllerAccessibility _mailboxIconString] : 224 -> 212
~ -[HeaderViewControllerAccessibility _axcTextView] : 312 -> 300
~ ___49-[HeaderViewControllerAccessibility _axcTextView]_block_invoke : 80 -> 68
~ -[HeaderViewControllerAccessibility _axcTruncationCell] : 332 -> 320
~ ___55-[HeaderViewControllerAccessibility _axcTruncationCell]_block_invoke : 80 -> 68
~ -[HeaderViewControllerAccessibility _axcUpdateDetailsAttachmentCell] : 80 -> 68
~ +[MailboxOutlineItemViewAccessibility _accessibilityPerformValidations:] : 180 -> 168
~ -[MailboxOutlineItemViewAccessibility _axcHeaderIndicatorView] : 584 -> 572
~ ___62-[MailboxOutlineItemViewAccessibility _axcHeaderIndicatorView]_block_invoke : 120 -> 108
~ -[MailboxOutlineItemViewAccessibility accessibilityChildren] : 260 -> 248
~ -[MailboxOutlineItemViewAccessibility accessibilityCustomActions] : 496 -> 484
~ ___65-[MailboxOutlineItemViewAccessibility accessibilityCustomActions]_block_invoke_2 : 88 -> 76
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ ___copy_helper_block_e8_32w40w : 72 -> 60
~ ___destroy_helper_block_e8_32w40w : 60 -> 48
~ +[MessageListCellAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[MessageListCellAccessibility accessibilityDescriptionAttribute] : 144 -> 132
~ -[MessageListCellAccessibility accessibilityRole] : 156 -> 144
~ -[MessageListCellAccessibility accessibilityValue] : 144 -> 132
~ +[AttachmentViewAccessibility _accessibilityPerformValidations:] : 184 -> 172
~ -[AttachmentViewAccessibility accessibilityAttributeNames] : 232 -> 220
~ -[AttachmentViewAccessibility accessibilityAttributeValue:] : 316 -> 304
~ -[AttachmentViewAccessibility accessibilityActionNames] : 140 -> 128
~ +[ListSuggestionCollectionViewItemAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ -[ListSuggestionCollectionViewItemAccessibility accessibilityLabel] : 324 -> 312
~ +[HeadersEditorAccessibility _accessibilityPerformValidations:] : 264 -> 252
~ +[MailSearchFieldCellAccessibility _accessibilityPerformValidations:] : 248 -> 236
~ -[MailSearchFieldCellAccessibility accessibilitySharedFocusElements] : 412 -> 400
~ +[QuickReplyViewAccessibility _accessibilityPerformValidations:] : 316 -> 304
~ ___73-[QuickReplyViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 192 -> 180
~ -[QuickReplyViewAccessibility accessibilityContents] : 184 -> 172
~ -[QuickReplyViewAccessibility accessibilityLabel] : 188 -> 176
~ +[FavoritesMenuControllerAccessibility _accessibilityPerformValidations:] : 188 -> 176
~ -[ViewingPaneViewControllerAccessibility accessibilityLinkTarget] : 376 -> 364
~ ___65-[ViewingPaneViewControllerAccessibility accessibilityLinkTarget]_block_invoke : 80 -> 68
~ -[NSImageAccessibility__Mail__AppKit __axcDescription] : 276 -> 264
~ -[NSImageAccessibility__Mail__AppKit accessibilityDescription] : 152 -> 140
~ +[ConversationViewControllerAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[TableViewManagerAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ -[TableViewManagerAccessibility _unreadActionIsRead:isChild:] : 176 -> 164
~ -[TableViewManagerAccessibility _deleteActionForMessageCount:] : 156 -> 144
~ +[AXMailGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___57+[AXMailGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___57+[AXMailGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 1036 -> 1024
~ _accessibilityLocalizedString : 184 -> 172
~ -[ContactCollectionViewItemAccessibility accessibilityLabel] : 324 -> 312
~ ___60-[ContactCollectionViewItemAccessibility accessibilityLabel]_block_invoke : 140 -> 128
~ +[ProgressViewControllerAccessibility _accessibilityPerformValidations:] : 232 -> 220
~ +[SearchSuggestionsCollectionViewAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[ComposeViewControllerAccessibility touchBar:makeItemForIdentifier:] : 648 -> 636
~ +[ActivityViewControllerAccessibility _accessibilityPerformValidations:] : 212 -> 200
~ +[SGBannerViewAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[MessageViewControllerAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[MailSearchFieldAccessibility accessibilityLinkedUIElements] : 232 -> 220
~ -[AXCAccessibleFilterCheckbox accessibilityValue] : 152 -> 140
~ -[AXCAccessibleFilterCheckbox accessibilityLabel] : 80 -> 68
~ -[AXCAccessibleFilterCheckbox _tableRowView] : 132 -> 120
~ -[AXCAccessibleFilterCheckbox _textFieldCell] : 384 -> 372
~ -[AXCAccessibleFilterCheckbox .cxx_destruct] : 104 -> 92
~ -[LocationCollectionViewItemAccessibility accessibilityLabel] : 576 -> 564
~ ___61-[LocationCollectionViewItemAccessibility accessibilityLabel]_block_invoke : 140 -> 128
```
