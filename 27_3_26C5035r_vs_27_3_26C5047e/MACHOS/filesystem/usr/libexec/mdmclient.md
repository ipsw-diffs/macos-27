## mdmclient

> `/usr/libexec/mdmclient`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1911.60.5.0.0
-  __TEXT.__text: 0x134578
-  __TEXT.__auth_stubs: 0x2520
-  __TEXT.__objc_stubs: 0x9de0
+1911.60.9.0.0
+  __TEXT.__text: 0x1352c0
+  __TEXT.__auth_stubs: 0x2530
+  __TEXT.__objc_stubs: 0x9e00
   __TEXT.__init_offsets: 0x28
   __TEXT.__objc_methlist: 0x2a68
-  __TEXT.__gcc_except_tab: 0x2f5e8
-  __TEXT.__cstring: 0x371ef
+  __TEXT.__gcc_except_tab: 0x2f860
+  __TEXT.__cstring: 0x3733a
   __TEXT.__const: 0x231
-  __TEXT.__objc_methname: 0x9cde
+  __TEXT.__objc_methname: 0x9cf2
   __TEXT.__objc_classname: 0x510
   __TEXT.__objc_methtype: 0x13b8
   __TEXT.__oslogstring: 0x148

   __TEXT.__swift5_typeref: 0x14
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x6df8
-  __DATA_CONST.__const: 0x3518
-  __DATA_CONST.__cfstring: 0x32f60
+  __TEXT.__unwind_info: 0x6e38
+  __DATA_CONST.__const: 0x3520
+  __DATA_CONST.__cfstring: 0x330a0
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0xd0
-  __DATA_CONST.__objc_arraydata: 0x18b0
+  __DATA_CONST.__objc_arraydata: 0x18b8
   __DATA_CONST.__objc_dictobj: 0x690
   __DATA_CONST.__objc_arrayobj: 0x798
   __DATA_CONST.__objc_intobj: 0x420
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA_CONST.__auth_got: 0x12a8
-  __DATA_CONST.__got: 0xd50
+  __DATA_CONST.__auth_got: 0x12b0
+  __DATA_CONST.__got: 0xd88
   __DATA.__objc_const: 0x4548
-  __DATA.__objc_selrefs: 0x2be8
+  __DATA.__objc_selrefs: 0x2bf0
   __DATA.__objc_ivar: 0x2f4
   __DATA.__objc_data: 0xd88
   __DATA.__data: 0xb42

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 3546
-  Symbols:   1035
-  CStrings:  8860
+  Functions: 3551
+  Symbols:   1043
+  CStrings:  8871
 
Symbols:
+ _ACAccountTypeIdentifierCalDAV
+ _ACAccountTypeIdentifierCardDAV
+ _ACAccountTypeIdentifierIMAP
+ _ACAccountTypeIdentifierLDAP
+ _ACAccountTypeIdentifierPOP
+ _ACAccountTypeIdentifierSMTP
+ _CP_ManagedAppsPostDidChangeNotification
+ _OBJC_CLASS_$_SUOSUMDMController
CStrings:
+ "-SoftwareUpdateDeviceID"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MCXTools/ConfigProfiles/CPCommon/AccountTakeover.mm"
+ "AC_CardDAV_Contacts"
+ "Account %@ is managed by a profile not installed by MDM: %@"
+ "GeneratedUID for uid: %@ is not a UUID - using it as-is"
+ "LDAPSearchAccounts_Identifier"
+ "MailAccounts_Identifier"
+ "Profile not found for managing link: %@"
+ "Profile not found for payload: %@"
+ "Refusing to build secure settings path for uid: %@ - unsafe GeneratedUID"
+ "Transferred account %@ from profile %@ (payload: %@, new owner: %@)"
+ "Unsafe GeneratedUID for uid: %@"
+ "hardwareModelString"
+ "iCalAccounts_Identifier"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MCXTools/ConfigProfiles/CPServices/Exchange/ExchangeAccountUtil.mm"
- "No Exchange payload bookmark in profile %@ matches account %@"
- "Transferred Exchange account %@ from profile %@ (payload: %@, new owner: %@)"
```
