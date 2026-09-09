## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

-1517.0.1.401.0
-  __TEXT.__text: 0x253fb4
+1517.0.1.402.0
+  __TEXT.__text: 0x25513c
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0xede4
-  __TEXT.__const: 0xab8
-  __TEXT.__cstring: 0x3364f
-  __TEXT.__oslogstring: 0x224d3
-  __TEXT.__gcc_except_tab: 0x345d4
+  __TEXT.__objc_methlist: 0xee14
+  __TEXT.__const: 0xac8
+  __TEXT.__cstring: 0x3383b
+  __TEXT.__oslogstring: 0x2262f
+  __TEXT.__gcc_except_tab: 0x347d8
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
-  __TEXT.__unwind_info: 0xeb60
+  __TEXT.__unwind_info: 0xeba8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3ed8
+  __DATA_CONST.__const: 0x3ee0
   __DATA_CONST.__objc_classlist: 0x7a8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6e70
+  __DATA_CONST.__objc_selrefs: 0x6e80
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0xa10
   __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0xab58
-  __AUTH_CONST.__cfstring: 0x1df60
-  __AUTH_CONST.__objc_const: 0x16680
+  __AUTH_CONST.__const: 0xab88
+  __AUTH_CONST.__cfstring: 0x1e020
+  __AUTH_CONST.__objc_const: 0x16688
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x750

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 11169
-  Symbols:   19543
-  CStrings:  7933
+  Functions: 11180
+  Symbols:   19557
+  CStrings:  7948
 
Symbols:
+ -[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]
+ -[_LSDModifyClient setSystemBuildVersion:completionHandler:]
+ GCC_except_table220
+ GCC_except_table227
+ GCC_except_table236
+ GCC_except_table242
+ GCC_except_table255
+ GCC_except_table263
+ GCC_except_table282
+ GCC_except_table283
+ GCC_except_table284
+ GCC_except_table344
+ GCC_except_table345
+ GCC_except_table349
+ GCC_except_table354
+ GCC_except_table360
+ GCC_except_table370
+ GCC_except_table393
+ _LSDatabaseSetSeededSystemBuildVersion
+ _ZL7ScanURLPK7__CFURLPhj
+ __LSDatabaseSetSeededSystemBuildVersion
+ __LSServer_SetDatabaseSystemBuildVersion
+ __ZL39URLIsDescendableAfterFailedRegistrationPK7__CFURL
+ ___60-[_LSDModifyClient setSystemBuildVersion:completionHandler:]_block_invoke
+ ___62-[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]_block_invoke
+ ___62-[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]_block_invoke_2
+ ___ZL7ScanURLPK7__CFURLPhj_block_invoke
+ ___block_descriptor_48_ea8_32r_e42_v24?0"LSDBExecutionContext"8"NSError"16l
+ ___block_descriptor_84_ea8_32s40s48r56r64r_e42_v24?0"LSDBExecutionContext"8"NSError"16l
+ _kLSCanSetSystemBuildVersionEntitlement
+ _objc_msgSend$setSystemBuildVersion:completionHandler:
- GCC_except_table189
- GCC_except_table221
- GCC_except_table234
- GCC_except_table245
- GCC_except_table254
- GCC_except_table258
- GCC_except_table278
- GCC_except_table279
- GCC_except_table280
- GCC_except_table341
- GCC_except_table342
- GCC_except_table343
- GCC_except_table351
- GCC_except_table357
- GCC_except_table367
- GCC_except_table390
- ___block_descriptor_68_ea8_32s40r48r_e42_v24?0"LSDBExecutionContext"8"NSError"16l
CStrings:
+ "#LSDatabaseBuilder could not create node for %@: %@"
+ "-[_LSDModifyClient setSystemBuildVersion:completionHandler:]"
+ "BOOL _LSDatabaseSetSeededSystemBuildVersion(_LSDatabase *__unsafe_unretained, NSString *__strong, NSError *__autoreleasing *)"
+ "BOOL _LSRegisterBundleNodeForRebuildIfNecessary(LSContext *, FSNode *__strong, const LSBundleClass *, LSRegisterOptions, LSInstallInfo *__strong, Boolean *, NSError *__autoreleasing *)"
+ "BOOL _LSServer_SetDatabaseSystemBuildVersion(NSString *__strong, NSError *__autoreleasing *)"
+ "Build version %{public}s is too long to store in the database header."
+ "Overriding database system build version %{public}s with %{public}s (the OS really is %{public}s)."
+ "_LSDatabaseSetSeededSystemBuildVersion"
+ "arm64.x1"
+ "arm64e.x1"
+ "buildVersion != nil"
+ "com.apple.private.coreservices.can-set-system-build-version"
+ "inBuildVersion != nil"
+ "invalid system build version"
+ "setting database system build version to %{public}@ from pid %d"
+ "unentitled attempt to set the system build version from pid %d"
- "BOOL _LSRegisterBundleNodeForRebuildIfNecessary(LSContext *, FSNode *__strong, LSRegisterOptions, LSInstallInfo *__strong, Boolean *, NSError *__autoreleasing *)"
```
