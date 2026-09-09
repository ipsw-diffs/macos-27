## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__cstring`
- `__TEXT.__swift5_capture`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0x5be58
+  __TEXT.__text: 0x5ae1c
   __TEXT.__auth_stubs: 0x23b0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x20c

   __TEXT.__oslogstring: 0xd5
   __TEXT.__config: 0x3b2f
   __TEXT.__dof_launchd: 0x81d
-  __TEXT.__unwind_info: 0x1128
+  __TEXT.__unwind_info: 0x1760
   __TEXT.__eh_frame: 0x210
   __DATA_CONST.__const: 0x59d8
   __DATA_CONST.__objc_classlist: 0xc0
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Aug 22 16:52:45 PDT 2026; root:libxpc_executables-3298.1.1~67/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sat Aug 22 16:52:45 PDT 2026; root:libxpc_executables-3298.1.1~67/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Tue Aug 25 19:30:21 PDT 2026; root:libxpc_executables-3298.1.1~70/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Tue Aug 25 19:30:21 PDT 2026; root:libxpc_executables-3298.1.1~70/launchd/RELEASE_ARM64E"
```
