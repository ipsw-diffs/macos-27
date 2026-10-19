## CharacterPicker

> `/System/Library/PrivateFrameworks/CharacterPicker.framework/Versions/A/CharacterPicker`

```diff

-324.1.5.1.500
-  __TEXT.__text: 0xaf8c8
-  __TEXT.__objc_methlist: 0x79fc
-  __TEXT.__cstring: 0x3f4d
+324.1.5.1.501
+  __TEXT.__text: 0xafc30
+  __TEXT.__objc_methlist: 0x7a64
+  __TEXT.__cstring: 0x3fbd
   __TEXT.__const: 0x5804
   __TEXT.__gcc_except_tab: 0x82c
-  __TEXT.__oslogstring: 0x2045
+  __TEXT.__oslogstring: 0x2075
   __TEXT.__ustring: 0x6c
   __TEXT.__dlopen_cstrs: 0x395
   __TEXT.__swift5_typeref: 0x5628

   __TEXT.__swift_as_cont: 0xa8
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x3d40
+  __TEXT.__unwind_info: 0x3d60
   __TEXT.__eh_frame: 0x12d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x760
+  __DATA_CONST.__const: 0x780
   __DATA_CONST.__objc_classlist: 0x350
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x51f8
+  __DATA_CONST.__objc_selrefs: 0x5230
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x260
   __DATA_CONST.__objc_arraydata: 0x448
-  __DATA_CONST.__got: 0xfd8
+  __DATA_CONST.__got: 0xfe8
   __AUTH_CONST.__const: 0x4700
-  __AUTH_CONST.__cfstring: 0x3fe0
-  __AUTH_CONST.__objc_const: 0xe268
+  __AUTH_CONST.__cfstring: 0x4000
+  __AUTH_CONST.__objc_const: 0xe2b0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_intobj: 0x198

   __AUTH_CONST.__auth_got: 0x1850
   __AUTH.__objc_data: 0x27a0
   __AUTH.__data: 0x6e8
-  __DATA.__objc_ivar: 0x7c4
+  __DATA.__objc_ivar: 0x7c8
   __DATA.__data: 0x2160
   __DATA.__bss: 0x41d8
   __DATA.__common: 0x68

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4865
-  Symbols:   13111
-  CStrings:  893
+  Functions: 4874
+  Symbols:   13130
+  CStrings:  897
 
Symbols:
+ -[CPKGenmojiListener didChangeMenuTracking:]
+ -[CPKPopover popoverShouldClose:withReason:]
+ -[CPKPopoverController didChangeMenuTracking:]
+ -[CPKPopoverController isRemotelyTrackingMenu]
+ -[RemoteGenerationViewService menuDidBeginTracking:]
+ -[RemoteGenerationViewService menuDidEndTracking:]
+ -[RemoteGenerationViewService sendMenuTracking:]
+ GCC_except_table120
+ GCC_except_table48
+ GCC_except_table58
+ GCC_except_table79
+ OBJC_IVAR_$_CPKPopoverController._isRemotelyTrackingMenu
+ _NSMenuDidBeginTrackingNotification
+ _NSMenuDidEndTrackingNotification
+ __48-[RemoteGenerationViewService sendMenuTracking:]_block_invoke
+ ___48-[RemoteGenerationViewService sendMenuTracking:]_block_invoke
+ ___block_descriptor_33_e53_v24?0"NSError"8"<CPKGenerationUIRemoteProtocol>"16l
+ _objc_msgSend$didChangeMenuTracking:
+ _objc_msgSend$isActive
+ _objc_msgSend$isRemotelyTrackingMenu
+ _objc_msgSend$sendMenuTracking:
- GCC_except_table119
- GCC_except_table78
CStrings:
+ "-[RemoteGenerationViewService sendMenuTracking:]_block_invoke"
+ "CPKGenerationUIDidChangeMenuTrackingNotification"
+ "not closing popover while the generation UI shows a menu"
+ "\xf0\xf0!"
```
