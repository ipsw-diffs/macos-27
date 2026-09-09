## TextInput_chr

> `/System/Library/TextInput/TextInput_chr.bundle/Versions/A/TextInput_chr`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`

```diff

 3567.400.0.0.0
-  __TEXT.__text: 0xc44
+  __TEXT.__text: 0xc08
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x68
   __TEXT.__const: 0xa8
Functions:
~ +[TIKeyboardInputManager_chr stringByComposingInput:] : 772 -> 760
~ -[TIKeyboardInputManager_chr internalStringToExternal:] : 120 -> 108
~ -[TIKeyboardInputManager_chr externalStringToInternal:] : 968 -> 956
~ -[TIKeyboardInputManager_chr contextualDisplayKeys] : 608 -> 596
~ _GLOBAL__sub_I_TIKeyboardInputManager_chr.mm : 92 -> 80
```
