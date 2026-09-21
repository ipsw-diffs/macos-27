## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/Versions/A/DMCEnrollmentLibrary`

```diff

-113.40.17.0.0
-  __TEXT.__text: 0x2a6d0
-  __TEXT.__objc_methlist: 0x1b34
-  __TEXT.__const: 0xf8
-  __TEXT.__oslogstring: 0x3f11
-  __TEXT.__cstring: 0x255d
-  __TEXT.__gcc_except_tab: 0x7d0
+113.40.18.0.0
+  __TEXT.__text: 0x2adfc
+  __TEXT.__objc_methlist: 0x1b64
+  __TEXT.__const: 0x100
+  __TEXT.__oslogstring: 0x403c
+  __TEXT.__cstring: 0x264a
+  __TEXT.__gcc_except_tab: 0x7f0
   __TEXT.__dlopen_cstrs: 0xa2
-  __TEXT.__unwind_info: 0xb78
+  __TEXT.__unwind_info: 0xb98
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3d8
+  __DATA_CONST.__const: 0x3e0
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b28
+  __DATA_CONST.__objc_selrefs: 0x1b60
   __DATA_CONST.__objc_superrefs: 0x28
-  __DATA_CONST.__objc_arraydata: 0x568
+  __DATA_CONST.__objc_arraydata: 0x578
   __DATA_CONST.__got: 0x478
-  __AUTH_CONST.__const: 0x1180
-  __AUTH_CONST.__cfstring: 0x18c0
+  __AUTH_CONST.__const: 0x11a0
+  __AUTH_CONST.__cfstring: 0x1960
   __AUTH_CONST.__objc_const: 0x1c50
-  __AUTH_CONST.__objc_intobj: 0xb70
+  __AUTH_CONST.__objc_intobj: 0xb88
   __AUTH_CONST.__objc_arrayobj: 0x4f8
   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0x16c
-  __DATA.__data: 0x1e0
-  __DATA.__bss: 0x1f8
+  __DATA.__bss: 0x208
   __DATA_DIRTY.__objc_data: 0x2d0
+  __DATA_DIRTY.__data: 0x1e0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 830
-  Symbols:   2179
-  CStrings:  566
+  Functions: 838
+  Symbols:   2200
+  CStrings:  576
 
Symbols:
+ -[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]
+ -[DMCEnrollmentFlowController(Utilities) _duplicateAccountErrorForConflictingAccounts:]
+ -[DMCEnrollmentFlowController(Utilities) _requiresAppNetworkAccessConsent]
+ -[DMCEnrollmentFlowController(Utilities) _signOutFromAppBundleIDs]
+ GCC_except_table102
+ GCC_except_table106
+ GCC_except_table127
+ GCC_except_table131
+ GCC_except_table137
+ GCC_except_table142
+ GCC_except_table149
+ GCC_except_table154
+ GCC_except_table163
+ GCC_except_table180
+ GCC_except_table186
+ GCC_except_table187
+ GCC_except_table188
+ GCC_except_table203
+ GCC_except_table23
+ GCC_except_table243
+ GCC_except_table247
+ GCC_except_table257
+ GCC_except_table264
+ GCC_except_table295
+ GCC_except_table53
+ GCC_except_table77
+ GCC_except_table78
+ GCC_except_table87
+ GCC_except_table95
+ _DMCIsGreenTea
+ ___66-[DMCEnrollmentFlowController(Utilities) _signOutFromAppBundleIDs]_block_invoke
+ ___87-[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]_block_invoke
+ ___87-[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]_block_invoke_2
+ _objc_msgSend$_appNameWithBundleID:
+ _objc_msgSend$_appWithBundleIDExists:
+ _objc_msgSend$_duplicateAccountErrorForConflictingAccounts:
+ _objc_msgSend$_ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:
+ _objc_msgSend$_requiresAppNetworkAccessConsent
+ _objc_msgSend$_signOutFromAppBundleIDs
+ _objc_msgSend$dmc_conflictingAccountsWithAltDSID:error:
+ _objc_msgSend$dmc_conflictingAccountsWithUsername:error:
+ _objc_msgSend$ensureAppNetworkAccessForCapabilities:completionHandler:
+ _objc_msgSend$owningBundleID
+ _objc_msgSend$setWithObjects:
+ _signOutFromAppBundleIDs.bundleIDs
+ _signOutFromAppBundleIDs.onceToken
- GCC_except_table103
- GCC_except_table124
- GCC_except_table128
- GCC_except_table134
- GCC_except_table139
- GCC_except_table146
- GCC_except_table151
- GCC_except_table160
- GCC_except_table171
- GCC_except_table183
- GCC_except_table184
- GCC_except_table185
- GCC_except_table200
- GCC_except_table234
- GCC_except_table244
- GCC_except_table251
- GCC_except_table258
- GCC_except_table292
- GCC_except_table49
- GCC_except_table75
- GCC_except_table84
- GCC_except_table89
- GCC_except_table96
- _objc_msgSend$dmc_conflictingAccountsExistWithAltDSID:error:
- _objc_msgSend$dmc_conflictingAccountsExistWithUsername:error:
CStrings:
+ "-[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]_block_invoke_2"
+ "App network access check complete. Continuing: %d"
+ "Checking app network access for capabilities: 0x%lx"
+ "DMC_DUPLICATE_ACCOUNT_EXISTS_IN_APP_%@_%@"
+ "EnsureAppNetworkAccess"
+ "Not checking app network access. This device does not gate app network access behind user consent."
+ "Not checking app network access. This enrollment does not depend on any app reaching the network."
+ "com.apple.MobileAddressBook"
+ "com.apple.mobilecal"
+ "com.apple.mobilemail"
```
