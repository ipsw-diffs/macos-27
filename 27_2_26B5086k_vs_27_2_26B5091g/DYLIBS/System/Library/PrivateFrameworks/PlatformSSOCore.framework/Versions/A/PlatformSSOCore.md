## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/Versions/A/PlatformSSOCore`

```diff

-643.40.23.0.0
-  __TEXT.__text: 0xfd044
-  __TEXT.__objc_methlist: 0x7240
-  __TEXT.__const: 0x3530
-  __TEXT.__cstring: 0xf7b7
-  __TEXT.__oslogstring: 0x669c
-  __TEXT.__gcc_except_tab: 0x1164
+643.40.27.0.0
+  __TEXT.__text: 0xfe7f0
+  __TEXT.__objc_methlist: 0x7400
+  __TEXT.__const: 0x3540
+  __TEXT.__cstring: 0xf937
+  __TEXT.__oslogstring: 0x6dbc
+  __TEXT.__gcc_except_tab: 0x1144
   __TEXT.__dlopen_cstrs: 0x363
   __TEXT.__swift5_typeref: 0x694
   __TEXT.__constg_swiftt: 0xbfc

   __TEXT.__swift_as_cont: 0x118
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x47d0
+  __TEXT.__unwind_info: 0x4860
   __TEXT.__eh_frame: 0x20d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1fa8
-  __DATA_CONST.__objc_classlist: 0x570
+  __DATA_CONST.__objc_classlist: 0x580
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3768
+  __DATA_CONST.__objc_selrefs: 0x38b0
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__objc_superrefs: 0x230
+  __DATA_CONST.__objc_superrefs: 0x238
   __DATA_CONST.__objc_arraydata: 0x68
-  __DATA_CONST.__got: 0xb78
-  __AUTH_CONST.__const: 0x2e88
-  __AUTH_CONST.__cfstring: 0x8be0
-  __AUTH_CONST.__objc_const: 0x17978
+  __DATA_CONST.__got: 0xb90
+  __AUTH_CONST.__const: 0x2ec8
+  __AUTH_CONST.__cfstring: 0x8cc0
+  __AUTH_CONST.__objc_const: 0x17c50
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1088
-  __AUTH.__objc_data: 0x3438
+  __AUTH_CONST.__auth_got: 0x10c0
+  __AUTH.__objc_data: 0x34d8
   __AUTH.__data: 0x948
-  __DATA.__objc_ivar: 0x708
+  __DATA.__objc_ivar: 0x728
   __DATA.__data: 0x1538
-  __DATA.__bss: 0x1770
+  __DATA.__bss: 0x1790
   __DATA.__common: 0x89
   __DATA_DIRTY.__objc_data: 0x6e0
   __DATA_DIRTY.__bss: 0x140

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 5728
-  Symbols:   8821
-  CStrings:  2671
+  Functions: 5782
+  Symbols:   8925
+  CStrings:  2701
 
Symbols:
+ +[POKeychainAccess isRunningInTestProcess]
+ -[POKeybagBindingInfo .cxx_destruct]
+ -[POKeybagBindingInfo bindingProtocol]
+ -[POKeybagBindingInfo flags]
+ -[POKeybagBindingInfo matchesPublicKeyOfCertificate:]
+ -[POKeybagBindingInfo needsPairing]
+ -[POKeybagBindingInfo pairingQueryAvailable]
+ -[POKeybagBindingInfo registeredPublicKeyHash]
+ -[POKeybagBindingInfo registeredTokenIds]
+ -[POKeybagBindingInfo setBindingProtocol:]
+ -[POKeybagBindingInfo setFlags:]
+ -[POKeybagBindingInfo setNeedsPairing:]
+ -[POKeybagBindingInfo setPairingQueryAvailable:]
+ -[POKeybagBindingInfo setRegisteredPublicKeyHash:]
+ -[POKeybagBindingInfo setRegisteredTokenIds:]
+ -[POKeybagBindingInfo setTokenInfoStatus:]
+ -[POKeybagBindingInfo tokenInfoStatus]
+ -[POKeychainAccess addSecureTokenForUserName:password:tokenId:wrapPublicKeyHash:]
+ -[POKeychainAccess changeLoginKeychainPassword:newPassword:]
+ -[POKeychainAccess eraseUnlockKeyWithPublicKeyHash:]
+ -[POKeychainAccess loginKeychainForUserName:password:]
+ -[POKeychainAccess readSecureTokenDataForUserName:tokenId:pin:]
+ -[POKeychainAccess removeSecureTokenForUserName:]
+ -[POKeychainAccess resetLoginKeychainWithPassword:resetSearchList:]
+ -[POKeychainAccess secureTokenStatusForUserName:needed:valid:]
+ -[POKeychainHelper .cxx_destruct]
+ -[POKeychainHelper init]
+ -[POKeychainHelper keychainAccess]
+ -[POKeychainHelper setKeychainAccess:]
+ -[POTokenHelper fileVaultNeedsPairingForUid:]
+ -[POTokenHelper findInfoForTokenId:uid:]
+ -[POTokenHelper keybagBindingInfoForTokenId:uid:]
+ -[POTokenHelper keybagNeedsPairingForTokenId:uid:]
+ -[POTokenHelper keybagRotatingKeyPresentForUserName:pubKeyHash:]
+ -[POTokenHelper pairKeybagWithTokenId:pubKeyHash:pin:userPassword:uid:]
+ GCC_except_table28
+ GCC_except_table32
+ GCC_except_table42
+ OBJC_IVAR_$_POKeybagBindingInfo._bindingProtocol
+ OBJC_IVAR_$_POKeybagBindingInfo._flags
+ OBJC_IVAR_$_POKeybagBindingInfo._needsPairing
+ OBJC_IVAR_$_POKeybagBindingInfo._pairingQueryAvailable
+ OBJC_IVAR_$_POKeybagBindingInfo._registeredPublicKeyHash
+ OBJC_IVAR_$_POKeybagBindingInfo._registeredTokenIds
+ OBJC_IVAR_$_POKeybagBindingInfo._tokenInfoStatus
+ OBJC_IVAR_$_POKeychainHelper._keychainAccess
+ PO_LOG_POKeychainAccess
+ PO_LOG_POKeychainAccess.log
+ PO_LOG_POKeychainAccess.once
+ _NSClassFromString
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_POKeybagBindingInfo
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_METACLASS_$_POKeybagBindingInfo
+ _OBJC_METACLASS_$_POKeychainAccess
+ _PO_LOG_POKeychainAccess
+ _SecKeychainChangePassword
+ _SecKeychainCopyLogin
+ _SecKeychainEraseUnlockKeyWithPubKeyHash
+ _SecKeychainResetLogin
+ __60-[POKeychainAccess changeLoginKeychainPassword:newPassword:]_block_invoke
+ __71-[POTokenHelper pairKeybagWithTokenId:pubKeyHash:pin:userPassword:uid:]_block_invoke
+ __OBJC_$_CLASS_METHODS_POKeychainAccess
+ __OBJC_$_CLASS_PROP_LIST_POKeychainAccess
+ __OBJC_$_INSTANCE_METHODS_POKeybagBindingInfo
+ __OBJC_$_INSTANCE_METHODS_POKeychainAccess
+ __OBJC_$_INSTANCE_VARIABLES_POKeybagBindingInfo
+ __OBJC_$_INSTANCE_VARIABLES_POKeychainHelper
+ __OBJC_$_PROP_LIST_POKeybagBindingInfo
+ __OBJC_$_PROP_LIST_POKeychainHelper
+ __OBJC_CLASS_RO_$_POKeybagBindingInfo
+ __OBJC_CLASS_RO_$_POKeychainAccess
+ __OBJC_METACLASS_RO_$_POKeybagBindingInfo
+ __OBJC_METACLASS_RO_$_POKeychainAccess
+ ___42+[POKeychainAccess isRunningInTestProcess]_block_invoke
+ ___60-[POKeychainAccess changeLoginKeychainPassword:newPassword:]_block_invoke
+ ___71-[POTokenHelper pairKeybagWithTokenId:pubKeyHash:pin:userPassword:uid:]_block_invoke
+ ___PO_LOG_POKeychainAccess_block_invoke
+ __os_log_fault_impl
+ _objc_msgSend$environment
+ _objc_msgSend$fileVaultNeedsPairing:
+ _objc_msgSend$findInfoForTokenId:uid:
+ _objc_msgSend$getTokenInfo:tokenID:flags:pubKeyHash:
+ _objc_msgSend$isRunningInTestProcess
+ _objc_msgSend$keybagNeedsPairing:tokenID:
+ _objc_msgSend$keybagRotatingKey:
+ _objc_msgSend$keychainAccess
+ _objc_msgSend$lengthOfBytesUsingEncoding:
+ _objc_msgSend$listTokens:
+ _objc_msgSend$loginKeychainForUserName:password:
+ _objc_msgSend$needsPairing
+ _objc_msgSend$pairKeybag:loginContext:
+ _objc_msgSend$pairingQueryAvailable
+ _objc_msgSend$processInfo
+ _objc_msgSend$registeredPublicKeyHash
+ _objc_msgSend$registeredTokenIds
+ _objc_msgSend$setBindingProtocol:
+ _objc_msgSend$setFlags:
+ _objc_msgSend$setNeedsPairing:
+ _objc_msgSend$setPairingQueryAvailable:
+ _objc_msgSend$setRegisteredPublicKeyHash:
+ _objc_msgSend$setRegisteredTokenIds:
+ _objc_msgSend$setTokenInfoStatus:
+ _objc_msgSend$tokenInfoStatus
+ _objc_opt_respondsToSelector
+ isRunningInTestProcess.isTest
+ isRunningInTestProcess.onceToken
- GCC_except_table34
- GCC_except_table36
- GCC_except_table41
CStrings:
+ "%s tokenID = %{public}@ on %@"
+ "%s tokenId = %{public}@, uid = %{public}@ on %@"
+ "-[POTokenHelper findInfoForTokenId:uid:]"
+ "-[POTokenHelper keybagBindingInfoForTokenId:uid:]"
+ "-[POTokenHelper keybagRotatingKeyPresentForUserName:pubKeyHash:]"
+ "-[POTokenHelper pairKeybagWithTokenId:pubKeyHash:pin:userPassword:uid:]"
+ "00000000-0000-0000-0000-"
+ "Could not read the secure token data: %d %{public}@"
+ "CryptoTokenKit has no keybag pairing query; leaving the pairing state undetermined"
+ "Failed to copy the login keychain."
+ "Failed to pair the keybag for the user token."
+ "Keybag needs pairing for the user token: %{public}@"
+ "Keybag paired for the user token"
+ "Keybag password change failed for token %{public}@ (key hash %{public}@): %{public}d. Registered keybag tokens: %{public}@"
+ "No keybag rotating key in the login configuration for %{public}@"
+ "No login configuration for the user; treating the keybag rotating key as present"
+ "POKeychainAccess"
+ "Refusing to change the login keychain password from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Refusing to create a secure token from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Refusing to erase the token unlock key from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Refusing to remove a secure token from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Refusing to reset the login keychain from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Refusing to unlock or rekey the login keychain from a test process. Inject POKeychainAccessMock instead - running this would change the credential store of the machine running the test."
+ "Registered keybag tokens: %{public}@"
+ "Resetting the login keychain"
+ "TKLoginConfiguration"
+ "TKLoginConfiguration is unavailable; treating the keybag rotating key as present"
+ "XCTestCase"
+ "XCTestConfigurationFilePath"
+ "XCTestSessionIdentifier"
+ "isRunningInTestProcess is true"
- "-[POTokenHelper findInfoForTokenId:]"
```
