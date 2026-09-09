## shutdown

> `/System/Library/MultiversePlugins/shutdown.plugin/Contents/MacOS/shutdown`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 117.1.2.0.0
-  __TEXT.__text: 0x28c
+  __TEXT.__text: 0x280
   __TEXT.__auth_stubs: 0x150
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x117
   __TEXT.__oslogstring: 0x33
-  __TEXT.__unwind_info: 0x68
+  __TEXT.__unwind_info: 0x78
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0xa8
Functions:
~ _init_shutdown_plugin : 220 -> 208
```
