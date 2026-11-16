## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit`

```diff

-560.250.3.0.0
-  __TEXT.__text: 0x2cb5d8
-  __TEXT.__objc_methlist: 0x10a54
-  __TEXT.__const: 0x3ac40
-  __TEXT.__cstring: 0x131b7
-  __TEXT.__oslogstring: 0x16215
+560.250.6.0.0
+  __TEXT.__text: 0x2cbb0c
+  __TEXT.__objc_methlist: 0x10a74
+  __TEXT.__const: 0x3ac50
+  __TEXT.__cstring: 0x131be
+  __TEXT.__oslogstring: 0x162ea
   __TEXT.__gcc_except_tab: 0x6760
   __TEXT.__dlopen_cstrs: 0x250
   __TEXT.__ustring: 0x3be
-  __TEXT.__unwind_info: 0x72e8
+  __TEXT.__unwind_info: 0x72f8
   __TEXT.__eh_frame: 0xc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x81f0
+  __DATA_CONST.__objc_selrefs: 0x8208
   __DATA_CONST.__objc_protorefs: 0xf8
   __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x368
   __DATA_CONST.__got: 0xa78
   __AUTH_CONST.__const: 0xb740
   __AUTH_CONST.__cfstring: 0x14580
-  __AUTH_CONST.__objc_const: 0x2faa8
+  __AUTH_CONST.__objc_const: 0x2fac8
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x438
   __AUTH_CONST.__objc_arrayobj: 0x90

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6343
-  Symbols:   14764
-  CStrings:  4690
+  Functions: 6347
+  Symbols:   14772
+  CStrings:  4694
 
Symbols:
+ -[AKDevice isAuthenticatedGuestMode]
+ -[AKDevice isSharedIPad]
+ -[AKDevice supportsSharedIPadPasscodeAuth]
+ -[NSMutableURLRequest(AuthKit) ak_addAuthenticatedGuestModeHeader]
+ GCC_except_table156
+ _AKApprovalFlowErrorIsEndWithoutFailure
+ _AKOSEDomainFirstPartyAppConsentRequired
+ __AKHTTPHeaderMultiUserGuestMode
+ _kAKFirstPartyAppConsentRequiredDomain
+ _objc_msgSend$ak_addAuthenticatedGuestModeHeader
+ _objc_msgSend$isAuthenticatedGuestMode
+ _objc_msgSend$isSharedIPad
+ _objc_msgSend$setHeartbeatToken:
+ _objc_msgSend$supportsSharedIPadPasscodeAuth
- -[AKDevice isMultiUserMode]
- GCC_except_table159
- GCC_except_table164
- _kAKAnalyticsEventCodeDisplayedWithInvisibleInk
- _kAKAnalyticsEventInvisibleInkRemovedFromCode
- _objc_msgSend$isMultiUserMode
CStrings:
+ "FIRST_PARTY_APP_CONSENT_REQUIRED"
+ "No area IDs found for domain %@ (%llu), falling back to age assurance region"
+ "No area IDs or age assurance region found for domain %@ (%llu)"
+ "OS_ELIGIBILITY_CONTEXT_AGE_ASSURANCE_REGION"
+ "Updating delegate heartbeat token failed: key not found in results"
+ "Updating delegate heartbeat token succeeded."
+ "X-Apple-I-MU-Guest-Mode"
- "No area IDs found for domain %@ (%llu)"
- "com.apple.authkit.codeDisplayedWithinvisibleInk"
- "com.apple.authkit.invisibleInkRemovedFromCode"
```
