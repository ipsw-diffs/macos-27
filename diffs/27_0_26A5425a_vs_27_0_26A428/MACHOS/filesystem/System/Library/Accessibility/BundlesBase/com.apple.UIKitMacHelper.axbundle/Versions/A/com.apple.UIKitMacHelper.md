## com.apple.UIKitMacHelper

> `/System/Library/Accessibility/BundlesBase/com.apple.UIKitMacHelper.axbundle/Versions/A/com.apple.UIKitMacHelper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x3378
+  __TEXT.__text: 0x31b0
   __TEXT.__auth_stubs: 0x240
   __TEXT.__objc_stubs: 0xa00
   __TEXT.__objc_methlist: 0xb10

   __TEXT.__objc_methtype: 0xa25
   __TEXT.__const: 0x28
   __TEXT.__gcc_except_tab: 0x80
-  __TEXT.__unwind_info: 0x1d8
+  __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x2f0
   __DATA_CONST.__cfstring: 0x6a0
   __DATA_CONST.__objc_classlist: 0x80
Functions:
~ -[UINSWindowAccessibility accessibilityAttributeValue:] : 228 -> 216
~ -[UINSWindowAccessibility accessibilityHitTest:] : 388 -> 376
~ +[UINSSceneViewAccessibility _accessibilityPerformValidations:] : 292 -> 280
~ -[UINSSceneViewAccessibility _accessibilityUIKitWindowsForHitTest:] : 564 -> 552
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[UINSSceneViewAccessibility accessibilityAttributeValue:] : 196 -> 184
~ -[UINSSceneViewAccessibility accessibilityAuditHierarchy] : 252 -> 240
~ -[UINSSceneViewAccessibility accessibilityAuditLabel] : 252 -> 240
~ -[UINSSceneViewAccessibility accessibilityAuditPotentialChildren] : 264 -> 252
~ -[UINSSceneViewAccessibility accessibilityAuditContrast] : 252 -> 240
~ -[UINSSceneViewAccessibility accessibilityWindow] : 176 -> 164
~ -[UINSSceneViewAccessibility _accessibilityChildrenForHitTest:] : 220 -> 208
~ ___63-[UINSSceneViewAccessibility _accessibilityChildrenForHitTest:]_block_invoke : 348 -> 336
~ __63-[UINSSceneViewAccessibility _accessibilityChildrenForHitTest:]_block_invoke.402 : 84 -> 72
~ -[UINSSceneViewAccessibility _caxBridgedHosts] : 92 -> 80
~ ___46-[UINSSceneViewAccessibility _caxBridgedHosts]_block_invoke : 44 -> 32
~ -[UINSSceneViewAccessibility accessibilityHitTest:] : 600 -> 588
~ -[UINSSceneViewAccessibility accessibilityFocusedUIElement] : 176 -> 164
~ +[UINSPopoverManagerAccessibility _accessibilityPerformValidations:] : 196 -> 184
~ +[UINSInputViewAccessibility _accessibilityPerformValidations:] : 168 -> 156
~ -[UINSInputViewAccessibility accessibilityFocusedUIElement] : 160 -> 148
~ -[UINSInputViewAccessibility accessibilityPopUpMenuParent:] : 172 -> 160
~ +[UINSMenuControllerAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ -[UINSApplicationDelegateAccessibility _accessibilityWindowProxyForContextId:] : 172 -> 160
~ -[UINSApplicationDelegateAccessibility accessibilityTranslationRootParentWithContext:] : 80 -> 68
~ _getAXPMacPlatformElementClass : 224 -> 212
~ _getAXPTranslatorClass : 224 -> 212
~ _getUIWindowClass : 224 -> 212
~ ___iOSMacAppAccessibilityInitializeIfNeeded_block_invoke_2 : 76 -> 64
~ +[AXUIKitMacHelperGlue accessibilityPrincipalClassInitializeBundle] : 164 -> 152
~ ___67+[AXUIKitMacHelperGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___67+[AXUIKitMacHelperGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 200 -> 188
~ -[iOSMacNonRetainedObjectContainer nonRetainedObject] : 44 -> 32
~ _accessibilityLocalizedString : 184 -> 172
~ +[UINSAlertAccessibility _accessibilityPerformValidations:] : 200 -> 188
```
