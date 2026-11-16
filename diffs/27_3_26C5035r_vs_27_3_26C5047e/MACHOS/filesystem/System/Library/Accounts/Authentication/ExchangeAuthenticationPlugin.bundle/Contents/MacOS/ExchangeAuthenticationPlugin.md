## ExchangeAuthenticationPlugin

> `/System/Library/Accounts/Authentication/ExchangeAuthenticationPlugin.bundle/Contents/MacOS/ExchangeAuthenticationPlugin`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__data`

```diff

-846.300.31.1.1
-  __TEXT.__text: 0xf544
+846.300.41.0.0
+  __TEXT.__text: 0x1256c
   __TEXT.__auth_stubs: 0x350
-  __TEXT.__objc_stubs: 0x2460
-  __TEXT.__objc_methlist: 0x784
-  __TEXT.__const: 0x100
-  __TEXT.__cstring: 0x658
-  __TEXT.__oslogstring: 0x1a2d
-  __TEXT.__objc_classname: 0x15c
-  __TEXT.__objc_methname: 0x2aa8
-  __TEXT.__objc_methtype: 0x7f8
-  __TEXT.__gcc_except_tab: 0x224
-  __TEXT.__unwind_info: 0x4f8
-  __DATA_CONST.__const: 0x700
-  __DATA_CONST.__cfstring: 0x4a0
-  __DATA_CONST.__objc_classlist: 0x40
+  __TEXT.__objc_stubs: 0x2a60
+  __TEXT.__objc_methlist: 0x954
+  __TEXT.__const: 0x148
+  __TEXT.__cstring: 0x7b8
+  __TEXT.__oslogstring: 0x2081
+  __TEXT.__objc_classname: 0x181
+  __TEXT.__objc_methname: 0x32ec
+  __TEXT.__objc_methtype: 0x92f
+  __TEXT.__gcc_except_tab: 0x25c
+  __TEXT.__unwind_info: 0x5c8
+  __DATA_CONST.__const: 0x8a0
+  __DATA_CONST.__cfstring: 0x660
+  __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_superrefs: 0x20
+  __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_intobj: 0x60
   __DATA_CONST.__auth_got: 0x1b8
-  __DATA_CONST.__got: 0x3b8
-  __DATA.__objc_const: 0x11d0
-  __DATA.__objc_selrefs: 0xa40
-  __DATA.__objc_ivar: 0x74
-  __DATA.__objc_data: 0x280
+  __DATA_CONST.__got: 0x3d0
+  __DATA.__objc_const: 0x13b0
+  __DATA.__objc_selrefs: 0xbc0
+  __DATA.__objc_ivar: 0x90
+  __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x180
   __DATA.__bss: 0x10
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 314
-  Symbols:   207
-  CStrings:  602
+  Functions: 381
+  Symbols:   215
+  CStrings:  714
 
