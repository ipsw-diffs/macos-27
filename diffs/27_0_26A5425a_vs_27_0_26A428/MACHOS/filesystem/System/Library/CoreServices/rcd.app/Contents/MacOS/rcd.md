## rcd

> `/System/Library/CoreServices/rcd.app/Contents/MacOS/rcd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 363.0.0.0.0
-  __TEXT.__text: 0x1870
+  __TEXT.__text: 0x181c
   __TEXT.__auth_stubs: 0x4e0
   __TEXT.__objc_stubs: 0x120
   __TEXT.__const: 0x40

   __TEXT.__cstring: 0x298
   __TEXT.__oslogstring: 0x1f3
   __TEXT.__objc_methname: 0xf8
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x108
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__cfstring: 0x1e0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ _processLowBatteryMessage : 252 -> 228
~ _doLowBatteryNotification : 240 -> 228
```
