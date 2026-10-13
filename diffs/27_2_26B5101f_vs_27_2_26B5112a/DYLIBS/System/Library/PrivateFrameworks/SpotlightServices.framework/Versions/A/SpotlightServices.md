## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/Versions/A/SpotlightServices`

```diff

-2465.1.7.0.0
-  __TEXT.__text: 0x180584
+2465.1.9.0.0
+  __TEXT.__text: 0x1809f8
   __TEXT.__delay_helper: 0xdc
-  __TEXT.__objc_methlist: 0xfc70
+  __TEXT.__objc_methlist: 0xfcb0
   __TEXT.__const: 0x2f44
-  __TEXT.__cstring: 0x3c415
-  __TEXT.__oslogstring: 0xb57b
+  __TEXT.__cstring: 0x3c425
+  __TEXT.__oslogstring: 0xb66b
   __TEXT.__gcc_except_tab: 0x52ac
   __TEXT.__ustring: 0x892
   __TEXT.__dlopen_cstrs: 0x12f

   __TEXT.__swift5_types: 0x20
   __TEXT.__swift5_capture: 0xa4
   __TEXT.__swift5_builtin: 0x14
-  __TEXT.__unwind_info: 0x4260
+  __TEXT.__unwind_info: 0x4288
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9bf8
+  __DATA_CONST.__objc_selrefs: 0x9c20
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x440
   __DATA_CONST.__objc_arraydata: 0x44e0
   __DATA_CONST.__got: 0x1cd0
   __AUTH_CONST.__const: 0x4878
-  __AUTH_CONST.__cfstring: 0x38900
+  __AUTH_CONST.__cfstring: 0x38920
   __AUTH_CONST.__objc_const: 0x1a5a0
   __AUTH_CONST.__objc_intobj: 0x48f0
   __AUTH_CONST.__objc_arrayobj: 0xbb8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7004
-  Symbols:   16118
-  CStrings:  8148
+  Functions: 7011
+  Symbols:   16128
+  CStrings:  8152
 
Symbols:
+ +[SPKQuery appScopeBundleIdentifiers]
+ +[SPKQuery isAllowedUnderAppScopeInContext:]
+ -[SPSearchQueryContext appScopeBundleIdentifier]
+ -[SPSearchQueryContext appScopeEntity]
+ -[SPSearchQueryContext isAppScopedSearch]
+ GCC_except_table24
+ GCC_except_table48
+ _objc_msgSend$appScopeBundleIdentifier
+ _objc_msgSend$appScopeBundleIdentifiers
+ _objc_msgSend$appScopeEntity
+ _objc_msgSend$isAllowedUnderAppScopeInContext:
+ _objc_msgSend$isAppScopedSearch
- GCC_except_table22
- GCC_except_table46
CStrings:
+ "(unresolved)"
+ "[qid=%lu][AppScope] %{public}@ is in a multi-producer domain but declares no appScopeBundleIdentifiers — denying under app scope %{public}@ rather than leaking."
+ "[qid=%lu][AppScope] Bundle ID: %{public}@"
+ "[qid=%lu][AppScope] Detected app-scoped search"
```
