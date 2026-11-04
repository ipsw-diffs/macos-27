## ScreenTimeServiceUI

> `/System/Library/PrivateFrameworks/ScreenTimeServiceUI.framework/Versions/A/ScreenTimeServiceUI`

```diff

-655.1.14.1.0
-  __TEXT.__text: 0xd10
-  __TEXT.__objc_methlist: 0x28c
-  __TEXT.__const: 0x50
-  __TEXT.__cstring: 0xda
-  __TEXT.__oslogstring: 0x30
-  __TEXT.__unwind_info: 0xd0
+655.2.7.0.0
+  __TEXT.__text: 0x1820
+  __TEXT.__objc_methlist: 0x30c
+  __TEXT.__const: 0x60
+  __TEXT.__gcc_except_tab: 0x2c
+  __TEXT.__cstring: 0xf6
+  __TEXT.__oslogstring: 0x187
+  __TEXT.__unwind_info: 0x128
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x190
+  __DATA_CONST.__objc_selrefs: 0x248
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__got: 0x38
-  __AUTH_CONST.__const: 0xf0
-  __AUTH_CONST.__cfstring: 0x80
-  __AUTH_CONST.__objc_const: 0xdb0
+  __DATA_CONST.__objc_superrefs: 0x10
+  __DATA_CONST.__got: 0x78
+  __AUTH_CONST.__const: 0x180
+  __AUTH_CONST.__cfstring: 0xa0
+  __AUTH_CONST.__objc_const: 0xe40
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0x4
+  __DATA.__objc_ivar: 0xc
   __DATA.__data: 0x1e8
+  - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 34
-  Symbols:   143
-  CStrings:  8
+  Functions: 53
+  Symbols:   209
+  CStrings:  15
 
Symbols:
+ -[STBlockingRemoteViewController .cxx_destruct]
+ -[STBlockingRemoteViewController _didExitFullScreenToHideApplication]
+ -[STBlockingRemoteViewController _exitFullScreenToHideApplicationWithReplyHandler:]
+ -[STBlockingRemoteViewController _replyWhenApplicationCanHide:exitedFullScreenAtUptime:]
+ -[STBlockingRemoteViewController blockingViewControllerPrepareToHideApplicationWithReplyHandler:]
+ -[STBlockingRemoteViewController dealloc]
+ -[STBlockingRemoteViewController fullScreenExitObserver]
+ -[STBlockingRemoteViewController fullScreenExitReplyHandlers]
+ -[STBlockingRemoteViewController setFullScreenExitObserver:]
+ -[STBlockingRemoteViewController setFullScreenExitReplyHandlers:]
+ GCC_except_table20
+ _NSApp
+ _NSWindowDidExitFullScreenNotification
+ _OBJC_CLASS_$_NSMenuItem
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_STBlockingRemoteViewController._fullScreenExitObserver
+ _OBJC_IVAR_$_STBlockingRemoteViewController._fullScreenExitReplyHandlers
+ _OUTLINED_FUNCTION_0
+ __OBJC_$_INSTANCE_VARIABLES_STBlockingRemoteViewController
+ __Unwind_Resume
+ ___83-[STBlockingRemoteViewController _exitFullScreenToHideApplicationWithReplyHandler:]_block_invoke
+ ___88-[STBlockingRemoteViewController _replyWhenApplicationCanHide:exitedFullScreenAtUptime:]_block_invoke
+ ___97-[STBlockingRemoteViewController blockingViewControllerPrepareToHideApplicationWithReplyHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e24_v16?0"NSNotification"8l
+ ___block_descriptor_48_e8_32s40w_e5_v8?0l
+ ___block_descriptor_56_e8_32s40w_e5_v8?0l
+ ___copy_helper_block_e8_32s40w
+ ___destroy_helper_block_e8_32s40w
+ ___objc_personality_v0
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __dispatch_main_q
+ __os_log_error_impl
+ _dispatch_after
+ _dispatch_time
+ _objc_alloc
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_enumerationMutation
+ _objc_getProperty
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_msgSend$_didExitFullScreenToHideApplication
+ _objc_msgSend$_exitFullScreenToHideApplicationWithReplyHandler:
+ _objc_msgSend$_replyWhenApplicationCanHide:exitedFullScreenAtUptime:
+ _objc_msgSend$addObject:
+ _objc_msgSend$addObserverForName:object:queue:usingBlock:
+ _objc_msgSend$addOperationWithBlock:
+ _objc_msgSend$arrayWithObject:
+ _objc_msgSend$countByEnumeratingWithState:objects:count:
+ _objc_msgSend$fullScreenExitObserver
+ _objc_msgSend$fullScreenExitReplyHandlers
+ _objc_msgSend$initWithTitle:action:keyEquivalent:
+ _objc_msgSend$mainQueue
+ _objc_msgSend$processInfo
+ _objc_msgSend$removeObserver:
+ _objc_msgSend$setFullScreenExitObserver:
+ _objc_msgSend$setFullScreenExitReplyHandlers:
+ _objc_msgSend$styleMask
+ _objc_msgSend$systemUptime
+ _objc_msgSend$toggleFullScreen:
+ _objc_msgSend$validateUserInterfaceItem:
+ _objc_retainBlock
+ _objc_setProperty_atomic
CStrings:
+ ""
+ "Already exiting full screen to hide the application. Replying together with the earlier request"
+ "Application became hideable %.0f ms after exiting full screen"
+ "Exiting full screen to hide the application"
+ "Timed out waiting for the application to be hideable after exiting full screen"
+ "Timed out waiting for the blocking window to exit full screen"
+ "v16@?0@\"NSNotification\"8"
```
