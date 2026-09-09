## Computer Name

> `/System/Library/ExtensionKit/Extensions/Computer Name.appex/Contents/MacOS/Computer Name`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 2027.0.1.0.0
-  __TEXT.__text: 0x14e8
+  __TEXT.__text: 0x1458
   __TEXT.__auth_stubs: 0x110
   __TEXT.__objc_stubs: 0x720
   __TEXT.__objc_methlist: 0xf4

   __TEXT.__const: 0x20
   __TEXT.__cstring: 0xa7
   __TEXT.__oslogstring: 0x2b
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__cfstring: 0xe0
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ -[ComputerNameViewController loadView] : 108 -> 96
~ -[ComputerNameView prepareToAnimate] : 612 -> 600
~ -[ComputerNameView animateOneFrame] : 1644 -> 1632
~ +[ComputerNameView currentMessageFromDefaults] : 168 -> 156
~ +[ComputerNameView storeMessageToDefaults:] : 280 -> 268
~ -[ComputerNameView updateMessage:] : 616 -> 604
~ -[ComputerNameView clockWindowWillMove:] : 300 -> 288
~ -[ComputerNameView .cxx_destruct] : 84 -> 72
~ -[MessageConfigurationViewController configureSheetWillPresent] : 236 -> 224
~ -[MessageConfigurationViewController dismissController:] : 140 -> 128
~ -[MessageConfigurationViewController controlTextDidChange:] : 112 -> 100
~ -[MessageConfigurationViewController .cxx_destruct] : 144 -> 132
```
