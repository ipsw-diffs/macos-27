## CarPlay

> `/System/iOSSupport/System/Library/Frameworks/CarPlay.framework/Versions/A/CarPlay`

```diff

-553.9.1.0.0
-  __TEXT.__text: 0x5c464
-  __TEXT.__objc_methlist: 0x90f8
+553.14.2.0.0
+  __TEXT.__text: 0x5cdd0
+  __TEXT.__objc_methlist: 0x9180
   __TEXT.__const: 0x36a
-  __TEXT.__cstring: 0x5496
-  __TEXT.__oslogstring: 0x24ce
+  __TEXT.__cstring: 0x54b6
+  __TEXT.__oslogstring: 0x250e
   __TEXT.__gcc_except_tab: 0x794
   __TEXT.__constg_swiftt: 0x134
   __TEXT.__swift5_typeref: 0x7f

   __TEXT.__swift5_fieldmd: 0x64
   __TEXT.__swift5_proto: 0x4
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x23d8
+  __TEXT.__unwind_info: 0x2400
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1d20
+  __DATA_CONST.__const: 0x1d90
   __DATA_CONST.__objc_classlist: 0x3e8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d20
+  __DATA_CONST.__objc_selrefs: 0x3d58
   __DATA_CONST.__objc_protorefs: 0x108
   __DATA_CONST.__objc_superrefs: 0x348
-  __DATA_CONST.__got: 0x680
-  __AUTH_CONST.__const: 0x9a8
-  __AUTH_CONST.__cfstring: 0x5440
-  __AUTH_CONST.__objc_const: 0x1f8b0
+  __DATA_CONST.__got: 0x690
+  __AUTH_CONST.__const: 0x9e8
+  __AUTH_CONST.__cfstring: 0x5480
+  __AUTH_CONST.__objc_const: 0x1f8d8
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x630
   __AUTH.__objc_data: 0x98
   __DATA.__objc_ivar: 0xa1c
-  __DATA.__data: 0x1940
-  __DATA.__bss: 0x360
+  __DATA.__data: 0x1950
+  __DATA.__bss: 0x390
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x2698
   __DATA_DIRTY.__data: 0x1f8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3114
-  Symbols:   7132
-  CStrings:  969
+  Functions: 3128
+  Symbols:   7157
+  CStrings:  973
 
Symbols:
+ +[CPListImageRowItemCondensedElement _setMaximumImageSize:]
+ +[CPListImageRowItemGridElement _setMaximumImageSize:]
+ +[CPListImageRowItemImageGridElement _setMaximumImageSize:]
+ +[CPListTemplate _setSupportsPlaybackConfirmationBlock:]
+ +[CPSessionConfiguration _setHostSupportsVideoPlayback:]
+ -[CPTemplateApplicationDashboardScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:statusBarAxis:]
+ -[CPTemplateApplicationInstrumentClusterScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:statusBarAxis:]
+ -[CPTemplateApplicationScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:statusBarAxis:]
+ GCC_except_table140
+ GCC_except_table32
+ GCC_except_table40
+ GCC_except_table53
+ GCC_except_table62
+ GCC_except_table82
+ __OBJC_$_CLASS_METHODS_CPSessionConfiguration
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_11
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_12
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_13
+ ___95-[CPListTemplate listTemplateWithIdentifier:didSelectListItemWithIdentifier:completionHandler:]_block_invoke_2
+ ___96-[CPListTemplate listTemplateWithIdentifier:didSelectImageAtIndex:inImageRowItemWithIdentifier:]_block_invoke_2
+ ___96-[CPListTemplate listTemplateWithIdentifier:didSelectImageAtIndex:inImageRowItemWithIdentifier:]_block_invoke_3
+ ___block_descriptor_32_e8_v12?0B8l
+ ___block_descriptor_48_e8_32bs40bs_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ __hostSupportsVideoPlayback
+ __supportsPlaybackConfirmationBlock
+ _objc_msgSend$_setHostSupportsVideoPlayback:
+ _objc_msgSend$_setSupportsPlaybackConfirmationBlock:
+ _objc_msgSend$initWithIdentifier:
+ _objc_msgSend$preferredImageRowCondensedElementMaximumImageSizeWithReply:
+ _objc_msgSend$preferredImageRowGridElementMaximumImageSizeWithReply:
+ _objc_msgSend$preferredImageRowImageGridElementMaximumImageSizeWithReply:
+ _objc_msgSend$supportsPlaybackConfirmationBlockWithReply:
+ _objc_msgSend$supportsVideoPlaybackWithReply:
- -[CPTemplateApplicationDashboardScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:]
- -[CPTemplateApplicationInstrumentClusterScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:]
- -[CPTemplateApplicationScene _safeAreaInsetsForInterfaceOrientation:statusBarHidden:]
- GCC_except_table135
- GCC_except_table28
- GCC_except_table31
- GCC_except_table39
- GCC_except_table52
- GCC_except_table61
CStrings:
+ "Server %@ playback confirmation block"
+ "Server %@ video playback"
+ "does not support"
+ "supports"
```
