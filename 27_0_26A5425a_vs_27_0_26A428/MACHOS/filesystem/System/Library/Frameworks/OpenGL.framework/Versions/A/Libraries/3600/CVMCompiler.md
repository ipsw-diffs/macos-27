## CVMCompiler

> `/System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries/3600/CVMCompiler`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 404.0.0.0.0
-  __TEXT.__text: 0x1260
+  __TEXT.__text: 0x1224
   __TEXT.__auth_stubs: 0x500
   __TEXT.__gcc_except_tab: 0x30
   __TEXT.__cstring: 0x182
   __TEXT.__const: 0x28
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x160
   __DATA_CONST.__auth_got: 0x288
   __DATA_CONST.__got: 0x50
Functions:
~ __ZL19cvmsContentAllocatePK22_cvms_plugin_element_sm : 176 -> 164
~ _cvmsCompDestroyObjects : 312 -> 300
~ __ZN4llvm17CVMSMemoryManagerD0Ev : 56 -> 44
~ ___runCVMSCompiler_block_invoke : 292 -> 280
~ ___cvmsCompInitializeConnection_block_invoke : 1392 -> 1380
```
