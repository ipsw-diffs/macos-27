## audioaccessoryd

> `/System/Library/CoreServices/audioaccessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-42.4.1.0.0
-  __TEXT.__text: 0x238280
+42.6.0.0.0
+  __TEXT.__text: 0x23c8f0
   __TEXT.__auth_stubs: 0x3760
-  __TEXT.__objc_stubs: 0x1b160
+  __TEXT.__objc_stubs: 0x1b180
   __TEXT.__objc_methlist: 0xcebc
-  __TEXT.__const: 0x4f40
+  __TEXT.__const: 0x4f20
   __TEXT.__gcc_except_tab: 0x5034
-  __TEXT.__cstring: 0x4ca83
+  __TEXT.__cstring: 0x4cd93
   __TEXT.__objc_classname: 0xf83
-  __TEXT.__objc_methname: 0x274b5
+  __TEXT.__objc_methname: 0x274c5
   __TEXT.__objc_methtype: 0x3ed9
   __TEXT.__oslogstring: 0xa02a
   __TEXT.__ustring: 0x10
-  __TEXT.__swift5_typeref: 0x1ef6
-  __TEXT.__constg_swiftt: 0x2100
-  __TEXT.__swift5_reflstr: 0x1bab
-  __TEXT.__swift5_fieldmd: 0x19a8
+  __TEXT.__swift5_typeref: 0x1f1a
+  __TEXT.__constg_swiftt: 0x2128
+  __TEXT.__swift5_reflstr: 0x1bdb
+  __TEXT.__swift5_fieldmd: 0x19b4
   __TEXT.__swift5_builtin: 0xf0
   __TEXT.__swift5_assocty: 0x228
   __TEXT.__swift5_capture: 0x1f98

   __TEXT.__swift_as_cont: 0xe8
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x8938
-  __TEXT.__eh_frame: 0x2d68
+  __TEXT.__unwind_info: 0x89d8
+  __TEXT.__eh_frame: 0x2fb8
   __DATA_CONST.__const: 0xc978
   __DATA_CONST.__cfstring: 0xb140
   __DATA_CONST.__objc_classlist: 0x378

   __DATA_CONST.__auth_got: 0x1bc0
   __DATA_CONST.__got: 0xe30
   __DATA_CONST.__auth_ptr: 0x7c0
-  __DATA.__objc_const: 0x1cfb0
-  __DATA.__objc_selrefs: 0x7f30
+  __DATA.__objc_const: 0x1cfd0
+  __DATA.__objc_selrefs: 0x7f38
   __DATA.__objc_ivar: 0x150c
   __DATA.__objc_data: 0x32c0
-  __DATA.__data: 0x5310
+  __DATA.__data: 0x5370
   __DATA.__bss: 0x7640
-  __DATA.__common: 0x3a8
+  __DATA.__common: 0x3a0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10931
+  Functions: 10958
   Symbols:   1529
-  CStrings:  14470
+  CStrings:  14484
 
CStrings:
+ "CD Session activate skipped, session already active"
+ "Clearing incomingPairedDevices (%@): %@"
+ "IncomingPairedDevices"
+ "Loaded %d incomingPairedDevices from prefs: %@"
+ "No cloudMetadata (record not yet saved to cloud) -- creating new %@ record"
+ "Pruned incomingPairedDevices without a MagicSettings record or legacy blob entry: %@"
+ "Registering for STMediaStatusDomainData changes, domain valid: %s"
+ "Removed %@ from incomingPairedDevices (removed from legacyMagicPairingSettingsRecords blob)"
+ "Removed %@ from incomingPairedDevices (unpaired)"
+ "_incomingPairedDevices"
+ "bluetooth device info zone purged"
+ "cloudMetadata failed to unarchive -- creating new %@ record"
+ "incomingPairedDevices call failed because device is in beforeFirstUnlock state"
+ "incomingPairedDevices update dropped because device is in beforeFirstUnlock state"
+ "incomingPairedDevicesPrefs"
+ "local records reset"
+ "stringArrayForKey:"
- "Failed to unarchive record -- creating new %@ record"
- "Registering for STMediaStatusDomainData changes"
- "incomingPairedDevices"
```
