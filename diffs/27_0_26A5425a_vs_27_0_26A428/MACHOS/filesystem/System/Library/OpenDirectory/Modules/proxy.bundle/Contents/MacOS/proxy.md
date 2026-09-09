## proxy

> `/System/Library/OpenDirectory/Modules/proxy.bundle/Contents/MacOS/proxy`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x2398
+  __TEXT.__text: 0x2320
   __TEXT.__auth_stubs: 0x520
   __TEXT.__const: 0x58
   __TEXT.__cstring: 0x2f4
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x130
   __DATA_CONST.__const: 0x238
   __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__auth_got: 0x290
Functions:
~ sub_904 : 80 -> 68
~ sub_a8c -> sub_a80 : 80 -> 68
~ sub_d70 -> sub_d58 : 92 -> 80
~ sub_14d8 -> sub_14b4 : 84 -> 72
~ _connection_destroy : 128 -> 116
~ sub_1658 -> sub_161c : 236 -> 224
~ sub_188c -> sub_1844 : 84 -> 72
~ sub_2388 -> sub_2334 : 272 -> 260
~ _odm_proxy_process_request : 228 -> 216
~ sub_2588 -> sub_251c : 296 -> 284
```
