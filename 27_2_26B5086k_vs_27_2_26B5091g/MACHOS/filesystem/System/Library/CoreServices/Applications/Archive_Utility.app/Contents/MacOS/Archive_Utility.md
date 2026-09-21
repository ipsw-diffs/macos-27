## Archive Utility

> `/System/Library/CoreServices/Applications/Archive Utility.app/Contents/MacOS/Archive Utility`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-184.0.0.0.0
-  __TEXT.__text: 0x2df6c
+185.0.0.0.0
+  __TEXT.__text: 0x2e088
   __TEXT.__auth_stubs: 0x1140
-  __TEXT.__objc_stubs: 0x4520
-  __TEXT.__objc_methlist: 0x1ee0
-  __TEXT.__cstring: 0x538e
+  __TEXT.__objc_stubs: 0x4580
+  __TEXT.__objc_methlist: 0x1f10
+  __TEXT.__cstring: 0x53c1
   __TEXT.__const: 0x14c4
-  __TEXT.__gcc_except_tab: 0x2678
-  __TEXT.__objc_methname: 0x5a79
+  __TEXT.__gcc_except_tab: 0x2694
+  __TEXT.__objc_methname: 0x5b1c
   __TEXT.__objc_classname: 0x4fb
-  __TEXT.__objc_methtype: 0x11ac
+  __TEXT.__objc_methtype: 0x11cf
   __TEXT.__ustring: 0xa04
-  __TEXT.__unwind_info: 0xe70
+  __TEXT.__unwind_info: 0xe80
   __DATA_CONST.__const: 0x12b0
-  __DATA_CONST.__cfstring: 0x2f20
+  __DATA_CONST.__cfstring: 0x2f40
   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x48

   __DATA_CONST.__auth_got: 0x8b8
   __DATA_CONST.__got: 0x2b0
   __DATA_CONST.__auth_ptr: 0x10
-  __DATA.__objc_const: 0x3048
-  __DATA.__objc_selrefs: 0x1870
-  __DATA.__objc_ivar: 0x284
+  __DATA.__objc_const: 0x3078
+  __DATA.__objc_selrefs: 0x1890
+  __DATA.__objc_ivar: 0x288
   __DATA.__objc_data: 0x8c0
   __DATA.__data: 0x468
   __DATA.__common: 0x288

   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 748
+  Functions: 752
   Symbols:   361
-  CStrings:  2336
+  CStrings:  2345
 
CStrings:
+ "@32@0:8@16^B24"
+ "@44@0:8@16Q24@32B40"
+ "Ignoring %@: its folder carries no security scope, so the user did not choose it"
+ "Ignoring %@: the open request did not come from a UI agent"
+ "TB,V_urlIsUserSelected"
+ "_urlIsUserSelected"
+ "canHonorRelocationPref:"
+ "initWithKey:selection:url:userSelected:"
+ "setUrlIsUserSelected:"
+ "unvalidatedTargetFolderForPrefKey:isEDSParent:"
+ "urlIsUserSelected"
- "Leaving source in place: open request did not come from a UI agent, so %@ does not apply"
- "canRelocateCopySourceForPref:"
```
