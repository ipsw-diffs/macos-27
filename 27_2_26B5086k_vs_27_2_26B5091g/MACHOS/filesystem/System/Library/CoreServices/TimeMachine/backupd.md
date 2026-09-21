## backupd

> `/System/Library/CoreServices/TimeMachine/backupd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-2614.1.0.0.0
-  __TEXT.__text: 0x145bf4
-  __TEXT.__auth_stubs: 0x4000
-  __TEXT.__objc_stubs: 0x8960
-  __TEXT.__objc_methlist: 0x3098
-  __TEXT.__const: 0x89b0
-  __TEXT.__gcc_except_tab: 0xc8c
-  __TEXT.__cstring: 0x1222a
-  __TEXT.__objc_methname: 0xaea5
-  __TEXT.__objc_classname: 0x101c
-  __TEXT.__objc_methtype: 0x2bfb
-  __TEXT.__swift5_typeref: 0x3669
-  __TEXT.__constg_swiftt: 0x2b70
+2615.1.0.0.0
+  __TEXT.__text: 0x148be4
+  __TEXT.__auth_stubs: 0x3ff0
+  __TEXT.__objc_stubs: 0x8ae0
+  __TEXT.__objc_methlist: 0x3140
+  __TEXT.__const: 0x8a80
+  __TEXT.__gcc_except_tab: 0xc08
+  __TEXT.__cstring: 0x1261a
+  __TEXT.__objc_methname: 0xb055
+  __TEXT.__objc_classname: 0x103c
+  __TEXT.__objc_methtype: 0x2d6b
+  __TEXT.__swift5_typeref: 0x368b
+  __TEXT.__constg_swiftt: 0x2b90
   __TEXT.__swift5_reflstr: 0x2843
   __TEXT.__swift5_fieldmd: 0x2a80
-  __TEXT.__swift5_capture: 0x2668
-  __TEXT.__swift5_builtin: 0x258
+  __TEXT.__swift5_capture: 0x2724
+  __TEXT.__swift5_builtin: 0x26c
   __TEXT.__swift5_assocty: 0x968
   __TEXT.__swift5_protos: 0x50
   __TEXT.__swift5_proto: 0x740
-  __TEXT.__swift5_types: 0x3b0
-  __TEXT.__swift_as_entry: 0x340
-  __TEXT.__swift_as_ret: 0x300
-  __TEXT.__swift_as_cont: 0x4fc
+  __TEXT.__swift5_types: 0x3b4
+  __TEXT.__swift_as_entry: 0x358
+  __TEXT.__swift_as_ret: 0x310
+  __TEXT.__swift_as_cont: 0x51c
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x5b18
-  __TEXT.__eh_frame: 0xa4a8
-  __DATA_CONST.__const: 0x8948
-  __DATA_CONST.__cfstring: 0x56e0
-  __DATA_CONST.__objc_classlist: 0x278
+  __TEXT.__unwind_info: 0x57a8
+  __TEXT.__eh_frame: 0xa748
+  __DATA_CONST.__const: 0x8aa8
+  __DATA_CONST.__cfstring: 0x57a0
+  __DATA_CONST.__objc_classlist: 0x280
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x2c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x140
-  __DATA_CONST.__objc_superrefs: 0xd8
+  __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_intobj: 0x60
   __DATA_CONST.__objc_arraydata: 0xe8
   __DATA_CONST.__objc_arrayobj: 0x150
-  __DATA_CONST.__auth_got: 0x2018
-  __DATA_CONST.__got: 0xec0
+  __DATA_CONST.__auth_got: 0x2010
+  __DATA_CONST.__got: 0xed8
   __DATA_CONST.__auth_ptr: 0xa78
-  __DATA.__objc_const: 0x7938
-  __DATA.__objc_selrefs: 0x26d8
-  __DATA.__objc_ivar: 0x2bc
-  __DATA.__objc_data: 0x28d8
+  __DATA.__objc_const: 0x7a20
+  __DATA.__objc_selrefs: 0x2750
+  __DATA.__objc_ivar: 0x2c4
+  __DATA.__objc_data: 0x2928
   __DATA.__data: 0x4c38
-  __DATA.__bss: 0xa768
+  __DATA.__bss: 0xa778
   __DATA.__common: 0x128
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/Carbon.framework/Versions/A/Carbon

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5277
-  Symbols:   1719
-  CStrings:  3688
+  Functions: 5316
+  Symbols:   1721
+  CStrings:  3732
 
Symbols:
+ _$s10Foundation3URLV15fileURLWithPathACSSh_tcfC
+ _$sSo7NSErrorCs5Error10FoundationMc
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$_NSTimeZone
+ _SecAccessCreateFromOwnerAndACL
+ _SecKeychainFindGenericPassword
+ _SecKeychainItemCreateFromContent
+ _SecKeychainItemFreeContent
- _objc_exception_rethrow
- _objc_terminate
- _xpc_connection_get_pid
- _xpc_copy_entitlement_for_token
- _xpc_dictionary_get_audit_token
- _xpc_dictionary_get_remote_connection
CStrings:
+ "' is not an absolute path"
+ "' is not an acceptable disk image path"
+ "'%@' already unlocks from the System keychain; leaving the stored password alone"
+ "'%@' cannot be attached because the image is damaged: %@"
+ "': not an encrypted disk image"
+ ", underlying error: "
+ ". Failing this attempt rather than propagating content into an un-checkpointed backup. error: "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/backupd/Utility/TMSystemKeychain.m"
+ "@28@0:8^{__SecKeychain=}16I24"
+ "B32@0:8^@16^@24"
+ "B40@0:8@16Q24^@32"
+ "Could not validate a password for '%@': the disk image is busy"
+ "Deleted %lu System keychain item(s) for account '%@'"
+ "Deleted duplicate System keychain item for account '%@' with mod date %@"
+ "Failed to copy keychain item attributes, error: %d"
+ "Failed to create a keychain access control list for account '%@'"
+ "Failed to create checkpoint property list data, error: %@"
+ "Failed to delete System keychain items for account '%@', error: %d"
+ "Failed to find a System keychain password, error: %d"
+ "Failed to get keychain attribute info for item ID, error: %d"
+ "Failed to get the next System keychain item, error: %d"
+ "Failed to obtain the System keychain, error: %d"
+ "Failed to remove duplicate System keychain items for account '%@', error: %d"
+ "Failed to search the System keychain, error: %d"
+ "Failed to serialize checkpoint %@, error: %@"
+ "Failed to store a System keychain password for account '%@', service '%@', error: %d"
+ "Password validation for '"
+ "Refusing to validate a password for '"
+ "Refusing to validate a password for '%@': not an encrypted disk image"
+ "Refusing to validate a password: '"
+ "Stored a System keychain password for account '%@', service '%@'"
+ "Stored a password for '%@' but it still does not unlock from the System keychain, error: %@"
+ "TMSystemKeychain"
+ "UTC"
+ "^{__SecKeychain=}"
+ "^{__SecKeychain=}24@0:8^i16"
+ "_canAttachWithPassphrase:readPassphraseFlags:attachError:"
+ "_copyKeychainStatus:"
+ "_enumerateItemsInKeychain:forAccount:usingBlock:"
+ "_errorForStatus:"
+ "_keychain"
+ "_keychainServiceName"
+ "_ownerUID"
+ "attachFileMode:autoMount:passphrase:readPassphraseFlags:error:"
+ "backupErrorForAttachError:"
+ "deleteItemsForAccount:error:"
+ "distantPast"
+ "en_US_POSIX"
+ "getCheckpointData:error:"
+ "i40@0:8^{__SecKeychain=}16@24@?32"
+ "indexSet"
+ "initWithBytes:length:encoding:"
+ "initWithKeychain:ownerUID:"
+ "localeWithLocaleIdentifier:"
+ "passwordForAccount:error:"
+ "q32@0:8@16^@24"
+ "removeDuplicateItemsForAccount:error:"
+ "removeObjectsAtIndexes:"
+ "setLocale:"
+ "setTimeZone:"
+ "storeDiskImagePassword(_:forKeychainAccount:displayName:)"
+ "storeDiskImagePassword:forKeychainAccount:displayName:reply:"
+ "storePassword:service:forAccount:error:"
+ "timeZoneWithAbbreviation:"
+ "tm_dataSafelyReadFromURL:error:"
+ "tm_safelyWriteToURL:mode:error:"
+ "v16@?0^{__SecKeychainItem=}8"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?q@\"NSError\">32"
+ "v48@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@?<v@?@\"NSError\">40"
+ "v48@0:8@16@24@32@?40"
+ "validatePassword(_:forDiskImageAtPath:)"
+ "validatePassword:error:"
+ "validatePassword:forDiskImageAtPath:reply:"
+ "yyyyMMddHHmmss'Z'"
- "; destination is likely full. Failing this attempt rather than propagating content into an un-checkpointed backup. error: "
- "Couldn't open checkpoint file '%@' for writing - error: %d %s"
- "Deleted system keychain item with mod date %@"
- "DiskImagePath"
- "F_FULLFSYNC failed - error: %d %s"
- "Failed to create checkpoint property list data!"
- "Failed to delete system keychain item with mod date %@"
- "Failed to get attribute info for item ID, error: %d"
- "Failed to get attributes for item, error: %d"
- "Failed to get next keychain item, error: %d"
- "Failed to obtain system keychain, error: %d"
- "Failed to search keychain, error: %d"
- "Failed to update checkpoint %@, exception: %@"
- "Messaging backupd to validate keychain password for %@"
- "Refusing to validate the password for '%@': not an acceptable disk image path"
- "Refusing to validate the password for '%@': not an encrypted disk image"
- "Rejecting a message from pid %d: '%@' entitlement is required"
- "Rejecting a message without a peer connection"
- "YYYYMMDDhhmmSSZ"
- "_removeOldKeychainItems"
- "closeFile"
- "createOrFetchCheckpointFile"
- "fileDescriptor"
- "fileHandleForWritingAtPath:"
- "initWithUTF8String:"
- "truncateAtOffset:error:"
- "validateKeychainItemsError:"
- "validateKeychainPasswordForDiskImageURL:replyHandler:"
- "willSynchWithFileHandle:error:"
- "writeData:error:"
```
