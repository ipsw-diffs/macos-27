## configure

> `/System/Library/OpenDirectory/Modules/configure.bundle/Contents/MacOS/configure`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 1003.0.1.0.0
-  __TEXT.__text: 0x3ff0
+  __TEXT.__text: 0x3f70
   __TEXT.__auth_stubs: 0x840
   __TEXT.__const: 0x98
   __TEXT.__cstring: 0x29d8
   __TEXT.__oslogstring: 0x2d4
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0x320
   __DATA_CONST.__cfstring: 0x3c0
   __DATA_CONST.__auth_got: 0x420

   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /System/Library/PrivateFrameworks/Heimdal.framework/Versions/A/Heimdal
   - /usr/lib/libSystem.B.dylib
-  Functions: 59
+  Functions: 58
   Symbols:   260
   CStrings:  62
 
Functions:
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ __custom_delete_node_configuration : 320 -> 308
~ __custom_write_node_configuration : 296 -> 284
~ ___custom_read_node_configuration_block_invoke.75 : 104 -> 92
~ ____get_plugin_list_block_invoke : 196 -> 184
~ ____get_plugin_list_block_invoke_2 : 116 -> 104
~ __fixup_legacy_plugin : 296 -> 284
- _OUTLINED_FUNCTION_1
```
