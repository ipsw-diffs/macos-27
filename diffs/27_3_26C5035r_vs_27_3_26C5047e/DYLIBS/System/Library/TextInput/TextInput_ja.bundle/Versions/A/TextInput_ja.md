## TextInput_ja

> `/System/Library/TextInput/TextInput_ja.bundle/Versions/A/TextInput_ja`

```diff

-3568.2.4.0.0
-  __TEXT.__text: 0x1ffa4
+3568.2.7.0.0
+  __TEXT.__text: 0x20098
   __TEXT.__init_offsets: 0x18
-  __TEXT.__objc_methlist: 0x2150
+  __TEXT.__objc_methlist: 0x2160
   __TEXT.__cstring: 0xd0c
   __TEXT.__ustring: 0x250
   __TEXT.__const: 0x240
   __TEXT.__oslogstring: 0x144
-  __TEXT.__unwind_info: 0xa58
+  __TEXT.__unwind_info: 0xa60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1840
+  __DATA_CONST.__objc_selrefs: 0x1858
   __DATA_CONST.__objc_superrefs: 0x90
   __DATA_CONST.__objc_arraydata: 0x290
   __DATA_CONST.__got: 0x380

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libmecabra.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 765
-  Symbols:   1984
+  Functions: 766
+  Symbols:   1987
   CStrings:  324
 
Symbols:
+ -[TIKeyboardInputManager_ja_Kana keyboardConfigurationAssertDefaultKeyPlane]
+ _objc_msgSend$shouldSuppressEnglishCandidates
+ _objc_msgSend$shouldSuppressPredictionCandidates
Functions:
~ -[TIWordSearchKana makeCandidates:input:contextString:onScreenContext:predictionEnabled:reanalysisMode:withInputManager:geometryModelData:flickUsed:hardwareKeyboardMode:referenceMode:singlePhrase:] : 908 -> 1004
+ -[TIKeyboardInputManager_ja_Kana keyboardConfigurationAssertDefaultKeyPlane]
```
