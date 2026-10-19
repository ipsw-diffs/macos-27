## Safari

> `/System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-625.2.8.11.6
-  __TEXT.__text: 0x7c7b10
-  __TEXT.__objc_methlist: 0x5ee5c
+625.2.8.11.9
+  __TEXT.__text: 0x7c8240
+  __TEXT.__objc_methlist: 0x5eea4
   __TEXT.__cstring: 0x45448
-  __TEXT.__gcc_except_tab: 0xd05c8
+  __TEXT.__gcc_except_tab: 0xd05f8
   __TEXT.__const: 0xa988
   __TEXT.__ustring: 0x11390
   __TEXT.__oslogstring: 0x249c1

   __TEXT.__swift_as_cont: 0x1c8
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x42ca0
+  __TEXT.__unwind_info: 0x42cd8
   __TEXT.__eh_frame: 0x3258
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_nlcatlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1278
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x344e8
+  __DATA_CONST.__objc_selrefs: 0x34518
   __DATA_CONST.__objc_protorefs: 0x2d0
   __DATA_CONST.__objc_superrefs: 0x1988
   __DATA_CONST.__objc_arraydata: 0xc20
   __DATA_CONST.__got: 0x4aa8
   __AUTH_CONST.__const: 0x20f78
   __AUTH_CONST.__cfstring: 0x38a20
-  __AUTH_CONST.__objc_const: 0x8b5a8
+  __AUTH_CONST.__objc_const: 0x8b5e8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x14b8
   __AUTH_CONST.__objc_dictobj: 0x5f0

   __AUTH_CONST.__auth_got: 0x3f98
   __AUTH.__objc_data: 0x105a8
   __AUTH.__data: 0x1ea0
-  __DATA.__objc_ivar: 0x6740
+  __DATA.__objc_ivar: 0x6744
   __DATA.__data: 0xffe0
   __DATA.__objc_stublist: 0x20
   __DATA.__bss: 0x5660

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 42060
-  Symbols:   84223
+  Functions: 42070
+  Symbols:   84236
   CStrings:  10980
 
Symbols:
+ -[SafariAppExtensionsController _canExtension:accessURL:]
+ -[SafariAppExtensionsController _getAPIProxyForExtension:shareExtensionContext:reason:completionHandler:]
+ -[SafariAppExtensionsController dispatchValidateContextMenuItem:toExtension:fromPageWithUUID:validationHandler:]
+ GCC_except_table1773
+ GCC_except_table1775
+ OBJC_IVAR_$_SafariAppExtensionData._permissionOriginsLock
+ __105-[SafariAppExtensionsController _getAPIProxyForExtension:shareExtensionContext:reason:completionHandler:]_block_invoke
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSDragContextMenuControllerDelegate
+ __ZNK6Safari10FileLocker8isLockedEv
+ ___105-[SafariAppExtensionsController _getAPIProxyForExtension:shareExtensionContext:reason:completionHandler:]_block_invoke
+ ___105-[SafariAppExtensionsController _getAPIProxyForExtension:shareExtensionContext:reason:completionHandler:]_block_invoke_2
+ ___112-[SafariAppExtensionsController dispatchValidateContextMenuItem:toExtension:fromPageWithUUID:validationHandler:]_block_invoke
+ ___60-[BrowserWindowController _menuForUnifiedTabViewItem:event:]_block_invoke_3
+ ___69-[LibrarySidebarNavigationViewController _createMenuForReportConcern]_block_invoke_3
+ ___85-[SafariAppExtensionData removeGrantedPermissionsForOrigins:exactPatternMatchesOnly:]_block_invoke
+ ___85-[SafariAppExtensionData removeRevokedPermissionsForOrigins:exactPatternMatchesOnly:]_block_invoke
+ ____ZN6Safari10FileLocker25lockWithCompletionHandlerEU13block_pointerFvNS_10LockResultEE_block_invoke_3
+ ____ZN6Safari10FileLocker27unlockWithCompletionHandlerEU13block_pointerFvvE_block_invoke_3
+ ____ZNK6Safari10FileLocker8isLockedEv_block_invoke
+ ___block_descriptor_56_ea8_32s40r_e8_v12?0i8l
+ _objc_msgSend$_canExtension:accessURL:
+ _objc_msgSend$_getAPIProxyForExtension:shareExtensionContext:reason:completionHandler:
+ _objc_msgSend$_userSelectedReportConcern
+ _objc_msgSend$dispatchValidateContextMenuItem:toExtension:fromPageWithUUID:validationHandler:
- -[SafariAppExtensionsController dispatchValidateContextMenuItem:toExtensionWithUUID:fromPageWithUUID:validationHandler:]
- GCC_except_table1770
- GCC_except_table1774
- __113-[SafariAppExtensionsController _getAPIProxyForExtensionWithUUID:shareExtensionContext:reason:completionHandler:]_block_invoke
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSDragContextMenuControllerDelegate
- ___113-[SafariAppExtensionsController _getAPIProxyForExtensionWithUUID:shareExtensionContext:reason:completionHandler:]_block_invoke
- ___113-[SafariAppExtensionsController _getAPIProxyForExtensionWithUUID:shareExtensionContext:reason:completionHandler:]_block_invoke_2
- ___120-[SafariAppExtensionsController dispatchValidateContextMenuItem:toExtensionWithUUID:fromPageWithUUID:validationHandler:]_block_invoke
- ___ZN6Safari10FileLocker25lockWithCompletionHandlerEU13block_pointerFvNS_10LockResultEE_block_invoke
- ___block_descriptor_48_ea8_32s40r_e8_v12?0i8l
- _objc_msgSend$dispatchValidateContextMenuItem:toExtensionWithUUID:fromPageWithUUID:validationHandler:
```
