## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/Versions/A/UIFoundation`

```diff

-1057.1.0.0.0
-  __TEXT.__text: 0x14289c
-  __TEXT.__objc_methlist: 0xd12c
+1057.2.0.0.0
+  __TEXT.__text: 0x1428c8
+  __TEXT.__objc_methlist: 0xd134
   __TEXT.__const: 0x1434
   __TEXT.__cstring: 0x173e3
   __TEXT.__ustring: 0x42e
-  __TEXT.__gcc_except_tab: 0x3824
+  __TEXT.__gcc_except_tab: 0x3828
   __TEXT.__oslogstring: 0x53a
   __TEXT.__dlopen_cstrs: 0x41
   __TEXT.__dof_UIFoundat: 0x2bd

   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7778
+  __DATA_CONST.__objc_selrefs: 0x7780
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x478
   __DATA_CONST.__objc_arraydata: 0xa8
   __DATA_CONST.__got: 0xad8
   __AUTH_CONST.__const: 0x4818
   __AUTH_CONST.__cfstring: 0x107e0
-  __AUTH_CONST.__objc_const: 0x14f40
+  __AUTH_CONST.__objc_const: 0x14f60
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1408
-  __AUTH.__objc_data: 0x1680
+  __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x1d0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x1
-  __DATA.__objc_ivar: 0x1610
-  __DATA.__data: 0x1370
+  __DATA.__objc_ivar: 0x1614
+  __DATA.__data: 0x1378
   __DATA.__bss: 0xb70
   __DATA.__common: 0x9
-  __DATA_DIRTY.__objc_data: 0x1a90
-  __DATA_DIRTY.__data: 0x459
+  __DATA_DIRTY.__objc_data: 0x1b80
+  __DATA_DIRTY.__data: 0x451
   __DATA_DIRTY.__bss: 0xa98
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 6139
-  Symbols:   13745
+  Functions: 6140
+  Symbols:   13749
   CStrings:  4007
 
Symbols:
+ -[NSTextContainer _serialNumber]
+ OBJC_IVAR_$_NSTextContainer._serialNumber
+ OBJC_IVAR_$_NSTextLayoutFragment._textContainerSerialNumberForAnchoredAttachmentViewProviderCache
+ _commonInit.__NSTextContainerSerialNumberSource
+ _objc_msgSend$_serialNumber
- OBJC_IVAR_$_NSTextLayoutFragment._textContainerForAnchoredAttachmentViewProviderCache
Functions:
~ -[NSTextContainer _commonInit] : 112 -> 164
+ +[NSTextContainer supportsSecureCoding]
~ -[NSTextLayoutFragment setTextLayoutManager:] : 96 -> 88
~ -[NSTextLayoutFragment dealloc] : 224 -> 216
```
