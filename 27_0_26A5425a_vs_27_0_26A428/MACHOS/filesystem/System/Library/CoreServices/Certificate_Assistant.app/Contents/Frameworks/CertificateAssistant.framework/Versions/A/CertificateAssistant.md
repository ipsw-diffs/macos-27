## CertificateAssistant

> `/System/Library/CoreServices/Certificate Assistant.app/Contents/Frameworks/CertificateAssistant.framework/Versions/A/CertificateAssistant`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 55202.0.0.0.0
-  __TEXT.__text: 0x3ac4
+  __TEXT.__text: 0x3860
   __TEXT.__auth_stubs: 0x1a0
   __TEXT.__objc_stubs: 0x18a0
   __TEXT.__objc_methlist: 0xaac

   __TEXT.__objc_methtype: 0x327
   __TEXT.__cstring: 0x668
   __TEXT.__gcc_except_tab: 0x34
-  __TEXT.__unwind_info: 0x1d8
+  __TEXT.__unwind_info: 0x240
   __DATA_CONST.__cfstring: 0x780
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
Functions:
~ -[AFAssistantContentView drawRect:] : 160 -> 148
~ +[AFAssistantPane initialize] : 88 -> 76
~ -[AFAssistantPane localizedStringForKey:] : 68 -> 56
~ -[AFAssistantPane pathForResource:ofType:] : 92 -> 80
~ -[AFAssistantPane encodeWithCoder:] : 276 -> 252
~ -[AFAssistantPane forwardInvocation:] : 212 -> 200
~ -[AFAssistantPane(AFAssistantPage_reserved) _setObject:forKey:] : 200 -> 176
~ -[AFAssistantPane(AFAssistantPage_reserved) _objectForKey:] : 56 -> 44
~ _AFAssistantAddAssertionHandlerForLock : 128 -> 116
~ _AFAssistantRemoveAssertionHandlerForLock : 228 -> 204
~ +[AFAssistantSection initialize] : 88 -> 76
~ +[AFAssistantSection assistantSectionWithName:fromAssistantBundle:] : 116 -> 104
~ -[AFAssistantSection forwardInvocation:] : 220 -> 208
~ -[AFAssistantSection methodSignatureForSelector:] : 56 -> 44
~ -[AFAssistantSection(AFAssistantSectionPrivate) loadMainNibFile] : 424 -> 412
~ -[AFAssistantSection(AFAssistantSection_reserved) _setObject:forKey:] : 100 -> 76
~ -[AFAssistantSection(AFAssistantSection_reserved) _objectForKey:] : 56 -> 44
~ +[AFAssistantController initialize] : 88 -> 76
~ -[AFAssistantController assistantBundle] : 88 -> 76
~ -[AFAssistantController assistantBundleWithPath:] : 68 -> 56
~ -[AFAssistantController finishAssistant:] : 144 -> 132
~ -[AFAssistantController terminateAssistant:] : 144 -> 132
~ -[AFAssistantController advancePane:] : 384 -> 360
~ -[AFAssistantController startProgressAnimation:] : 124 -> 112
~ -[AFAssistantController updateProgressStatus:] : 88 -> 76
~ -[AFAssistantController endProgressAnimation] : 72 -> 60
~ -[AFAssistantController(Private) doChangeCurrentViewToNewView:] : 280 -> 268
~ -[AFAssistantController(Private) updateKeyboardFocusChain:] : 432 -> 408
~ -[AFAssistantController(Private) addSection:] : 456 -> 444
~ -[AFAssistantController(Private) firstPageOfCurrentSection] : 48 -> 36
~ -[AFAssistantController(Private) internalSetGoBackButtonEnabled:] : 132 -> 120
~ -[AFAssistantController(Private) internalSetContinueButtonEnabled:] : 132 -> 120
~ -[AFAssistantController(Private) endEditing] : 96 -> 84
~ -[AFAssistantController(Private) doContinue] : 88 -> 76
~ -[AFAssistantController(Private) doGoBack] : 412 -> 400
~ -[AFAssistantController(AFAssistantController_reserved) _setObject:forKey:] : 200 -> 176
~ -[AFAssistantController(AFAssistantController_reserved) _objectForKey:] : 56 -> 44
~ +[AFAssistantBundle initialize] : 88 -> 76
~ -[AFAssistantBundle(AFAssistantBundlePrivate) isBackgroundImageLoaded] : 56 -> 44
~ -[AFAssistantBundle(AFAssistantBundlePrivate) isSectionBundleNamesLoaded] : 56 -> 44
~ -[AFAssistantBundle(AFAssistantBundle_reserved) _setObject:forKey:] : 200 -> 176
~ -[AFAssistantBundle(AFAssistantBundle_reserved) _objectForKey:] : 56 -> 44
~ -[CALearnMoreSheetWindowController closeLearnMoreSheet:] : 72 -> 60
```
