## AudioServerDriverTransports_Base

> `/System/Library/PrivateFrameworks/AudioServerDriverTransports_Base.framework/Versions/A/AudioServerDriverTransports_Base`

```diff

-420.1.0.0.0
-  __TEXT.__text: 0x4678c
-  __TEXT.__objc_methlist: 0x35a4
-  __TEXT.__gcc_except_tab: 0x63e4
+420.2.0.0.0
+  __TEXT.__text: 0x47644
+  __TEXT.__objc_methlist: 0x3624
+  __TEXT.__gcc_except_tab: 0x6680
   __TEXT.__const: 0x546
-  __TEXT.__cstring: 0x192f
-  __TEXT.__oslogstring: 0x3241
-  __TEXT.__unwind_info: 0x2848
+  __TEXT.__cstring: 0x1936
+  __TEXT.__oslogstring: 0x3336
+  __TEXT.__unwind_info: 0x2888
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x1dd0
+  __DATA_CONST.__objc_selrefs: 0x1e28
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x170
   __DATA_CONST.__objc_arraydata: 0x60
-  __DATA_CONST.__got: 0x2d0
+  __DATA_CONST.__got: 0x2d8
   __AUTH_CONST.__const: 0x818
   __AUTH_CONST.__cfstring: 0x1980
-  __AUTH_CONST.__objc_const: 0x54c0
+  __AUTH_CONST.__objc_const: 0x5540
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x2a0
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x780
   __AUTH.__objc_data: 0x690
-  __DATA.__objc_ivar: 0x328
+  __DATA.__objc_ivar: 0x330
   __DATA.__data: 0x850
   __DATA.__bss: 0x40
   __DATA_DIRTY.__objc_data: 0xa50

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1928
-  Symbols:   3980
-  CStrings:  640
+  Functions: 1940
+  Symbols:   4005
+  CStrings:  646
 
Symbols:
+ -[ASDTChangeRequestManager currentQueueForObject:withName:]
+ -[ASDTChangeRequestManager deviceAdded:]
+ -[ASDTChangeRequestManager deviceRemoved:]
+ -[ASDTChangeRequestManager removedObjects]
+ -[ASDTChangeRequestManager setRemovedObjects:]
+ -[ASDTChangeRequestManager waitForBusyQueueWithName:forObject:withTimeout:]
+ -[ASDTChangeRequestQueue abandon]
+ -[ASDTChangeRequestQueue abandoned]
+ -[ASDTChangeRequestQueue executingOnCurrentThread]
+ -[ASDTChangeRequestQueue isRunning]
+ -[ASDTChangeRequestQueue setAbandoned:]
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_IVAR_$_ASDTChangeRequestManager._removedObjects
+ _OBJC_IVAR_$_ASDTChangeRequestQueue._abandoned
+ _objc_msgSend$abandon
+ _objc_msgSend$abandoned
+ _objc_msgSend$currentQueueForObject:withName:
+ _objc_msgSend$deviceAdded:
+ _objc_msgSend$deviceRemoved:
+ _objc_msgSend$executingOnCurrentThread
+ _objc_msgSend$hashTableWithOptions:
+ _objc_msgSend$removedObjects
+ _objc_msgSend$setAbandoned:
+ _objc_msgSend$setRemovedObjects:
+ _objc_msgSend$waitForBusyQueueWithName:forObject:withTimeout:
CStrings:
+ "\""
+ "%@: Device %@ removed; dropped %lu pending change requests"
+ "%@: Discarding %lu change requests for released device %@"
+ "%@: Dropping config change %u for removed device: %@"
+ "%@: Replacing stale change request queue for %@ (flags 0x%x, %lu requests)"
+ "420.2"
+ "B"
- "420.1"
```
