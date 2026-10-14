## LoginUIKit

> `/System/Library/PrivateFrameworks/LoginUIKit.framework/Versions/A/LoginUIKit`

```diff

-415.2.4.0.0
-  __TEXT.__text: 0xa9a88
-  __TEXT.__objc_methlist: 0xb08c
-  __TEXT.__const: 0x1344
-  __TEXT.__cstring: 0xa703
-  __TEXT.__gcc_except_tab: 0x11f4
+415.2.6.0.0
+  __TEXT.__text: 0xab220
+  __TEXT.__objc_methlist: 0xb10c
+  __TEXT.__const: 0x1348
+  __TEXT.__cstring: 0xa725
+  __TEXT.__gcc_except_tab: 0x1210
   __TEXT.__dlopen_cstrs: 0x404
   __TEXT.__ustring: 0x3a
   __TEXT.__oslogstring: 0x701
-  __TEXT.__swift5_typeref: 0x51d
-  __TEXT.__constg_swiftt: 0x464
+  __TEXT.__swift5_typeref: 0x524
+  __TEXT.__constg_swiftt: 0x480
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_capture: 0x78c
-  __TEXT.__swift5_types: 0x38
+  __TEXT.__swift5_types: 0x3c
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x8c
-  __TEXT.__swift5_fieldmd: 0x15c
+  __TEXT.__swift5_fieldmd: 0x16c
   __TEXT.__swift5_reflstr: 0xfe
   __TEXT.__swift5_assocty: 0x48
   __TEXT.__swift5_proto: 0x3c
-  __TEXT.__unwind_info: 0x3978
+  __TEXT.__unwind_info: 0x39f8
   __TEXT.__eh_frame: 0xf10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x62b8
+  __DATA_CONST.__objc_selrefs: 0x6310
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x4e8
   __DATA_CONST.__objc_arraydata: 0x210
-  __DATA_CONST.__got: 0x11b0
-  __AUTH_CONST.__const: 0x34f1
+  __DATA_CONST.__got: 0x11e8
+  __AUTH_CONST.__const: 0x35f8
   __AUTH_CONST.__cfstring: 0x91a0
-  __AUTH_CONST.__objc_const: 0x112c8
+  __AUTH_CONST.__objc_const: 0x11358
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_arrayobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x80
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1138
+  __AUTH_CONST.__auth_got: 0x11a8
   __AUTH.__objc_data: 0x35c0
   __AUTH.__data: 0x340
-  __DATA.__objc_ivar: 0xb88
-  __DATA.__data: 0xf90
+  __DATA.__objc_ivar: 0xb94
+  __DATA.__data: 0xfb8
   __DATA.__bss: 0xe40
   __DATA.__common: 0xc0
   __DATA_DIRTY.__objc_data: 0x4a8

   - /System/Library/Frameworks/SecurityFoundation.framework/Versions/A/SecurityFoundation
   - /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
+  - /System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils
   - /System/Library/PrivateFrameworks/CoreWLANKit.framework/Versions/A/CoreWLANKit
   - /System/Library/PrivateFrameworks/DiskManagement.framework/Versions/A/DiskManagement
   - /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/Versions/A/IOMobileFramebuffer

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4797
-  Symbols:   9804
-  CStrings:  1442
+  Functions: 4842
+  Symbols:   9840
+  CStrings:  1443
 
Symbols:
+ -[LUI2CollectionView _handlePointerEvent:]
+ -[LUI2CollectionView isHandlingPointerEvent]
+ -[LUI2CollectionView mouseDragged:]
+ -[LUI2UserCollectionViewController _beginLayoutTransitionTo:]
+ -[LUI2UserCollectionViewController _endLayoutTransition:]
+ -[LUI2UserCollectionViewController _pointerInputIsDrivingSelection]
+ -[LUI2UserCollectionViewController layoutTransitionGeneration]
+ -[LUI2UserCollectionViewController openingMultiUserLayout]
+ -[LUI2UserCollectionViewController setLayoutTransitionGeneration:]
+ -[LUI2UserCollectionViewController setOpeningMultiUserLayout:]
+ GCC_except_table100
+ GCC_except_table112
+ GCC_except_table115
+ GCC_except_table119
+ GCC_except_table137
+ GCC_except_table59
+ GCC_except_table63
+ GCC_except_table66
+ GCC_except_table67
+ GCC_except_table71
+ GCC_except_table82
+ GCC_except_table87
+ GCC_except_table88
+ OBJC_IVAR_$_LUI2CollectionView._pointerEventDepth
+ OBJC_IVAR_$_LUI2UserCollectionViewController._layoutTransitionGeneration
+ OBJC_IVAR_$_LUI2UserCollectionViewController._openingMultiUserLayout
+ _IsAppleInternalBuild
+ _MGCopyMultipleAnswers
+ ___30-[LUI2CollectionView mouseUp:]_block_invoke
+ ___32-[LUI2CollectionView mouseDown:]_block_invoke
+ ___35-[LUI2CollectionView mouseDragged:]_block_invoke
+ ___block_descriptor_72_e8_32s40bs_e5_v8?0l
+ ___swift_memcpy0_1
+ _objc_exception_rethrow
+ _objc_msgSend$_beginLayoutTransitionTo:
+ _objc_msgSend$_endLayoutTransition:
+ _objc_msgSend$_handlePointerEvent:
+ _objc_msgSend$_pointerInputIsDrivingSelection
+ _objc_msgSend$isHandlingPointerEvent
+ _objc_msgSend$layoutTransitionGeneration
+ _objc_msgSend$openingMultiUserLayout
+ _objc_msgSend$setLayoutTransitionGeneration:
+ _objc_msgSend$setOpeningMultiUserLayout:
+ _objc_msgSend$valueForKey:
+ _objc_terminate
+ _swift_bridgeObjectRelease_n
+ _symbolic _____ 15WallpaperAccess9ModelInfoO
- GCC_except_table113
- GCC_except_table117
- GCC_except_table135
- GCC_except_table64
- GCC_except_table65
- GCC_except_table69
- GCC_except_table80
- GCC_except_table83
- GCC_except_table86
- GCC_except_table90
- GCC_except_table98
CStrings:
+ "DeviceEnclosureColor"
+ "\xf0Q"
- "\xf0A"
```
