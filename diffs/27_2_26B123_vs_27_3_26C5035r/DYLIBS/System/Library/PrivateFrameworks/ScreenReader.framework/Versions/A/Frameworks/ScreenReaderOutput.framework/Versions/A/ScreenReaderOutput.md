## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderOutput.framework/Versions/A/ScreenReaderOutput`

```diff

-1050.3.5.0.0
-  __TEXT.__text: 0xa5e2c
-  __TEXT.__objc_methlist: 0x96f8
-  __TEXT.__const: 0x1938
-  __TEXT.__cstring: 0x65f9
+1050.3.12.0.0
+  __TEXT.__text: 0xaa088
+  __TEXT.__objc_methlist: 0x99e8
+  __TEXT.__const: 0x1948
+  __TEXT.__cstring: 0x6784
   __TEXT.__swift5_typeref: 0xeec
   __TEXT.__constg_swiftt: 0x960
   __TEXT.__swift5_builtin: 0xb4
   __TEXT.__swift5_types: 0xa4
-  __TEXT.__oslogstring: 0x28a1
+  __TEXT.__oslogstring: 0x2df8
   __TEXT.__swift5_reflstr: 0x605
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_fieldmd: 0x7f8

   __TEXT.__swift5_protos: 0x8
   __TEXT.__gcc_except_tab: 0x1984
   __TEXT.__ustring: 0x9e
-  __TEXT.__unwind_info: 0x35d0
+  __TEXT.__unwind_info: 0x3698
   __TEXT.__eh_frame: 0xa28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x390
-  __DATA_CONST.__objc_classlist: 0x338
+  __DATA_CONST.__objc_classlist: 0x358
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a80
+  __DATA_CONST.__objc_selrefs: 0x4c60
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x218
+  __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x808
-  __AUTH_CONST.__const: 0x4588
-  __AUTH_CONST.__cfstring: 0x6580
-  __AUTH_CONST.__objc_const: 0xc2c0
+  __AUTH_CONST.__const: 0x4698
+  __AUTH_CONST.__cfstring: 0x67c0
+  __AUTH_CONST.__objc_const: 0xc860
   __AUTH_CONST.__objc_intobj: 0x1218
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x60
-  __AUTH_CONST.__auth_got: 0xef0
-  __AUTH.__objc_data: 0x400
-  __AUTH.__data: 0x70
-  __DATA.__objc_ivar: 0x920
-  __DATA.__data: 0x1690
-  __DATA.__bss: 0x1100
+  __AUTH_CONST.__auth_got: 0xef8
+  __AUTH.__objc_data: 0x540
+  __AUTH.__data: 0x78
+  __DATA.__objc_ivar: 0x964
+  __DATA.__data: 0x16a0
+  __DATA.__bss: 0x1118
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x1d10
-  __DATA_DIRTY.__data: 0xc20
+  __DATA_DIRTY.__data: 0xc28
   __DATA_DIRTY.__bss: 0x130
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4143
-  Symbols:   7993
-  CStrings:  1186
+  Functions: 4219
+  Symbols:   8171
+  CStrings:  1225
 
Symbols:
+ +[SCROBrailleUIFinderApp _loadTextOfPDFAtURL:section:intoResult:]
+ +[SCROBrailleUIPDFSections _appendPageRangeSectionsFrom:to:documentTitle:pageCount:toSections:]
+ +[SCROBrailleUIPDFSections _chapterSectionsForDocument:documentTitle:pageCount:]
+ +[SCROBrailleUIPDFSections sectionsForPDFAtURL:]
+ +[SCROBrailleUIUtilities textFromPDFAtURL:isTooLarge:]
+ +[SCROBrailleUIUtilities textFromPDFAtURL:pageRange:isTooLarge:]
+ -[SCROBrailleUIFinderApp _cancelLoading]
+ -[SCROBrailleUIFinderApp _closePDFSectionsMenu]
+ -[SCROBrailleUIFinderApp _handleActionInLoadingView:]
+ -[SCROBrailleUIFinderApp _handleActionInPDFSectionsMenu:]
+ -[SCROBrailleUIFinderApp _isLoading]
+ -[SCROBrailleUIFinderApp _isPDFSectionsMenuOpen]
+ -[SCROBrailleUIFinderApp _loadURL:inBackground:completion:]
+ -[SCROBrailleUIFinderApp _openPDFSectionsMenuForURL:sections:]
+ -[SCROBrailleUIFinderApp _openPlainTextOrPDF:]
+ -[SCROBrailleUIFinderApp _openViewerForPlainText:section:content:]
+ -[SCROBrailleUIFinderApp _performOnEventQueue:]
+ -[SCROBrailleUIFinderApp _plainTextPersistenceKey]
+ -[SCROBrailleUIFinderApp _presentViewerForBRFFile:]
+ -[SCROBrailleUIFinderApp _resetLoadingState]
+ -[SCROBrailleUIFinderApp _scheduleLoadingAnimationTickForGeneration:]
+ -[SCROBrailleUIFinderApp currentPDFSection]
+ -[SCROBrailleUIFinderApp loadGeneration]
+ -[SCROBrailleUIFinderApp loadingURL]
+ -[SCROBrailleUIFinderApp loadingView]
+ -[SCROBrailleUIFinderApp pdfSectionsMenuView]
+ -[SCROBrailleUIFinderApp pdfSections]
+ -[SCROBrailleUIFinderApp setCurrentPDFSection:]
+ -[SCROBrailleUIFinderApp setLoadGeneration:]
+ -[SCROBrailleUIFinderApp setLoadingURL:]
+ -[SCROBrailleUIFinderApp setLoadingView:]
+ -[SCROBrailleUIFinderApp setPdfSections:]
+ -[SCROBrailleUIFinderApp setPdfSectionsMenuView:]
+ -[SCROBrailleUIFinderAppLoadResult .cxx_destruct]
+ -[SCROBrailleUIFinderAppLoadResult brfFile]
+ -[SCROBrailleUIFinderAppLoadResult errorMessageKey]
+ -[SCROBrailleUIFinderAppLoadResult pdfSection]
+ -[SCROBrailleUIFinderAppLoadResult pdfSections]
+ -[SCROBrailleUIFinderAppLoadResult plainTextContent]
+ -[SCROBrailleUIFinderAppLoadResult setBrfFile:]
+ -[SCROBrailleUIFinderAppLoadResult setErrorMessageKey:]
+ -[SCROBrailleUIFinderAppLoadResult setPdfSection:]
+ -[SCROBrailleUIFinderAppLoadResult setPdfSections:]
+ -[SCROBrailleUIFinderAppLoadResult setPlainTextContent:]
+ -[SCROBrailleUILoadingView .cxx_destruct]
+ -[SCROBrailleUILoadingView _animatedText]
+ -[SCROBrailleUILoadingView advanceAnimation]
+ -[SCROBrailleUILoadingView contentValue]
+ -[SCROBrailleUILoadingView contentVisualRepresentation]
+ -[SCROBrailleUILoadingView displayContent]
+ -[SCROBrailleUILoadingView dotCount]
+ -[SCROBrailleUILoadingView handleBackButtonNavigationEvent:]
+ -[SCROBrailleUILoadingView handleContentEvent:]
+ -[SCROBrailleUILoadingView initWithIdentifier:text:]
+ -[SCROBrailleUILoadingView setDotCount:]
+ -[SCROBrailleUILoadingView setText:]
+ -[SCROBrailleUILoadingView text]
+ -[SCROBrailleUIPDFSection .cxx_destruct]
+ -[SCROBrailleUIPDFSection bottomTitle]
+ -[SCROBrailleUIPDFSection identifier]
+ -[SCROBrailleUIPDFSection initWholeDocumentWithTitle:pageCount:]
+ -[SCROBrailleUIPDFSection initWithDocumentTitle:chapterTitle:pageRange:pageCount:]
+ -[SCROBrailleUIPDFSection pageRange]
+ -[SCROBrailleUIPDFSection title]
+ -[SCROBrailleUIPDFSection topTitle]
+ -[SCROBrailleUIPlainTextView _captionsForRows:originalBraille:locations:sourceLine:]
+ -[SCROBrailleUIPlainTextView currentRowCaptions]
+ -[SCROBrailleUIPlainTextView setCurrentRowCaptions:]
+ GCC_except_table1020
+ GCC_except_table1022
+ GCC_except_table1159
+ GCC_except_table1223
+ GCC_except_table1225
+ GCC_except_table1227
+ GCC_except_table1229
+ GCC_except_table1341
+ GCC_except_table1344
+ GCC_except_table1346
+ GCC_except_table1376
+ GCC_except_table1383
+ GCC_except_table1515
+ GCC_except_table1728
+ GCC_except_table1854
+ GCC_except_table1995
+ GCC_except_table1997
+ GCC_except_table2006
+ GCC_except_table2018
+ GCC_except_table2102
+ GCC_except_table2147
+ GCC_except_table2153
+ GCC_except_table2267
+ GCC_except_table2288
+ GCC_except_table2297
+ GCC_except_table2305
+ GCC_except_table2408
+ GCC_except_table2591
+ GCC_except_table2612
+ GCC_except_table2722
+ GCC_except_table2723
+ GCC_except_table2724
+ GCC_except_table2728
+ GCC_except_table2733
+ GCC_except_table2734
+ GCC_except_table2735
+ GCC_except_table2736
+ GCC_except_table2737
+ GCC_except_table2739
+ GCC_except_table2740
+ GCC_except_table2741
+ GCC_except_table2745
+ GCC_except_table2750
+ GCC_except_table2752
+ GCC_except_table2755
+ GCC_except_table3131
+ GCC_except_table3149
+ GCC_except_table3168
+ GCC_except_table3170
+ GCC_except_table3236
+ GCC_except_table3238
+ GCC_except_table3240
+ GCC_except_table3241
+ GCC_except_table3243
+ GCC_except_table3245
+ GCC_except_table499
+ GCC_except_table513
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table569
+ GCC_except_table570
+ GCC_except_table580
+ GCC_except_table582
+ GCC_except_table605
+ GCC_except_table607
+ GCC_except_table610
+ GCC_except_table611
+ GCC_except_table624
+ GCC_except_table644
+ GCC_except_table647
+ GCC_except_table655
+ GCC_except_table657
+ GCC_except_table679
+ GCC_except_table680
+ GCC_except_table681
+ GCC_except_table682
+ GCC_except_table684
+ GCC_except_table688
+ GCC_except_table689
+ GCC_except_table693
+ GCC_except_table697
+ GCC_except_table715
+ GCC_except_table716
+ GCC_except_table719
+ GCC_except_table979
+ _NSURLFileSizeKey
+ _OBJC_CLASS_$_SCROBrailleUIFinderAppLoadResult
+ _OBJC_CLASS_$_SCROBrailleUILoadingView
+ _OBJC_CLASS_$_SCROBrailleUIPDFSection
+ _OBJC_CLASS_$_SCROBrailleUIPDFSections
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._currentPDFSection
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._loadGeneration
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._loadingURL
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._loadingView
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._pdfSections
+ _OBJC_IVAR_$_SCROBrailleUIFinderApp._pdfSectionsMenuView
+ _OBJC_IVAR_$_SCROBrailleUIFinderAppLoadResult._brfFile
+ _OBJC_IVAR_$_SCROBrailleUIFinderAppLoadResult._errorMessageKey
+ _OBJC_IVAR_$_SCROBrailleUIFinderAppLoadResult._pdfSection
+ _OBJC_IVAR_$_SCROBrailleUIFinderAppLoadResult._pdfSections
+ _OBJC_IVAR_$_SCROBrailleUIFinderAppLoadResult._plainTextContent
+ _OBJC_IVAR_$_SCROBrailleUILoadingView._dotCount
+ _OBJC_IVAR_$_SCROBrailleUILoadingView._text
+ _OBJC_IVAR_$_SCROBrailleUIPDFSection._bottomTitle
+ _OBJC_IVAR_$_SCROBrailleUIPDFSection._identifier
+ _OBJC_IVAR_$_SCROBrailleUIPDFSection._pageRange
+ _OBJC_IVAR_$_SCROBrailleUIPDFSection._title
+ _OBJC_IVAR_$_SCROBrailleUIPDFSection._topTitle
+ _OBJC_IVAR_$_SCROBrailleUIPlainTextView._currentRowCaptions
+ _OBJC_METACLASS_$_SCROBrailleUIFinderAppLoadResult
+ _OBJC_METACLASS_$_SCROBrailleUILoadingView
+ _OBJC_METACLASS_$_SCROBrailleUIPDFSection
+ _OBJC_METACLASS_$_SCROBrailleUIPDFSections
+ __OBJC_$_CLASS_METHODS_SCROBrailleUIPDFSections
+ __OBJC_$_INSTANCE_METHODS_SCROBrailleUIFinderAppLoadResult
+ __OBJC_$_INSTANCE_METHODS_SCROBrailleUILoadingView
+ __OBJC_$_INSTANCE_METHODS_SCROBrailleUIPDFSection
+ __OBJC_$_INSTANCE_VARIABLES_SCROBrailleUIFinderAppLoadResult
+ __OBJC_$_INSTANCE_VARIABLES_SCROBrailleUILoadingView
+ __OBJC_$_INSTANCE_VARIABLES_SCROBrailleUIPDFSection
+ __OBJC_$_PROP_LIST_SCROBrailleUIFinderAppLoadResult
+ __OBJC_$_PROP_LIST_SCROBrailleUILoadingView
+ __OBJC_$_PROP_LIST_SCROBrailleUIPDFSection
+ __OBJC_CLASS_RO_$_SCROBrailleUIFinderAppLoadResult
+ __OBJC_CLASS_RO_$_SCROBrailleUILoadingView
+ __OBJC_CLASS_RO_$_SCROBrailleUIPDFSection
+ __OBJC_CLASS_RO_$_SCROBrailleUIPDFSections
+ __OBJC_METACLASS_RO_$_SCROBrailleUIFinderAppLoadResult
+ __OBJC_METACLASS_RO_$_SCROBrailleUILoadingView
+ __OBJC_METACLASS_RO_$_SCROBrailleUIPDFSection
+ __OBJC_METACLASS_RO_$_SCROBrailleUIPDFSections
+ ___44-[SCROBrailleUIFinderApp _openViewerForBRF:]_block_invoke
+ ___46-[SCROBrailleUIFinderApp _openPlainTextOrPDF:]_block_invoke
+ ___46-[SCROBrailleUIFinderApp _openPlainTextOrPDF:]_block_invoke_2
+ ___57-[SCROBrailleUIFinderApp _handleActionInPDFSectionsMenu:]_block_invoke
+ ___57-[SCROBrailleUIFinderApp _handleActionInPDFSectionsMenu:]_block_invoke_2
+ ___59-[SCROBrailleUIFinderApp _loadURL:inBackground:completion:]_block_invoke
+ ___69-[SCROBrailleUIFinderApp _scheduleLoadingAnimationTickForGeneration:]_block_invoke
+ ___69-[SCROBrailleUIFinderApp _scheduleLoadingAnimationTickForGeneration:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e42_v16?0"SCROBrailleUIFinderAppLoadResult"8l
+ ___block_descriptor_48_e8_32s40s_e42_v16?0"SCROBrailleUIFinderAppLoadResult"8l
+ ___block_descriptor_56_e8_32s40w48w_e5_v8?0l
+ ___block_descriptor_64_e8_32s40bs48bs_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_74_e8_32s40s48s_e42_v16?0"SCROBrailleUIFinderAppLoadResult"8l
+ ___copy_helper_block_e8_32s40b48b
+ ___copy_helper_block_e8_32s40s48b
+ ___copy_helper_block_e8_32s40w48w
+ ___destroy_helper_block_e8_32s40w48w
+ _kSCROBrailleUIRequestBlockKey
+ _kSCROCaptionAttribute
+ _objc_msgSend$_animatedText
+ _objc_msgSend$_appendPageRangeSectionsFrom:to:documentTitle:pageCount:toSections:
+ _objc_msgSend$_cancelLoading
+ _objc_msgSend$_captionsForRows:originalBraille:locations:sourceLine:
+ _objc_msgSend$_chapterSectionsForDocument:documentTitle:pageCount:
+ _objc_msgSend$_closePDFSectionsMenu
+ _objc_msgSend$_handleActionInLoadingView:
+ _objc_msgSend$_handleActionInPDFSectionsMenu:
+ _objc_msgSend$_isLoading
+ _objc_msgSend$_isPDFSectionsMenuOpen
+ _objc_msgSend$_loadTextOfPDFAtURL:section:intoResult:
+ _objc_msgSend$_loadURL:inBackground:completion:
+ _objc_msgSend$_openPDFSectionsMenuForURL:sections:
+ _objc_msgSend$_openPlainTextOrPDF:
+ _objc_msgSend$_openViewerForPlainText:section:content:
+ _objc_msgSend$_performOnEventQueue:
+ _objc_msgSend$_plainTextPersistenceKey
+ _objc_msgSend$_presentViewerForBRFFile:
+ _objc_msgSend$_resetLoadingState
+ _objc_msgSend$_scheduleLoadingAnimationTickForGeneration:
+ _objc_msgSend$advanceAnimation
+ _objc_msgSend$alertWithMessage:priority:kind:timeout:
+ _objc_msgSend$bottomTitle
+ _objc_msgSend$childAtIndex:
+ _objc_msgSend$currentPDFSection
+ _objc_msgSend$currentRowCaptions
+ _objc_msgSend$destination
+ _objc_msgSend$documentAttributes
+ _objc_msgSend$dotCount
+ _objc_msgSend$errorMessageKey
+ _objc_msgSend$indexForPage:
+ _objc_msgSend$initWholeDocumentWithTitle:pageCount:
+ _objc_msgSend$initWithDocumentTitle:chapterTitle:pageRange:pageCount:
+ _objc_msgSend$initWithIdentifier:text:
+ _objc_msgSend$lengthOfBytesUsingEncoding:
+ _objc_msgSend$loadGeneration
+ _objc_msgSend$loadingURL
+ _objc_msgSend$loadingView
+ _objc_msgSend$numberOfChildren
+ _objc_msgSend$outlineRoot
+ _objc_msgSend$page
+ _objc_msgSend$pageAtIndex:
+ _objc_msgSend$pageCount
+ _objc_msgSend$pageRange
+ _objc_msgSend$pdfSection
+ _objc_msgSend$pdfSections
+ _objc_msgSend$pdfSectionsMenuView
+ _objc_msgSend$plainTextContent
+ _objc_msgSend$rangeOfComposedCharacterSequencesForRange:
+ _objc_msgSend$sectionsForPDFAtURL:
+ _objc_msgSend$setCurrentPDFSection:
+ _objc_msgSend$setCurrentRowCaptions:
+ _objc_msgSend$setDotCount:
+ _objc_msgSend$setErrorMessageKey:
+ _objc_msgSend$setLoadGeneration:
+ _objc_msgSend$setLoadingURL:
+ _objc_msgSend$setLoadingView:
+ _objc_msgSend$setPdfSection:
+ _objc_msgSend$setPdfSections:
+ _objc_msgSend$setPdfSectionsMenuView:
+ _objc_msgSend$setPlainTextContent:
+ _objc_msgSend$sortUsingSelector:
+ _objc_msgSend$stringByDeletingPathExtension
+ _objc_msgSend$stringByReplacingOccurrencesOfString:withString:options:range:
+ _objc_msgSend$textFromPDFAtURL:pageRange:isTooLarge:
+ _objc_msgSend$topTitle
+ _task_info
- +[SCROBrailleUIUtilities textFromPDFAtURL:]
- -[SCROBrailleDisplayInput currentHIDCommand]
- -[SCROBrailleDisplayInput setCurrentHIDCommand:]
- -[SCROBrailleUIApp lazyLoad]
- -[SCROBrailleUIFinderApp _openViewerForPlainText:]
- -[SCROBrailleUIFinderApp isViewerViewLoading]
- -[SCROBrailleUIFinderApp lazyLoad]
- -[SCROBrailleUIFinderApp setIsViewerViewLoading:]
- GCC_except_table1113
- GCC_except_table1177
- GCC_except_table1179
- GCC_except_table1181
- GCC_except_table1183
- GCC_except_table1254
- GCC_except_table1284
- GCC_except_table1291
- GCC_except_table1295
- GCC_except_table1298
- GCC_except_table1469
- GCC_except_table1682
- GCC_except_table1808
- GCC_except_table1949
- GCC_except_table1951
- GCC_except_table1960
- GCC_except_table1972
- GCC_except_table2056
- GCC_except_table2101
- GCC_except_table2107
- GCC_except_table2221
- GCC_except_table2242
- GCC_except_table2251
- GCC_except_table2259
- GCC_except_table2362
- GCC_except_table2546
- GCC_except_table2567
- GCC_except_table2677
- GCC_except_table2678
- GCC_except_table2679
- GCC_except_table2683
- GCC_except_table2688
- GCC_except_table2689
- GCC_except_table2690
- GCC_except_table2691
- GCC_except_table2692
- GCC_except_table2694
- GCC_except_table2695
- GCC_except_table2696
- GCC_except_table2700
- GCC_except_table2705
- GCC_except_table2707
- GCC_except_table2710
- GCC_except_table3058
- GCC_except_table3076
- GCC_except_table3095
- GCC_except_table3096
- GCC_except_table3097
- GCC_except_table3160
- GCC_except_table3162
- GCC_except_table3164
- GCC_except_table3165
- GCC_except_table3167
- GCC_except_table448
- GCC_except_table462
- GCC_except_table494
- GCC_except_table495
- GCC_except_table518
- GCC_except_table519
- GCC_except_table529
- GCC_except_table531
- GCC_except_table553
- GCC_except_table554
- GCC_except_table556
- GCC_except_table559
- GCC_except_table560
- GCC_except_table563
- GCC_except_table573
- GCC_except_table593
- GCC_except_table595
- GCC_except_table596
- GCC_except_table606
- GCC_except_table628
- GCC_except_table629
- GCC_except_table630
- GCC_except_table631
- GCC_except_table633
- GCC_except_table637
- GCC_except_table638
- GCC_except_table642
- GCC_except_table664
- GCC_except_table668
- GCC_except_table932
- GCC_except_table973
- GCC_except_table975
- _OBJC_IVAR_$_SCROBrailleDisplayInput._currentHIDCommand
- _OBJC_IVAR_$_SCROBrailleUIFinderApp._isViewerViewLoading
- ___52-[SCROBrailleDisplayManager handleBrailleUIRequest:]_block_invoke_4
- ___block_descriptor_56_e8_32s40s48w_e5_v8?0l
- ___copy_helper_block_e8_32s40s48w
- ___destroy_helper_block_e8_32s40s48w
- _objc_msgSend$_openViewerForPlainText:
- _objc_msgSend$alertWithMessage:priority:timeout:
- _objc_msgSend$currentHIDCommand
- _objc_msgSend$isViewerViewLoading
- _objc_msgSend$lazyLoad
- _objc_msgSend$loadContent:cursor:
- _objc_msgSend$setCurrentHIDCommand:
- _objc_msgSend$setIsViewerViewLoading:
- _objc_msgSend$textFromPDFAtURL:
CStrings:
+ "%@\n%@\n%@"
+ "%@#%@"
+ "%@%lu%lu%lu"
+ "%lu%lu%lu"
+ "/Library/Accessibility/ktoa_u_kwa_v7.dic"
+ "Braille UI Finder: Load %lu: background load finished, error %@"
+ "Braille UI Finder: Load %lu: background load started"
+ "Braille UI Finder: Load %lu: cancelled"
+ "Braille UI Finder: Load %lu: discarding result of cancelled load"
+ "Braille UI Finder: Load %lu: dispatching background load of .%@ file"
+ "Braille UI Finder: Load %lu: presenting result"
+ "Braille UI Finder: Load %lu: requesting completion on event queue"
+ "Braille UI: Failed to reopen PDF at page %lu"
+ "Braille UI: Finished reading PDF: %lu pages, text size %llu bytes, footprint %llu KB, %.3f s"
+ "Braille UI: Ignoring PDF outline because chapter %lu spans %lu pages"
+ "Braille UI: Ignoring PDF outline with %lu usable chapters for %lu pages"
+ "Braille UI: PDF text exceeds %llu bytes after page %lu/%lu"
+ "Braille UI: Plain text locations don't match braille, captioning first row only"
+ "Braille UI: Plain text locations out of order, captioning first row only"
+ "Braille UI: Read PDF page %lu/%lu: text size %llu bytes, footprint %llu KB"
+ "Braille UI: Reading PDF %@: pages %lu to %lu of %lu, file size %llu bytes, footprint %llu KB"
+ "Braille UI: Reflowed row %lu/%lu doesn't match braille at cell %lu, captioning first row only"
+ "Braille UI: Reflowed rows cover %lu of %lu braille cells, captioning first row only"
+ "Braille UI: Split PDF of %lu pages into %lu page ranges"
+ "Braille UI: Split PDF of %lu pages into %lu sections using its outline"
+ "PDFLastSection"
+ "SCROCaptionAttribute"
+ "Title"
+ "\\p{Cf}"
+ "block"
+ "finder.loading"
+ "finder.pdf.section.bottom.format"
+ "finder.pdf.section.chapter.format"
+ "finder.pdf.section.heading.format"
+ "finder.pdf.section.pages.format"
+ "finder.pdf.section.top.format"
+ "finder.pdf.sections.menu"
+ "pages=%lu-%lu"
+ "v16@?0@\"SCROBrailleUIFinderAppLoadResult\"8"
```
