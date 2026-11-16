## mds

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/Metadata.framework/Versions/Current/Support/mds`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__dof_mds`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2465.2.7.400.0
-  __TEXT.__text: 0x169968
-  __TEXT.__auth_stubs: 0x3d20
+2465.2.13.400.0
+  __TEXT.__text: 0x16a72c
+  __TEXT.__auth_stubs: 0x3d40
   __TEXT.__objc_stubs: 0xd2c0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x8154
-  __TEXT.__const: 0x5f20
-  __TEXT.__cstring: 0x196d1
-  __TEXT.__objc_methname: 0x1174d
+  __TEXT.__const: 0x5f30
+  __TEXT.__cstring: 0x19760
+  __TEXT.__objc_methname: 0x11725
   __TEXT.__objc_classname: 0xcdf
   __TEXT.__objc_methtype: 0x5c56
-  __TEXT.__gcc_except_tab: 0x1bb4
-  __TEXT.__oslogstring: 0x13af2
+  __TEXT.__gcc_except_tab: 0x1bbc
+  __TEXT.__oslogstring: 0x13d26
   __TEXT.__ustring: 0x1f0
   __TEXT.__dof_mds: 0x58d5
-  __TEXT.__unwind_info: 0x7960
-  __DATA_CONST.__const: 0x19b48
-  __DATA_CONST.__cfstring: 0xf3e0
+  __TEXT.__unwind_info: 0x79e0
+  __DATA_CONST.__const: 0x19cf8
+  __DATA_CONST.__cfstring: 0xf400
   __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
+  __DATA_CONST.__objc_classrefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x408
   __DATA_CONST.__objc_arraydata: 0xf70
   __DATA_CONST.__objc_arrayobj: 0x1e0
   __DATA_CONST.__objc_dictobj: 0x550
   __DATA_CONST.__objc_intobj: 0x150
-  __DATA_CONST.__auth_got: 0x1ea0
-  __DATA_CONST.__got: 0xac8
+  __DATA_CONST.__auth_got: 0x1eb0
+  __DATA_CONST.__got: 0xac0
   __DATA_CONST.__auth_ptr: 0x190
   __DATA.__objc_const: 0x19580
   __DATA.__objc_selrefs: 0x3aa8

   __DATA.__objc_data: 0x2bc0
   __DATA.__data: 0x3ba0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xb998
+  __DATA.__bss: 0xb9a8
   __DATA.__common: 0x8c54
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/libfakelink.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9858
-  Symbols:   1317
-  CStrings:  9360
+  Functions: 9901
+  Symbols:   1319
+  CStrings:  9374
 
Symbols:
+ __os_log_fault_impl
+ _dispatch_assert_queue_not$V2
CStrings:
+ "%s (%s:%d) failed assertion -- importer queue stalled: %s within %llu ms"
+ "%s waits for another process on the importer queue"
+ "%s/meCard.%d.plist"
+ "%s/meCard.%d.scratch"
+ "%{public}s waits for another process on the importer queue"
+ "1 1"
+ "SetMeCard did not finish on the importer queue"
+ "code"
+ "domain"
+ "fixupDerivedAttributes"
+ "importer queue stalled: %s within %llu ms"
+ "importer queue stalled: %{public}s within %llu ms"
+ "importerQueueWatchdogFired"
+ "me card directSetMeCard calling completion with status %lld"
+ "me card for user: %u is not a property list"
+ "me card open of %s failed, errno: %d"
+ "me card rename to %s failed, errno: %d"
+ "me card setMeCard returning reply status -11: caller pid %d lacks the mecard.provider entitlement"
+ "me card setMeCard returning reply status -12: payload bytes could not be copied"
+ "me card setMeCard returning reply status -12: payload is not a property list, error domain: %@ code: %ld"
+ "me card setMeCard returning reply status -12: property list is not a dictionary"
+ "me card write of %s failed or was short, errno: %d"
- "/private/var/db/Spotlight/meCard.%d.plist"
- "/private/var/db/Spotlight/meCard.%d.scratch"
- "before posting notification for user: %u me card dictionary count: 0 content: NULL"
- "me card directSetMeCard calling completion with status -21"
- "me card setMeCard returning reply status -11"
- "me card setMeCard returning reply status -12"
- "setMaxConcurrentOperationCount:"
- "setUnderlyingQueue:"
```
