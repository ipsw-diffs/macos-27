## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3896.300.31.0.0
-  __TEXT.__text: 0x64a38
-  __TEXT.__auth_stubs: 0xf80
+3896.300.71.1.4
+  __TEXT.__text: 0x65048
+  __TEXT.__auth_stubs: 0xf90
   __TEXT.__lazy_helpers: 0xfc
   __TEXT.__objc_stubs: 0x8c40
   __TEXT.__objc_methlist: 0x3234
   __TEXT.__const: 0x260
-  __TEXT.__gcc_except_tab: 0xc894
+  __TEXT.__gcc_except_tab: 0xc940
   __TEXT.__objc_methname: 0xb6eb
   __TEXT.__objc_classname: 0x4e5
-  __TEXT.__cstring: 0x36d3
+  __TEXT.__cstring: 0x3a6f
   __TEXT.__objc_methtype: 0x206c
-  __TEXT.__oslogstring: 0xe660
-  __TEXT.__unwind_info: 0x22b0
-  __DATA_CONST.__const: 0x13f8
-  __DATA_CONST.__cfstring: 0x1560
+  __TEXT.__oslogstring: 0xe85f
+  __TEXT.__unwind_info: 0x22d8
+  __DATA_CONST.__const: 0x1630
+  __DATA_CONST.__cfstring: 0x1780
   __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xe8

   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x7d8
+  __DATA_CONST.__auth_got: 0x7e0
   __DATA_CONST.__got: 0x618
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x43e8

   __DATA.__objc_data: 0x870
   __DATA.__lazy_load_got: 0x18
   __DATA.__data: 0xae4
-  __DATA.__bss: 0xe8
+  __DATA.__bss: 0xf8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1159
-  Symbols:   446
-  CStrings:  3025
+  Functions: 1162
+  Symbols:   447
+  CStrings:  3076
 
Symbols:
+ _sysctlbyname
CStrings:
+ "0x%08x (%@)"
+ "CS_ADHOC"
+ "CS_CHECK_EXPIRATION"
+ "CS_DATAVAULT_CONTROLLER"
+ "CS_DEBUGGED"
+ "CS_DEV_CODE"
+ "CS_ENFORCEMENT"
+ "CS_ENTITLEMENTS_VALIDATED"
+ "CS_EXEC_INHERIT_SIP"
+ "CS_EXEC_SET_ENFORCEMENT"
+ "CS_EXEC_SET_HARD"
+ "CS_EXEC_SET_KILL"
+ "CS_FORCED_LV"
+ "CS_GET_TASK_ALLOW"
+ "CS_HARD"
+ "CS_INSTALLER"
+ "CS_INVALID_ALLOWED"
+ "CS_KILL"
+ "CS_KILLED"
+ "CS_LINKER_SIGNED"
+ "CS_NO_UNTRUSTED_HELPERS"
+ "CS_NVRAM_UNRESTRICTED"
+ "CS_PLATFORM_BINARY"
+ "CS_PLATFORM_PATH"
+ "CS_REQUIRE_LV"
+ "CS_RESTRICT"
+ "CS_RUNTIME"
+ "CS_SIGNED"
+ "CS_VALID"
+ "CS_VALIDATION_CATEGORY_APP_STORE"
+ "CS_VALIDATION_CATEGORY_DEVELOPER_ID"
+ "CS_VALIDATION_CATEGORY_DEVELOPMENT"
+ "CS_VALIDATION_CATEGORY_ENTERPRISE"
+ "CS_VALIDATION_CATEGORY_INVALID"
+ "CS_VALIDATION_CATEGORY_LOCAL_SIGNING"
+ "CS_VALIDATION_CATEGORY_NONE"
+ "CS_VALIDATION_CATEGORY_OOPJIT"
+ "CS_VALIDATION_CATEGORY_PLATFORM"
+ "CS_VALIDATION_CATEGORY_ROSETTA"
+ "CS_VALIDATION_CATEGORY_TESTFLIGHT"
+ "Client %{public}@ (pid %d) validation category %{public}@, csFlags %{public}@"
+ "Code signing configuration 0x%08x relaxes trust evaluation. Not enforcing identity tiers"
+ "Failed to read code signing configuration, errno: %{darwin.errno}d. Enforcing identity tiers"
+ "Failed to read validation category for %@, error: %d. Treating client as unsigned"
+ "NDNWSession <%{public}@> Client tried to set an SZExtractor but is not a platform binary and is missing the %@ entitlement"
+ "NDSession <%{public}@> Client tried to set an SZExtractor but is not a platform binary and is missing the %@ entitlement"
+ "UNKNOWN(%u)"
+ "UNKNOWN(0x%08x)"
+ "com.apple.private.nsurlsession.custom-extractor"
+ "none"
+ "security.codesigning.config"
+ "|"
- "Failed to read validation category, error: %d. Treating client as unsigned"
```