Symbols:
+ _OBJC_CLASS_$_ExchangeUnauthenticatedPromptContext
+ _OBJC_IVAR_$_ExchangeAuthenticationPlugin._unauthenticatedPromptInFlightTracker
+ _OBJC_METACLASS_$_ExchangeUnauthenticatedPromptContext
+ _kACRenewCredentialsShouldForceKey
+ _kExchangeOAuthRefreshFailureCount
+ _kExchangeOAuthRefreshFirstFailureTime
+ _kExchangeUnauthenticatedPromptInterval
+ _kOAuthRefreshGraceWindow
CStrings:
+ "@\"NSString\""
+ "@\"NSUUID\""
+ "@40@0:8@16q24@32"
+ "Account %{public}@ is unauthenticated and Graph capable; requesting reauthentication (action=%ld)."
+ "B32@0:8d16d24"
+ "B36@0:8@16B24^@28"
+ "B36@0:8B16@20B28B32"
+ "B36@0:8q16q24B32"
+ "B44@0:8d16q24d32B40"
+ "Could not clear the prompt date of %{public}@ after it authenticated: %{public}@"
+ "Could not mark %{public}@ unauthenticated after %{public}@: %{public}@"
+ "Could not restore the prompt date of %{public}@: %{public}@"
+ "Could not save the cleared refresh state for %{public}@: %{public}@"
+ "Could not save the refresh grace state for %{public}@: %{public}@"
+ "Couldn't renew credential and no UI is allowed; cleared the refresh token and marked the account unauthenticated without a prompt. Renewal result %{public}@"
+ "ExchangeUnauthenticatedPromptContext"
+ "Ignoring a stale refresh rejection for %{public}@: the stored refresh token is not the one the server rejected."
+ "Not clearing the refresh token for %{public}@: none is stored to compare."
+ "Not marking %{public}@ unauthenticated after %{public}@: it is not in the store."
+ "Not prompting account %{public}@: could not save the prompt date: %{private}@"
+ "Not prompting account %{public}@: it authenticated or went away since the decision."
+ "Not prompting account %{public}@: it changed during the prompt (tokenMatch=%ld)."
+ "Not prompting account %{public}@: the token clear did not save."
+ "OAuth refresh for account %{public}@ failed with HTTP %ld, but the refresh token was replaced meanwhile; not opening a grace window."
+ "OAuth refresh for account %{public}@ failed with HTTP %ld; keeping the refresh token (failure %ld of a %.0fs window)."
+ "OAuth refresh for account %{public}@ is inside its grace window (failures: %ld); not contacting the server yet."
+ "Renewal failed for account %{public}@: action=%{public}@ status=%ld verdict=%ld avoidUI=%d force=%d bypassed=%d (%{public}@) errorCodes=%{public}@ errorName=%{private}@"
+ "T@\"NSDate\",C,N,V_previousRejectionDate"
+ "T@\"NSDate\",C,N,V_promptStampDate"
+ "T@\"NSString\",C,N,V_capturedRefreshToken"
+ "T@\"NSString\",R,C,N,V_accountIdentifier"
+ "T@\"NSUUID\",R,N,V_claimToken"
+ "Tq,R,N,V_action"
+ "_accountIdentifier"
+ "_action"
+ "_capturedRefreshToken"
+ "_claimToken"
+ "_clearPromptStampOfAuthenticatedAccountForPrompt:store:"
+ "_clearRefreshGraceStateOnAccount:"
+ "_clearRejectedRefreshToken:forAccount:store:completion:"
+ "_clearRejectedRefreshToken:forAccount:store:savedCompletion:"
+ "_clearTokenForUnauthenticatedPrompt:store:"
+ "_dispatchUnauthenticatedPromptIfNeededForAccount:accountIdentifier:client:store:"
+ "_finishUnauthenticatedPrompt:"
+ "_isGraphCapabilityLocationStampedOnAccount:"
+ "_isRefreshGraceBypassedForAccount:hasRefreshToken:summary:"
+ "_markAccountUnauthenticated:store:reason:completion:"
+ "_postPromptForUnauthenticatedPrompt:account:tokenMatch:store:"
+ "_previousRejectionDate"
+ "_promptStampDate"
+ "_promptUnauthenticatedAccountWithIdentifier:accountStore:"
+ "_readRefreshGraceStateForAccount:store:firstFailureTime:failureCount:"
+ "_refreshOAuthTokenForAccount:accountStore:force:graceBypassed:completion:"
+ "_restorePromptStampForPrompt:store:"
+ "_stillUnauthenticatedAccountForPrompt:store:"
+ "_unauthenticatedActionForAccount:"
+ "_unauthenticatedPromptInFlightTracker"
+ "a rejected renewal with no UI allowed"
+ "a renewal with no refresh token and no UI allowed"
+ "accountWithIdentifier:"
+ "action"
+ "actionForFailedResponse:graceVerdict:shouldAvoidUI:bypassed:"
+ "actionForUnauthenticatedAccount:"
+ "audienceForAccount:"
+ "capturedRefreshToken"
+ "claimToken"
+ "clampedFailureCount:"
+ "clearAndMarkUnauthenticated"
+ "clearAndPrompt"
+ "consent_required"
+ "defer"
+ "errorCodesSummary"
+ "graceVerdict"
+ "gradeFailedResponse:firstFailureTime:failureCount:now:"
+ "initWithAccountIdentifier:action:claimToken:"
+ "initWithIdentifier:emailAddress:displayName:inAccountStore:managed:graphCapable:audience:"
+ "isClientErrorStatus:"
+ "isRefreshGraceBypassedForOnPrem:migrationStatus:hasRefreshToken:graphSyncEnabled:"
+ "isTerminalErrorName:"
+ "isTransientRefreshFailure:"
+ "isWindowOpenWithFirstFailureTime:now:"
+ "its mailbox access was lost"
+ "lastCredentialRenewalRejectionDate"
+ "login_required"
+ "matchOfRejectedRefreshToken:storedRefreshToken:"
+ "none"
+ "onPrem=%d migrationStatus=%@ hasRefreshToken=%d graph=%d"
+ "previousRejectionDate"
+ "prompt"
+ "promptStampDate"
+ "q16@0:8"
+ "q24@0:8@16"
+ "q24@0:8q16"
+ "q32@0:8@16@24"
+ "q40@0:8@16q24B32B36"
+ "q40@0:8{?=BBBdd}16"
+ "server_error"
+ "setCapturedRefreshToken:"
+ "setGraceVerdict:"
+ "setLastCredentialRenewalRejectionDate:"
+ "setOauthRefreshToken:"
+ "setPreviousRejectionDate:"
+ "setPromptStampDate:"
+ "shouldAttemptRefreshWithFirstFailureTime:failureCount:now:force:"
+ "shouldPostUnauthenticatedPromptForAction:tokenMatch:stillUnauthenticated:"
+ "stampEnterpriseOnAccount:ifVerifiedBy:"
+ "stringValue"
+ "stringWithFormat:"
+ "temporarily_unavailable"
+ "timeIntervalSinceReferenceDate"
+ "unauthenticated account prompt"
+ "unknown"
+ "v16@?0q8"
+ "v20@?0q8B16"
+ "v48@0:8@16@24@32@40"
+ "v48@0:8@16@24B32B36@?40"
+ "v48@0:8@16@24^d32^q40"
+ "v48@0:8@16@24q32@40"
+ "{?=qdq}48@0:8@16d24q32d40"
- "B28@0:8@16B24"
- "Could not mark %{public}@ unauthenticated after its mailbox access was lost: %{public}@"
- "_markAccountUnauthenticatedAfterMailboxAccessLost:store:"
- "_refreshOAuthTokenForAccount:accountStore:completion:"
- "initWithIdentifier:emailAddress:displayName:inAccountStore:managed:graphCapable:"
- "invalid_token"
- "shouldInvalidateForFailedRenewalResponse:shouldAvoidUI:"
```
