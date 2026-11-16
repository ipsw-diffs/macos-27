## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/Versions/A/NotesUI`

```diff

-3195.61.6.0.0
-  __TEXT.__text: 0x2672e8
+3195.61.10.0.0
+  __TEXT.__text: 0x2683fc
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x12348
+  __TEXT.__objc_methlist: 0x123b8
   __TEXT.__const: 0x9324
   __TEXT.__cstring: 0x118e4
-  __TEXT.__gcc_except_tab: 0x4338
-  __TEXT.__oslogstring: 0x8f22
+  __TEXT.__gcc_except_tab: 0x4348
+  __TEXT.__oslogstring: 0x8f92
   __TEXT.__ustring: 0x149c0
   __TEXT.__constg_swiftt: 0x32f4
   __TEXT.__swift5_typeref: 0xc0e6

   __TEXT.__swift_as_entry: 0xd0
   __TEXT.__swift_as_ret: 0xf4
   __TEXT.__swift_as_cont: 0x1a0
-  __TEXT.__unwind_info: 0xa960
-  __TEXT.__eh_frame: 0x3f90
+  __TEXT.__unwind_info: 0xa998
+  __TEXT.__eh_frame: 0x3f98
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x268
   __DATA_CONST.__objc_protolist: 0x2a0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd5f8
+  __DATA_CONST.__objc_selrefs: 0xd648
   __DATA_CONST.__objc_protorefs: 0xf8
-  __DATA_CONST.__objc_superrefs: 0x548
+  __DATA_CONST.__objc_superrefs: 0x558
   __DATA_CONST.__objc_arraydata: 0x2f0
-  __DATA_CONST.__got: 0x27d8
+  __DATA_CONST.__got: 0x27e8
   __AUTH_CONST.__const: 0xd488
   __AUTH_CONST.__cfstring: 0xa9a0
-  __AUTH_CONST.__objc_const: 0x1ce58
+  __AUTH_CONST.__objc_const: 0x1ced8
   __AUTH_CONST.__objc_arrayobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x4f8
   __AUTH_CONST.__objc_doubleobj: 0x190

   __AUTH_CONST.__auth_got: 0x2ba8
   __AUTH.__objc_data: 0x2568
   __AUTH.__data: 0x17d8
-  __DATA.__objc_ivar: 0xed8
+  __DATA.__objc_ivar: 0xee0
   __DATA.__data: 0x4738
   __DATA.__objc_stublist: 0x20
   __DATA.__bss: 0x3bd0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12889
-  Symbols:   18480
-  CStrings:  2879
+  Functions: 12904
+  Symbols:   18504
+  CStrings:  2881
 
Symbols:
+ -[ICNote(UI) convertUnconvertedAttachmentsInTextStorage:]
+ -[ICPressGestureRecognizer ignoresLongerTouchPresses]
+ -[ICPressGestureRecognizer setIgnoresLongerTouchPresses:]
+ -[ICPressGestureRecognizer setWaitsForLongerTouchPresses:]
+ -[ICPressGestureRecognizer shouldRequireFailureOfGestureRecognizer:]
+ -[ICPressGestureRecognizer waitsForLongerTouchPresses]
+ -[ICTK2TextController attachmentNeedsConversion:]
+ -[ICTK2TextController init]
+ -[ICTTTextStorage unconvertedAttachmentRange]
+ GCC_except_table131
+ GCC_except_table137
+ GCC_except_table144
+ GCC_except_table146
+ GCC_except_table150
+ GCC_except_table157
+ GCC_except_table168
+ GCC_except_table80
+ GCC_except_table85
+ GCC_except_table93
+ _ICTTAttachmentNeedsConversionNotification
+ _OBJC_IVAR_$_ICPressGestureRecognizer._ignoresLongerTouchPresses
+ _OBJC_IVAR_$_ICTK2TextController._didFailAttachmentConversion
+ __OBJC_$_INSTANCE_VARIABLES_ICPressGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES_ICTK2TextController
+ ___45-[ICTTTextStorage unconvertedAttachmentRange]_block_invoke
+ ___50-[ICTTTextStorage resetHighlightsAttributedString]_block_invoke_2
+ ___56-[ICTTTextStorage redactAuthorAttributionsToCurrentUser]_block_invoke
+ _objc_msgSend$containsWritingToolsGeneratedStrokes
+ _objc_msgSend$convertUnconvertedAttachmentsInTextStorage:
+ _objc_msgSend$ignoresLongerTouchPresses
+ _objc_msgSend$minimumPressDuration
+ _objc_msgSend$setIgnoresLongerTouchPresses:
+ _objc_msgSend$unconvertedAttachmentRange
+ _objc_msgSend$waitsForLongerTouchPresses
- GCC_except_table108
- GCC_except_table130
- GCC_except_table134
- GCC_except_table136
- GCC_except_table143
- GCC_except_table145
- GCC_except_table149
- GCC_except_table156
- GCC_except_table167
- GCC_except_table84
CStrings:
+ "Attachments in %@ at %@ are still unconverted after filtering"
+ "Converting unconverted attachments in %@ at %@"
```
