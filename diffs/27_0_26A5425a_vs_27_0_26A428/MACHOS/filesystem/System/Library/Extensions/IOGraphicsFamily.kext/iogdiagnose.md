## iogdiagnose

> `/System/Library/Extensions/IOGraphicsFamily.kext/iogdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA.__data`

```diff

 600.0.0.0.0
-  __TEXT.__text: 0x1d4c
+  __TEXT.__text: 0x1d1c
   __TEXT.__auth_stubs: 0x290
   __TEXT.__const: 0x68
   __TEXT.__gcc_except_tab: 0x148
   __TEXT.__cstring: 0x7fc
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__auth_got: 0x150
   __DATA_CONST.__got: 0x60
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_1000006b8 : 3924 -> 3916
~ sub_10000160c -> sub_100001604 : 172 -> 160
~ sub_1000016b8 -> sub_1000016a4 : 304 -> 292
~ sub_100001a6c -> sub_100001a4c : 344 -> 340
~ sub_1000020b0 -> sub_10000208c : 84 -> 72
```
