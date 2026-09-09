## launchctl

> `/bin/launchctl`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0xea64
+  __TEXT.__text: 0xe9bc
   __TEXT.__auth_stubs: 0xd80
   __TEXT.__const: 0x2f0
   __TEXT.__launchctl: 0x1
   __TEXT.__cstring: 0x62d8
   __TEXT.__oslogstring: 0x19
-  __TEXT.__unwind_info: 0x1d0
+  __TEXT.__unwind_info: 0x2c0
   __DATA_CONST.__const: 0x6998
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x6c0
Functions:
~ sub_100001690 : 96 -> 84
~ sub_1000019f8 -> sub_1000019ec : 220 -> 208
~ sub_1000027f8 -> sub_1000027e0 : 396 -> 392
~ sub_100004994 -> sub_100004978 : 9424 -> 9400
~ sub_1000070e4 -> sub_1000070b0 : 2204 -> 2196
~ sub_10000b0cc -> sub_10000b090 : 172 -> 160
~ sub_10000b178 -> sub_10000b130 : 796 -> 784
~ sub_10000ba00 -> sub_10000b9ac : 252 -> 240
~ sub_10000c0f8 -> sub_10000c098 : 3044 -> 3008
~ sub_10000ed1c -> sub_10000ec98 : 116 -> 104
~ sub_10000ed98 -> sub_10000ed08 : 68 -> 56
~ sub_10000eddc -> sub_10000ed40 : 88 -> 76
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Control Interface Version 7.0.0: Sat Aug 22 16:54:46 PDT 2026; root:libxpc_executables-3298.1.1~67/launchctl/RELEASE_ARM64E"
+ "Darwin Bootstrapper Control Interface Version 7.0.0: Sat Aug 22 16:54:46 PDT 2026; root:libxpc_executables-3298.1.1~67/launchctl/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Control Interface Version 7.0.0: Tue Aug 25 19:32:23 PDT 2026; root:libxpc_executables-3298.1.1~70/launchctl/RELEASE_ARM64E"
- "Darwin Bootstrapper Control Interface Version 7.0.0: Tue Aug 25 19:32:23 PDT 2026; root:libxpc_executables-3298.1.1~70/launchctl/RELEASE_ARM64E"
```
