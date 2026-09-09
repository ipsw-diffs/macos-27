## libUAEHPointerControl.dylib

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Frameworks/UAEHCommon.framework/Versions/A/Libraries/libUAEHPointerControl.dylib`

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
-  __TEXT.__text: 0x8824
+  __TEXT.__text: 0x84dc
   __TEXT.__objc_methlist: 0x9e4
   __TEXT.__const: 0xc8
   __TEXT.__gcc_except_tab: 0x9c
   __TEXT.__oslogstring: 0x633
   __TEXT.__cstring: 0x4fe
-  __TEXT.__unwind_info: 0x270
+  __TEXT.__unwind_info: 0x328
   __TEXT.__objc_stubs: 0x1f60
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__objc_classname: 0x1fc
Functions:
~ -[UAUserSwitch(UAEPointerControlDriver) uaehPointerControl_draggedButton] : 136 -> 124
~ -[UAUserSwitch(UAEPointerControlDriver) _uaeh_clickCount] : 152 -> 140
~ -[UAUserSwitch(UAEPointerControlDriver) _uaeh_event] : 204 -> 192
~ -[UAHIDUserSwitch(UAEHPointerControlDriver) _uaeh_axe_modifierMask] : 256 -> 244
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___75-[UAEHPointerControlDriver applySettingsFromPreferencesDuringInitialState:]_block_invoke : 132 -> 120
~ __75-[UAEHPointerControlDriver applySettingsFromPreferencesDuringInitialState:]_block_invoke.106 : 212 -> 200
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[UAEHPointerControlDriver _settingsChangedNotificationsToObserve] : 128 -> 116
~ -[UAEHPointerControlDriver _stopEyeTrackingInputManager] : 64 -> 52
~ -[UAEHPointerControlDriver motionTracker:updatedState:] : 608 -> 596
~ ___56-[UAEHPointerControlDriver _debugThrottledLogStateInfo:]_block_invoke : 68 -> 56
~ ___90-[UAEHPointerControlDriver eventTapManager:activelyTappedKeyboardEvent:cgEvent:withProxy:]_block_invoke_2 : 116 -> 104
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___87-[UAEHPointerControlDriver eventTapManager:activelyTappedMouseEvent:cgEvent:withProxy:]_block_invoke_2 : 144 -> 132
~ __50-[UAEHPointerControlDriver _setActiveExpressions:]_block_invoke.182 : 104 -> 92
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ __50-[UAEHPointerControlDriver _setActiveExpressions:]_block_invoke.185 : 104 -> 92
~ ___50-[UAEHPointerControlDriver _deactivateAllSwitches]_block_invoke : 184 -> 172
~ ___72-[UAEHPointerControlDriver _deactivateKeyboardSwitchesAsNeededForEvent:]_block_invoke : 312 -> 300
~ -[UAEHPointerControlDriver _deactivateSwitchIfNeeded:] : 452 -> 440
~ -[UAEHPointerControlDriver _togglePauseResumeMotionTracking] : 116 -> 92
~ ___61-[UAEHPointerControlDriver _motionTrackingLostFaceWithError:]_block_invoke : 156 -> 144
~ +[UAEHPointerControlDriver _eventTapManager] : 84 -> 72
~ ___44+[UAEHPointerControlDriver _eventTapManager]_block_invoke : 72 -> 60
~ -[UAEHPointerControlDriver _updateMouseListenerState] : 136 -> 112
~ ___48-[UAEHPointerControlDriver device:didPostEvent:]_block_invoke_2 : 124 -> 112
~ -[UAEHPointerControlDriver _hardwareMouseEventReceivedOnMainThread] : 236 -> 224
~ -[UAEHPointerControlDriver _modalDraggedMouseButtonNumber] : 156 -> 144
~ -[UAEHPointerControlDriver _switchDownDraggedMouseButtonNumber] : 80 -> 68
~ -[UAEHPointerControlDriver _setSwitchDownDraggedMouseButtonNumber:] : 124 -> 112
~ -[UAEHPointerControlDriver _setModalDraggedSwitch:] : 124 -> 112
~ -[UAEHPointerControlDriver _modalDraggedSwitch] : 80 -> 68
~ ___46+[UAEHPointerControlDriver eventMarkupHandler]_block_invoke : 64 -> 52
~ -[UAEHPointerControlDriver _moveMouseToLocation:] : 136 -> 124
~ -[UAEHPointerControlDriver _provideUserFeedback:] : 468 -> 456
~ -[UAEHPointerControlDriver _visualsAgent] : 280 -> 268
~ ___79-[UAEHPointerControlDriver motionTrackingInputManager:updatedCompatibleInputs:]_block_invoke : 104 -> 92
~ -[UAEHPointerControlDriver .cxx_destruct] : 344 -> 332
~ +[UAEHPointerControlSwitchStorage _switchesFromPreferencesUsingAlternateMouseButtons:usingHeadMouse:] : 192 -> 180
~ ___51-[UAEHPointerControlSwitchStorage keyboardSwitches]_block_invoke : 252 -> 240
~ ___48-[UAEHPointerControlSwitchStorage mouseSwitches]_block_invoke : 196 -> 184
~ ___50-[UAEHPointerControlSwitchStorage gamepadSwitches]_block_invoke : 196 -> 184
~ ___53-[UAEHPointerControlSwitchStorage expressionSwitches]_block_invoke : 116 -> 104
~ -[UAEHPointerControlSwitchStorage mouseSwitchesMatchingEvent:cgEvent:] : 436 -> 424
~ ___70-[UAEHPointerControlSwitchStorage mouseSwitchesMatchingEvent:cgEvent:]_block_invoke : 92 -> 80
~ -[UAEHPointerControlSwitchStorage keyboardSwitchesMatchingEvent:cgEvent:] : 436 -> 424
~ ___73-[UAEHPointerControlSwitchStorage keyboardSwitchesMatchingEvent:cgEvent:]_block_invoke : 92 -> 80
~ -[UAEHPointerControlSwitchStorage gamepadSwitchesMatchingDevice:] : 428 -> 416
~ ___65-[UAEHPointerControlSwitchStorage gamepadSwitchesMatchingDevice:]_block_invoke : 164 -> 152
~ -[UAEHPointerControlSwitchStorage gamepadSwitchesMatchingEvent:fromDevice:] : 496 -> 484
~ ___75-[UAEHPointerControlSwitchStorage gamepadSwitchesMatchingEvent:fromDevice:]_block_invoke : 100 -> 88
~ -[UAEHPointerControlSwitchStorage expressionSwitchesMatchingExpression:] : 392 -> 380
~ ___72-[UAEHPointerControlSwitchStorage expressionSwitchesMatchingExpression:]_block_invoke : 140 -> 128
~ -[UAEHPointerControlSwitchStorage switchWithUUID:] : 224 -> 212
~ ___50-[UAEHPointerControlSwitchStorage switchWithUUID:]_block_invoke : 164 -> 152
~ -[UAEHPointerControlSwitchStorage switches] : 108 -> 96
~ -[UAEHPointerControlSwitchStorage _switchesMatching:] : 292 -> 280
~ ___53-[UAEHPointerControlSwitchStorage _switchesMatching:]_block_invoke : 92 -> 80
~ -[UAEHPointerControlSwitchStorage _switches] : 60 -> 48
~ -[UAEHPointerControlSwitchStorage _setSwitches:] : 108 -> 96
~ _handleEvent : 76 -> 64
~ _initialize : 136 -> 124
~ _updateSettings : 68 -> 56
~ _userSessionDidChange : 68 -> 56
```
