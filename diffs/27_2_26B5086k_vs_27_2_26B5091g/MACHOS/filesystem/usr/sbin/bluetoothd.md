## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_ivar`
- `__DATA.__data`

```diff

-2701.3.0.0.0
-  __TEXT.__text: 0x8b283c
+2701.4.0.0.0
+  __TEXT.__text: 0x8b3a8c
   __TEXT.__auth_stubs: 0x4570
-  __TEXT.__objc_stubs: 0x16540
-  __TEXT.__init_offsets: 0x68
-  __TEXT.__objc_methlist: 0x8cec
-  __TEXT.__gcc_except_tab: 0x6b1cc
+  __TEXT.__objc_stubs: 0x165e0
+  __TEXT.__init_offsets: 0x6c
+  __TEXT.__objc_methlist: 0x8d04
+  __TEXT.__gcc_except_tab: 0x6b2dc
   __TEXT.__const: 0x90cc
-  __TEXT.__cstring: 0xc2a2b
-  __TEXT.__oslogstring: 0xc0f07
-  __TEXT.__objc_methname: 0x1bda9
-  __TEXT.__objc_classname: 0x7b9
+  __TEXT.__cstring: 0xc2bc8
+  __TEXT.__oslogstring: 0xc12ee
+  __TEXT.__objc_methname: 0x1be33
+  __TEXT.__objc_classname: 0x7cc
   __TEXT.__objc_methtype: 0x4f61
   __TEXT.__ustring: 0x2c
   __TEXT.__dlopen_cstrs: 0x70
-  __TEXT.__unwind_info: 0x2c798
-  __DATA_CONST.__const: 0x31bc0
-  __DATA_CONST.__cfstring: 0x25000
-  __DATA_CONST.__objc_classlist: 0x278
+  __TEXT.__unwind_info: 0x2c838
+  __DATA_CONST.__const: 0x31c10
+  __DATA_CONST.__cfstring: 0x25040
+  __DATA_CONST.__objc_classlist: 0x280
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_dictobj: 0x320
   __DATA_CONST.__objc_arrayobj: 0x180
   __DATA_CONST.__auth_got: 0x22d0
-  __DATA_CONST.__got: 0x988
+  __DATA_CONST.__got: 0x990
   __DATA_CONST.__auth_ptr: 0x200
-  __DATA.__objc_const: 0xee10
-  __DATA.__objc_selrefs: 0x6860
+  __DATA.__objc_const: 0xeea0
+  __DATA.__objc_selrefs: 0x6888
   __DATA.__objc_ivar: 0x10b8
-  __DATA.__objc_data: 0x18b0
+  __DATA.__objc_data: 0x1900
   __DATA.__data: 0x4c40
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x22582
-  __DATA.__common: 0x17258
+  __DATA.__bss: 0x22572
+  __DATA.__common: 0x17280
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /usr/lib/libiconv.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 36228
-  Symbols:   1419
-  CStrings:  41492
+  Functions: 36255
+  Symbols:   1420
+  CStrings:  41519
 
Symbols:
+ _OBJC_CLASS_$_LSBundleRecord
CStrings:
+ "%{public}s %p"
+ "20:16:13"
+ "AppMigrationHelper"
+ "AppMigrationHelper: %{public}@ supersedes %{public}@ — substituting for privilege check"
+ "AppMigrationHelper: LSBundleRecord lookup failed for %{public}@ (%{public}@)"
+ "AppMigrationHelper: malformed superseded entry for %{public}@"
+ "AppMigrationHelper: skipping LS lookup for %{public}@ — device not unlocked since boot"
+ "AppMigrationHelper: superseded entry \"%{public}@\" missing TEAMID.bundleID separator"
+ "BTAppMigrationMsgHandler: received migration event source=\"%{public}s\" dest=\"%{public}s\" entityType=%llu"
+ "BTAppMigrationMsgHandler: rejecting migration event — SecTaskCopySigningIdentifier failed"
+ "BTAppMigrationMsgHandler: rejecting migration event — SecTaskCreateWithAuditToken failed"
+ "BTAppMigrationMsgHandler: rejecting migration event — args=%p sourceBundleID=%p destBundleID=%p"
+ "BTAppMigrationMsgHandler: rejecting migration event — caller signing identity is \"%{public}@\", expected \"com.apple.BTAppDataMigration\""
+ "Channel sounding not supported for country code: %{public}@"
+ "OI_STATUS _ACI_HCIPPGenericCmdV2(uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t *, BT_VSC_BYTESTREAM_CB)"
+ "Sep 13 2026"
+ "bundleRecordWithBundleIdentifier:allowPlaceholder:error:"
+ "com.apple.BTAppDataMigration"
+ "com.apple.bluetooth.PurpleLocation.countryCode"
+ "com.apple.developer.superseded-application-identifiers"
+ "effectivePrivilegeBundleIDFor:"
+ "kCBCSPhyDebugData"
+ "kCBCSPhyDebugNumSteps"
+ "kCBMsgArgAppMigrationDestBundleID"
+ "kCBMsgArgAppMigrationEntityType"
+ "kCBMsgArgAppMigrationSourceBundleID"
+ "kCBMsgIdAppMigrationEventMsg"
+ "objectForKey:ofClass:"
+ "rangeOfString:"
+ "virtual BTAppMigrationMsgHandler::~BTAppMigrationMsgHandler()"
+ "virtual void BTAppMigrationMsgHandler::handleDisconnection(xpc_connection_t, bool)"
- "05:00:03"
- "OI_STATUS _ACI_HCIPPGenericCmdV2(uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t *, BT_VSC_COMPLETE_CB)"
- "Sep  5 2026"
- "countryCodes_regV5.0_sarV1.14.plist"
```
