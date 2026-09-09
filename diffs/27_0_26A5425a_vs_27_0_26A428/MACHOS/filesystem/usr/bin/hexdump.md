## hexdump

> `/usr/bin/hexdump`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 334.0.0.0.0
-  __TEXT.__text: 0x2c40
+  __TEXT.__text: 0x2c14
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__const: 0x74
   __TEXT.__cstring: 0x5db
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x170
   __DATA_CONST.__auth_got: 0x170
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100000e04 : 724 -> 720
~ sub_100002000 -> sub_100001ffc : 828 -> 824
~ sub_100002fd8 -> sub_100002fd0 : 28 -> 16
~ sub_100002ff4 -> sub_100002fe0 : 24 -> 12
~ sub_10000300c -> sub_100002fec : 32 -> 20
```
