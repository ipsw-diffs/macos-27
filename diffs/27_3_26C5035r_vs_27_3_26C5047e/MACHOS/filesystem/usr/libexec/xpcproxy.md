## xpcproxy

> `/usr/libexec/xpcproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-3298.60.14.0.0
-  __TEXT.__text: 0xb2fc
-  __TEXT.__auth_stubs: 0xc80
-  __TEXT.__lazy_helpers: 0x1a4
+3298.60.20.0.0
+  __TEXT.__text: 0xb3a4
+  __TEXT.__auth_stubs: 0xc90
+  __TEXT.__lazy_helpers: 0x1f8
   __TEXT.__const: 0x1c0
   __TEXT.__xpcproxy: 0x1
   __TEXT.__oslogstring: 0x1977
-  __TEXT.__cstring: 0x1c93
+  __TEXT.__cstring: 0x1ceb
   __TEXT.__dof_launchd: 0x2e5
   __TEXT.__unwind_info: 0x220
   __DATA_CONST.__const: 0x260
-  __DATA_CONST.__auth_got: 0x640
+  __DATA_CONST.__auth_got: 0x648
   __DATA_CONST.__got: 0xa0
-  __DATA.__lazy_load_got: 0x28
+  __DATA.__lazy_load_got: 0x30
   __DATA.__os_assumes_log: 0x8
   __DATA.__data: 0x28
   __DATA.__crash_info: 0x148

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 103
-  Symbols:   227
-  CStrings:  339
+  Symbols:   229
+  CStrings:  342
 
Symbols:
+ __os_feature_enabled_impl
+ _xpc_support_register_xpcservice_with_btm
Functions:
~ sub_100005fb8 : 6420 -> 6588
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Tue Nov 10 01:36:28 PST 2026; root:libxpc_executables-3298.60.20~43/xpcproxy/RELEASE_ARM64E"
+ "BackgroundTaskManagement"
+ "ControlXPCServices"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Tue Nov 10 01:36:28 PST 2026; root:libxpc_executables-3298.60.20~43/xpcproxy/RELEASE_ARM64E"
+ "Unable to register XPC service with BTM: %d"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Thu Oct 29 00:45:38 PDT 2026; root:libxpc_executables-3298.60.14~78/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Thu Oct 29 00:45:38 PDT 2026; root:libxpc_executables-3298.60.14~78/xpcproxy/RELEASE_ARM64E"
```
