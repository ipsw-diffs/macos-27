## NetLogon

> `/System/Library/OpenDirectory/Modules/NetLogon.bundle/Contents/MacOS/NetLogon`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 114.0.0.0.0
-  __TEXT.__text: 0x1258
+  __TEXT.__text: 0x1234
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__const: 0x78
   __TEXT.__cstring: 0x11c
   __TEXT.__oslogstring: 0x107
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__auth_got: 0x168
Functions:
~ sub_ad0 : 248 -> 236
~ sub_bc8 -> sub_bbc : 96 -> 84
~ sub_c28 -> sub_c10 : 80 -> 68
```
