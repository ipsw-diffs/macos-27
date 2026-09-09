## netstat

> `/usr/sbin/netstat`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 755.0.0.0.0
-  __TEXT.__text: 0x1b304
+  __TEXT.__text: 0x1b28c
   __TEXT.__auth_stubs: 0x4e0
   __TEXT.__cstring: 0xf2c1
   __TEXT.__const: 0x3d8
-  __TEXT.__unwind_info: 0x200
+  __TEXT.__unwind_info: 0x268
   __DATA_CONST.__const: 0x14b8
   __DATA_CONST.__auth_got: 0x270
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100002944 : 572 -> 560
~ sub_100004f30 -> sub_100004f24 : 28 -> 16
~ sub_10000f824 -> sub_10000f80c : 1192 -> 1144
~ sub_10000fd3c -> sub_10000fcf4 : 240 -> 216
~ sub_1000126e0 -> sub_100012680 : 236 -> 224
~ sub_10001b770 -> sub_10001b704 : 40 -> 28
```
