## AOSUI

> `/System/Library/PrivateFrameworks/AOSUI.framework/Versions/A/AOSUI`

```diff

 920.3.1.0.0
-  __TEXT.__text: 0x114250
+  __TEXT.__text: 0x114204
   __TEXT.__objc_methlist: 0x10c4c
   __TEXT.__const: 0x2d8
   __TEXT.__cstring: 0x12a65

   __TEXT.__gcc_except_tab: 0x1774
   __TEXT.__ustring: 0x132
   __TEXT.__dlopen_cstrs: 0x1f4
-  __TEXT.__unwind_info: 0x4778
+  __TEXT.__unwind_info: 0x4770
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   - /usr/lib/libDiagnosticMessagesClient.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7273
+  Functions: 7270
   Symbols:   14850
   CStrings:  3311
 
Functions:
- _OUTLINED_FUNCTION_0
- _OUTLINED_FUNCTION_0
~ -[MMServiceFactory serviceWithServiceID:forAccount:].cold.1 : 92 -> 88
~ -[MMServiceFactory serviceWithServiceID:forAccount:].cold.2 : 96 -> 92
~ -[MMServiceFactory serviceWithServiceID:forAccount:].cold.3 : 64 -> 72
~ -[MMServiceFactory serviceWithServiceID:forAccount:].cold.4 : 64 -> 72
~ __105-[AOSUISignOutFlowControllerDelegate signOutFlowController:performWalrusValidationForAccount:completion:]_block_invoke.cold.1 : 76 -> 72
~ __105-[AOSUISignOutFlowControllerDelegate signOutFlowController:performWalrusValidationForAccount:completion:]_block_invoke.cold.2 : 56 -> 64
~ __95-[AOSUISignOutFlowControllerDelegate _performLastDeviceCheckForAccount:withContext:completion:]_block_invoke.cold.1 : 96 -> 92
~ __65-[iCloudFollowUpActionHandler _handleItemActivateWithCompletion:]_block_invoke.cold.1 : 52 -> 72
~ -[iCloudFollowUpActionHandler _isValidAction:].cold.1 : 84 -> 72
- -[AOSUIRecoveryContactsViewController _showTrustedContactsDetails:].cold.3
~ -[MMTermsOfServiceController showTermsOfServiceDialogForWindow:completion:].cold.1 : 68 -> 84
~ -[MMTermsOfServiceController showTermsOfServiceDialogForWindow:completion:].cold.2 : 68 -> 84
```
