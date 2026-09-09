## com.apple.AppKit

> `/System/Library/Accessibility/BundlesBase/com.apple.AppKit.axbundle/Versions/A/com.apple.AppKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x345c
+  __TEXT.__text: 0x3204
   __TEXT.__auth_stubs: 0x280
   __TEXT.__objc_stubs: 0xc60
   __TEXT.__objc_methlist: 0x530

   __TEXT.__const: 0x28
   __TEXT.__gcc_except_tab: 0x7c
   __TEXT.__dlopen_cstrs: 0x54
-  __TEXT.__unwind_info: 0x1e0
+  __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x288
   __DATA_CONST.__cfstring: 0xa80
   __DATA_CONST.__objc_classlist: 0xe0
Functions:
~ +[NSCampoLightweightUIHostWindowAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ ___73-[NSCampoLightweightUIHostWindowAccessibility accessibilityPerformCancel]_block_invoke : 100 -> 88
~ +[NSViewWritingToolsAccessibility _accessibilityPerformValidations:] : 236 -> 224
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[NSViewWritingToolsAccessibility accessibilityActionNames] : 204 -> 192
~ -[NSViewWritingToolsAccessibility accessibilityActionDescription:] : 156 -> 144
~ ___62-[NSViewWritingToolsAccessibility accessibilityPerformAction:]_block_invoke : 116 -> 104
~ +[NSTextInputContextAccessibility _accessibilityPerformValidations:] : 144 -> 132
~ ___43-[NSTextInputContextAccessibility activate]_block_invoke_2 : 112 -> 100
~ +[NSViewAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[NSViewAccessibility axb_accessibilityViewController] : 260 -> 248
~ -[NSViewAccessibility axb_secondaryClickEventAtCenter] : 252 -> 240
~ -[NSViewAccessibility axb_accessibilityViewAncestorIsKindOf:] : 180 -> 168
~ +[NSVisualTabPickerNewTabViewAccessibility _accessibilityPerformValidations:] : 120 -> 108
~ -[NSVisualTabPickerNewTabViewAccessibility accessibilityAttributeValue:] : 204 -> 192
~ -[NSVisualTabPickerNewTabViewAccessibility accessibilityActionNames] : 128 -> 116
~ ___71-[NSVisualTabPickerNewTabViewAccessibility accessibilityPerformAction:]_block_invoke : 84 -> 72
~ -[NSCellAccessibility axb_accessibilityViewAncestorIsKindOf:] : 88 -> 76
~ -[NSCellAccessibility axb_accessibilityViewController] : 80 -> 68
~ +[NSMenuItemViewAccessibility _accessibilityPerformValidations:] : 212 -> 200
~ -[NSSplitViewAccessibility accessibilityAttributeNames] : 148 -> 136
~ -[NSSplitViewAccessibility accessibilitySplitViewItemsAttribute] : 332 -> 320
~ +[NSVisualTabPickerThumbnailViewAccessibility _accessibilityPerformValidations:] : 204 -> 192
~ -[NSVisualTabPickerThumbnailViewAccessibility accessibilityAttributeValue:] : 160 -> 148
~ -[NSVisualTabPickerThumbnailViewAccessibility accessibilityCustomActions] : 476 -> 464
~ ___73-[NSVisualTabPickerThumbnailViewAccessibility accessibilityCustomActions]_block_invoke : 96 -> 84
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ +[AXAppKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXAppKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXAppKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 396 -> 384
~ _accessibilityLocalizedString : 184 -> 172
~ ___accessibilityAppKitAllowedProcess_block_invoke : 188 -> 176
~ +[AXOpenInReaderMenuHelper installReaderMenu] : 152 -> 140
~ -[AXOpenInReaderMenuHelper _findSpeechMenu] : 576 -> 564
~ -[AXOpenInReaderMenuHelper _setupEditMenu:] : 236 -> 224
~ -[AXOpenInReaderMenuHelper _updateMenuItemState] : 136 -> 124
~ -[AXOpenInReaderMenuHelper _addMenuItemIfNeeded] : 440 -> 428
~ -[AXOpenInReaderMenuHelper _removeMenuItemIfNeeded] : 184 -> 172
~ -[AXOpenInReaderMenuHelper openInReader:] : 176 -> 164
~ +[NSTableViewAccessibility _accessibilityPerformValidations:] : 208 -> 196
~ -[NSTableViewAccessibility accessibilityAttributeValue:] : 188 -> 176
~ -[NSTableViewAccessibility _accessibilityLastSelectedRow] : 288 -> 276
~ ___57-[NSTableViewAccessibility _accessibilityLastSelectedRow]_block_invoke : 84 -> 72
~ -[NSTableViewAccessibility _accessibilityPreviousSelectedRow] : 288 -> 276
~ ___61-[NSTableViewAccessibility _accessibilityPreviousSelectedRow]_block_invoke : 84 -> 72
~ +[NSApplicationAccessibility _accessibilityPerformValidations:] : 140 -> 128
~ -[NSApplicationAccessibility accessibilityTitleAttribute] : 552 -> 540
~ +[NSDocumentRevisionsViewAccessibility _accessibilityPerformValidations:] : 128 -> 116
```
