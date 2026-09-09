## System

> `/System/Library/CoreAccessories/PlugIns/Platform/System.platform/Contents/MacOS/System`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0xe1c
+  __TEXT.__text: 0xdd4
   __TEXT.__objc_methlist: 0x304
   __TEXT.__cstring: 0x178
   __TEXT.__const: 0x30
   __TEXT.__oslogstring: 0x2e4
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xd0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__auth_stubs: 0x180
   __TEXT.__objc_classname: 0x6d
Functions:
~ _WeakLinkSymbol : 76 -> 64
~ _WeakLinkClass : 104 -> 92
~ _WeakLinkStringConstant : 80 -> 68
~ _init_logging : 60 -> 48
~ -[ACCPlatformPluginSystem pluginName] : 40 -> 28
~ -[ACCPlatformPluginSystem initPlugin] : 60 -> 48
```
