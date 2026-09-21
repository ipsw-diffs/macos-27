## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/Versions/A/PlatformSSO`

```diff

-643.40.23.0.0
-  __TEXT.__text: 0x118c60
-  __TEXT.__objc_methlist: 0x4874
-  __TEXT.__const: 0x21b0
-  __TEXT.__gcc_except_tab: 0x208c
-  __TEXT.__cstring: 0xec24
-  __TEXT.__oslogstring: 0xadb8
-  __TEXT.__dlopen_cstrs: 0x42d
-  __TEXT.__swift5_typeref: 0x6d0
-  __TEXT.__swift5_fieldmd: 0x8fc
-  __TEXT.__constg_swiftt: 0xc18
-  __TEXT.__swift5_reflstr: 0x92a
+643.40.27.0.0
+  __TEXT.__text: 0x11e1f0
+  __TEXT.__objc_methlist: 0x4994
+  __TEXT.__const: 0x2250
+  __TEXT.__gcc_except_tab: 0x20e8
+  __TEXT.__cstring: 0xf234
+  __TEXT.__oslogstring: 0xb838
+  __TEXT.__dlopen_cstrs: 0x47b
+  __TEXT.__swift5_typeref: 0x75c
+  __TEXT.__swift5_fieldmd: 0x934
+  __TEXT.__constg_swiftt: 0xc64
+  __TEXT.__swift5_reflstr: 0x94a
   __TEXT.__swift5_builtin: 0x50
-  __TEXT.__swift5_protos: 0x20
-  __TEXT.__swift5_proto: 0x7c
-  __TEXT.__swift5_types: 0x70
+  __TEXT.__swift5_protos: 0x24
+  __TEXT.__swift5_proto: 0x80
+  __TEXT.__swift5_types: 0x74
   __TEXT.__swift_as_entry: 0x2c0
-  __TEXT.__swift_as_ret: 0x2b8
-  __TEXT.__swift_as_cont: 0x2a4
+  __TEXT.__swift_as_ret: 0x2bc
+  __TEXT.__swift_as_cont: 0x2a8
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__swift5_capture: 0x280
+  __TEXT.__swift5_capture: 0x27c
   __TEXT.__swift5_assocty: 0x18
-  __TEXT.__unwind_info: 0x4448
-  __TEXT.__eh_frame: 0x4278
+  __TEXT.__unwind_info: 0x4568
+  __TEXT.__eh_frame: 0x42b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5b8
-  __DATA_CONST.__objc_classlist: 0x178
+  __DATA_CONST.__const: 0x5d0
+  __DATA_CONST.__objc_classlist: 0x180
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x33c8
+  __DATA_CONST.__objc_selrefs: 0x34a0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0xe8
+  __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0xa0
-  __DATA_CONST.__got: 0x9c0
-  __AUTH_CONST.__const: 0x2d90
-  __AUTH_CONST.__cfstring: 0x64e0
-  __AUTH_CONST.__objc_const: 0xaa60
+  __DATA_CONST.__got: 0x9d0
+  __AUTH_CONST.__const: 0x2ea8
+  __AUTH_CONST.__cfstring: 0x6740
+  __AUTH_CONST.__objc_const: 0xac38
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xd00
-  __AUTH.__objc_data: 0x960
-  __AUTH.__data: 0xf70
-  __DATA.__objc_ivar: 0x418
-  __DATA.__data: 0x7d0
-  __DATA.__bss: 0xed8
+  __AUTH_CONST.__auth_got: 0xce0
+  __AUTH.__objc_data: 0x9b0
+  __AUTH.__data: 0xf80
+  __DATA.__objc_ivar: 0x428
+  __DATA.__data: 0x7e0
+  __DATA.__bss: 0xef8
   __DATA.__common: 0xb0
   __DATA_DIRTY.__objc_data: 0x550
   __DATA_DIRTY.__bss: 0x130

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4287
-  Symbols:   5668
-  CStrings:  2232
+  Functions: 4364
+  Symbols:   5759
+  CStrings:  2294
 
Symbols:
+ +[POSoftwareUpdateCredentialPolicy credentialsWanted]
+ +[POSoftwareUpdateCredentialPolicy harvestPassword:forUserId:]
+ -[POAgentAuthenticationProcess keychainAccess]
+ -[POAgentAuthenticationProcess repairKeybagRegistrationIfNeededWithPasswordContext:]
+ -[POAgentAuthenticationProcess setKeychainAccess:]
+ -[POAgentProcess configurationManagerForUserName:]
+ -[POAgentProcess keychainAccess]
+ -[POAgentProcess repairTokenBindingForUser:passwordContextData:configurationManager:]
+ -[POAgentProcess setKeychainAccess:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ -[POAuthPluginProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POConfigurationManager keychainAccess]
+ -[POConfigurationManager platformSSOSecureTokenNeedsResetForUser:pin:]
+ -[POConfigurationManager setKeychainAccess:]
+ -[PODirectoryServices .cxx_destruct]
+ -[PODirectoryServices init]
+ -[PODirectoryServices keychainAccess]
+ -[PODirectoryServices setKeychainAccess:]
+ -[PORegistrationManager setUserAuthPluginProcess:]
+ -[PORegistrationManager storeCredentialContext:]
+ -[PORegistrationManager updatePasswordHint]
+ -[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ -[POUnlockProcess unlockKeybagWithTokenId:publicKeyHash:]
+ GCC_except_table113
+ GCC_except_table14
+ GCC_except_table143
+ GCC_except_table149
+ GCC_except_table150
+ GCC_except_table162
+ GCC_except_table163
+ GCC_except_table170
+ GCC_except_table177
+ GCC_except_table178
+ GCC_except_table183
+ GCC_except_table190
+ GCC_except_table202
+ GCC_except_table212
+ GCC_except_table218
+ GCC_except_table233
+ GCC_except_table243
+ GCC_except_table285
+ GCC_except_table286
+ GCC_except_table61
+ GCC_except_table84
+ OBJC_IVAR_$_POAgentAuthenticationProcess._keychainAccess
+ OBJC_IVAR_$_POAgentProcess._keychainAccess
+ OBJC_IVAR_$_POConfigurationManager._keychainAccess
+ OBJC_IVAR_$_PODirectoryServices._keychainAccess
+ OSUpdateLibraryCore.frameworkLibrary
+ PO_LOG_POSoftwareUpdateCredentialPolicy
+ PO_LOG_POSoftwareUpdateCredentialPolicy.log
+ PO_LOG_POSoftwareUpdateCredentialPolicy.once
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_CLASS_$_POSoftwareUpdateCredentialPolicy
+ _OBJC_METACLASS_$_POSoftwareUpdateCredentialPolicy
+ _OUTLINED_FUNCTION_16
+ _OUTLINED_FUNCTION_17
+ _PO_LOG_POSoftwareUpdateCredentialPolicy
+ __104-[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]_block_invoke
+ __43-[PORegistrationManager updatePasswordHint]_block_invoke
+ __48-[PORegistrationManager storeCredentialContext:]_block_invoke
+ __57-[POUnlockProcess unlockKeybagWithTokenId:publicKeyHash:]_block_invoke
+ __84-[POAgentAuthenticationProcess repairKeybagRegistrationIfNeededWithPasswordContext:]_block_invoke
+ __85-[POAgentProcess repairTokenBindingForUser:passwordContextData:configurationManager:]_block_invoke
+ __91-[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]_block_invoke
+ __91-[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]_block_invoke_2
+ __OBJC_$_CLASS_METHODS_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_CLASS_PROP_LIST_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_INSTANCE_VARIABLES_PODirectoryServices
+ __OBJC_CLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ __OBJC_METACLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ ___104-[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]_block_invoke
+ ___43-[PORegistrationManager updatePasswordHint]_block_invoke
+ ___48-[PORegistrationManager storeCredentialContext:]_block_invoke
+ ___57-[POUnlockProcess unlockKeybagWithTokenId:publicKeyHash:]_block_invoke
+ ___84-[POAgentAuthenticationProcess repairKeybagRegistrationIfNeededWithPasswordContext:]_block_invoke
+ ___85-[POAgentProcess repairTokenBindingForUser:passwordContextData:configurationManager:]_block_invoke
+ ___91-[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]_block_invoke
+ ___91-[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]_block_invoke_2
+ ___OSUpdateLibraryCore_block_invoke
+ ___PO_LOG_POSoftwareUpdateCredentialPolicy_block_invoke
+ ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96s104s112bs_e47_v32?0Q8"POAuthenticationContext"16"NSData"24l
+ ___block_descriptor_56_e8_32s40s48bs_e20_v24?0Q8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48s_e14_"NSError"8?0l
+ ___block_descriptor_65_e8_32s40s48s56s_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e20_v24?0Q8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e9_B16?0^8l
+ ___copy_helper_block_e8_32s40s48s56s64b
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112b
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112s
+ ___getSUOSULoginCredentialPolicyClass_block_invoke
+ ___swift_memcpy128_8
+ _audit_stringOSUpdate
+ _getSUOSULoginCredentialPolicyClass
+ _objc_msgSend$addSecureTokenForUserName:password:tokenId:wrapPublicKeyHash:
+ _objc_msgSend$bindingProtocol
+ _objc_msgSend$changeLoginKeychainPassword:newPassword:
+ _objc_msgSend$configurationManagerForUserName:
+ _objc_msgSend$credentialsWanted
+ _objc_msgSend$currentLoginCredentialPolicy
+ _objc_msgSend$harvestPassword:forUserId:
+ _objc_msgSend$keybagBindingInfoForTokenId:uid:
+ _objc_msgSend$keybagNeedsPairingForTokenId:uid:
+ _objc_msgSend$keybagRotatingKeyPresentForUserName:pubKeyHash:
+ _objc_msgSend$keychainAccess
+ _objc_msgSend$loginKeychainForUserName:password:
+ _objc_msgSend$pairKeybagWithTokenId:pubKeyHash:pin:userPassword:uid:
+ _objc_msgSend$platformSSOSecureTokenNeedsResetForUser:pin:
+ _objc_msgSend$readSecureTokenDataForUserName:tokenId:pin:
+ _objc_msgSend$removeSecureTokenForUserName:
+ _objc_msgSend$repairKeybagRegistrationIfNeededWithPasswordContext:
+ _objc_msgSend$repairTokenBindingForUser:passwordContextData:configurationManager:
+ _objc_msgSend$resetLoginKeychainWithPassword:resetSearchList:
+ _objc_msgSend$secureTokenStatusForUserName:needed:valid:
+ _objc_msgSend$setCredential:type:error:
+ _objc_msgSend$setExternalizedLocalAuthenticationContextData:
+ _objc_msgSend$setOptionUserId:
+ _objc_msgSend$storeCredentialContext:
+ _objc_msgSend$unlockKeybagWithTokenId:publicKeyHash:
+ _objc_msgSend$updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:
+ _objc_msgSend$updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:
+ _objc_msgSend$updatePasswordHint
+ _symbolic $s11PlatformSSO36POSoftwareUpdateCredentialHarvestingP
+ _symbolic ScCy_____6result_______pSg5errort_____G So13POLoginResultV s5ErrorP s5NeverO
+ _symbolic _____ 11PlatformSSO40DefaultSoftwareUpdateCredentialHarvesterV
+ _symbolic _____6result_______pSg5errort So13POLoginResultV s5ErrorP
+ _symbolic ______p 11PlatformSSO36POSoftwareUpdateCredentialHarvestingP
+ getSUOSULoginCredentialPolicyClass.softClass
- -[POConfigurationManager platformSSOSecureTokenNeedsResetForUser:]
- -[PORegistrationManager storeCredentialAndUpdatePasswordHint]
- GCC_except_table103
- GCC_except_table109
- GCC_except_table141
- GCC_except_table147
- GCC_except_table156
- GCC_except_table157
- GCC_except_table161
- GCC_except_table165
- GCC_except_table175
- GCC_except_table176
- GCC_except_table181
- GCC_except_table182
- GCC_except_table195
- GCC_except_table205
- GCC_except_table211
- GCC_except_table226
- GCC_except_table236
- GCC_except_table269
- GCC_except_table278
- GCC_except_table41
- GCC_except_table82
- GCC_except_table88
- GCC_except_table99
- _SecKeychainChangePassword
- _SecKeychainEraseUnlockKeyWithPubKeyHash
- _SecKeychainLogin
- _SecKeychainResetLogin
- __61-[PORegistrationManager storeCredentialAndUpdatePasswordHint]_block_invoke
- __72-[POAgentProcess updateLocalAccountPassword:passwordContext:completion:]_block_invoke
- ___61-[PORegistrationManager storeCredentialAndUpdatePasswordHint]_block_invoke
- ___72-[POAgentProcess updateLocalAccountPassword:passwordContext:completion:]_block_invoke
- ___block_descriptor_121_e8_32s40s48s56s64s72s80s88s96s104bs_e47_v32?0Q8"POAuthenticationContext"16"NSData"24l
- ___block_descriptor_44_e8_32s_e14_"NSError"8?0l
- _objc_msgSend$lengthOfBytesUsingEncoding:
- _objc_msgSend$platformSSOSecureTokenNeedsResetForUser:
- _objc_msgSend$storeCredentialAndUpdatePasswordHint
CStrings:
+ "\v"
+ "%s failed to encode the credential on %@"
+ "%s failed to externalize the credential context, uid:%{public}@ on %@"
+ "%s failed to set the boot password credential, uid:%{public}@ error:%{public}@ on %@"
+ "%s failed to set the secure passphrase credential, uid:%{public}@ error:%{public}@ on %@"
+ "+[POSoftwareUpdateCredentialPolicy harvestPassword:forUserId:]"
+ "-[POAuthPluginProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]"
+ "-[POConfigurationManager platformSSOSecureTokenNeedsResetForUser:pin:]"
+ "/System/Library/PrivateFrameworks/OSUpdate.framework/Contents/MacOS/OSUpdate"
+ "AllowWebLoginPasswordSync is set but the IdP supplied no extractable password; skipping the password sync"
+ "B16@?0^@8"
+ "Binding credential context is not externalized"
+ "Binding repair is pending but no extractable credential is available; deferring to the next login that supplies one"
+ "Failed to build the token unlock blob."
+ "Failed to migrate the keybag registration to the current protocol."
+ "Failed to pair the keybag during token binding for user."
+ "Failed to restore user configuration after a deferred keybag migration."
+ "Failed to save user configuration after re-pairing the token."
+ "Failed to unlock the keybag with the token."
+ "Falling back to password-authorized local account password change"
+ "Incomplete token unlock configuration (key hash %{public}@, certificate %{public}@, unlock data %{public}@, token id %{public}@); nothing to pair"
+ "Invalid user id for keybag unlock."
+ "Keybag has no current registration for this token (POKeybagBindingProtocol %{public}ld); pairing it with the verified local account password"
+ "Keybag has no usable registration for this token; pairing before the keybag password change"
+ "Keybag migration deferred; leaving the user state as it was rather than marking a binding owed"
+ "Keybag needs pairing and the submitted credential is not the local account password"
+ "Keybag pairing failed, so the keybag password cannot be changed with the token: "
+ "Keybag registration for the current token is up to date"
+ "Keybag registration for the current token needs repair (%{public}@); pairing it with the local account password"
+ "Keybag unlocked with token"
+ "Local account password change failed for user, including the forced change"
+ "Local account password sync failed; continuing with the existing account password"
+ "Login type %{public}ld does not pair with a password; nothing to repair"
+ "Missing credential for token keybag unlock."
+ "Missing token values for keybag unlock."
+ "No configuration; nothing to repair"
+ "No extractable credential is available for binding; skipping the key request so the existing token pairing is left intact"
+ "No extractable credential; deferring the keybag repair to the next unlock or login that supplies one"
+ "No keybag repair for temporary users"
+ "No uid for the user; cannot pair the keybag."
+ "No usable old credential was supplied; using the stashed credential"
+ "Not flagging %{public}@ for binding repair: token unlock is not supported, so there is nothing to bind (%{public}s)"
+ "POSoftwareUpdateCredentialPolicy"
+ "Password sync required but no credential context is available; continuing with the existing account password"
+ "Password update fallback result: %{public}@"
+ "PlatformSSO secure token KEK resolves and cannot be test-unwrapped; leaving it alone"
+ "PlatformSSO secure token KEK resolves but cannot be unwrapped (%d); it is wrapped to a key this account no longer has, so it has to be recreated"
+ "SUOSULoginCredentialPolicy"
+ "Syncing the local account password to the IdP password"
+ "The account's own secure token does not accept this password; retrying with the forced password change"
+ "The new credential context cannot be externalized"
+ "Token binding is owed for %{public}@; using password authentication instead of token unlock"
+ "Token binding updated for the new password; clearing binding repair flag"
+ "Token re-paired after password-authorized fallback; clearing binding repair flag"
+ "Token unlock is not supported; nothing to pair"
+ "Unlocking keybag with token for uid: %{public}@"
+ "finishSuccessfulUserRegistration()"
+ "missing"
+ "no rotating key in the login configuration"
+ "nothing registered"
+ "present"
+ "softlink:o:path:/System/Library/PrivateFrameworks/OSUpdate.framework/OSUpdate"
+ "softwareUpdateHarvest: harvested=%{bool,public}d, sessionType=%{public}s, uid=%{public}u"
+ "softwareUpdateHarvest: skipped, reason=rootUid"
+ "softwareUpdateHarvest: skipped, reason=temporaryUser"
+ "the legacy v1 protocol"
+ "token binding failed after password-authorized change"
+ "token re-pair after the password-authorized fallback did not take"
+ "\xf0\xf0A"
- "\n"
- "-[POConfigurationManager platformSSOSecureTokenNeedsResetForUser:]"
- "Creating context for synced user credential"
- "IdP credential context is not externalized; cannot sync local account password"
- "Remove previous keychain binding, if it exists"
- "failed to remove previous keychain binding: %{public}d"
- "\xf0\xf01"
```
