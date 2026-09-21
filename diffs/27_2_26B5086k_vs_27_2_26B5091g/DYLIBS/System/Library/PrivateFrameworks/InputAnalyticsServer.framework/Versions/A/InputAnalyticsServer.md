## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/Versions/A/InputAnalyticsServer`

```diff

-154.1.4.0.0
-  __TEXT.__text: 0x7fd88
-  __TEXT.__objc_methlist: 0x630c
+154.1.5.0.0
+  __TEXT.__text: 0x80cf4
+  __TEXT.__objc_methlist: 0x6374
   __TEXT.__const: 0x6d0
   __TEXT.__gcc_except_tab: 0xcd0
-  __TEXT.__cstring: 0x6162
-  __TEXT.__oslogstring: 0x7a10
+  __TEXT.__cstring: 0x6342
+  __TEXT.__oslogstring: 0x7d60
   __TEXT.__swift5_typeref: 0x1f6
   __TEXT.__constg_swiftt: 0x118
   __TEXT.__swift5_fieldmd: 0x50

   __TEXT.__swift5_capture: 0x98
   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__unwind_info: 0x1e40
+  __TEXT.__unwind_info: 0x1ea0
   __TEXT.__eh_frame: 0x3d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1488
-  __DATA_CONST.__objc_classlist: 0x3e0
+  __DATA_CONST.__const: 0x14b0
+  __DATA_CONST.__objc_classlist: 0x3e8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30f0
+  __DATA_CONST.__objc_selrefs: 0x3148
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x220
   __DATA_CONST.__objc_arraydata: 0x398
-  __DATA_CONST.__got: 0x17f8
-  __AUTH_CONST.__const: 0x1998
-  __AUTH_CONST.__cfstring: 0x6840
-  __AUTH_CONST.__objc_const: 0xa780
-  __AUTH_CONST.__objc_intobj: 0x18c0
+  __DATA_CONST.__got: 0x1808
+  __AUTH_CONST.__const: 0x19d8
+  __AUTH_CONST.__cfstring: 0x6940
+  __AUTH_CONST.__objc_const: 0xa828
+  __AUTH_CONST.__objc_intobj: 0x1938
   __AUTH_CONST.__objc_arrayobj: 0x4e0
   __AUTH_CONST.__auth_got: 0x950
-  __AUTH.__objc_data: 0xb78
+  __AUTH.__objc_data: 0xa38
   __AUTH.__data: 0x28
   __DATA.__objc_ivar: 0x748
-  __DATA.__data: 0x480
-  __DATA.__bss: 0x1f0
-  __DATA_DIRTY.__objc_data: 0x1d10
-  __DATA_DIRTY.__data: 0x250
-  __DATA_DIRTY.__bss: 0x638
+  __DATA.__data: 0x478
+  __DATA.__bss: 0x180
+  __DATA_DIRTY.__objc_data: 0x1ea0
+  __DATA_DIRTY.__data: 0x258
+  __DATA_DIRTY.__bss: 0x6c8
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
+  - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2796
-  Symbols:   875
-  CStrings:  1457
+  Functions: 2817
+  Symbols:   877
+  CStrings:  1477
 
Symbols:
+ _CBCentralManagerOptionShowPowerAlertKey
+ _OBJC_CLASS_$_CBCentralManager
CStrings:
+ "A1603"
+ "A2051"
+ "A2538"
+ "A3085"
+ "BEGIN TRANSACTION;DROP TABLE IF EXISTS %1$@;CREATE TABLE %1$@ (date TEXT NOT NULL, pencilVersion INTEGER NOT NULL, usageType INTEGER NOT NULL, appInfo TEXT NOT NULL, inUseDisplay INTEGER NOT NULL, activeMinutes INTEGER, activeSeconds INTEGER, lastActivityTimestamp INTEGER, PRIMARY KEY (date, pencilVersion, usageType, appInfo, inUseDisplay));COMMIT;"
+ "Cannot migrate the pencil usage table: no database."
+ "Column lookup for the pencil usage table migration returned no row: %{private}s"
+ "Could not determine the pencil usage table's on-disk version. Leaving the table alone."
+ "Failed to bind the column name for the pencil usage table migration: %{private}s"
+ "Failed to get pencil version from CoreBluetooth. Falling back to the self.pencilVersion (last known pencil version)."
+ "Failed to migrate the pencil usage table to v2 with error %{private}s"
+ "Failed to prepare the column lookup for the pencil usage table migration: %{private}s"
+ "Migrated the pencil usage table to v2 (dropped the old table, added the inUseDisplay column)."
+ "No Apple Pencil among the %lu paired bluetooth device(s)."
+ "No migration defined to take the pencil usage table to version %ld."
+ "ROLLBACK;"
+ "SELECT COUNT(*) FROM pragma_table_info('%@') WHERE name = ?"
+ "inUseDisplay"
+ "pairedPencilVersion failed to get a pairing agent."
+ "pairingState"
```
