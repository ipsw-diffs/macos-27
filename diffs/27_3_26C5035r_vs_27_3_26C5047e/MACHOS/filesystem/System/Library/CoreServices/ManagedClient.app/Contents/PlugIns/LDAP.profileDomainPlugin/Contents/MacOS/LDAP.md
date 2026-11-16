## LDAP

> `/System/Library/CoreServices/ManagedClient.app/Contents/PlugIns/LDAP.profileDomainPlugin/Contents/MacOS/LDAP`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-1847.60.6.0.0
-  __TEXT.__text: 0x638c
+1847.60.10.0.0
+  __TEXT.__text: 0x6d14
   __TEXT.__auth_stubs: 0x600
-  __TEXT.__objc_stubs: 0xaa0
+  __TEXT.__objc_stubs: 0xb40
   __TEXT.__objc_methlist: 0xa4
   __TEXT.__const: 0x74
   __TEXT.__gcc_except_tab: 0x6c
-  __TEXT.__oslogstring: 0x1073
-  __TEXT.__cstring: 0x2305
-  __TEXT.__objc_methname: 0x985
+  __TEXT.__oslogstring: 0x1169
+  __TEXT.__cstring: 0x24ab
+  __TEXT.__objc_methname: 0x9f5
   __TEXT.__objc_classname: 0x21
   __TEXT.__objc_methtype: 0xa6
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x238
   __DATA_CONST.__const: 0x1a0
-  __DATA_CONST.__cfstring: 0xc80
+  __DATA_CONST.__cfstring: 0xd00
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__auth_got: 0x310
-  __DATA_CONST.__got: 0x178
+  __DATA_CONST.__got: 0x180
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x2e8
+  __DATA.__objc_selrefs: 0x310
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x8
   __DATA.__common: 0x150

   - /System/Library/PrivateFrameworks/UserManagement.framework/Versions/A/UserManagement
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 110
-  Symbols:   153
-  CStrings:  337
+  Functions: 115
+  Symbols:   154
+  CStrings:  349
 
Symbols:
+ _ACAccountPropertyDAAccountHost
CStrings:
+ "AccountIDsNotManagedByDDM skipping account owned by DDM: %s"
+ "Cannot install LDAP account - a DDM-managed LDAP account already exists for host %@"
+ "Cannot update LDAP account %@ - it is managed by DDM"
+ "LDAPPayloadPlugin.pdp_pluginInstallPayload a DDM-managed LDAP account already exists for host: %s"
+ "LDAPPayloadPlugin.pdp_pluginInstallPayload skipping update of accounts owned by DDM: %s"
+ "MCTakeoverErrorDomain"
+ "RemoteManagement"
+ "accountsWithAccountType:"
+ "dictionaryWithObjects:forKeys:count:"
+ "isEqualToNumber:"
+ "managingOwnerIdentifier"
+ "username"
```
