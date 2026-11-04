## FileProviderDaemon

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/Versions/A/FileProviderDaemon`

```diff

-4838.41.1.0.0
-  __TEXT.__text: 0xaab9b4
-  __TEXT.__objc_methlist: 0x9f8c
-  __TEXT.__const: 0x2e2c0
-  __TEXT.__cstring: 0x50f25
-  __TEXT.__oslogstring: 0x21cd2
-  __TEXT.__gcc_except_tab: 0xdafc
-  __TEXT.__ustring: 0x1830
+4838.60.42.0.0
+  __TEXT.__text: 0xaac1dc
+  __TEXT.__objc_methlist: 0x9fec
+  __TEXT.__const: 0x2e2b0
+  __TEXT.__cstring: 0x50fe5
+  __TEXT.__oslogstring: 0x21df2
+  __TEXT.__gcc_except_tab: 0xdb68
+  __TEXT.__ustring: 0x17be
   __TEXT.__dlopen_cstrs: 0x114
-  __TEXT.__constg_swiftt: 0x14b48
-  __TEXT.__swift5_typeref: 0x14e2a
-  __TEXT.__swift5_builtin: 0x910
-  __TEXT.__swift5_reflstr: 0xfbbd
-  __TEXT.__swift5_fieldmd: 0xd2ac
-  __TEXT.__swift5_mpenum: 0x144
+  __TEXT.__constg_swiftt: 0x14b84
+  __TEXT.__swift5_typeref: 0x14dda
+  __TEXT.__swift5_builtin: 0x924
+  __TEXT.__swift5_reflstr: 0xfc4d
+  __TEXT.__swift5_fieldmd: 0xd310
+  __TEXT.__swift5_mpenum: 0x154
   __TEXT.__swift5_assocty: 0x29c0
-  __TEXT.__swift5_capture: 0x1ac18
+  __TEXT.__swift5_capture: 0x1ab70
   __TEXT.__swift5_proto: 0x1c70
   __TEXT.__swift5_types: 0xc68
   __TEXT.__swift5_types2: 0x8

   __TEXT.__swift_as_ret: 0x190
   __TEXT.__swift_as_cont: 0x3d8
   __TEXT.__swift5_protos: 0xbc
-  __TEXT.__unwind_info: 0x1bee8
-  __TEXT.__eh_frame: 0x2d6f8
+  __TEXT.__unwind_info: 0x1bf18
+  __TEXT.__eh_frame: 0x2d710
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x310
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x64c0
+  __DATA_CONST.__objc_selrefs: 0x64f8
   __DATA_CONST.__objc_protorefs: 0x178
   __DATA_CONST.__objc_superrefs: 0x2b8
-  __DATA_CONST.__objc_arraydata: 0x168
-  __DATA_CONST.__got: 0x19e8
-  __AUTH_CONST.__const: 0x50878
-  __AUTH_CONST.__cfstring: 0x7b40
-  __AUTH_CONST.__objc_const: 0x28898
+  __DATA_CONST.__objc_arraydata: 0x178
+  __DATA_CONST.__got: 0x19f0
+  __AUTH_CONST.__const: 0x507b0
+  __AUTH_CONST.__cfstring: 0x7c20
+  __AUTH_CONST.__objc_const: 0x289b0
   __AUTH_CONST.__objc_arrayobj: 0x138
   __AUTH_CONST.__objc_intobj: 0x1b0
-  __AUTH_CONST.__objc_dictobj: 0xf0
+  __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__auth_got: 0x30e0
   __AUTH.__objc_data: 0x1e38
   __AUTH.__data: 0x26b8
-  __DATA.__objc_ivar: 0xbf4
-  __DATA.__data: 0x8110
+  __DATA.__objc_ivar: 0xc08
+  __DATA.__data: 0x8100
   __DATA.__bss: 0x26750
   __DATA.__common: 0x20b
   __DATA_DIRTY.__objc_data: 0x3578
-  __DATA_DIRTY.__data: 0x110b0
+  __DATA_DIRTY.__data: 0x110f0
   __DATA_DIRTY.__bss: 0x101a0
   __DATA_DIRTY.__common: 0x958
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 32004
-  Symbols:   15611
-  CStrings:  8411
+  Symbols:   15633
+  CStrings:  8422
 
