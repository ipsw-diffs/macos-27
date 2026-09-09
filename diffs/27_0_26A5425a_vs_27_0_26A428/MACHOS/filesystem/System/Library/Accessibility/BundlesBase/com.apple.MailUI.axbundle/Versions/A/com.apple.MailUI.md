## com.apple.MailUI

> `/System/Library/Accessibility/BundlesBase/com.apple.MailUI.axbundle/Versions/A/com.apple.MailUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x292c
+  __TEXT.__text: 0x27d0
   __TEXT.__auth_stubs: 0x180
   __TEXT.__objc_stubs: 0x740
   __TEXT.__objc_methlist: 0x290

   __TEXT.__objc_methtype: 0x5d
   __TEXT.__const: 0x18
   __TEXT.__gcc_except_tab: 0x80
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x160
   __DATA_CONST.__const: 0x1d0
   __DATA_CONST.__cfstring: 0xc20
   __DATA_CONST.__objc_classlist: 0x88
Functions:
~ +[MUITokenAddressFieldCellAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[MUITokenAddressFieldCellAccessibility accessibilitySharedFocusElements] : 564 -> 552
~ ___73-[MUITokenAddressFieldCellAccessibility accessibilitySharedFocusElements]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[MUITokenAddressFieldCellAccessibility _axcTokenAddressField] : 196 -> 184
~ +[NSTableViewCellMockElementAccessibility__MailUI__AppKit _accessibilityPerformValidations:] : 256 -> 244
~ -[NSTableViewCellMockElementAccessibility__MailUI__AppKit accessibilityChildrenAttribute] : 492 -> 480
~ ___89-[NSTableViewCellMockElementAccessibility__MailUI__AppKit accessibilityChildrenAttribute]_block_invoke : 92 -> 80
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ -[NSTableViewCellMockElementAccessibility__MailUI__AppKit accessibilityChildrenInNavigationOrderAttribute] : 492 -> 480
~ ___106-[NSTableViewCellMockElementAccessibility__MailUI__AppKit accessibilityChildrenInNavigationOrderAttribute]_block_invoke : 92 -> 80
~ +[MessageStatusStackViewAccessibility _accessibilityPerformValidations:] : 96 -> 84
~ -[MessageStatusStackViewAccessibility accessibilityLabel] : 532 -> 520
~ +[MUIAddressFieldAccessibility _accessibilityPerformValidations:] : 288 -> 276
~ -[MUIAddressFieldAccessibility _axcAddressTokenIconsForAddress:includeExternalAddressTokenIcon:] : 400 -> 388
~ ___96-[MUIAddressFieldAccessibility _axcAddressTokenIconsForAddress:includeExternalAddressTokenIcon:]_block_invoke : 88 -> 76
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ -[MUIAddressFieldAccessibility tokenField:setUpTokenAttachmentCell:forRepresentedObject:] : 772 -> 760
~ +[AXMailUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXMailUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXMailUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 216 -> 204
~ _accessibilityLocalizedString : 184 -> 172
~ +[MUIRichMessageCellBaseAccessibility _accessibilityPerformValidations:] : 588 -> 576
~ -[MUIRichMessageCellBaseAccessibility accessibilityChildrenInNavigationOrder] : 336 -> 324
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
```
