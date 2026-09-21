## xpcproxy

> `/usr/libexec/xpcproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_launchd`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

   __TEXT.__const: 0x1c0
   __TEXT.__xpcproxy: 0x1
   __TEXT.__oslogstring: 0x18f8
-  __TEXT.__cstring: 0x1c4a
+  __TEXT.__cstring: 0x1c4c
   __TEXT.__dof_launchd: 0x2e5
   __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x260
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 19:28:12 PDT 2026; root:libxpc_executables-3298.40.20~221/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 19:28:12 PDT 2026; root:libxpc_executables-3298.40.20~221/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:48:39 PDT 2026; root:libxpc_executables-3298.40.20~23/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:48:39 PDT 2026; root:libxpc_executables-3298.40.20~23/xpcproxy/RELEASE_ARM64E"
```
