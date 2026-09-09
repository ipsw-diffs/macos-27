## VirtualGameController

> `/System/iOSSupport/System/Library/Frameworks/GameController.framework/Versions/Current/Resources/VirtualGameController.bundle/Contents/MacOS/VirtualGameController`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 14.0.24.0.0
-  __TEXT.__text: 0x71c4
+  __TEXT.__text: 0x6f30
   __TEXT.__auth_stubs: 0x520
   __TEXT.__objc_stubs: 0x15e0
   __TEXT.__objc_methlist: 0x50c

   __TEXT.__objc_classname: 0xeb
   __TEXT.__objc_methtype: 0x49b
   __TEXT.__gcc_except_tab: 0x124
-  __TEXT.__unwind_info: 0x228
+  __TEXT.__unwind_info: 0x290
   __DATA_CONST.__const: 0x218
   __DATA_CONST.__cfstring: 0x460
   __DATA_CONST.__objc_classlist: 0x40
Functions:
~ -[GCControllerView setupSide:thumbstick:buttons:] : 936 -> 924
~ -[GCControllerView setupPositions] : 460 -> 448
~ -[GCControllerView getUIControlForName:] : 480 -> 468
~ -[GCControllerView getConfigurationForElement:] : 256 -> 244
~ -[GCControllerView setConfigurationForElement:configuration:] : 260 -> 248
~ -[GCControllerView hitTest:withEvent:] : 172 -> 160
~ -[GCControllerView .cxx_destruct] : 324 -> 312
~ +[GCControllerViewFeedback sharedInstance] : 68 -> 56
~ ___42+[GCControllerViewFeedback sharedInstance]_block_invoke : 60 -> 48
~ -[GCControllerViewFeedback .cxx_destruct] : 68 -> 56
~ _VirtualControllerBundle : 68 -> 56
~ ___VirtualControllerBundle_block_invoke : 92 -> 80
~ _GCVirtualControllerBlurEffectView : 124 -> 112
~ _GCVirtualControllerSaturationVibrancyEffectView : 112 -> 100
~ _GCVirtualControllerSaturationVibrancyEffect : 68 -> 56
~ _GCVirtualControllerAdditiveVibrancyEffectView : 84 -> 72
~ ___GCVirtualControllerAdditiveVibrancyEffectView_block_invoke : 132 -> 120
~ -[GCControllerThumbstickInputView processTouch:] : 472 -> 460
~ -[GCControllerThumbstickInputView touchesBegan:withEvent:] : 264 -> 252
~ -[GCControllerThumbstickInputView touchesMoved:withEvent:] : 152 -> 140
~ -[GCControllerThumbstickInputView touchesEnded:withEvent:] : 292 -> 280
~ -[GCControllerThumbstickInputView setThumbstickPos:center:] : 364 -> 352
~ -[GCControllerThumbstickInputView initButtons] : 608 -> 596
~ -[GCControllerThumbstickInputView .cxx_destruct] : 120 -> 108
~ -[GCControllerDpadInputView createDpadButton:backingMask:fillMask:] : 764 -> 752
~ -[GCControllerDpadInputView initButtons] : 1116 -> 1104
~ -[GCControllerDpadInputView processTouch:] : 380 -> 368
~ -[GCControllerDpadInputView touchesBegan:withEvent:] : 188 -> 176
~ -[GCControllerDpadInputView touchesMoved:withEvent:] : 152 -> 140
~ -[GCControllerDpadInputView touchesEnded:withEvent:] : 292 -> 280
~ -[GCControllerDpadInputView setHighlight:highlight:] : 196 -> 184
~ -[GCControllerDpadInputView setThumbstickPos:center:] : 356 -> 344
~ -[GCControllerDpadInputView .cxx_destruct] : 180 -> 168
~ +[NSError gc_VirtualControllerError:userInfo:] : 120 -> 108
~ __gc_log_virtualcontroller : 68 -> 56
~ ____gc_log_virtualcontroller_block_invoke : 68 -> 56
~ -[GCControllerButtonInputView initUI] : 984 -> 972
~ ___43-[GCControllerButtonInputView setupActions]_block_invoke : 140 -> 128
~ ___43-[GCControllerButtonInputView setupActions]_block_invoke_2 : 140 -> 128
~ -[GCControllerButtonInputView triggerButtonWithValue:] : 124 -> 112
~ -[GCControllerButtonInputView .cxx_destruct] : 184 -> 172
~ ___52-[_GCVirtualControllerImpl connectWithReplyHandler:]_block_invoke : 444 -> 432
~ ___38-[_GCVirtualControllerImpl disconnect]_block_invoke : 60 -> 48
~ -[_GCVirtualControllerImpl controller] : 84 -> 60
~ -[_GCVirtualControllerImpl updateConfigurationForElement:configuration:] : 172 -> 160
~ -[_GCVirtualControllerImpl .cxx_destruct] : 80 -> 68
~ ___destructor_8_s0_s48_s56_s64 : 76 -> 64
~ -[GCTouchController setValue:forButtonElement:] : 1256 -> 1244
~ -[GCTouchController setPosition:forDirectionPadElement:] : 536 -> 524
~ -[GCTouchController .cxx_destruct] : 84 -> 72
~ -[GCControllerView applyPadLayout] : 324 -> 312
~ -[GCControllerView applyPhoneLayout] : 476 -> 464
~ __GCAnalyticsSendVirtualControllerConnectedEvent_block_invoke.cold.1 : 84 -> 72
~ -[_GCVirtualControllerImpl findKeyWindow] : 344 -> 332
```
