## Mail

> `/System/Library/CoreServices/ManagedClient.app/Contents/PlugIns/Mail.profileDomainPlugin/Contents/MacOS/Mail`

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
-  __TEXT.__text: 0x88f8
+1847.60.10.0.0
+  __TEXT.__text: 0x9460
   __TEXT.__auth_stubs: 0x610
-  __TEXT.__objc_stubs: 0xbc0
+  __TEXT.__objc_stubs: 0xc60
   __TEXT.__objc_methlist: 0x98
-  __TEXT.__cstring: 0x2e15
+  __TEXT.__cstring: 0x2fbb
   __TEXT.__const: 0x90
-  __TEXT.__gcc_except_tab: 0x104
-  __TEXT.__oslogstring: 0x17b7
-  __TEXT.__objc_methname: 0xa65
+  __TEXT.__gcc_except_tab: 0x108
+  __TEXT.__oslogstring: 0x18ad
+  __TEXT.__objc_methname: 0xabc
   __TEXT.__objc_classname: 0x21
   __TEXT.__objc_methtype: 0x8a
-  __TEXT.__unwind_info: 0x2c8
+  __TEXT.__unwind_info: 0x2d8
   __DATA_CONST.__const: 0x290
-  __DATA_CONST.__cfstring: 0x1200
+  __DATA_CONST.__cfstring: 0x1280
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__objc_arrayobj: 0x48
   __DATA_CONST.__auth_got: 0x318
-  __DATA_CONST.__got: 0x1a0
+  __DATA_CONST.__got: 0x1a8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x330
+  __DATA.__objc_selrefs: 0x358
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x8
   __DATA.__common: 0x150

   - /System/Library/PrivateFrameworks/UserManagement.framework/Versions/A/UserManagement
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 142
-  Symbols:   159
-  CStrings:  417
+  Functions: 147
+  Symbols:   160
+  CStrings:  429
 
Symbols:
+ _ACAccountPropertyDAAccountHost
CStrings:
+ "AccountIDsNotManagedByDDM skipping account owned by DDM: %s"
+ "Cannot install mail account - a DDM-managed mail account already exists for host %@"
+ "Cannot update mail account %@ - it is managed by DDM"
+ "MCTakeoverErrorDomain"
+ "MailPayloadPlugin.pdp_pluginInstallPayload a DDM-managed Mail account already exists for host: %s"
+ "MailPayloadPlugin.pdp_pluginInstallPayload skipping update of accounts owned by DDM: %s"
+ "RemoteManagement"
+ "accountsWithAccountType:"
+ "firstObject"
+ "isEqualToNumber:"
+ "managingOwnerIdentifier"
+ "username"
```
