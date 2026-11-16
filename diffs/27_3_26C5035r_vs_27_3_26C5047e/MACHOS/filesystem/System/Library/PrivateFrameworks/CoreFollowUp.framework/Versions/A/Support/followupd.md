## followupd

> `/System/Library/PrivateFrameworks/CoreFollowUp.framework/Versions/A/Support/followupd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2027.2.2.0.0
-  __TEXT.__text: 0xe5b0
+2027.2.4.0.0
+  __TEXT.__text: 0xe968
   __TEXT.__auth_stubs: 0x6b0
-  __TEXT.__objc_stubs: 0x29e0
-  __TEXT.__objc_methlist: 0xb2c
+  __TEXT.__objc_stubs: 0x2b00
+  __TEXT.__objc_methlist: 0xb4c
   __TEXT.__const: 0x108
   __TEXT.__gcc_except_tab: 0x200
-  __TEXT.__cstring: 0x1dcb
-  __TEXT.__oslogstring: 0xe41
+  __TEXT.__cstring: 0x1e01
+  __TEXT.__oslogstring: 0xe64
   __TEXT.__objc_classname: 0x13f
-  __TEXT.__objc_methname: 0x2691
+  __TEXT.__objc_methname: 0x27aa
   __TEXT.__objc_methtype: 0x79e
-  __TEXT.__unwind_info: 0x570
-  __DATA_CONST.__const: 0x840
-  __DATA_CONST.__cfstring: 0xc20
+  __TEXT.__unwind_info: 0x580
+  __DATA_CONST.__const: 0x8c0
+  __DATA_CONST.__cfstring: 0xc80
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__auth_got: 0x368
-  __DATA_CONST.__got: 0x250
+  __DATA_CONST.__got: 0x270
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x14d8
-  __DATA.__objc_selrefs: 0xc28
-  __DATA.__objc_ivar: 0x50
+  __DATA.__objc_const: 0x14f8
+  __DATA.__objc_selrefs: 0xc70
+  __DATA.__objc_ivar: 0x54
   __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x2a8
   __DATA.__crash_info: 0x148

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 311
-  Symbols:   189
-  CStrings:  748
+  Functions: 315
+  Symbols:   193
+  CStrings:  764
 
Symbols:
+ _FLTelemetrySnapshotTriggerDaily
+ _XPC_ACTIVITY_GRACE_PERIOD
+ _XPC_ACTIVITY_INTERVAL_4_HOURS
+ _XPC_ACTIVITY_PRIORITY_MAINTENANCE
CStrings:
+ "/"
+ "@\"NSArray\"8@?0"
+ "Capturing daily telemetry snapshot"
+ "Users"
+ "_processName"
+ "_registerAnalyticsSnapshotActivity"
+ "captureTelemetrySnapshotWithTrigger:"
+ "com.apple.followup.analytics"
+ "fl_pathRedactingHomeFolder:"
+ "objectAtIndexedSubscript:"
+ "pathComponents"
+ "pathWithComponents:"
+ "processItemPost:isNew:process:"
+ "processNotificationDelivery:reason:"
+ "processSnapshotWithItems:trigger:"
+ "sharedProcessor"
+ "stringByAppendingPathComponent:"
+ "subarrayWithRange:"
+ "~"
- "_telemetryProcessor"
- "initWithController:"
- "processItemAddition:"
```
