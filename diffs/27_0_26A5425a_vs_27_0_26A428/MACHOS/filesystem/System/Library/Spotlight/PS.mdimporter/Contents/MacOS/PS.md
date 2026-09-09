## PS

> `/System/Library/Spotlight/PS.mdimporter/Contents/MacOS/PS`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x8fc
+  __TEXT.__text: 0x8cc
   __TEXT.__auth_stubs: 0x160
   __TEXT.__cstring: 0x63
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0x80
   __DATA_CONST.__const: 0x28
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0xb0
Functions:
~ _DeallocMetadataImporterPluginType : 92 -> 80
~ _OUTLINED_FUNCTION_0 : 28 -> 16
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ _OUTLINED_FUNCTION_7 : 32 -> 20
```
