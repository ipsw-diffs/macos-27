## scodec_host_v1.im4p

> `Firmware/scodec/scodec_host_v1.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._afk_sys_objt`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4ce88
+  __TEXT.__text: 0x4cf10
   __TEXT.__const: 0x3938
   __TEXT.__cstring: 0x2a21
   __TEXT.__init_offsets: 0x0

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x89530
+  __DATA.__zerofill: 0x89538
   __OS_LOG.__string: 0x2dab
-  Functions: 1067
+  Functions: 1068
   Symbols:   3738
   CStrings:  733
 
Symbols:
+ __ZN14AFKRTKMBIRouteC1EP13AFKDictionaryRKNS_6ConfigE
- _OUTLINED_FUNCTION_632
Functions:
~ __ZN14AFKRTKMBIRoute5startEP10AFKService : 380 -> 424
~ __ZN7libkern20intrusive_shared_ptrI9AFKNumber27intrusive_osobject_retainerE5resetEv : 184 -> 56
+ __ZN14AFKRTKMBIRouteC1EP13AFKDictionaryRKNS_6ConfigE
~ _OUTLINED_FUNCTION_388 : 3884 -> 3872
~ __GLOBAL__sub_I_scodec_host_v1.dt_cpp.cpp : 1568 -> 1476
~ __rtk_lock_lock : 376 -> 368
```
