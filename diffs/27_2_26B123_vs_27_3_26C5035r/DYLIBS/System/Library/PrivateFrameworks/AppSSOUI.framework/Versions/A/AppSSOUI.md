## AppSSOUI

> `/System/Library/PrivateFrameworks/AppSSOUI.framework/Versions/A/AppSSOUI`

```diff

-643.40.34.0.0
-  __TEXT.__text: 0x9140
-  __TEXT.__objc_methlist: 0xb4c
+643.60.12.0.0
+  __TEXT.__text: 0x99cc
+  __TEXT.__objc_methlist: 0xb74
   __TEXT.__const: 0xb0
-  __TEXT.__oslogstring: 0x902
-  __TEXT.__cstring: 0xe09
-  __TEXT.__gcc_except_tab: 0x2e8
+  __TEXT.__oslogstring: 0xb28
+  __TEXT.__cstring: 0xdf7
+  __TEXT.__gcc_except_tab: 0x330
   __TEXT.__dlopen_cstrs: 0x1fc
-  __TEXT.__unwind_info: 0x3a8
+  __TEXT.__unwind_info: 0x3d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb28
+  __DATA_CONST.__objc_selrefs: 0xb68
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__got: 0x138
-  __AUTH_CONST.__const: 0x380
+  __AUTH_CONST.__const: 0x3b0
   __AUTH_CONST.__cfstring: 0x300
-  __AUTH_CONST.__objc_const: 0x1a78
+  __AUTH_CONST.__objc_const: 0x1ab8
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1b0
+  __AUTH_CONST.__auth_got: 0x1b8
   __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0x6c
+  __DATA.__objc_ivar: 0x74
   __DATA.__data: 0x3c0
   __DATA.__bss: 0x90
   __DATA_DIRTY.__objc_data: 0x190
   __DATA_DIRTY.__bss: 0x58
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
+  - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Security.framework/Versions/A/Security

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 184
-  Symbols:   660
-  CStrings:  139
+  Functions: 194
+  Symbols:   681
+  CStrings:  147
 
Symbols:
+ +[SOAgent _canPresentUINow]
+ -[SOAgent _attachViewControllerThenPresentWithHints:requestIdentifier:completion:]
+ -[SOAgent _presentAuthorizationViewControllerWithHints:requestIdentifier:completion:]
+ GCC_except_table47
+ GCC_except_table56
+ GCC_except_table57
+ GCC_except_table65
+ GCC_except_table66
+ GCC_except_table67
+ GCC_except_table69
+ _CGSessionCopyCurrentDictionary
+ _OBJC_IVAR_$_SOAgent._inFlightRequestIdentifier
+ _OBJC_IVAR_$_SOAgent._screenLockedBehavior
+ _OUTLINED_FUNCTION_4
+ ___82-[SOAgent _attachViewControllerThenPresentWithHints:requestIdentifier:completion:]_block_invoke
+ ___82-[SOAgent _attachViewControllerThenPresentWithHints:requestIdentifier:completion:]_block_invoke_2
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72b
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ _objc_msgSend$_attachViewControllerThenPresentWithHints:requestIdentifier:completion:
+ _objc_msgSend$_canPresentUINow
+ _objc_msgSend$_presentAuthorizationViewControllerWithHints:requestIdentifier:completion:
+ _objc_msgSend$abandonRequestWithIdentifier:
+ _objc_msgSend$attachAuthorizationViewControllerWithCompletion:
+ _objc_msgSend$boolValue
+ _objc_msgSend$errorWithCode:
+ _objc_msgSend$screenLockedBehavior
- GCC_except_table45
- GCC_except_table50
- GCC_except_table58
- GCC_except_table59
- GCC_except_table60
- GCC_except_table62
CStrings:
+ "\t4"
+ "CGSSessionScreenIsLocked"
+ "Failed to attach a view controller to the existing session: %{public}@"
+ "UI is now presentable — attaching a view controller to the existing session for requestIdentifier = %{public}@"
+ "UI is permitted but cannot be presented right now — using a non-UI session for requestIdentifier = %{public}@"
+ "UI required but screen is locked => authorization request not handled"
+ "UI required but screen is locked => canceling authorization request"
+ "not unloading %{public}@ -- %d request(s) still outstanding from other agents"
+ "screen is locked => cannot present UI"
+ "\x92"
- "No extension authorization view controller"
- "\x82"
```
