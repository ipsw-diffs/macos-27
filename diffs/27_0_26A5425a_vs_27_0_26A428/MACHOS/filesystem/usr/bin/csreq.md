## csreq

> `/usr/bin/csreq`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`

```diff

 135.0.6.0.0
-  __TEXT.__text: 0x2374
+  __TEXT.__text: 0x22f0
   __TEXT.__auth_stubs: 0x530
   __TEXT.__const: 0x148
   __TEXT.__gcc_except_tab: 0x2c8
   __TEXT.__cstring: 0x2a0
   __TEXT.__oslogstring: 0x48
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x1c0
+  __TEXT.__unwind_info: 0x1e0
   __DATA_CONST.__const: 0x238
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x2a0
Functions:
~ sub_1000015ec : 180 -> 156
~ sub_1000016a0 -> sub_100001688 : 92 -> 80
~ sub_1000019c8 -> sub_1000019a4 : 56 -> 44
~ sub_100001a00 -> sub_1000019d0 : 340 -> 328
~ sub_100001c1c -> sub_100001be0 : 292 -> 268
~ sub_100001d58 -> sub_100001d04 : 72 -> 60
~ sub_1000026cc -> sub_10000266c : 56 -> 44
~ sub_100002704 -> sub_100002698 : 56 -> 44
~ sub_10000273c -> sub_1000026c4 : 56 -> 44
```
