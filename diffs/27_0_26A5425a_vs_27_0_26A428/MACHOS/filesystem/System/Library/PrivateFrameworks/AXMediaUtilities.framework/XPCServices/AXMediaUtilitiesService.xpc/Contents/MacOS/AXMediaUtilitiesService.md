## AXMediaUtilitiesService

> `/System/Library/PrivateFrameworks/AXMediaUtilities.framework/XPCServices/AXMediaUtilitiesService.xpc/Contents/MacOS/AXMediaUtilitiesService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 186.0.0.0.0
-  __TEXT.__text: 0x1e70
+  __TEXT.__text: 0x1d8c
   __TEXT.__auth_stubs: 0x240
   __TEXT.__objc_stubs: 0x720
   __TEXT.__objc_methlist: 0x314

   __TEXT.__cstring: 0xb4
   __TEXT.__objc_classname: 0xb6
   __TEXT.__objc_methtype: 0x2d4
-  __TEXT.__unwind_info: 0x100
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0x190
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ -[AXMServiceInstance _cachedEngineForEngine:] : 236 -> 224
~ -[AXMServiceInstance _removeEngineFromCache:] : 132 -> 120
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[AXMServiceInstance .cxx_destruct] : 80 -> 68
~ -[AXMServiceXPCServer run] : 88 -> 76
~ ___45-[AXMServiceXPCServer _destroyXPCConnection:]_block_invoke : 76 -> 64
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___49-[AXMServiceXPCServer prewarmVisionEngineService]_block_invoke : 68 -> 56
~ ___74-[AXMServiceXPCServer visionEngine:evaluateSource:context:options:result:]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ __58-[AXMServiceXPCServer listener:shouldAcceptNewConnection:]_block_invoke.72 : 76 -> 64
~ -[AXMServiceXPCServer delegate] : 44 -> 32
~ -[AXMServiceXPCServer .cxx_destruct] : 64 -> 52
~ -[AXMIdleManager delegate] : 44 -> 32
~ -[AXMIdleManager .cxx_destruct] : 100 -> 88
```
