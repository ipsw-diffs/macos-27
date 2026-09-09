## com.apple.Terminal

> `/System/Library/Accessibility/BundlesBase/com.apple.Terminal.axbundle/Versions/A/com.apple.Terminal`

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
-  __TEXT.__text: 0x3614
+  __TEXT.__text: 0x34b4
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__objc_stubs: 0xb60
   __TEXT.__objc_methlist: 0x2dc

   __TEXT.__const: 0x30
   __TEXT.__gcc_except_tab: 0x148
   __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x218
+  __TEXT.__unwind_info: 0x278
   __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__cfstring: 0x6e0
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ +[AXTerminalGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___61+[AXTerminalGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___61+[AXTerminalGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 116 -> 104
~ _accessibilityLocalizedString : 184 -> 172
~ +[TTLogicalScreenAccessibility _accessibilityPerformValidations:] : 420 -> 408
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[TTLogicalScreenAccessibility _axcCurrentLineIsPrompt] : 60 -> 48
~ +[TTKeyMappingsControllerAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ ___73+[TTKeyMappingsControllerAccessibility accessibilitySetupExistingObjects]_block_invoke : 216 -> 204
~ +[TTViewAccessibility _accessibilityPerformValidations:] : 484 -> 472
~ -[TTViewAccessibility accessibilityAttributeNames] : 248 -> 236
~ -[TTViewAccessibility accessibilityAttributeValue:] : 176 -> 164
~ -[TTViewAccessibility accessibilityParameterizedAttributeNames] : 264 -> 252
~ -[TTViewAccessibility accessibilityAttributeValue:forParameter:] : 260 -> 248
~ -[TTViewAccessibility accessibilityNumberOfCharacters] : 656 -> 652
~ __54-[TTViewAccessibility accessibilityNumberOfCharacters]_block_invoke.441 : 88 -> 76
~ ___49-[TTViewAccessibility accessibilityRangeForLine:]_block_invoke_3 : 84 -> 72
~ ___48-[TTViewAccessibility keyDown:withAutoMarkLine:]_block_invoke : 132 -> 120
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[TTViewAccessibility cachedStatesIfApplicable:] : 376 -> 364
~ -[TTViewAccessibility _axcInvalidate] : 160 -> 148
~ -[TTViewAccessibility _axcLogicalScreen] : 332 -> 320
~ ___40-[TTViewAccessibility _axcLogicalScreen]_block_invoke : 80 -> 68
~ -[TTViewAccessibility _axJumpToSelectedMarker] : 68 -> 56
~ -[TTViewAccessibility _moveVoiceOverCursorToLine:] : 100 -> 88
~ _axcTerminalLog : 68 -> 56
~ ___axcTerminalLog_block_invoke : 72 -> 60
~ _OUTLINED_FUNCTION_1 : 28 -> 16
```
