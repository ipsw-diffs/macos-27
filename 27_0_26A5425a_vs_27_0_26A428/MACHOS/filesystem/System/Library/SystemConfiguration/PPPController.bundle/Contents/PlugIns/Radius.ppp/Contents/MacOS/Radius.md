## Radius

> `/System/Library/SystemConfiguration/PPPController.bundle/Contents/PlugIns/Radius.ppp/Contents/MacOS/Radius`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1031.0.0.0.4
-  __TEXT.__text: 0x3db8
+  __TEXT.__text: 0x3d68
   __TEXT.__auth_stubs: 0x440
   __TEXT.__const: 0x1b
   __TEXT.__cstring: 0xf11
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x118
   __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__auth_got: 0x220
   __DATA_CONST.__got: 0x80
Functions:
~ sub_81c : 2124 -> 2112
~ _makeint : 84 -> 72
~ _rad_close : 192 -> 180
~ _rad_put_attr : 452 -> 432
~ _rad_put_string : 88 -> 76
~ _rad_put_vendor_string : 96 -> 84
```