Symbols:
+ -[FPDDeadEndExtensionSession cancelAsyncSuspendingExtensionCreation]
+ -[FPDDeadEndExtensionSession resumeExtensionCreationWithBackingStoreIdentity:]
+ -[FPDDomain startSessionSuspended]
+ -[FPDExtensionManager clearStartupErrorForProviderDomainID:]
+ -[FPDExtensionManager reportStartupErrorForProviderDomainID:using:]
+ -[FPDExtensionSession cancelAsyncSuspendingExtensionCreation]
+ -[FPDExtensionSession initWithDomain:extension:queue:creationSuspended:]
+ -[FPDExtensionSession resumeExtensionCreationWithBackingStoreIdentity:]
+ -[FPDProviderDescriptor owningApplicationIsInstallationHeld]
+ -[FPDProviderDescriptor setOwningApplicationIsInstallationHeld:]
+ _OBJC_IVAR_$_FPDExtensionManager._installationHeldProviderUUIDs
+ _OBJC_IVAR_$_FPDExtensionManager._providerDomainsSentStartupTelemetry
+ _OBJC_IVAR_$_FPDExtensionSession._creationBackingStoreIdentity
+ _OBJC_IVAR_$_FPDExtensionSession._creationSuspendedSinceDate
+ _OBJC_IVAR_$_FPDProviderDescriptor._owningApplicationIsInstallationHeld
+ ___24-[FPDDomain finishSetup]_block_invoke
+ ___61-[FPDExtensionSession cancelAsyncSuspendingExtensionCreation]_block_invoke
+ ___71-[FPDExtensionSession resumeExtensionCreationWithBackingStoreIdentity:]_block_invoke
+ ___72-[FPDExtensionSession initWithDomain:extension:queue:creationSuspended:]_block_invoke
+ ___swift_closure_destructor.102Tm
+ ___swift_closure_destructor.116Tm
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.126Tm
+ ___swift_closure_destructor.132Tm
+ ___swift_closure_destructor.148Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.152Tm
+ ___swift_closure_destructor.1599Tm
+ ___swift_closure_destructor.161Tm
+ ___swift_closure_destructor.1634Tm
+ ___swift_closure_destructor.1685Tm
+ ___swift_closure_destructor.1688Tm
+ ___swift_closure_destructor.1744Tm
+ ___swift_closure_destructor.1767Tm
+ ___swift_closure_destructor.1774Tm
+ ___swift_closure_destructor.1775Tm
+ ___swift_closure_destructor.1790Tm
+ ___swift_closure_destructor.1874Tm
+ ___swift_closure_destructor.189Tm
+ ___swift_closure_destructor.1902Tm
+ ___swift_closure_destructor.1972Tm
+ ___swift_closure_destructor.208Tm
+ ___swift_closure_destructor.2105Tm
+ ___swift_closure_destructor.214Tm
+ ___swift_closure_destructor.228Tm
+ ___swift_closure_destructor.235Tm
+ ___swift_closure_destructor.248Tm
+ ___swift_closure_destructor.2558Tm
+ ___swift_closure_destructor.280Tm
+ ___swift_closure_destructor.285Tm
+ ___swift_closure_destructor.2866Tm
+ ___swift_closure_destructor.294Tm
+ ___swift_closure_destructor.295Tm
+ ___swift_closure_destructor.2979Tm
+ ___swift_closure_destructor.303Tm
+ ___swift_closure_destructor.3116Tm
+ ___swift_closure_destructor.3123Tm
+ ___swift_closure_destructor.3133Tm
+ ___swift_closure_destructor.3210Tm
+ ___swift_closure_destructor.321Tm
+ ___swift_closure_destructor.3241Tm
+ ___swift_closure_destructor.330Tm
+ ___swift_closure_destructor.3347Tm
+ ___swift_closure_destructor.336Tm
+ ___swift_closure_destructor.3485Tm
+ ___swift_closure_destructor.3515Tm
+ ___swift_closure_destructor.351Tm
+ ___swift_closure_destructor.356Tm
+ ___swift_closure_destructor.3591Tm
+ ___swift_closure_destructor.3601Tm
+ ___swift_closure_destructor.3683Tm
+ ___swift_closure_destructor.3689Tm
+ ___swift_closure_destructor.3698Tm
+ ___swift_closure_destructor.381Tm
+ ___swift_closure_destructor.396Tm
+ ___swift_closure_destructor.402Tm
+ ___swift_closure_destructor.4184Tm
+ ___swift_closure_destructor.418Tm
+ ___swift_closure_destructor.4228Tm
+ ___swift_closure_destructor.4234Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.4328Tm
+ ___swift_closure_destructor.432Tm
+ ___swift_closure_destructor.4353Tm
+ ___swift_closure_destructor.4566Tm
+ ___swift_closure_destructor.4573Tm
+ ___swift_closure_destructor.468Tm
+ ___swift_closure_destructor.4691Tm
+ ___swift_closure_destructor.4717Tm
+ ___swift_closure_destructor.474Tm
+ ___swift_closure_destructor.4756Tm
+ ___swift_closure_destructor.483Tm
+ ___swift_closure_destructor.4873Tm
+ ___swift_closure_destructor.4879Tm
+ ___swift_closure_destructor.490Tm
+ ___swift_closure_destructor.5282Tm
+ ___swift_closure_destructor.530Tm
+ ___swift_closure_destructor.533Tm
+ ___swift_closure_destructor.539Tm
+ ___swift_closure_destructor.5555Tm
+ ___swift_closure_destructor.5587Tm
+ ___swift_closure_destructor.561Tm
+ ___swift_closure_destructor.5890Tm
+ ___swift_closure_destructor.6101Tm
+ ___swift_closure_destructor.621Tm
+ ___swift_closure_destructor.627Tm
+ ___swift_closure_destructor.6392Tm
+ ___swift_closure_destructor.6406Tm
+ ___swift_closure_destructor.6612Tm
+ ___swift_closure_destructor.6619Tm
+ ___swift_closure_destructor.6644Tm
+ ___swift_closure_destructor.700Tm
+ ___swift_closure_destructor.727Tm
+ ___swift_closure_destructor.780Tm
+ ___swift_closure_destructor.849Tm
+ ___swift_closure_destructor.893Tm
+ ___swift_closure_destructor.96Tm
+ _extensionUnavailableError
+ _objc_msgSend$cancelAsyncSuspendingExtensionCreation
+ _objc_msgSend$clearStartupErrorForProviderDomainID:
+ _objc_msgSend$initWithDomain:extension:queue:creationSuspended:
+ _objc_msgSend$owningApplicationIsInstallationHeld
+ _objc_msgSend$reportStartupErrorForProviderDomainID:using:
+ _objc_msgSend$resumeExtensionCreationWithBackingStoreIdentity:
+ _objc_msgSend$setDomain:
+ _objc_msgSend$setOwningApplicationIsInstallationHeld:
+ _objc_msgSend$startSessionSuspended
+ _objc_msgSend$timeIntervalSinceNow
+ _symbolic Sb18requiresQuickFlush_t
+ _symbolic _____ 18FileProviderDaemon15FlushWaitReasonO
+ _symbolic ______pSgIegg_AB_____XjSg_____Iegggny_ s5ErrorP 18FileProviderDaemon25_DatabaseReadOnlyAccessor_pRi0_s_XPXg AC15FlushWaitReasonO
- -[FPDDeadEndExtensionSession cancelAsync]
- -[FPDExtensionSession cancelAsync]
- -[FPDExtensionSession initWithDomain:extension:queue:]
- GCC_except_table78
- ___34-[FPDExtensionSession cancelAsync]_block_invoke
- ___54-[FPDExtensionSession initWithDomain:extension:queue:]_block_invoke
- ___swift_closure_destructor.1028Tm
- ___swift_closure_destructor.112Tm
- ___swift_closure_destructor.120Tm
- ___swift_closure_destructor.121Tm
- ___swift_closure_destructor.1237Tm
- ___swift_closure_destructor.129Tm
- ___swift_closure_destructor.135Tm
- ___swift_closure_destructor.158Tm
- ___swift_closure_destructor.1602Tm
- ___swift_closure_destructor.1646Tm
- ___swift_closure_destructor.167Tm
- ___swift_closure_destructor.1697Tm
- ___swift_closure_destructor.1700Tm
- ___swift_closure_destructor.1747Tm
- ___swift_closure_destructor.1770Tm
- ___swift_closure_destructor.1777Tm
- ___swift_closure_destructor.1787Tm
- ___swift_closure_destructor.1793Tm
- ___swift_closure_destructor.1886Tm
- ___swift_closure_destructor.1914Tm
- ___swift_closure_destructor.192Tm
- ___swift_closure_destructor.1975Tm
- ___swift_closure_destructor.2108Tm
- ___swift_closure_destructor.217Tm
- ___swift_closure_destructor.224Tm
- ___swift_closure_destructor.231Tm
- ___swift_closure_destructor.238Tm
- ___swift_closure_destructor.251Tm
- ___swift_closure_destructor.2561Tm
- ___swift_closure_destructor.262Tm
- ___swift_closure_destructor.263Tm
- ___swift_closure_destructor.277Tm
- ___swift_closure_destructor.2869Tm
- ___swift_closure_destructor.288Tm
- ___swift_closure_destructor.2982Tm
- ___swift_closure_destructor.300Tm
- ___swift_closure_destructor.309Tm
- ___swift_closure_destructor.3119Tm
- ___swift_closure_destructor.3126Tm
- ___swift_closure_destructor.312Tm
- ___swift_closure_destructor.3139Tm
- ___swift_closure_destructor.3213Tm
- ___swift_closure_destructor.3244Tm
- ___swift_closure_destructor.324Tm
- ___swift_closure_destructor.3350Tm
- ___swift_closure_destructor.338Tm
- ___swift_closure_destructor.339Tm
- ___swift_closure_destructor.3488Tm
- ___swift_closure_destructor.3518Tm
- ___swift_closure_destructor.354Tm
- ___swift_closure_destructor.3594Tm
- ___swift_closure_destructor.3610Tm
- ___swift_closure_destructor.363Tm
- ___swift_closure_destructor.3686Tm
- ___swift_closure_destructor.3692Tm
- ___swift_closure_destructor.3701Tm
- ___swift_closure_destructor.384Tm
- ___swift_closure_destructor.399Tm
- ___swift_closure_destructor.401Tm
- ___swift_closure_destructor.408Tm
- ___swift_closure_destructor.4187Tm
- ___swift_closure_destructor.4231Tm
- ___swift_closure_destructor.4237Tm
- ___swift_closure_destructor.4331Tm
- ___swift_closure_destructor.4356Tm
- ___swift_closure_destructor.447Tm
- ___swift_closure_destructor.4572Tm
- ___swift_closure_destructor.4579Tm
- ___swift_closure_destructor.4694Tm
- ___swift_closure_destructor.471Tm
- ___swift_closure_destructor.4720Tm
- ___swift_closure_destructor.4759Tm
- ___swift_closure_destructor.477Tm
- ___swift_closure_destructor.486Tm
- ___swift_closure_destructor.4876Tm
- ___swift_closure_destructor.4882Tm
- ___swift_closure_destructor.493Tm
- ___swift_closure_destructor.513Tm
- ___swift_closure_destructor.516Tm
- ___swift_closure_destructor.522Tm
- ___swift_closure_destructor.5285Tm
- ___swift_closure_destructor.544Tm
- ___swift_closure_destructor.5558Tm
- ___swift_closure_destructor.5590Tm
- ___swift_closure_destructor.5893Tm
- ___swift_closure_destructor.6104Tm
- ___swift_closure_destructor.624Tm
- ___swift_closure_destructor.630Tm
- ___swift_closure_destructor.6395Tm
- ___swift_closure_destructor.6409Tm
- ___swift_closure_destructor.6615Tm
- ___swift_closure_destructor.6622Tm
- ___swift_closure_destructor.6647Tm
- ___swift_closure_destructor.703Tm
- ___swift_closure_destructor.730Tm
- ___swift_closure_destructor.783Tm
- ___swift_closure_destructor.852Tm
- ___swift_closure_destructor.896Tm
- ___swift_closure_destructor.99Tm
- _objc_msgSend$cancelAsync
- _objc_msgSend$initWithDomain:extension:queue:
- _symbolic ______pSgIegg_AB_____XjSgIegggn_ s5ErrorP 18FileProviderDaemon25_DatabaseReadOnlyAccessor_pRi0_s_XPXg
- _symbolic ______pSgXw So29FPDReplicationSessionProtocolP
CStrings:
+ "\r"
+ " creation suspended for %.1fs;"
+ "<none yet>"
+ "[DEBUG] Updating extensions: %@ -> %@ (held: %@ -> %@)"
+ "[DEBUG] [installation held] Initializing disconnected provider for %@"
+ "[INFO] %{public}@: resuming extension creation after %.3fs, backing store %{public}@"
+ "[WARNING] %{public}@: cancelling extension request and suspending extension creation"
+ "_owningApplicationIsInstallationHeld"
+ "could not decode the backingStoreIdentity, extension will not be available: %@"
+ "domain-unable-to-startup"
+ "extension-session"
+ "fpfsDomain"
+ "new-proxy"
+ "refreshSession()"
+ "unableToStartup"
+ "\xd1"
- "\v"
- "[ASSERT] ‼️ missing backing store identity for domain %@"
- "[DEBUG] Updating extensions: %@ -> %@"
- "[WARNING] %{public}@: cancelling extension request"
- "\xb1"
```
