## SetupAssistantFramework

> `/System/Library/PrivateFrameworks/SetupAssistantFramework.framework/Versions/A/SetupAssistantFramework`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-7550.2.3.0.0
-  __TEXT.__text: 0xc9ac
-  __TEXT.__objc_methlist: 0x1098
+7550.2.5.0.0
+  __TEXT.__text: 0xca7c
+  __TEXT.__objc_methlist: 0x10b0
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x1990
   __TEXT.__oslogstring: 0x1ba
   __TEXT.__gcc_except_tab: 0xa4
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__unwind_info: 0x588
+  __TEXT.__unwind_info: 0x590
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa10
+  __DATA_CONST.__objc_selrefs: 0xa18
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__got: 0x198
   __AUTH_CONST.__const: 0x310
   __AUTH_CONST.__cfstring: 0x1220
-  __AUTH_CONST.__objc_const: 0x24c0
+  __AUTH_CONST.__objc_const: 0x24e8
   __AUTH_CONST.__auth_got: 0x260
   __AUTH.__objc_data: 0x3c0
   __DATA.__objc_ivar: 0x70

   - /System/Library/PrivateFrameworks/SystemAdministration.framework/Versions/A/SystemAdministration
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 368
-  Symbols:   969
+  Functions: 370
+  Symbols:   972
   CStrings:  215
 
Symbols:
+ -[MBSAConnection setSendDiagnosticsToApple:withCompletionBlock:]
+ -[MBSAConnection setSendThirdPartyDiagnostics:withCompletionBlock:]
+ ___64-[MBSAConnection setSendDiagnosticsToApple:withCompletionBlock:]_block_invoke
+ ___67-[MBSAConnection setSendThirdPartyDiagnostics:withCompletionBlock:]_block_invoke
+ _objc_msgSend$setSendDiagnosticsToApple:withCompletionBlock:
+ _objc_msgSend$setSendThirdPartyDiagnostics:withCompletionBlock:
- -[MBSAConnection setSendDiagnosticsToApple:sendThirdPartyDiagnostics:withCompletionBlock:]
- ___90-[MBSAConnection setSendDiagnosticsToApple:sendThirdPartyDiagnostics:withCompletionBlock:]_block_invoke
- _objc_msgSend$setSendDiagnosticsToApple:sendThirdPartyDiagnostics:withCompletionBlock:
CStrings:
+ "EA1666"
- "EA2005"
```
