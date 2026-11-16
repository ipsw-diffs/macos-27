## PDFKit

> `/System/Library/Frameworks/PDFKit.framework/Versions/A/PDFKit`

```diff

-1537.2.2.0.0
-  __TEXT.__text: 0xde7c8
-  __TEXT.__objc_methlist: 0xc9d0
+1537.2.4.0.0
+  __TEXT.__text: 0xded00
+  __TEXT.__objc_methlist: 0xca48
   __TEXT.__const: 0x9b4
-  __TEXT.__gcc_except_tab: 0x8410
-  __TEXT.__cstring: 0x8074
+  __TEXT.__gcc_except_tab: 0x8428
+  __TEXT.__cstring: 0x8064
   __TEXT.__dlopen_cstrs: 0x257
   __TEXT.__ustring: 0xc2
   __TEXT.__oslogstring: 0x1a

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x18
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x4eb8
+  __TEXT.__unwind_info: 0x4ee0
   __TEXT.__eh_frame: 0x128
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xca8
+  __DATA_CONST.__const: 0xc88
   __DATA_CONST.__objc_classlist: 0x568
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x188
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7a40
+  __DATA_CONST.__objc_selrefs: 0x7a80
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x378
   __DATA_CONST.__objc_arraydata: 0x1d0
-  __DATA_CONST.__got: 0xdd0
-  __AUTH_CONST.__const: 0x2308
+  __DATA_CONST.__got: 0xdc8
+  __AUTH_CONST.__const: 0x2318
   __AUTH_CONST.__cfstring: 0x8880
-  __AUTH_CONST.__objc_const: 0x119e0
+  __AUTH_CONST.__objc_const: 0x11a80
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_intobj: 0x5e8

   __AUTH_CONST.__auth_got: 0x18a8
   __AUTH.__objc_data: 0x19a0
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0xe9c
+  __DATA.__objc_ivar: 0xeb0
   __DATA.__data: 0x1310
   __DATA.__bss: 0x630
   __DATA_DIRTY.__objc_data: 0x1c20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4509
-  Symbols:   11775
+  Functions: 4519
+  Symbols:   11797
   CStrings:  1426
 
Symbols:
+ +[PDFPage _shouldRenderDarkModeInContext:withOptions:]
+ -[PDFAnnotation _acroFormDictionaryForPage:]
+ -[PDFAnnotation _colorWithComponents:inColorSpaceNamed:]
+ -[PDFAnnotation _getInheritedDefaultAppearanceString:fromDictionary:forPage:]
+ -[PDFAnnotation addDefaultPopup]
+ -[PDFAnnotation prefersAppearanceStream]
+ -[PDFDocument appearanceStyle]
+ -[PDFDocument setAppearanceStyle:]
+ -[PDFPage _createDisplayListAsynchronouslyForDarkMode:generation:]
+ -[PDFPage _createDisplayListTrackingGlyphs:darkMode:]
+ -[PDFPage _drawOptionsForThumbnail:]
+ -[PDFPage _installDisplayList:forDarkMode:]
+ -[PDFPage _startCreatingDisplayListForDarkMode:]
+ -[PDFPage copyDisplayListForDarkMode:]
+ -[PDFPage requestDisplayListForDarkMode:]
+ GCC_except_table100
+ GCC_except_table129
+ GCC_except_table137
+ GCC_except_table141
+ GCC_except_table147
+ GCC_except_table152
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table165
+ GCC_except_table166
+ GCC_except_table170
+ GCC_except_table171
+ GCC_except_table194
+ GCC_except_table198
+ GCC_except_table214
+ GCC_except_table223
+ GCC_except_table225
+ GCC_except_table231
+ GCC_except_table232
+ GCC_except_table242
+ GCC_except_table246
+ GCC_except_table247
+ GCC_except_table251
+ GCC_except_table252
+ GCC_except_table253
+ GCC_except_table340
+ GCC_except_table346
+ GCC_except_table82
+ GCC_except_table90
+ GCC_except_table95
+ _OBJC_IVAR_$_PDFAnnotation._appearanceStreamStringValue
+ _OBJC_IVAR_$_PDFAnnotation._formNeedsAppearances
+ _OBJC_IVAR_$_PDFPage._creatingDisplayListIsDarkMode
+ _OBJC_IVAR_$_PDFPage._displayListGeneration
+ _OBJC_IVAR_$_PDFPage._displayListIsDarkMode
+ _OBJC_IVAR_$_PDFPage._displayListRequestedForOtherMode
+ ___48-[PDFPage _startCreatingDisplayListForDarkMode:]_block_invoke
+ ___block_descriptor_49_ea8_32w_e5_v8?0l
+ _objc_msgSend$_acroFormDictionaryForPage:
+ _objc_msgSend$_colorWithComponents:inColorSpaceNamed:
+ _objc_msgSend$_createDisplayListAsynchronouslyForDarkMode:generation:
+ _objc_msgSend$_createDisplayListTrackingGlyphs:darkMode:
+ _objc_msgSend$_drawOptionsForThumbnail:
+ _objc_msgSend$_getInheritedDefaultAppearanceString:fromDictionary:forPage:
+ _objc_msgSend$_installDisplayList:forDarkMode:
+ _objc_msgSend$_shouldRenderDarkModeInContext:withOptions:
+ _objc_msgSend$_startCreatingDisplayListForDarkMode:
+ _objc_msgSend$addDefaultPopup
+ _objc_msgSend$copyDisplayListForDarkMode:
+ _objc_msgSend$prefersAppearanceStream
+ _objc_msgSend$requestDisplayListForDarkMode:
+ _os_unfair_recursive_lock_lock
- -[PDFPage _createDisplayListTrackingGlyphs:]
- -[PDFPage _createRetainedDisplayList]
- -[PDFPage copyDisplayList]
- -[PDFPage getDisplayListWithCompletion:onQueue:]
- GCC_except_table103
- GCC_except_table104
- GCC_except_table118
- GCC_except_table131
- GCC_except_table143
- GCC_except_table150
- GCC_except_table155
- GCC_except_table156
- GCC_except_table160
- GCC_except_table161
- GCC_except_table167
- GCC_except_table168
- GCC_except_table173
- GCC_except_table190
- GCC_except_table196
- GCC_except_table200
- GCC_except_table201
- GCC_except_table209
- GCC_except_table216
- GCC_except_table226
- GCC_except_table234
- GCC_except_table244
- GCC_except_table248
- GCC_except_table249
- GCC_except_table335
- GCC_except_table341
- GCC_except_table47
- GCC_except_table92
- _OBJC_IVAR_$_PDFPage._createDisplayListCompletionBlocks
- ___37-[PDFPage _createRetainedDisplayList]_block_invoke
- ___48-[PDFPage getDisplayListWithCompletion:onQueue:]_block_invoke
- ___block_descriptor_32_e34_v32?0"PDFBlockQueuePair"8Q16^B24l
- _kCGColorSpaceGenericRGB
- _objc_msgSend$_createDisplayListTrackingGlyphs:
- _objc_msgSend$_createRetainedDisplayList
- _objc_msgSend$blockQueuePairWithBlock:andQueue:
- _objc_msgSend$copyDisplayList
- _objc_msgSend$getDisplayListWithCompletion:onQueue:
- _objc_msgSend$getRed:green:blue:alpha:
- _objc_msgSend$queue
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "NeedAppearances"
- "v32@?0@\"PDFBlockQueuePair\"8Q16^B24"
```
