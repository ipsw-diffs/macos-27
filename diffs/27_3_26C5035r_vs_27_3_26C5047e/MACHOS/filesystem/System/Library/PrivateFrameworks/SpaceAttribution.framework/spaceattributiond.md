## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
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
- `__DATA.__data`

```diff

-499.40.4.0.1
-  __TEXT.__text: 0x413f4
-  __TEXT.__auth_stubs: 0x760
-  __TEXT.__objc_stubs: 0x7320
-  __TEXT.__objc_methlist: 0x2f48
+499.60.3.0.0
+  __TEXT.__text: 0x41de8
+  __TEXT.__auth_stubs: 0x770
+  __TEXT.__objc_stubs: 0x7460
+  __TEXT.__objc_methlist: 0x2fc0
   __TEXT.__const: 0x228
   __TEXT.__gcc_except_tab: 0x14a4
-  __TEXT.__cstring: 0x3538
-  __TEXT.__oslogstring: 0x5251
+  __TEXT.__cstring: 0x3595
+  __TEXT.__oslogstring: 0x539a
   __TEXT.__objc_classname: 0x2e8
-  __TEXT.__objc_methname: 0x87e7
-  __TEXT.__objc_methtype: 0x1192
-  __TEXT.__unwind_info: 0x1478
+  __TEXT.__objc_methname: 0x89f4
+  __TEXT.__objc_methtype: 0x11a6
+  __TEXT.__unwind_info: 0x1498
   __DATA_CONST.__const: 0x1ad8
-  __DATA_CONST.__cfstring: 0x2d20
+  __DATA_CONST.__cfstring: 0x2d80
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x188
   __DATA_CONST.__objc_dictobj: 0x50
   __DATA_CONST.__objc_arrayobj: 0xa8
-  __DATA_CONST.__auth_got: 0x3c0
+  __DATA_CONST.__auth_got: 0x3c8
   __DATA_CONST.__got: 0x250
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x4520
-  __DATA.__objc_selrefs: 0x2288
-  __DATA.__objc_ivar: 0x370
+  __DATA.__objc_const: 0x45e0
+  __DATA.__objc_selrefs: 0x22d8
+  __DATA.__objc_ivar: 0x380
   __DATA.__objc_data: 0xd20
   __DATA.__data: 0x250
   __DATA.__bss: 0x210

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1503
-  Symbols:   192
-  CStrings:  2717
+  Functions: 1519
+  Symbols:   193
+  CStrings:  2749
 
Symbols:
+ _setiopolicy_np
CStrings:
+ "%s: No counters output pointer was provided"
+ "%s: No path was provided"
+ "+[SASupport getAtimeUpdateCountersForPath:info:]"
+ "A-Time"
+ "FAILED to send A-Time counters telemetry\n"
+ "FSyncUpdateCount"
+ "Failed to GET atime update counters for %s with error %d (%s)"
+ "Failed to set IOPOL_ATIME_UPDATES_OFF: %s"
+ "Initial run. Set initial lastEventId, atime counters and abort."
+ "No kFSyncUpdateCount found"
+ "No kReclaimUpdateCount found"
+ "ReclaimUpdateCount"
+ "T@\"NSMutableDictionary\",&,V_fsyncUpdateCount"
+ "T@\"NSMutableDictionary\",&,V_lastFsyncUpdateCount"
+ "T@\"NSMutableDictionary\",&,V_lastReclaimUpdateCount"
+ "T@\"NSMutableDictionary\",&,V_reclaimUpdateCount"
+ "_fsyncUpdateCount"
+ "_lastFsyncUpdateCount"
+ "_lastReclaimUpdateCount"
+ "_reclaimUpdateCount"
+ "fsyncUpdateCount"
+ "fsyncUpdateCount %@"
+ "getAtimeUpdateCountersForPath:info:"
+ "i32@0:8@16^{?=QQ}24"
+ "lastFsyncUpdateCount"
+ "lastReclaimUpdateCount"
+ "reclaimUpdateCount"
+ "reclaimUpdateCount %@"
+ "setFsyncUpdateCount:"
+ "setLastFsyncUpdateCount:"
+ "setLastReclaimUpdateCount:"
+ "setReclaimUpdateCount:"
+ "updateATimeCountersForVolPath:reset:"
- "Initial run. Set initial lastEventId and abort."
```
