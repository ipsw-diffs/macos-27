## AdID

> `/System/Library/PrivateFrameworks/AdID.framework/Versions/A/AdID`

```diff

-638.2.3.0.0
-  __TEXT.__text: 0x1a8fc
+638.3.0.0.0
+  __TEXT.__text: 0x1a92c
   __TEXT.__objc_methlist: 0xfec
   __TEXT.__const: 0x60
   __TEXT.__gcc_except_tab: 0x6d8
-  __TEXT.__cstring: 0x6ae2
+  __TEXT.__cstring: 0x6ad3
   __TEXT.__unwind_info: 0x728
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0x3a8
+  __DATA_CONST.__got: 0x3b0
   __AUTH_CONST.__const: 0xd60
   __AUTH_CONST.__cfstring: 0x4320
-  __AUTH_CONST.__objc_const: 0x2158
+  __AUTH_CONST.__objc_const: 0x2168
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x10

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 439
-  Symbols:   1425
+  Symbols:   1426
   CStrings:  580
 
Symbols:
+ _OBJC_CLASS_$_CKContainerOptions
+ _objc_msgSend$authKitAccountWithAltDSID:error:
+ _objc_msgSend$encryptedValues
+ _objc_msgSend$initWithContainerID:options:
+ _objc_msgSend$setApplicationBundleIdentifierOverride:
- _objc_msgSend$authKitAccountWithAltDSID:
- _objc_msgSend$encryptedValuesByKey
- _objc_msgSend$initWithContainerID:
- _objc_msgSend$setSourceApplicationBundleIdentifier:
Functions:
~ -[ADClientDPIDManager primaryiCloudAccountSecurityLevel] : 224 -> 260
~ -[ADClientDPIDManager containerWithIDString:] : 144 -> 188
~ -[ADClientDPIDManager secureContainer] : 168 -> 152
~ -[ADClientDPIDManager insecureContainer] : 164 -> 148
CStrings:
+ "Could not get account for altDSID %@, error: %@"
+ "Found error code as CKErrorManateeIdentityLost"
+ "Got error code as CKErrorManateeIdentityLost"
+ "We have attempted to use an encrypted container on a non HSA2 account CKUnderlyingErrorICDPRequired, please file a radar."
+ "We need to delete and re-create the zone due to CKErrorManateeIdentityLost"
+ "We need to wait and try again later because of CKUnderlyingErrorUnsyncedKeychain"
- "Could not get account for altDSID %@"
- "Found error code as CKErrorPrivateMissingManateeIdentity"
- "Got error code as CKErrorPrivateMissingManateeIdentity"
- "We have attempted to use an encrypted container on a non HSA2 account CKErrorInternaliCDPRequired, please file a radar."
- "We need to delete and re-create the zone due to CKErrorPrivateMissingManateeIdentity"
- "We need to wait and try again later because of CKErrorInternalUnsyncedKeychain"
```
