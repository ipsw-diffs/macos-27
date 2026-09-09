## libUAEHOther.dylib

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/Current/Frameworks/UAEHCommon.framework/Versions/A/Libraries/libUAEHOther.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`

```diff

 778.1.1.0.0
-  __TEXT.__text: 0x71cc
+  __TEXT.__text: 0x6efc
   __TEXT.__objc_methlist: 0x92c
   __TEXT.__dlopen_cstrs: 0x66
   __TEXT.__const: 0x48

   __TEXT.__oslogstring: 0x2a4
   __TEXT.__cstring: 0x57a
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x268
+  __TEXT.__unwind_info: 0x2d8
   __TEXT.__objc_stubs: 0x1e80
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__objc_classname: 0x248
Functions:
~ -[UAEHLiveSpeechDriver applySettingsFromPreferences] : 60 -> 48
~ -[UAEHLiveSpeechDriver _toggleLiveSpeech] : 48 -> 36
~ -[UAEHLiveCaptionsEnablementAlertController enableWithAlertIfNeeded] : 64 -> 52
~ -[UAEHLiveCaptionsEnablementAlertController _setupVisualsAgentXPC] : 264 -> 252
~ -[UAEHMouseDriver setupInitialState] : 120 -> 108
~ -[UAEHMouseDriver _startMouseDriver:] : 204 -> 192
~ ___37-[UAEHMouseDriver _startMouseDriver:]_block_invoke : 132 -> 120
~ -[UAEHMouseDriver _stopMouseDriver:] : 180 -> 168
~ -[UAEHMouseDriver _toggleMouseDriverWithReason:] : 72 -> 60
~ -[UAEHMouseDriver _hotKeyEvent:] : 352 -> 340
~ -[UAEHMouseDriver _setSuppressionState:] : 84 -> 72
~ __markupHandler : 152 -> 140
~ _handleEvent : 296 -> 284
~ _initialize : 592 -> 580
~ _libraryWillUnload : 160 -> 148
~ _updateSettings : 180 -> 168
~ _userSessionDidChange : 180 -> 168
~ -[UAEHStickyKeyOverlayWindow setWindowLocation:] : 88 -> 76
~ ___45-[UAEHStickyKeyOverlayWindow showModifierID:]_block_invoke : 320 -> 308
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___45-[UAEHStickyKeyOverlayWindow hideModifierID:]_block_invoke : 392 -> 380
~ -[UAEHStickyKeyOverlayWindow highlightModifierID:] : 196 -> 184
~ ___50-[UAEHStickyKeyOverlayWindow removeAllModifierIDs]_block_invoke : 248 -> 236
~ ___50-[UAEHStickyKeyOverlayWindow removeAllModifierIDs]_block_invoke_2 : 72 -> 60
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ +[UAEHStickyKeyOverlayWindow _modifierKeyTextFieldForModifierID:] : 776 -> 764
~ -[UAEHStickyKeyOverlayWindow _updateWindowVisibility] : 232 -> 220
~ -[UAEHStickyKeyOverlayWindow _updateWindowFrameAnimated:] : 348 -> 324
~ -[UAEHStickyKeyOverlayWindow _removeHorizontalEdgeConstraintsForAllModifierKeyViews] : 168 -> 156
~ ___87-[UAEHStickyKeyOverlayWindow _updateTargetPositionsOfAllModifierKeyViewsWithAnimation:]_block_invoke : 156 -> 144
~ -[UAEHStickyKeyOverlayWindow .cxx_destruct] : 124 -> 112
~ -[UAEHStickyKeysDriver setupInitialState] : 72 -> 60
~ -[UAEHStickyKeysDriver _enableStickyKeys:systemLevel:] : 280 -> 268
~ -[UAEHStickyKeysDriver _applyWindowLocation:alwaysHidden:] : 328 -> 316
~ ___58-[UAEHStickyKeysDriver _applyWindowLocation:alwaysHidden:]_block_invoke : 96 -> 84
~ -[UAEHStickyKeysDriver _showStickyKeysOverlay] : 256 -> 232
~ -[UAEHStickyKeysDriver _hideStickyKeysOverlay] : 200 -> 188
~ -[UAEHStickyKeysDriver _showModifier:] : 308 -> 296
~ -[UAEHStickyKeysDriver _hideModifier:] : 308 -> 296
~ -[UAEHStickyKeysDriver _highlightModifier:] : 308 -> 296
~ ____UAExecuteWithStickyKeysProxy_block_invoke : 204 -> 192
~ -[UAEHSlowKeysDriver setupInitialState] : 176 -> 164
~ -[UAEHAccessibilityReaderDriver applySettingsFromPreferences] : 164 -> 152
~ -[UAEHAccessibilityReaderDriver _settingsChangedNotificationsToObserve] : 128 -> 116
~ -[UAEHAccessibilityReaderDriver _startObservingApplications] : 240 -> 228
~ -[UAEHAccessibilityReaderDriver _stopObservingApplications] : 104 -> 92
~ -[UAEHAccessibilityReaderDriver _activateReader] : 132 -> 120
~ -[UAEHAccessibilityReaderDriver .cxx_destruct] : 84 -> 72
~ -[UAEHSpokenContentDriver _toggleSpeakItemUnderPointer] : 140 -> 128
~ -[UAEHSpokenContentDriver _toggleSpeakSelection] : 140 -> 128
~ -[UAEHSpokenContentDriver _toggleTypingEcho] : 140 -> 128
~ -[UAEHSpokenContentDriver _showStatusOverlayWithFeatureTitle:status:] : 232 -> 220
~ -[UAEHMotionCuesDriver applySettingsFromPreferences] : 68 -> 56
~ -[UAEHMotionCuesDriver _toggleMotionCues] : 48 -> 36
~ -[UAEHLiveCaptionsDriver _toggleLiveCaptions] : 108 -> 84
```
