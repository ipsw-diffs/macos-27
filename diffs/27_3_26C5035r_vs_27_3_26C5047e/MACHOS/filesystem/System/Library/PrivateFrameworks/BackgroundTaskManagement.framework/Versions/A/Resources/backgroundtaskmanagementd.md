## backgroundtaskmanagementd

> `/System/Library/PrivateFrameworks/BackgroundTaskManagement.framework/Versions/A/Resources/backgroundtaskmanagementd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-371.2.2.0.0
-  __TEXT.__text: 0x31970
-  __TEXT.__auth_stubs: 0x8a0
-  __TEXT.__objc_stubs: 0x46a0
+371.2.4.0.0
+  __TEXT.__text: 0x32610
+  __TEXT.__auth_stubs: 0x8b0
+  __TEXT.__objc_stubs: 0x4700
   __TEXT.__objc_methlist: 0x1ee4
   __TEXT.__const: 0x148
   __TEXT.__gcc_except_tab: 0x4c4
-  __TEXT.__objc_methname: 0x515b
-  __TEXT.__oslogstring: 0x3b21
+  __TEXT.__objc_methname: 0x51c0
+  __TEXT.__oslogstring: 0x3c72
   __TEXT.__cstring: 0x1db1
   __TEXT.__objc_classname: 0x24a
   __TEXT.__objc_methtype: 0x12ec
-  __TEXT.__unwind_info: 0xc80
+  __TEXT.__unwind_info: 0xc88
   __DATA_CONST.__const: 0xab0
   __DATA_CONST.__cfstring: 0x2060
   __DATA_CONST.__objc_classlist: 0x90

   __DATA_CONST.__objc_arraydata: 0x198
   __DATA_CONST.__objc_dictobj: 0xa0
   __DATA_CONST.__objc_arrayobj: 0x48
-  __DATA_CONST.__auth_got: 0x460
+  __DATA_CONST.__auth_got: 0x468
   __DATA_CONST.__got: 0x2d0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x3830
-  __DATA.__objc_selrefs: 0x1560
+  __DATA.__objc_selrefs: 0x1578
   __DATA.__objc_ivar: 0x1c0
   __DATA.__objc_data: 0x5a0
   __DATA.__data: 0x4f0

   - /usr/lib/libTLE.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 913
-  Symbols:   237
-  CStrings:  1685
+  Functions: 915
+  Symbols:   238
+  CStrings:  1692
 
Symbols:
+ _BTMItemIdentifierForAuditTokenAndType
CStrings:
+ "SFLClient.addURL: kLSSharedFileListManagedSessionLoginItems is read-only"
+ "_bundleURLForAuditToken: calling process pid=%d does not match container codesign info, returning nil"
+ "_bundleURLForAuditToken: error getting codesigning info for pid=%d: %{public}@"
+ "canAddURL:managed:"
+ "codeSignInfoForAuditToken:error:"
+ "updateGlobalDataContainer: container '%{public}@' doesn't match record '%{public}@"
+ "validateWithRequirement:basic:"
+ "validateWithRequirement:url:"
- "canAddURL:"
```
