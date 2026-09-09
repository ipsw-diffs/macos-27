## xpcproxy

> `/usr/libexec/xpcproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__dof_launchd`
- `__DATA_CONST.__const`
- `__DATA.__os_assumes_log`
- `__DATA.__data`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0xb150
+  __TEXT.__text: 0xb0f8
   __TEXT.__auth_stubs: 0xc80
   __TEXT.__lazy_helpers: 0x1a4
   __TEXT.__const: 0x1b0

   __TEXT.__oslogstring: 0x18f8
   __TEXT.__cstring: 0x1c46
   __TEXT.__dof_launchd: 0x2e5
-  __TEXT.__unwind_info: 0x188
+  __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x260
   __DATA_CONST.__auth_got: 0x640
   __DATA_CONST.__got: 0xa0
Functions:
~ sub_100000b34 : 72 -> 60
~ sub_10000120c -> sub_100001200 : 772 -> 760
~ sub_100007f18 -> sub_100007f00 : 184 -> 172
~ sub_100008010 -> sub_100007fec : 220 -> 224
~ sub_1000080ec -> sub_1000080cc : 604 -> 608
~ sub_100008348 -> sub_10000832c : 3044 -> 3008
~ sub_10000acf8 -> sub_10000acb8 : 536 -> 524
~ sub_10000b240 -> sub_10000b1f4 : 108 -> 96
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug 22 16:54:50 PDT 2026; root:libxpc_executables-3298.1.1~67/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug 22 16:54:50 PDT 2026; root:libxpc_executables-3298.1.1~67/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Tue Aug 25 19:32:28 PDT 2026; root:libxpc_executables-3298.1.1~70/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Tue Aug 25 19:32:28 PDT 2026; root:libxpc_executables-3298.1.1~70/xpcproxy/RELEASE_ARM64E"
```
