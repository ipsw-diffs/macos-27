## TextEdit

> `/System/Applications/TextEdit.app/Contents/MacOS/TextEdit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 419.0.0.0.0
-  __TEXT.__text: 0x14fcc
+  __TEXT.__text: 0x147bc
   __TEXT.__auth_stubs: 0x490
   __TEXT.__objc_stubs: 0x5440
   __TEXT.__objc_methlist: 0x1730

   __TEXT.__swift5_capture: 0x20
   __TEXT.__swift5_proto: 0x8
   __TEXT.__swift5_types: 0x18
-  __TEXT.__unwind_info: 0x688
+  __TEXT.__unwind_info: 0x830
   __DATA_CONST.__const: 0x940
   __DATA_CONST.__cfstring: 0x1a20
   __DATA_CONST.__objc_classlist: 0x98
Functions:
~ +[Controller initialize] : 212 -> 200
~ -[Controller applicationDidFinishLaunching:] : 72 -> 60
~ -[Document setBackgroundColor:] : 80 -> 68
~ -[Document knownDocumentProperties] : 40 -> 28
~ -[Document setValue:forKey:] : 156 -> 144
~ -[DocumentController defaultType] : 88 -> 76
~ -[Document readFromURL:ofType:error:] : 168 -> 156
~ -[DocumentController lastSelectedIgnoreHTMLForURL:] : 112 -> 100
~ -[DocumentController lastSelectedIgnoreRichForURL:] : 112 -> 100
~ -[DocumentController lastSelectedEncodingForURL:] : 84 -> 72
~ -[Document(TextEditNSDocumentOverrides) makeWindowControllers] : 116 -> 104
~ -[DocumentWindowController firstTextView] : 60 -> 48
~ -[DocumentWindowController configureTypingAttributesAndDefaultParagraphStyleForTextView:] : 156 -> 144
~ -[Document isRichText] : 72 -> 60
~ -[DocumentWindowController(Delegation) layoutManager:didCompleteLayoutForTextContainer:atEnd:] : 364 -> 340
~ -[DocumentWindowController setupInitialTextViewSharedState] : 80 -> 68
~ -[DocumentWindowController setupWindowForDocument] : 648 -> 636
~ -[DocumentWindowController observeValueForKeyPath:ofObject:change:context:] : 648 -> 576
~ -[DocumentWindowController resizeWindowForViewSize:] : 416 -> 404
~ _validateToggleItem : 144 -> 132
~ -[DocumentWindowController(Delegation) windowDidMove:] : 44 -> 32
~ -[DocumentWindowController showRuler:] : 136 -> 124
~ -[EncodingManager setupPopUpCell:selectedEncoding:withDefaultEntry:] : 612 -> 600
~ -[Document setPaperSize:] : 156 -> 144
~ -[DocumentController displayDocument:] : 140 -> 116
~ -[DocumentWindowController breakUndoCoalescing] : 40 -> 28
~ -[Document(TextEditNSDocumentOverrides) canAsynchronouslyWriteToURL:ofType:forSaveOperation:] : 56 -> 44
~ -[Document paperSize] : 40 -> 28
~ -[Document(TextEditNSDocumentOverrides) autosavingFileType] : 212 -> 200
~ -[PrintPanelAccessoryController setPageNumbering:] : 96 -> 84
~ -[NSTextView(TextEditAdditions) textEditDoForegroundLayoutToCharacterIndex:] : 332 -> 308
~ -[PrintPanelAccessoryController pageNumbering] : 60 -> 48
~ -[Document togglePageBreaks:] : 60 -> 48
~ -[MultiplePageView setLineColor:] : 140 -> 128
~ -[MultiplePageView setMarginColor:] : 140 -> 128
~ -[MultiplePageView setPrintInfo:] : 144 -> 132
~ -[MultiplePageView updateFrame] : 296 -> 284
~ -[DocumentWindowController numberOfPages] : 88 -> 76
~ -[MultiplePageView setNumberOfPages:] : 200 -> 188
~ -[Preferences windowDidLoad] : 108 -> 96
~ ___39-[Document applyDefaultTextAttributes:]_block_invoke_2 : 132 -> 120
~ ___copy_helper_block_e8_32o40o : 80 -> 68
~ ___destroy_helper_block_e8_32o40o : 68 -> 56
~ ___45-[Document printOperationWithSettings:error:]_block_invoke : 72 -> 60
~ -[Document toggleReadOnly:] : 184 -> 172
~ -[Document toggleHyphenation:] : 88 -> 76
~ -[Document encodingPopupChanged:] : 72 -> 60
~ -[Document setTextStorage:] : 212 -> 188
~ ___93-[Document(TextEditNSDocumentOverrides) saveToURL:ofType:forSaveOperation:completionHandler:]_block_invoke_2 : 96 -> 84
~ ___copy_helper_block_e8_32o40b48b : 96 -> 84
~ ___destroy_helper_block_e8_32o40b48b : 80 -> 68
~ ___copy_helper_block_e8_32o40o48o56b : 112 -> 100
~ ___destroy_helper_block_e8_32o40o48o56b : 92 -> 80
~ -[Document(TextEditNSDocumentOverrides) errorInTextEditDomainWithCode:] : 1672 -> 1660
~ ___59-[Document(TextEditNSDocumentOverrides) updateChangeCount:]_block_invoke : 112 -> 88
~ ___59-[Document(TextEditNSDocumentOverrides) updateChangeCount:]_block_invoke_2 : 116 -> 104
~ ___copy_helper_block_e8_32o40b : 80 -> 68
~ ___destroy_helper_block_e8_32o40b : 68 -> 56
~ ___copy_helper_block_e8_32o40o48o : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48o : 80 -> 68
~ -[Document(TextEditNSDocumentOverrides) document:didSave:block:] : 72 -> 60
~ -[Document(TextEditNSDocumentOverrides) didPresentErrorWithRecovery:block:] : 72 -> 60
~ ___118-[Document(TextEditNSDocumentOverrides) attemptRecoveryFromError:optionIndex:delegate:didRecoverSelector:contextInfo:]_block_invoke : 68 -> 56
~ ___118-[Document(TextEditNSDocumentOverrides) attemptRecoveryFromError:optionIndex:delegate:didRecoverSelector:contextInfo:]_block_invoke_2 : 72 -> 60
~ _truncatedString : 144 -> 132
~ -[Controller _setUpFormatMenu] : 72 -> 60
~ -[Controller(AppleSelfTestSupport) endTest:] : 176 -> 164
~ ___64-[Controller(AppleSelfTestSupport) application:runTest:options:]_block_invoke_3 : 76 -> 64
~ __64-[Controller(AppleSelfTestSupport) application:runTest:options:]_block_invoke.309 : 64 -> 52
~ -[ScalingScrollView zoomToActualSize:] : 44 -> 32
~ -[ScalingScrollView zoomIn:] : 108 -> 96
~ -[ScalingScrollView zoomOut:] : 112 -> 100
~ +[Preferences restoreWindowWithIdentifier:state:completionHandler:] : 92 -> 80
~ -[Preferences changeRichTextFont:] : 144 -> 132
~ -[Preferences changePlainTextFont:] : 140 -> 128
~ -[Preferences changeFont:] : 152 -> 128
~ -[Preferences setHTMLDocumentType:] : 96 -> 84
~ -[Preferences setHTMLStylingMode:] : 132 -> 120
~ -[Preferences revertToDefault:] : 240 -> 228
~ -[EncodingsWindowController encodingListChanged:] : 232 -> 220
~ -[EncodingsWindowController clearAll:] : 48 -> 36
~ -[EncodingsWindowController selectAll:] : 48 -> 36
~ -[EncodingsWindowController revertToDefault:] : 48 -> 36
~ -[EncodingManager(UIExtension) showPanel:] : 56 -> 44
~ -[EncodingPopUpButtonCell encodingsListChanged:] : 152 -> 140
~ -[EncodingManager setEnabledEncodings:] : 108 -> 96
~ -[EncodingManager noteEncodingListChange:postNotification:] : 176 -> 164
~ -[EncodingManager clearAll] : 92 -> 80
~ -[EncodingManager selectAll] : 92 -> 80
~ -[EncodingManager revertToDefault] : 104 -> 92
~ -[DocumentController replaceTransientDocument:] : 708 -> 696
~ ___copy_helper_block_e8_32o40o48o56o64b : 128 -> 116
~ ___destroy_helper_block_e8_32o40o48o56o64b : 104 -> 92
~ -[DocumentController newDocumentFromDockMenuItem:] : 104 -> 92
~ -[DocumentWindowController usesTextLayoutManagerForRichText:wrappedPage:] : 164 -> 152
~ -[DocumentWindowController usesTextLayoutManager] : 116 -> 104
~ -[DocumentWindowController reconfigureWrappedWindowTextViewUsingTextLayoutManager:layoutOrientation:] : 504 -> 492
~ -[DocumentWindowController firstTextViewUsingTextLayoutManager:] : 120 -> 96
~ -[DocumentWindowController setupRichTextDependentSubstitutions:] : 404 -> 392
~ -[DocumentWindowController setupInitialTextViewSharedStateForTextView:] : 292 -> 280
~ -[DocumentWindowController presenterDidPresent:soContinue:] : 72 -> 60
~ ___49-[DocumentWindowController chooseAndAttachFiles:]_block_invoke_2 : 1000 -> 988
~ ___copy_helper_block_e8_32o40o48b : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48b : 80 -> 68
~ -[DocumentWindowController updateForRichTextAndRulerState:] : 256 -> 244
~ -[DocumentWindowController updateBackgroundAppearance] : 184 -> 172
~ -[DocumentWindowController convertTextForRichTextState:removeAttachments:] : 312 -> 300
~ ___50-[DocumentWindowController updateTextViewGeometry]_block_invoke : 128 -> 116
~ -[DocumentWindowController setupPagesViewForLayoutOrientation:] : 140 -> 128
~ -[DocumentWindowController configureLayoutManager:] : 68 -> 56
~ __54-[DocumentWindowController setHasMultiplePages:force:]_block_invoke.160 : 80 -> 68
~ -[DocumentWindowController toggleRichWithNewFileType:] : 724 -> 712
~ ___54-[DocumentWindowController toggleRichWithNewFileType:]_block_invoke_2 : 72 -> 60
~ ___39-[DocumentWindowController toggleRich:]_block_invoke_3 : 76 -> 64
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ ___copy_helper_block_e8_32b40b : 80 -> 68
~ ___destroy_helper_block_e8_32b40b : 68 -> 56
~ -[DocumentWindowController toggleLayoutOrientation:] : 212 -> 188
~ -[DocumentWindowController(Delegation) textView:URLForContentsOfTextAttachment:atIndex:] : 148 -> 136
~ -[DocumentWindowController(Delegation) textView:writablePasteboardTypesForCell:atIndex:] : 136 -> 124
~ ___77-[DocumentWindowController(NSMenuValidation) textView:menu:forEvent:atIndex:]_block_invoke_2 : 96 -> 84
~ +[LinePanelController restoreWindowWithIdentifier:state:completionHandler:] : 92 -> 80
~ -[LinePanelController parseLineDescription:fromLineSpec:toLineSpec:relative:] : 240 -> 228
~ -[PrintPanelAccessoryController observeValueForKeyPath:ofObject:change:context:] : 276 -> 264
~ -[DocumentPropertiesPanelController activeDocumentChanged] : 192 -> 180
~ -[DocumentPropertiesPanelController observeValueForKeyPath:ofObject:change:context:] : 180 -> 168
~ +[DocumentPropertiesPanelController restoreWindowWithIdentifier:state:completionHandler:] : 92 -> 80
~ -[DocumentPropertiesPanelController toggleWindow:] : 144 -> 120
~ _$s8TextEdit019MultiplePageViewForA4Kit2C9printInfoSo07NSPrintI0Cvpfi : 56 -> 44
~ _$s8TextEdit019MultiplePageViewForA4Kit2C9printInfoSo07NSPrintI0Cvg : 88 -> 76
~ $s8TextEdit019MultiplePageViewForA4Kit2C9printInfoSo07NSPrintI0CvM.resume.0Tm : 80 -> 68
~ _$s8TextEdit019MultiplePageViewForA4Kit2C12viewProviderSo6NSViewCSgSu_So6CGSizeVtcSgvgTo : 224 -> 212
~ _$sSuSo6CGSizeVSo6NSViewCSgIegyyo_SuAbEIeyByya_TR : 120 -> 108
~ _$s8TextEdit019MultiplePageViewForA4Kit2C13prepareLayoutySo6CGRectVcSgvgTo : 224 -> 212
~ _$sSo6CGRectVIegy_ABIeyBy_TR : 116 -> 104
~ _$s8TextEdit019MultiplePageViewForA4Kit2C9lineColorSo7NSColorCvpfi : 56 -> 44
~ _$s8TextEdit019MultiplePageViewForA4Kit2C9lineColorSo7NSColorCvg : 88 -> 76
~ _$s8TextEdit019MultiplePageViewForA4Kit2C11marginColorSo7NSColorCvpfi : 56 -> 44
~ _$s8TextEdit019MultiplePageViewForA4Kit2C11marginColorSo7NSColorCvg : 88 -> 76
~ _$s8TextEdit019MultiplePageViewForA4Kit2C5frameACSo6CGRectV_tcfC : 92 -> 80
~ _$s8TextEdit019MultiplePageViewForA4Kit2C17updateConstraintsyyF : 876 -> 816
~ _$s8TextEdit019MultiplePageViewForA4Kit2C17updateConstraintsyyFTo : 60 -> 48
~ _$s8TextEdit019MultiplePageViewForA4Kit2C6layoutyyF : 304 -> 284
~ _$s8TextEdit019MultiplePageViewForA4Kit2C6layoutyyFTo : 332 -> 312
~ _$s8TextEdit019MultiplePageViewForA4Kit2C4drawyySo6CGRectVF : 1392 -> 1360
~ _$s8TextEdit019MultiplePageViewForA4Kit2C4drawyySo6CGRectVFTo : 108 -> 96
~ _$s8TextEdit019MultiplePageViewForA4Kit2CfETo : 164 -> 152
~ ___swift_closure_destructor : 56 -> 44
~ _$sSuSo6CGSizeVSo6NSViewCSgIeyByya_SuAbEIegyyo_TRTA : 60 -> 48
~ _$ss12_ArrayBufferV20_consumeAndCreateNewAByxGyFSo6NSViewC_Tg5 : 100 -> 88
```
